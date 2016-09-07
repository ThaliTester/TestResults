#### Test 83627337941f206_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 12:33:00.573  1519  1519 I ConfigService: onDestroy
,09-07 12:33:01.259  3431  3431 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 12:33:01.272  3431  3431 D AndroidRuntime: CheckJNI is OFF
09-07 12:33:01.315  3431  3431 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 12:33:01.365  3431  3431 I Radio-JNI: register_android_hardware_Radio DONE
09-07 12:33:01.388  3431  3431 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 12:33:01.393   874  2218 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 12:33:01.415  2054  2071 W SearchService: Abort, client detached.
09-07 12:33:01.426  3431  3431 D AndroidRuntime: Shutting down VM
09-07 12:33:01.428  2054  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3e8492f
09-07 12:33:01.428  2054  2054 I HotwordDetector: Closing mic
09-07 12:33:01.429  2054  2354 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 12:33:01.453   874  1700 I ActivityManager: Start proc 3441:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 12:33:01.467  2054  2054 W ErrorReporter: reportError [type: 29, code: 917507]: null
09-07 12:33:01.482   377  2356 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 12:33:01.483   377  2356 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 12:33:01.486   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 12:33:01.488  2054  2353 I MicroRecognitionRnrImpl: Detection finished
09-07 12:33:01.488  2054  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 12:33:01.528  3441  3441 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 12:33:01.549  3441  3441 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 12:33:01.643  3441  3441 I LibraryLoader: Time to load native libraries: 90 ms (timestamps 21-111)
09-07 12:33:01.644  3441  3441 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 12:33:01.673  3441  3441 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {461c499}
,09-07 12:33:01.674  3441  3441 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 12:33:01.674  3441  3441 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 12:33:01.684  3441  3441 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 12:33:01.686  3441  3441 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 12:33:01.742  3441  3456 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,09-07 12:33:01.752  3441  3441 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 12:33:01.767  3441  3441 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:33:01.768  3441  3441 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 12:33:01.768  3441  3441 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 12:33:01.768  3441  3441 I Adreno  : Build Date                       : 10/20/15
09-07 12:33:01.768  3441  3441 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 12:33:01.768  3441  3441 I Adreno  : Local Branch                     : M14
09-07 12:33:01.768  3441  3441 I Adreno  : Remote Branch                    : 
09-07 12:33:01.768  3441  3441 I Adreno  : Remote Branch                    : 
09-07 12:33:01.768  3441  3441 I Adreno  : Reconstruct Branch               : 
,09-07 12:33:01.841   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@837ec3:true
,09-07 12:33:01.914  3441  3441 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 12:33:01.928  3441  3441 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 12:33:02.001  3441  3479 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 12:33:02.012  3441  3465 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 12:33:02.046  3441  3479 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 12:33:02.114   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +685ms
,09-07 12:33:02.124  1888  1888 I Keyboard.Facilitator: onFinishInput()
,09-07 12:33:02.175  3441  3441 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3441
,09-07 12:33:02.278   874  2218 I ActivityManager: Killing 2511:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,09-07 12:33:02.283  3441  3441 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 12:33:02.321   874  2218 I ActivityManager: Killing 3149:com.qualcomm.telephony/1001 (adj 15): empty #18
,09-07 12:33:02.489  3441  3481 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1698236112
,09-07 12:33:02.493  3441  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 12:33:02.493  3441  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 12:33:02.493  3441  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 12:33:02.493  3441  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 12:33:02.493  3441  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 12:33:02.494  3441  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afc17cd added. We now have 1 listener(s)
,09-07 12:33:02.496  3441  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 12:33:02.498  3441  3481 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 12:33:02.499  3441  3481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 12:33:02.499  3441  3481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 12:33:02.502  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 12:33:02.503  3441  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd487d0 added. We now have 1 listener(s)
,09-07 12:33:02.503  3441  3481 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:33:02.509   874  1319 D WifiService: New client listening to asynchronous messages
,09-07 12:33:02.510  3441  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:33:02.510  3441  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 12:33:02.511  3441  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 12:33:02.511  3441  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-07 12:33:02.511  3441  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 12:33:02.513  3441  3481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:02.514  3441  3481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 12:33:02.515  3441  3481 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:02.515  3441  3481 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:02.516  3441  3481 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 12:33:02.516  3441  3481 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:33:02.516  3441  3481 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 12:33:02.517  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:02.552  3441  3441 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 12:33:02.684   977   977 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,09-07 12:33:02.684   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,09-07 12:33:02.716   977   977 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,09-07 12:33:02.716   977   977 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,09-07 12:33:03.452  3441  3489 W jxcore-log: Initializing JXcore engine
,09-07 12:33:03.452  3441  3489 W jxcore-log: JXcore engine is ready
,09-07 12:33:03.486  3489  3489 W Thread-281: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8798 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 12:33:03.490  3489  3489 W Thread-281: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11658]" dev="sockfs" ino=11658 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-07 12:33:03.490  3489  3489 W Thread-281: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 12:33:03.490  3489  3489 W Thread-281: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21371]" dev="sockfs" ino=21371 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 12:33:03.503  3441  3489 W jxcore-log: Starting JXcore engine
,09-07 12:33:03.584  3441  3489 W jxcore-log: Platform android
09-07 12:33:03.584  3441  3489 W jxcore-log: 
,09-07 12:33:03.584  3441  3489 W jxcore-log: Process ARCH arm
09-07 12:33:03.584  3441  3489 W jxcore-log: 
,09-07 12:33:03.704   977   977 I kickstart: STATUS: Received file 'm9kefs2'
,09-07 12:33:03.704   977   977 I kickstart: STATUS: 950272 bytes transferred in 0.987533 seconds
09-07 12:33:03.704   977   977 I kickstart: STATUS: Successfully downloaded files from target 
09-07 12:33:03.706   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,09-07 12:33:03.709   977   977 I kickstart: STATUS: Sahara protocol completed
,09-07 12:33:03.867  3441  3489 I jxcore-log: JXcore Cordova bridge is ready!
09-07 12:33:03.867  3441  3489 I jxcore-log: 
,09-07 12:33:03.867  3441  3489 W jxcore-log: JXcore engine is started
,09-07 12:33:03.880  3441  3481 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 12:33:03.886  3441  3441 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 12:33:09.940   874   887 I ActivityManager: Waited long enough for: ServiceRecord{2530e02 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-07 12:33:13.559  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 12:33:13.559  3441  3489 I jxcore-log: 
,09-07 12:33:13.561  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 12:33:13.561  3441  3489 I jxcore-log: 
,09-07 12:33:13.563  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:13.563  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:13.563  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:13.563  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:13.565  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 12:33:13.565  3441  3489 I jxcore-log: 
,09-07 12:33:13.567  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 12:33:13.567  3441  3489 I jxcore-log: 
,09-07 12:33:14.063  3441  3489 I jxcore-log: Unit Test app is loaded
09-07 12:33:14.063  3441  3489 I jxcore-log: 
,09-07 12:33:14.069  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:33:14.069  3441  3489 I jxcore-log: 
,09-07 12:33:14.075   874  2218 D WifiService: setWifiEnabled: true pid=3441, uid=10000
,09-07 12:33:14.075   874  2218 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:33:14.085   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-07 12:33:14.089  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.089  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:14.090  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.090  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:14.091  3441  3441 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 12:33:14.099   874  1317 D WifiConfigStore: loaded 0 passpoint configs
09-07 12:33:14.099   874   887 I ActivityManager: Start proc 3493:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-07 12:33:14.100   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-07 12:33:14.100   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 12:33:14.101   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 12:33:14.101   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 12:33:14.101   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 12:33:14.101   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-07 12:33:14.108  3441  3489 D executeNativeTests: Running unit tests
09-07 12:33:14.121   874   891 I ActivityManager: Start proc 3503:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 12:33:14.158  3493  3493 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 12:33:14.159   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 12:33:14.160   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:14.160   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
09-07 12:33:14.160   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 12:33:14.163   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
09-07 12:33:14.166   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 12:33:14.181   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:14.184   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:14.200  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 12:33:14.200  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 added. We now have 2 listener(s)
09-07 12:33:14.201  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 12:33:14.201  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:33:14.201  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:33:14.201  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:33:14.201  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 added. We now have 2 listener(s)
09-07 12:33:14.202  3441  3489 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:33:14.202  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:33:14.203  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:14.204  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.204  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:14.204  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.204  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:14.204  3441  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:33:14.204  3503  3503 D AdapterServiceConfig: Adding HeadsetService
09-07 12:33:14.204  3503  3503 D AdapterServiceConfig: Adding A2dpService
,09-07 12:33:14.204  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.204  3503  3503 D AdapterServiceConfig: Adding HidService
09-07 12:33:14.204  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:14.204  3503  3503 D AdapterServiceConfig: Adding HealthService
09-07 12:33:14.205  3441  3489 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
09-07 12:33:14.205  3503  3503 D AdapterServiceConfig: Adding PanService
09-07 12:33:14.205  3503  3503 D AdapterServiceConfig: Adding GattService
09-07 12:33:14.205  3503  3503 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 12:33:14.207  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 12:33:14.207  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:33:14.207  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 12:33:14.209  3441  3489 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 12:33:14.209  3441  3489 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:33:14.209  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 12:33:14.210  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 12:33:14.210  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:33:14.210  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.210  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.210  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:14.211  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:33:14.211  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 removed from the list
09-07 12:33:14.211  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.211  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 removed from the list
09-07 12:33:14.211  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.211  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:33:14.213  3441  3489 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 12:33:14.214  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.214  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:33:14.214  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.214  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.214  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.214  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.214  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.214  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.214  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:33:14.220  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:33:14.221  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:33:14.221  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:33:14.221  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.221  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.222  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.222  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.222  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.222  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:33:14.222  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.222  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.222  3441  3489 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 12:33:14.223  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.224  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.224  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:14.224  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.224  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:14.224  3441  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:33:14.224  3441  3489 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-07 12:33:14.225  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:14.225  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-07 12:33:14.225  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 12:33:14.225  3441  3489 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 12:33:14.225  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:33:14.225  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.225  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 12:33:14.225  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.225  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-07 12:33:14.225  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.226  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 12:33:14.226  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.226  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:33:14.229  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 12:33:14.229  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:14.229  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:33:14.230  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.230  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:14.230  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:33:14.230  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:33:14.230  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
,09-07 12:33:14.230  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.230  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.230  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:14.230  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:33:14.230  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:14.230  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:33:14.230  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:33:14.231  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:14.231  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:33:14.231  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.231  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.231  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.231  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.231  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:33:14.231  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.232  3441  3489 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 12:33:14.233   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@638cb82:true
09-07 12:33:14.233  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.233  3503  3503 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 12:33:14.234  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.234  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:14.234  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.234  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:14.234  3441  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:33:14.234  3441  3489 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-07 12:33:14.234  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-07 12:33:14.234  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:14.235  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 12:33:14.235  3441  3489 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 12:33:14.235  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:33:14.235  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.235  3503  3503 I bt_bluedroid: init
09-07 12:33:14.236  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 12:33:14.236  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.236  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-07 12:33:14.236  3503  3527 I BluetoothAdapterState: Entering OffState
09-07 12:33:14.236  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 12:33:14.236  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.236  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:33:14.236  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.238  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 12:33:14.238  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:14.239  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:33:14.239  3503  3528 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 12:33:14.239  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:14.239  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.239  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:33:14.239  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:33:14.239  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 12:33:14.239  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.239  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:33:14.239  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.239  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:14.239  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:33:14.239  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:14.240  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:33:14.240  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:14.240  3503  3528 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 12:33:14.240  3503  3528 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 12:33:14.240  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.240  3503  3528 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 12:33:14.240  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.240  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.240  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.240  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.240  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.240  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.241  3503  3503 I bt_bluedroid: get_profile_interface socket
09-07 12:33:14.241  3441  3489 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 12:33:14.241  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.241  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.241  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.241  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.242  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.242  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.242  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.242  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.242  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.242  3503  3503 I bt_bluedroid: get_profile_interface sdp
09-07 12:33:14.242  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:33:14.242  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.242  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.242  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.243  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.243  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.243  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.243  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.243  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.243  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.243  3441  3489 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 12:33:14.244  3503  3515 I bt_bluedroid: config_hci_snoop_log
09-07 12:33:14.244  3503  3531 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 12:33:14.244  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.244  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.244  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.244  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.245  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.245  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.245  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.245   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-07 12:33:14.246  3493  3493 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
09-07 12:33:14.245  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.246  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.246  3503  3531 D BluetoothAdapterProperties: Name is: Nexus 6
09-07 12:33:14.246  3441  3489 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 12:33:14.246  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.246  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.246  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.247  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.247  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.247  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.247  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.247  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.247  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.247  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:33:14.247  3503  3527 D BluetoothAdapterState: Current state: OFF, message: 0
09-07 12:33:14.247  3503  3527 D BluetoothAdapterProperties: Setting state to 14
09-07 12:33:14.247  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-07 12:33:14.248  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:33:14.248  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:33:14.248  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:33:14.248  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:33:14.248  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:33:14.248  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.248  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.248  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.248  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.248  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.248  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.248  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.248  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.248  3503  3527 D BluetoothBondStateMachine: make
09-07 12:33:14.248  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.249  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:33:14.249  3441  3489 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:33:14.249  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 12:33:14.250  3503  3532 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 12:33:14.252  3503  3527 I BluetoothAdapterState: Entering PendingCommandState
09-07 12:33:14.253  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:33:14.253  3441  3489 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 12:33:14.253  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:33:14.253  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:33:14.253  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:33:14.253  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:33:14.253  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:33:14.253  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:33:14.254  3503  3503 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-07 12:33:14.254  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:33:14.255  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:33:14.255  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:33:14.255  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 12:33:14.255  3441  3489 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:33:14.255  3441  3489 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 12:33:14.255  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:33:14.255  3441  3489 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:33:14.255  3441  3489 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 12:33:14.255  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:33:14.255  3441  3489 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:33:14.255  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 12:33:14.259  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 12:33:14.259  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 12:33:14.259  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
09-07 12:33:14.259  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 12:33:14.259  3503  3503 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:33:14.259  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 12:33:14.260  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 12:33:14.260  3503  3503 D BtGatt.GattService: Received start request. Starting profile...
09-07 12:33:14.260  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 12:33:14.260  3503  3503 D BtGatt.GattService: start()
09-07 12:33:14.260  3441  3489 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:33:14.260  3503  3503 I bt_bluedroid: get_profile_interface gatt
09-07 12:33:14.260  3441  3533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 378)
09-07 12:33:14.260  3441  3489 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 12:33:14.261  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
09-07 12:33:14.261  3503  3503 D BtGatt.AdvertiseManager: advertise manager created
09-07 12:33:14.261  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.261  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.261  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.261  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 12:33:14.262  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.262  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.262  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.262  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.262  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.262  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.262  3441  3535 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 378
09-07 12:33:14.263  3441  3489 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 12:33:14.263  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.263  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.263  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.263  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.263  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.263  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.263  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.263  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.263  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.264  3441  3489 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 12:33:14.264  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.264  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.264  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.264  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.264  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.264  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.264  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.264  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.264  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.265  3441  3489 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 12:33:14.265  3441  3489 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 12:33:14.265  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:33:14.265  3441  3489 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 12:33:14.265  3441  3489 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:33:14.265  3441  3489 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 12:33:14.265  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:33:14.265  3441  3489 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 12:33:14.265  3441  3489 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:33:14.265  3441  3489 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:33:14.265  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:33:14.265  3441  3489 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 12:33:14.265  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.265  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.266  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.266  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.266  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.266  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.266  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.266  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.266  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.266  3441  3489 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 12:33:14.267  3441  3533 E BluetoothDevice: Bluetooth is not enabled
09-07 12:33:14.267  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:14.267  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:14.267  3503  3503 V BluetoothAdapterState: isBleTurningOn()=true
09-07 12:33:14.267  3441  3533 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 378)
09-07 12:33:14.267  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:14.267  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 12:33:14.267  3503  3527 I bt_bluedroid: enable
09-07 12:33:14.268  3503  3528 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 12:33:14.268  3503  3528 I bt_hci  : start_up
09-07 12:33:14.268  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:14.270  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.270  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:14.271  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.271  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:14.271  3441  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:33:14.271  3441  3489 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-07 12:33:14.271  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-07 12:33:14.271  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 12:33:14.271  3441  3489 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 12:33:14.271  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:33:14.271  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.272  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 12:33:14.272  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.272  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-07 12:33:14.272  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 12:33:14.272  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.273  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:33:14.273  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:14.273  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.275  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 12:33:14.275  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:14.275  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:33:14.276  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:14.276  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.276  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:33:14.276  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:33:14.276  3503  3528 I bt_vendor: alloc value 0xb39de189
09-07 12:33:14.276  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 12:33:14.276  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.276  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:33:14.276  3503  3528 I bt_vendor: init
09-07 12:33:14.276  3503  3528 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 12:33:14.276  3503  3528 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
09-07 12:33:14.276  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.276  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:14.276  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:33:14.276  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:14.277  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:33:14.277  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:14.277  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.277  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.278  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.278  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.278  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.278  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.278  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.279  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:33:14.279  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:14.280  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 12:33:14.280  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.280  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:33:14.280  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:14.281  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.281  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:33:14.281  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.281  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 12:33:14.281  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.281  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.281  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:33:14.281  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:14.281  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:33:14.281  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:14.281  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.281  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.282  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.282  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.282  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.282  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.282  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.282  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.282  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:14.282  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:14.283  3441  3489 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 12:33:14.283  3441  3489 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:33:14.283  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:33:14.283  3441  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:33:14.283  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.283  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.283  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.283  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.283  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.284  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.284  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.284  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.284  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.288  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.288  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.288  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.288  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.288  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.288  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.288  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.288  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.288  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.289  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:14.289  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.289  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.289  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42cc207 not in the list
09-07 12:33:14.289  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:14.289  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296ef34 not in the list
09-07 12:33:14.289  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:14.289  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:14.289  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:33:14.290  3441  3489 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 12:33:14.290  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:33:14.290  3441  3489 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 12:33:14.290  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:33:14.290  3441  3489 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 12:33:14.290  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:33:14.291  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:33:14.291  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 12:33:14.292  3441  3489 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 12:33:14.292  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:33:14.292  3441  3489 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 12:33:14.292  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:33:14.292  3441  3489 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 12:33:14.292  3441  3489 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 12:33:14.292  3441  3489 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 12:33:14.292  3441  3489 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 12:33:14.293  3441  3489 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 12:33:14.293  3441  3489 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 12:33:14.293  3441  3489 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 12:33:14.293  3441  3489 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 12:33:14.294  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:33:14.294  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@525922a added. We now have 2 listener(s)
09-07 12:33:14.295  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 12:33:14.295  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:33:14.295  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:33:14.295  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:33:14.295  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a04381b added. We now have 2 listener(s)
09-07 12:33:14.295  3441  3489 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:33:14.295  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:33:14.295   874  1951 I ActivityManager: Killing 2818:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 12:33:14.328  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:14.330  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.330  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:14.331  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.331  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:14.331  3441  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:33:14.332  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:14.332   874  1395 D WifiService: setWifiEnabled: true pid=3441, uid=10000
09-07 12:33:14.333   874  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:33:14.333  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-07 12:33:14.335  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:14.341   874  1699 D WifiService: setWifiEnabled: false pid=3441, uid=10000
09-07 12:33:14.341   874  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:33:14.344   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:14.347  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.347  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:14.347  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:14.348  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:14.348  1902  2288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:33:14.349  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:14.349  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:14.350  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:14.350  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:14.383  3503  3528 D bt_hci  : start_up starting async portion
,09-07 12:33:14.383  3503  3538 I bt_hci  : event_finish_startup
09-07 12:33:14.384  3503  3538 I bt_hci_h4: hal_open
,09-07 12:33:14.384  3503  3538 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 12:33:14.389  3503  3538 I bt_userial_vendor: device fd = 51 open
,09-07 12:33:14.426  3503  3538 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 12:33:14.458  3503  3538 D bt_hwcfg: Chipset BCM4354A2
,09-07 12:33:14.459  3503  3538 D bt_hwcfg: Target name = [BCM4354A2]
09-07 12:33:14.459  3503  3538 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 12:33:14.783  3441  3441 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 12:33:15.210  3503  3538 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 12:33:15.210  3503  3538 D bt_hwcfg: Settlement delay -- 100 ms
09-07 12:33:15.210  3503  3538 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 12:33:15.325  3503  3538 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 12:33:15.325  3503  3538 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 12:33:15.359  3503  3538 I bt_hwcfg: vendor lib fwcfg completed
09-07 12:33:15.359  3503  3538 I bt_vendor: firmware callback
09-07 12:33:15.359  3503  3538 I bt_hci  : firmware_config_callback
,09-07 12:33:15.363  3503  3550 I bt_btu  : btu_task pending for preload complete event
,09-07 12:33:15.363  3503  3550 I bt_btu_task: Bluetooth chip preload is complete
,09-07 12:33:15.363  3503  3550 I bt_btu  : btu_task received preload complete event
,09-07 12:33:15.373  3503  3550 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 12:33:15.374  3503  3550 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 12:33:15.374  3503  3550 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 12:33:15.374  3503  3550 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 12:33:15.374  3503  3550 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:33:15.375  3503  3550 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 12:33:15.375  3503  3550 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:33:15.375  3503  3550 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 12:33:15.375  3503  3550 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 12:33:15.375  3503  3550 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 12:33:15.376  3503  3550 I         : BTE_InitTraceLevels -- TRC_SDP
,09-07 12:33:15.376  3503  3550 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 12:33:15.376  3503  3550 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 12:33:15.376  3503  3550 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:33:15.377  3503  3550 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 12:33:15.390  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:15.403  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:15.406  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:15.448  1519  2804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:33:15.449  1519  2804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 12:33:15.449  1519  2804 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:15.450  1519  2804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:15.483  2729  2729 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:33:15.484  2729  2729 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 12:33:15.484  2729  2729 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 12:33:15.500  3503  3550 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb395bd9d
,09-07 12:33:15.500  3503  3550 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb395bd9d 
,09-07 12:33:15.526  3503  3531 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-07 12:33:15.528  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 12:33:15.528  3503  3531 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 12:33:15.534  3503  3531 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 12:33:15.536  3503  3531 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:33:15.539  3503  3531 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:33:15.539  3503  3531 D bt_hci  : do_postload posting postload work item
,09-07 12:33:15.539  3503  3538 I bt_hci  : event_postload
,09-07 12:33:15.539  3503  3538 I bt_vendor: sco_config_cb
,09-07 12:33:15.540  3503  3538 I bt_hci  : sco_config_callback postload finished.
,09-07 12:33:15.540  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:15.543  3503  3531 D bt_bte_conf: Device ID record 1 : primary
09-07 12:33:15.543  3503  3531 D bt_bte_conf:   vendorId            = 000f
09-07 12:33:15.543  3503  3531 D bt_bte_conf:   vendorIdSource      = 0001
09-07 12:33:15.543  3503  3531 D bt_bte_conf:   product             = 1200
,09-07 12:33:15.543  3503  3531 D bt_bte_conf:   version             = 1436
09-07 12:33:15.543  3503  3531 D bt_bte_conf:   clientExecutableURL = 
09-07 12:33:15.543  3503  3531 D bt_bte_conf:   serviceDescription  = 
09-07 12:33:15.543  3503  3531 D bt_bte_conf:   documentationURL    = 
09-07 12:33:15.543  3503  3531 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-07 12:33:15.544  3503  3528 D bt_stack_manager: event_start_up_stack finished
09-07 12:33:15.544  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:15.544  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 12:33:15.544  3503  3527 D BluetoothAdapterProperties: Setting state to 15
,09-07 12:33:15.544  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 12:33:15.544  3503  3538 I bt_vendor: low_power_mode_cb
09-07 12:33:15.545  3503  3527 I BluetoothAdapterState: Entering BleOnState
,09-07 12:33:15.552  3503  3527 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 12:33:15.552  3503  3527 D BluetoothAdapterProperties: Setting state to 11
09-07 12:33:15.552  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 12:33:15.556  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
,09-07 12:33:15.557  3503  3503 D HeadsetService: Received start request. Starting profile...
09-07 12:33:15.561  3503  3503 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:33:15.561  3503  3503 D HeadsetStateMachine: make
09-07 12:33:15.564  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:15.567  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:15.578   874   887 I ActivityManager: Start proc 3557:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-07 12:33:15.580  3503  3503 D HeadsetStateMachine: max_hf_connections = 1
09-07 12:33:15.580  3503  3503 I bt_bluedroid: get_profile_interface handsfree
09-07 12:33:15.581  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-07 12:33:15.583  3503  3531 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 12:33:15.587  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
09-07 12:33:15.588  3503  3527 I BluetoothAdapterState: Entering PendingCommandState
09-07 12:33:15.588   874   874 D BluetoothA2dp: Proxy object connected
09-07 12:33:15.588  3503  3503 D A2dpService: Received start request. Starting profile...
,09-07 12:33:15.589  3503  3503 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 12:33:15.589  3503  3503 I bt_bluedroid: get_profile_interface avrcp
,09-07 12:33:15.596  3503  3503 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 12:33:15.597  3503  3503 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:33:15.597  3503  3503 D A2dpStateMachine: make
,09-07 12:33:15.598  3503  3503 I bt_bluedroid: get_profile_interface a2dp
09-07 12:33:15.599  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-07 12:33:15.600  3503  3570 D A2dpStateMachine: Enter Disconnected: -2
09-07 12:33:15.601  3503  3503 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 12:33:15.601  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
,09-07 12:33:15.605  3503  3503 D HidService: Received start request. Starting profile...
,09-07 12:33:15.605  1361  1361 D BluetoothInputDevice: Proxy object connected
09-07 12:33:15.605  3503  3503 I bt_bluedroid: get_profile_interface hidhost
09-07 12:33:15.605  3503  3503 D HidService: setHidService(): set to: null
09-07 12:33:15.605  1361  1361 D HidProfile: Bluetooth service connected
09-07 12:33:15.606  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:15.606  3503  3503 V BluetoothAdapterState: isTurningOn()=true
,09-07 12:33:15.606  3503  3531 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393d3e5
,09-07 12:33:15.606  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:15.606  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:15.606  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 12:33:15.608  3503  3503 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:33:15.608  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
,09-07 12:33:15.609  3503  3503 D HealthService: Received start request. Starting profile...
,09-07 12:33:15.610  3503  3503 I bt_bluedroid: get_profile_interface health
,09-07 12:33:15.611  3503  3556 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 12:33:15.611  3503  3503 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 12:33:15.612  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
,09-07 12:33:15.613  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:33:15.613  3503  3503 D PanService: Received start request. Starting profile...
09-07 12:33:15.614  3503  3503 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 12:33:15.614  1361  1361 D PanProfile: Bluetooth service connected
09-07 12:33:15.614  3503  3503 I bt_bluedroid: get_profile_interface pan
09-07 12:33:15.614  3503  3531 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 12:33:15.618  3503  3503 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d83545b
,09-07 12:33:15.619  1361  1361 D BluetoothMap: Proxy object connected
09-07 12:33:15.619  3503  3503 D BluetoothMapService: Received start request. Starting profile...
09-07 12:33:15.619  3503  3503 D BluetoothMapService: start()
09-07 12:33:15.619  1361  1361 D MapProfile: Bluetooth service connected
09-07 12:33:15.619  1361  1361 D BluetoothMap: getConnectedDevices()
09-07 12:33:15.620  1361  1361 D BluetoothMap: Bluetooth is Not enabled
09-07 12:33:15.621  3503  3503 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-07 12:33:15.621  3557  3557 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-07 12:33:15.621  3503  3503 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 12:33:15.621  3503  3503 D BluetoothMapAppObserver: createReceiver()
09-07 12:33:15.622  3503  3503 D BluetoothMapAppObserver: initObservers()
09-07 12:33:15.623  3503  3503 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isTurningOn()=true
09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isTurningOn()=true
09-07 12:33:15.628  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isTurningOn()=true
,09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isTurningOn()=true
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:15.629  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:15.630  3503  3503 V BluetoothAdapterState: isTurningOn()=true
09-07 12:33:15.630  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:15.630  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:33:15.630  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 12:33:15.630  3503  3527 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:33:15.630  3503  3527 D BluetoothAdapterProperties: State =  11
09-07 12:33:15.630   874  1951 I ActivityManager: Killing 2972:com.google.android.gm/u0a78 (adj 15): empty #17
,09-07 12:33:15.689  3503  3531 D BluetoothAdapterProperties: Scan Mode:21
,09-07 12:33:15.689  3503  3527 D BluetoothAdapterProperties: Setting state to 12
,09-07 12:33:15.689  3503  3531 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:33:15.689  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 12:33:15.692  1361  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 12:33:15.696  3503  3527 I BluetoothAdapterState: Entering OnState
09-07 12:33:15.697  1361  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 12:33:15.701  3441  3441 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 12:33:15.706  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:33:15.706  3441  3441 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 12:33:15.707  1361  2093 D BluetoothPan: onBluetoothStateChange on: true
,09-07 12:33:15.710  1361  1375 D BluetoothMap: onBluetoothStateChange: up=true
09-07 12:33:15.710  1969  2287 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:33:15.712   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:33:15.713   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:33:15.713   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:33:15.713   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:33:15.713  3441  3441 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 12:33:15.714   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:15.726  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:15.730  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:15.734  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:15.737  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:15.739  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:15.740  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:15.740   874  1408 I ActivityManager: Start proc 3577:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 12:33:15.741  3503  3503 D BluetoothMapService: onReceive
09-07 12:33:15.741  3503  3503 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:33:15.741  3503  3503 D BluetoothMapService: STATE_ON
,09-07 12:33:15.743  1361  1668 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-07 12:33:15.746  1361  1361 D BluetoothA2dp: Proxy object connected
,09-07 12:33:15.749  1361  1668 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 12:33:15.762  3503  3503 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 12:33:15.763  3503  3503 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 12:33:15.764  3503  3503 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:33:15.765  3503  3503 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:33:15.766  3503  3503 D ObexServerSockets: Succeed to create listening sockets 
,09-07 12:33:15.767  3503  3503 D ObexServerSockets0: startAccept()
09-07 12:33:15.767  3503  3503 D ObexServerSockets0: prepareForNewConnect()
,09-07 12:33:15.769  3503  3503 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-07 12:33:15.769  3503  3503 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-07 12:33:15.769  3503  3590 D ObexServerSockets0: Accepting socket connection...
09-07 12:33:15.770  3503  3591 D ObexServerSockets0: Accepting socket connection...
,09-07 12:33:15.776  3577  3577 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 12:33:15.812  1969  2163 D BluetoothHeadset: Proxy object connected
,09-07 12:33:15.813   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:33:15.814   874   891 D BluetoothHeadset: Proxy object connected
09-07 12:33:15.814   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:33:15.853  1361  2093 D BluetoothHeadset: Proxy object connected
,09-07 12:33:15.854  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-07 12:33:15.972  3577  3577 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:33:15.972  3577  3577 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.972  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:33:15.975  3577  3577 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:33:15.975  3577  3577 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251),
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:33:15.975  3577  3577 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:33:15.975  3577  3577 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.975  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:33:15.976  3577  3577 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.9,76  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:33:15.976  3577  3577 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:15.976  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:33:15.988  3557  3557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:33:15.994   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4a47f2:true
,09-07 12:33:15.999  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:33:16.007  3557  3557 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-07 12:33:16.013  3557  3557 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 12:33:16.022  1361  1361 D BluetoothPbap: Proxy object connected
,09-07 12:33:16.024  1361  1361 D PbapServerProfile: Bluetooth service connected
,09-07 12:33:16.031  3557  3557 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 12:33:16.032  3557  3557 D BluetoothMap: Create BluetoothMap proxy object
,09-07 12:33:16.044  3503  3609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:33:16.045  3557  3557 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 12:33:16.054  3557  3557 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:33:16.055  3557  3557 D BluetoothA2dp: Proxy object connected
,09-07 12:33:16.068  3557  3557 D BluetoothInputDevice: Proxy object connected
09-07 12:33:16.069  3557  3557 D HidProfile: Bluetooth service connected
09-07 12:33:16.073  3503  3615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:33:16.075  3557  3557 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:33:16.076  3557  3557 D PanProfile: Bluetooth service connected
09-07 12:33:16.076  3557  3557 D BluetoothMap: Proxy object connected
09-07 12:33:16.076  3557  3557 D MapProfile: Bluetooth service connected
09-07 12:33:16.076  3557  3557 D BluetoothMap: getConnectedDevices()
09-07 12:33:16.078  3557  3557 D BluetoothPbap: Proxy object connected
09-07 12:33:16.078  3503  3615 I BtOppRfcommListener: Accept thread started.
,09-07 12:33:16.078  3557  3557 D PbapServerProfile: Bluetooth service connected
09-07 12:33:16.080   874  2020 I ActivityManager: Killing 3170:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 12:33:16.118  3557  3569 D BluetoothHeadset: Proxy object connected
,09-07 12:33:16.119  3557  3557 D HeadsetProfile: Bluetooth service connected
,09-07 12:33:16.183  3577  3594 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 12:33:16.223   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2ab94c:true
,09-07 12:33:17.348   874   884 D WifiService: setWifiEnabled: true pid=3441, uid=10000
,09-07 12:33:17.349   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:33:17.364   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:17.381  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:17.388  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:17.394  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:17.395   874  1317 D WifiConfigStore: loaded 0 passpoint configs
,09-07 12:33:17.396   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 12:33:17.397   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 12:33:17.397   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 12:33:17.398   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 12:33:17.398   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 12:33:17.398   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 12:33:17.399  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:17.413   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 12:33:17.414   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:17.414   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '111 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 111 Failed to set address (No such device)'
,09-07 12:33:17.415   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 12:33:17.417   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 12:33:17.418   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 12:33:17.442   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:17.499   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:18.944   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-07 12:33:18.948   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 12:33:18.949   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:33:18.982   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 12:33:19.050   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 12:33:19.055  1476  1476 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 12:33:19.572  1476  1476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 12:33:19.635  1476  1476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 12:33:19.638  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 12:33:19.645   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:19.660   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 12:33:19.660   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:33:19.661   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 12:33:19.682   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:33:19.700   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:19.715   874  1317 D WifiStateMachine: Start Dhcp Watchdog 1
,09-07 12:33:19.736   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 12:33:19.736   874  1320 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-07 12:33:19.739   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 12:33:19.758   874  3625 D DhcpClient: Receive thread started
,09-07 12:33:19.840   874  1317 E native  : do suspend false
,09-07 12:33:19.864   874  3624 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 12:33:19.879   874  3625 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171122, domain null
,09-07 12:33:19.881   874  3624 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171122 seconds
,09-07 12:33:19.886   874  3624 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 12:33:19.919   874  3625 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 12:33:19.920   874  3624 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 12:33:19.925   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:19.935   874  3624 D DhcpClient: Scheduling renewal in 86399s
09-07 12:33:19.937   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 12:33:19.952   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 12:33:19.958   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 12:33:19.960   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 12:33:19.964   874  1320 D ConnectivityService: Adding iface wlan0 to network 100
,09-07 12:33:19.975   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 12:33:20.029   874  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 12:33:20.029   874  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,09-07 12:33:20.031   874  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,09-07 12:33:20.035   874  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,09-07 12:33:20.041   874  1320 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,09-07 12:33:20.052   874  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 12:33:20.057   874  1320 D ConnectivityService: scheduleUnvalidatedPrompt 100
,09-07 12:33:20.057   874  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,09-07 12:33:20.058   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-07 12:33:20.058   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 12:33:20.059   874  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
09-07 12:33:20.059   874  1320 D ConnectivityService:    accepting network in place of null
,09-07 12:33:20.062   874  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 12:33:20.074   874  3623 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118539, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 12:33:20.093   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:33:20.149   874  3622 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-07 12:33:20.150   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 12:33:20.155   874  1320 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,09-07 12:33:20.165   874  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-07 12:33:20.165   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:33:20.167   874  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
09-07 12:33:20.172   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 12:33:20.177   874  1951 V BackupManagerService: Scheduling immediate backup pass
09-07 12:33:20.179   874   874 V BackupManagerService: Running a backup pass
,09-07 12:33:20.179   874  1341 V BackupManagerService: clearing pending backups
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:20.185  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:33:20.188  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:20.193  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:33:20.196  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:33:20.198   874  1341 V PerformBackupTask: Beginning backup of 16 targets
09-07 12:33:20.199  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 12:33:20.216   874  1341 D PerformBackupTask: invokeAgentForBackup on @pm@
,09-07 12:33:20.218  1721  1721 D SystemUpdateService: onCreate,
,09-07 12:33:20.220   874  3622 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 10:33:19 GMT], X-Android-Received-Millis=[1473244400218], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473244400191]}
,09-07 12:33:20.221  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 12:33:20.222   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 12:33:20.222   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
,09-07 12:33:20.223   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-07 12:33:20.223   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 12:33:20.225  1721  3642 I SystemUpdateService: active receiver: enabled
09-07 12:33:20.232  1721  3642 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-07 12:33:20.233   874  1341 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,09-07 12:33:20.236  1721  3642 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 12:33:20.237  1721  3642 I SystemUpdateService: now status is 0 (complete)
,09-07 12:33:20.237  1721  3642 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 12:33:20.237  1721  3642 I SystemUpdateService: file has been verified
09-07 12:33:20.237  1721  3642 I SystemUpdateService: OTA package size = 12249756
,09-07 12:33:20.242   874  1941 D AlarmManagerService: Setting time of day to sec=1473244399
,09-07 12:33:19.478   874  1941 W AlarmManagerService: Unable to set rtc to 1473244399: Invalid argument
,09-07 12:33:19.480  1721  3642 I SystemUpdateService: showing system update notification
,09-07 12:33:19.501  1721  3650 I iu.SyncManager: SYNC; picasa accounts
,09-07 12:33:19.507  1721  1721 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-07 12:33:19.509  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 12:33:19.516  1721  3650 I iu.UploadsManager: num queued entries: 0
,09-07 12:33:19.517  1721  3650 I iu.UploadsManager: num updated entries: 0
,09-07 12:33:19.517  1721  3650 I iu.SyncManager: NEXT; no task
,09-07 12:33:19.519  1721  1721 D SystemUpdateService: onDestroy
,09-07 12:33:19.524  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 12:33:19.525  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 12:33:19.526  1721  3649 I MDM     : [144] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 12:33:19.526  1721  3649 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 12:33:19.532   874  1341 I BackupRestoreController: Getting widget state for user: 0
,09-07 12:33:19.536   874   885 I ActivityManager: Start proc 3652:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 12:33:19.556  1721  3649 V GoogleAuthProtoRequest: [144] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 12:33:19.562  3493  3646 V GoogleAuthProtoRequest: [274] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 12:33:19.564   874  3668 D GpsLocationProvider: NTP server returned: 1473244399479 (Wed Sep 07 12:33:19 GMT+02:00 2016) reference: 118710 certainty: 12 system time offset: -85
,09-07 12:33:19.564   874  3668 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,09-07 12:33:19.574  1902  1913 W GmsBackupTransport: Unknown package in backup request: @pm@
,09-07 12:33:19.575  1902  1913 V GmsBackupTransport: starting performBackup for @pm@
,09-07 12:33:19.585  1902  1913 V GmsBackupTransport: performBackup done for @pm@
,09-07 12:33:19.598  3503  3527 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 12:33:19.598  3503  3527 D BluetoothAdapterProperties: Setting state to 13
09-07 12:33:19.598  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 12:33:19.599  3503  3527 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 12:33:19.600  3503  3527 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:33:19.603  3652  3652 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 12:33:19.608  3652  3652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:33:19.608  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:19.611  3503  3531 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:33:19.611  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 12:33:19.614  3503  3503 D BluetoothMapService: onReceive
,09-07 12:33:19.614  3503  3503 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:33:19.615  3503  3503 D BluetoothMapService: STATE_TURNING_OFF
09-07 12:33:19.616  3503  3503 D HeadsetService: Received stop request...Stopping profile...
,09-07 12:33:19.619  3557  3569 D BluetoothHeadset: Proxy object disconnected
09-07 12:33:19.619  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:19.619  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:33:19.619   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 12:33:19.620  1969  2287 D BluetoothHeadset: Proxy object disconnected
09-07 12:33:19.620  3503  3503 D BluetoothMapService: MAP Service closeService in
,09-07 12:33:19.620  3503  3503 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 12:33:19.620  3503  3503 D ObexServerSockets0: shutdown(block = true)
09-07 12:33:19.620  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:19.620  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:33:19.620  3503  3503 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 12:33:19.620  3503  3503 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 12:33:19.621  3503  3591 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-07 12:33:19.621  3503  3590 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 12:33:19.621   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 12:33:19.621  1361  1375 D BluetoothHeadset: Proxy object disconnected
09-07 12:33:19.621  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-07 12:33:19.621   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 12:33:19.622  3503  3552 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 12:33:19.623  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 23
,09-07 12:33:19.623  3503  3503 I BtOppRfcommListener: stopping Accept Thread
09-07 12:33:19.623  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:19.623  3503  3615 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:19.623  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:33:19.623  3503  3615 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 12:33:19.624  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:19.624  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:19.625  3503  3503 D A2dpService: Received stop request...Stopping profile...
09-07 12:33:19.625  3503  3570 D A2dpStateMachine: Exit Disconnected: -1
,09-07 12:33:19.627  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.628  3557  3557 D HeadsetProfile: Bluetooth service disconnected
09-07 12:33:19.628   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 12:33:19.628  3557  3557 D BluetoothA2dp: Proxy object disconnected
09-07 12:33:19.629  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.630  3503  3503 D HidService: Received stop request...Stopping profile...
09-07 12:33:19.630  3503  3503 D HidService: Stopping Bluetooth HidService
09-07 12:33:19.631  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.632  3503  3503 V BluetoothAdapterState: isTurningOff()=true
,09-07 12:33:19.632  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:19.632  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:19.632  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:33:19.632  3557  3557 D BluetoothInputDevice: Proxy object disconnected
,09-07 12:33:19.632  3503  3503 D HealthService: Received stop request...Stopping profile...
09-07 12:33:19.632  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-07 12:33:19.632  3557  3557 D HidProfile: Bluetooth service disconnected
09-07 12:33:19.632  3503  3527 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
09-07 12:33:19.635  3503  3503 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 12:33:19.635  3503  3503 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 12:33:19.636  3503  3503 D PanService: Received stop request...Stopping profile...
09-07 12:33:19.637  3503  3550 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 12:33:19.637  3503  3550 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:33:19.637  3503  3550 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:33:19.637  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 12:33:19.637  3503  3531 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 12:33:19.638  3503  3503 D BluetoothMapService: Received stop request...Stopping profile...
09-07 12:33:19.638  3503  3503 D BluetoothMapService: stop()
09-07 12:33:19.638  3503  3503 D BluetoothMapAppObserver: deinitObservers()
09-07 12:33:19.638  3503  3503 D BluetoothMapAppObserver: removeReceiver()
09-07 12:33:19.638  3557  3557 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:33:19.639  3557  3557 D PanProfile: Bluetooth service disconnected
09-07 12:33:19.642  3557  3557 D BluetoothMap: Proxy object disconnected
09-07 12:33:19.642  3557  3557 D MapProfile: Bluetooth service disconnected
09-07 12:33:19.643  1361  1361 D BluetoothA2dp: Proxy object disconnected
,09-07 12:33:19.643  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-07 12:33:19.643  1361  1361 D HidProfile: Bluetooth service disconnected
09-07 12:33:19.643  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:33:19.644  1361  1361 D PanProfile: Bluetooth service disconnected
09-07 12:33:19.644  1361  1361 D BluetoothMap: Proxy object disconnected
,09-07 12:33:19.644  1361  1361 D MapProfile: Bluetooth service disconnected
09-07 12:33:19.645  3503  3503 V BluetoothAdapterState: isTurningOff()=true
,09-07 12:33:19.645  3503  3503 V BluetoothAdapterState: isTurningOn()=false
,09-07 12:33:19.645  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:19.645  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:33:19.646  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 12:33:19.646  3503  3550 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:33:19.646  3503  3550 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:33:19.646  3503  3550 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:33:19.646  3503  3550 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:33:19.646  3503  3550 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:33:19.646  3503  3550 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:33:19.646  3503  3503 V BluetoothAdapterState: isTurningOff()=true
09-07 12:33:19.646  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:19.647  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:19.647  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:19.647  3503  3503 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 12:33:19.647  3503  3503 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:33:19.647  3503  3503 V BluetoothAdapterState: isTurningOff()=true
09-07 12:33:19.647  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:19.647  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:33:19.647  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:33:19.647  3503  3503 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 12:33:19.648  3503  3503 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:33:19.648  3503  3531 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 12:33:19.648  3503  3503 V BluetoothAdapterState: isTurningOff()=true
,09-07 12:33:19.648  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:19.648  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:19.648  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:19.648  3503  3531 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 12:33:19.648  3503  3503 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:33:19.649  3503  3503 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 12:33:19.650  3503  3503 D BluetoothMapService: MAP Service closeService in
09-07 12:33:19.650  3503  3503 V BluetoothAdapterState: isTurningOff()=true
09-07 12:33:19.650  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:19.650  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:19.650  3503  3503 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:33:19.650  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 12:33:19.651  3503  3527 D BluetoothAdapterProperties: Setting state to 15
09-07 12:33:19.651  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 12:33:19.651  3503  3527 I BluetoothAdapterState: Entering BleOnState
09-07 12:33:19.651  3503  3527 D BluetoothAdapterState: Current state: BLE ON, message: 0
,09-07 12:33:19.651  1361  2093 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 12:33:19.651  3503  3503 D BluetoothMapService: cleanup()
09-07 12:33:19.651  3503  3503 D BluetoothMapService: MAP Service closeService in
09-07 12:33:19.653  1361  1375 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:33:19.654  1361  1374 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:33:19.655  1361  1375 D BluetoothMap: onBluetoothStateChange: up=false
09-07 12:33:19.656  1969  2287 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:33:19.656  3557  3569 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:33:19.657  1361  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:33:19.658  1361  2093 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 12:33:19.658   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:33:19.659  3557  3568 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 12:33:19.659  1519  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
09-07 12:33:19.659  1519  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
09-07 12:33:19.659  1519  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:19.659  1519  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:19.659  3557  3569 D BluetoothMap: onBluetoothStateChange: up=false
09-07 12:33:19.659  3557  3568 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:33:19.660   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:33:19.660   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:33:19.660   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:33:19.660  3557  3569 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:33:19.661  3557  3568 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:33:19.663  3503  3527 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 12:33:19.663  3503  3527 D BluetoothAdapterProperties: Setting state to 16
,09-07 12:33:19.663  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 12:33:19.664  3503  3527 D BluetoothAdapterProperties: onBleDisable
09-07 12:33:19.665  3503  3528 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 12:33:19.665  3503  3550 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 12:33:19.666  3503  3550 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:33:19.666  3503  3531 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:33:19.665  3503  3527 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:33:19.671  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.673  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.676  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.677  1721  3667 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
09-07 12:33:19.678  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:19.678  1519  2007 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:33:19.678  1519  2007 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:33:19.678  1519  2007 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:33:19.678  1519  2007 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 12:33:19.678  1519  2007 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 12:33:19.678  1519  2007 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 12:33:19.678  1519  2007 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: Error sending final backup to server: 
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 12:33:19.682  1902  2149 W GmsBackupTransport: 	... 1 more
,09-07 12:33:19.683  1902  1912 I GmsBackupTransport: Next backup will happen in 43199997 millis.
09-07 12:33:19.683   874  1341 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
09-07 12:33:19.685  3652  3652 D SprintDMHelper: simOperator: 
09-07 12:33:19.685  3652  3652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 12:33:19.693  1519  2001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 12:33:19.693  1519  2001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 12:33:19.693  1519  2001 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:33:19.693  1519  2001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:19.702   874  2020 I ActivityManager: Start proc 3677:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 12:33:19.761   874  1341 I BackupManagerService: Backup pass finished.
,09-07 12:33:19.761  1721  3649 E MDM     : [144] SitrepService.a: Error sending sitrep.
,09-07 12:33:19.762  1519  2807 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-07 12:33:19.763  1519  2807 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,09-07 12:33:19.763  1519  2807 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:19.763  1519  2807 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:19.820   874  2218 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1721 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: [274] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: [274] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 12:33:19.836  3493  3646 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 12:33:19.849  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:19.868  3503  3531 I bt_hci  : shut_down
,09-07 12:33:19.873  3503  3538 D bt_hwcfg: hw_epilog_process
,09-07 12:33:19.873  3503  3538 I bt_vendor: low_power_mode_cb
,09-07 12:33:19.900  3503  3538 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-07 12:33:19.900  3503  3538 I bt_vendor: epilog_cb
09-07 12:33:19.900  3503  3538 I bt_hci  : epilog_finished_callback
09-07 12:33:19.902  3503  3531 I bt_hci_h4: hal_close
09-07 12:33:19.902  3503  3531 I bt_userial_vendor: device fd = 51 close
,09-07 12:33:19.931   874   886 I ActivityManager: Start proc 3698:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-07 12:33:19.939  1721  3669 W DriveInitializer: Awaiting to be initialized
09-07 12:33:19.940  1721  3709 W DriveInitializer: Background init thread started
,09-07 12:33:19.962  3698  3698 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-07 12:33:20.012  3503  3528 D bt_stack_manager: event_shut_down_stack finished.
,09-07 12:33:20.013  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 12:33:20.014  3503  3503 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:33:20.014  3503  3503 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 12:33:20.014  3503  3503 D BtGatt.GattService: stop()
09-07 12:33:20.014  3503  3503 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 12:33:20.015  3503  3503 V BluetoothAdapterState: isTurningOff()=false
09-07 12:33:20.015  3503  3503 V BluetoothAdapterState: isTurningOn()=false
09-07 12:33:20.015  3503  3503 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:33:20.015  3503  3503 V BluetoothAdapterState: isBleTurningOff()=true
09-07 12:33:20.017  3503  3527 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 12:33:20.017  3503  3527 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 12:33:20.017  3503  3527 D BluetoothAdapterProperties: Setting state to 10
09-07 12:33:20.017  3503  3527 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 12:33:20.017  3503  3527 I BluetoothAdapterState: Entering OffState
09-07 12:33:20.021  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:20.022  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:20.040  1721  3709 W DriveInitializer: Background init thread ended
,09-07 12:33:20.080  1519  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 12:33:20.080  1519  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 12:33:20.080  1519  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:20.080  1519  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:20.089   874  2140 I ActivityManager: Start proc 3725:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 12:33:20.107  3254  3689 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 12:33:20.107  3254  3689 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jdm.a(PG:82)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jcs.o(PG:406)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jcn.a(PG:1379)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jcs.i(PG:143)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at blb.a(PG:3937)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at czp.a(PG:18188)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at czp.a(PG:9081)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at czq.run(PG:1686)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 12:33:20.107  3254  3689 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jdj.a(PG:4091)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jdj.a(PG:1125)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jdm.a(PG:77)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	... 12 more
09-07 12:33:20.107  3254  3689 E HttpOperation: Caused by: faj: BadAuthentication
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at fal.a(PG:38)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	at jdj.a(PG:4089)
09-07 12:33:20.107  3254  3689 E HttpOperation: 	... 14 more
,09-07 12:33:20.145  1519  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 12:33:20.146  1519  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 12:33:20.146  1519  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:20.146  1519  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:20.157  3254  3689 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 12:33:20.157  3254  3689 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jdm.a(PG:82)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jcs.o(PG:406)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jcn.a(PG:1379)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jcs.i(PG:143)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at hec.a(PG:42)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at hee.a(PG:102)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at czr.a(PG:65)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at kka.a(PG:108)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at czp.a(PG:19176)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at czp.a(PG:9081)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at czq.run(PG:1686)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 12:33:20.157  3254  3689 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jdj.a(PG:4091)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jdj.a(PG:1125)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jdm.a(PG:77)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	... 15 more
09-07 12:33:20.157  3254  3689 E HttpOperation: Caused by: faj: BadAuthentication
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at fal.a(PG:38)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	at jdj.a(PG:4089)
09-07 12:33:20.157  3254  3689 E HttpOperation: 	... 17 more
09-07 12:33:20.157  3254  3689 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 12:33:20.157  3254  3689 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at hec.a(PG:42)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at hee.a(PG:102)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at czr.a(PG:65)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at kka.a(PG:108)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	... 15 more
09-07 12:33:20.157  3254  3689 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at fal.a(PG:38)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 12:33:20.157  3254  3689 E ExperimentLoader: 	... 17 more
09-07 12:33:20.158  3698  3698 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 12:33:20.165  3725  3725 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
09-07 12:33:20.165  3698  3698 I BooksApp: Created application version: 3.6.9 (30609)
,09-07 12:33:20.250  2857  3730 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-07 12:33:20.298  3698  3746 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 12:33:20.361   874  1395 I ActivityManager: Killing 2619:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 12:33:20.361   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 26314, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 12:33:20.441  3725  3725 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 12:33:20.441  3725  3725 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 12:33:20.441  3725  3725 I GAv4    :   adb logcat -s GAv4
,09-07 12:33:20.475  3725  3725 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:33:20.482  3725  3725 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:33:20.511  3725  3758 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:33:20.565  3003  3756 V KeepSync: Connecting to GoogleApiClient
,09-07 12:33:20.566   874  1699 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 12:33:20.705  1519  2805 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 12:33:20.705  1519  2805 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 12:33:20.706  1519  2805 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:20.706  1519  2805 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:20.744  1721  3761 V BaseAuthAsyncOperation: access token request failed
,09-07 12:33:20.747  3003  3756 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 12:33:20.819  3725  3725 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 12:33:20.872  3698  3778 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 12:33:20.906  3725  3725 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 12:33:20.916  3725  3725 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 146-148)
,09-07 12:33:20.916  3725  3725 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 12:33:20.961  3725  3725 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9681f83}
,09-07 12:33:20.962  3725  3725 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:33:20.962  3725  3725 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 12:33:20.968  3725  3725 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 12:33:20.969  1519  2007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 12:33:20.969  3725  3725 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 12:33:20.969  1519  2007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 12:33:20.970  1519  2007 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:20.970  1519  2007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:21.004  3725  3725 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 12:33:21.016  3725  3725 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:33:21.016  3725  3725 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:33:21.016  3725  3725 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 12:33:21.016  3725  3725 I Adreno  : Build Date                       : 10/20/15
09-07 12:33:21.016  3725  3725 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 12:33:21.016  3725  3725 I Adreno  : Local Branch                     : M14
09-07 12:33:21.016  3725  3725 I Adreno  : Remote Branch                    : 
09-07 12:33:21.016  3725  3725 I Adreno  : Remote Branch                    : 
09-07 12:33:21.016  3725  3725 I Adreno  : Reconstruct Branch               : 
,09-07 12:33:21.023  1519  2804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 12:33:21.024  1519  2804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 12:33:21.024  1519  2804 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:21.024  1519  2804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:21.041  3698  3778 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 12:33:21.043  3698  3746 E BooksSync: Soft error
09-07 12:33:21.043  3698  3746 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 12:33:21.043  3698  3746 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 12:33:21.043  3698  3746 E BooksSync: Sync error
09-07 12:33:21.043  3698  3746 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 12:33:21.043  3698  3746 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 12:33:21.043  3698  3746 I BooksSync: Finished books sync
,09-07 12:33:21.052   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26329, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 12:33:21.095  3725  3725 I NSApplication: Starting up...
,09-07 12:33:21.100  3725  3792 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 12:33:21.130   874   885 I ActivityManager: Start proc 3797:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-07 12:33:21.131   874   885 I ActivityManager: Killing 2950:android.process.acore/u0a5 (adj 15): empty #17
,09-07 12:33:21.199  3797  3797 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
09-07 12:33:21.200  1519  2805 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 12:33:21.200  1519  2805 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 12:33:21.200  1519  2805 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:21.201  1519  2805 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:21.220  3003  3756 E KeepSync: IOException
09-07 12:33:21.220  3003  3756 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 12:33:21.220  3003  3756 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 12:33:21.220  3003  3756 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 12:33:21.220  3003  3756 E KeepSync: 	... 10 more
,09-07 12:33:21.220  3003  3756 W KeepSync: Sync result 2
,09-07 12:33:21.227   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 26329, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 12:33:21.228   874  1951 I ActivityManager: Killing 3334:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 12:33:21.330   874  1700 I ActivityManager: Killing 3349:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 12:33:21.647   874  1699 I ActivityManager: Killing 2126:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 12:33:21.774   874   885 I ActivityManager: Start proc 3817:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,09-07 12:33:21.825  3817  3817 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,09-07 12:33:21.889   874  2020 I ActivityManager: Start proc 3832:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,09-07 12:33:21.973  3832  3832 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,09-07 12:33:21.980   874  1408 I ActivityManager: Start proc 3847:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,09-07 12:33:21.981   874  1408 I ActivityManager: Killing 3300:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-07 12:33:21.992   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 12:33:22.049   874  1408 I ActivityManager: Killing 3372:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,09-07 12:33:22.133  3832  3832 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@461c499(com.android.providers.calendar.CalendarProvider2@edd835e)
,09-07 12:33:22.161  3817  3817 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,09-07 12:33:22.172  3847  3847 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-07 12:33:22.193  3847  3847 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-07 12:33:22.193  3847  3847 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 12:33:22.193  3847  3847 I GAv4    :   adb logcat -s GAv4
,09-07 12:33:22.208  3847  3847 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:33:22.216  3847  3847 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:33:22.228  3847  3863 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:33:22.318   874  1408 I ActivityManager: Start proc 3866:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,09-07 12:33:22.371  3866  3866 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,09-07 12:33:22.381  3866  3866 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473244402381
,09-07 12:33:22.381  3866  3866 D         : TimeServiceNative: User Time to be set is 1473244402381
09-07 12:33:22.382  3866  3866 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-07 12:33:22.382  3866  3866 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-07 12:33:22.382  3866  3866 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473244402381
09-07 12:33:22.382  3866  3866 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-07 12:33:22.382   421   983 D QC-time-services: Daemon: Connection accepted:time_genoff
09-07 12:33:22.383   421  3878 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473244402381
,09-07 12:33:22.383   421  3878 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473244402381, operation = 0
09-07 12:33:22.384   421  3878 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/24/71 6:43:25
,09-07 12:33:22.384   421  3878 D QC-time-services: Daemon:Value read from RTC seconds = 33547405000
09-07 12:33:22.385   421  3878 D QC-time-services: Daemon:new time 1473244402381 
,09-07 12:33:22.385   421  3878 D QC-time-services: Daemon: delta 1439696997381 genoff 1439696997381 
09-07 12:33:22.385   421  3878 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696997381 to memory
,09-07 12:33:22.385   421  3878 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-07 12:33:22.385   421  3878 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-07 12:33:22.398   421  3878 D QC-time-services: Updating the TOD offset
,09-07 12:33:22.399   421  3878 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696997381 to memory
09-07 12:33:22.399   421  3878 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-07 12:33:22.399   421  3878 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-07 12:33:22.404   421  3878 E QC-time-services: Daemon:Update to modem bit set
,09-07 12:33:22.404   421  3878 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-07 12:33:22.404   421  3878 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1157279602381
09-07 12:33:22.405  3866  3866 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,09-07 12:33:22.409  3557  3557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:33:22.418  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:33:22.420  3557  3557 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:33:22.430   874  2013 I ActivityManager: Killing 2729:com.android.vending/u0a19 (adj 15): empty #17
,09-07 12:33:22.477   421   983 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-07 12:33:22.483   421   981 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,09-07 12:33:22.495  3557  3557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:33:22.502  3557  3557 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:33:22.502  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:33:22.515  3557  3557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:33:22.525  3557  3557 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:33:22.536  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:33:23.258  3832  3832 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,09-07 12:33:23.259  3832  3832 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,09-07 12:33:25.190  3698  3744 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 12:33:25.647  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:25.650   874  2020 D WifiService: setWifiEnabled: false pid=3441, uid=10000
09-07 12:33:25.650   874  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:33:25.677  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 12:33:25.678   874  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 12:33:25.679   874  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 12:33:25.679   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 12:33:25.679   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:33:25.704   874  3624 D DhcpClient: Clearing IP address
,09-07 12:33:25.705   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:33:25.708   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:25.716  1519  3676 V NativeCrypto: Read error: ssl=0x9a435000: I/O error during system call, Connection timed out
,09-07 12:33:25.718  1519  3676 V NativeCrypto: SSL shutdown failed: ssl=0x9a435000: I/O error during system call, Broken pipe
,09-07 12:33:25.721   874  1956 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-07 12:33:25.722   874  3622 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-07 12:33:25.723   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 12:33:25.723   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-07 12:33:25.728   428   428 E Parcel  : Reading a NULL string not supported here.
,09-07 12:33:25.731   874  3622 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-07 12:33:25.733   874  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 12:33:25.733   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 12:33:25.737   874  3625 D DhcpClient: Receive thread stopped
09-07 12:33:25.740   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:33:25.750   874  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-07 12:33:25.755   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:25.759  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:25.759  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:25.759  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:25.759  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:33:25.760   874  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 12:33:25.761  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:25.761  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:25.761  1902  2288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:33:25.762  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:25.762  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:25.783   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:33:25.796  1519  3901 I VacuumService: Vacuum at: now=1473244405796 tag=VacuumService
,09-07 12:33:25.815   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:33:25.816   874  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-07 12:33:25.817   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 12:33:25.820   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 12:33:25.823  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:25.825  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:33:25.830  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 12:33:25.834  1721  1721 D SystemUpdateService: onCreate
,09-07 12:33:25.836  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 12:33:25.844  1721  3904 I SystemUpdateService: active receiver: enabled
09-07 12:33:25.844  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 12:33:25.850  1721  3650 I iu.UploadsManager: num queued entries: 0
,09-07 12:33:25.850  1721  3650 I iu.UploadsManager: num updated entries: 0
,09-07 12:33:25.852  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 12:33:25.853  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 12:33:25.856  3652  3652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:33:25.860  3652  3652 D SprintDMHelper: simOperator: 
,09-07 12:33:25.860  3652  3652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 12:33:25.869  1721  3904 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 12:33:25.884   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 12:33:25.885   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 12:33:25.900  2857  3909 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 12:33:25.902  1721  3904 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 12:33:25.903  1721  3904 I SystemUpdateService: now status is 0 (complete)
,09-07 12:33:25.903  1721  3904 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 12:33:25.907  1721  3904 I SystemUpdateService: file has been verified
09-07 12:33:25.907  1721  3904 I SystemUpdateService: OTA package size = 12249756
09-07 12:33:25.908  1721  3650 I iu.SyncManager: NEXT; no task,
,09-07 12:33:25.912  1721  3904 I SystemUpdateService: showing system update notification
,09-07 12:33:25.922  1721  1721 D SystemUpdateService: onDestroy
,09-07 12:33:26.970  3817  3838 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 12:33:27.294   874  1320 D ConnectivityService: handlePromptUnvalidated 100
,09-07 12:33:28.429   874  1700 I ActivityManager: Killing 2054:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,09-07 12:33:28.478   874  1319 D WifiService: Client connection lost with reason: 4
,09-07 12:33:28.663  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:28.665   874   884 D WifiService: setWifiEnabled: true pid=3441, uid=10000
,09-07 12:33:28.665   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:33:28.685   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,09-07 12:33:28.691  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:28.692  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:33:28.694  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:28.694  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:28.700  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:33:28.701  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:33:28.703  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:28.703  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:33:28.718   874  1317 D WifiConfigStore: loaded 0 passpoint configs
,09-07 12:33:28.719   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 12:33:28.720   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 12:33:28.721   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 12:33:28.721   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 12:33:28.721   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 12:33:28.721   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 12:33:28.733   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 12:33:28.733   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=2.12 rxSuccessRate=1.69 delta 1000 -> 1000
,09-07 12:33:28.734   373   872 D CommandListener: Setting iface cfg
09-07 12:33:28.735   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
,09-07 12:33:28.735   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 12:33:28.738   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 12:33:28.743   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 12:33:28.743   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 12:33:28.744   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:33:28.755   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 12:33:28.829   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 12:33:29.871  1476  1476 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 12:33:30.231   874  2020 I ActivityManager: Start proc 3920:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,09-07 12:33:30.298  1476  1476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 12:33:30.327  1476  1476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:33:30.327  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 12:33:30.333   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:33:30.341  3920  3920 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,09-07 12:33:30.345   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 12:33:30.345   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:33:30.345   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 12:33:30.369   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:33:30.382   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:30.383   874  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 12:33:30.400   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 12:33:30.400   874  1320 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-07 12:33:30.403   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 12:33:30.419   874  3938 D DhcpClient: Receive thread started
,09-07 12:33:30.423  3920  3920 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-07 12:33:30.477  3920  3920 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,09-07 12:33:30.491  3920  3920 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 12:33:30.492  3920  3920 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 12:33:30.497   874  1317 E native  : do suspend false
,09-07 12:33:30.510   874  3624 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 12:33:30.536   874  3938 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172789, domain null
,09-07 12:33:30.537   874  3624 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172789 seconds
,09-07 12:33:30.540   874  3624 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 12:33:30.542   874  1395 I ActivityManager: Killing 3698:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-07 12:33:30.569   874  3938 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 12:33:30.600   874  3624 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 12:33:30.604  3920  3920 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-07 12:33:30.605  3920  3920 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,09-07 12:33:30.605   373   872 D CommandListener: Setting iface cfg
,09-07 12:33:30.610   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 12:33:30.614   874  3624 D DhcpClient: Scheduling renewal in 86399s
,09-07 12:33:30.619  3920  3956 D Ads     : Skipping gmscore version check
,09-07 12:33:30.621   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 12:33:30.623   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 12:33:30.624   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 12:33:30.625   874  1320 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 12:33:30.642  3920  3920 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-07 12:33:30.648   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 12:33:30.659  3920  3920 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 12:33:30.665  3920  3956 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 12:33:30.669   874  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 12:33:30.669   874  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-07 12:33:30.670   874  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 12:33:30.672   874  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 12:33:30.673   874  1320 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 12:33:30.682   874  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 12:33:30.686   874  1320 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 12:33:30.686   874  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-07 12:33:30.687   874  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 12:33:30.687   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 12:33:30.687   874  1320 D ConnectivityService:    accepting network in place of null
09-07 12:33:30.687   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 12:33:30.687   874  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 12:33:30.693   874  3933 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129926, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 12:33:30.705   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:33:30.723   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:33:30.731   874  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 12:33:30.731   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:33:30.735   874  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 12:33:30.736   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 12:33:30.757  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:30.758  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:33:30.758  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:30.758  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:33:30.762  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:30.762  3441  3441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:33:30.762  3441  3441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:30.762  3441  3441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:33:30.764  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 12:33:30.769  1721  1721 D SystemUpdateService: onCreate
,09-07 12:33:30.772  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 12:33:30.775   874  3932 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-07 12:33:30.787  1721  3968 I SystemUpdateService: active receiver: enabled
,09-07 12:33:30.790  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 12:33:30.795  1721  3650 I iu.UploadsManager: num queued entries: 0
,09-07 12:33:30.799  1721  3650 I iu.UploadsManager: num updated entries: 0
09-07 12:33:30.800  1721  3968 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 12:33:30.801  1721  3968 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 12:33:30.801  1721  3968 I SystemUpdateService: now status is 0 (complete)
,09-07 12:33:30.802  1721  3968 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 12:33:30.802  1721  3968 I SystemUpdateService: file has been verified
09-07 12:33:30.802  1721  3968 I SystemUpdateService: OTA package size = 12249756
,09-07 12:33:30.805  1721  3650 I iu.SyncManager: NEXT; no task
,09-07 12:33:30.807  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 12:33:30.809  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 12:33:30.812  1721  3968 I SystemUpdateService: showing system update notification
,09-07 12:33:30.816  3652  3652 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:33:30.821  1721  3971 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 12:33:30.821  1721  3971 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 12:33:30.823  3652  3652 D SprintDMHelper: simOperator: 
,09-07 12:33:30.823  3652  3652 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 12:33:30.826  1721  3971 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 12:33:30.843  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:30.846  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:30.849   874  3932 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 10:33:30 GMT], X-Android-Received-Millis=[1473244410849], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473244410818]}
09-07 12:33:30.850   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 12:33:30.851   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed,
09-07 12:33:30.851   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 12:33:30.854   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 12:33:30.875  1721  1721 D SystemUpdateService: onDestroy
,09-07 12:33:30.879  1519  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 12:33:30.880  1519  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 12:33:30.880  1519  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:33:30.880  1519  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:30.894  1721  3971 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-07 12:33:30.978  2857  3973 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 12:33:31.066  1519  3979 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-07 12:33:31.075  1519  3979 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 12:33:31.118  1519  3979 W Uploader:  no longer exists, so no auth token.
,09-07 12:33:31.487  3920  3920 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-07 12:33:31.515  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:31.581  1519  2001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:33:31.582  1519  2001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 12:33:31.582  1519  2001 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:33:31.583  1519  2001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:31.636  3920  3920 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 12:33:31.662  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:31.689  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:31.705  3441  3989 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-07 12:33:31.706  3441  3989 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 12:33:31.716  1519  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:33:31.716  1519  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 12:33:31.716  1519  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:31.717  1519  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:31.729   874  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 12:33:31.744   874  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 3, 6 -> obsolete
,09-07 12:33:31.769  3920  3991 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 12:33:31.771  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:31.775  3920  3920 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,09-07 12:33:31.775  3920  3920 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,09-07 12:33:31.808  1519  2804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:33:31.809  1519  2804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:33:31.809  1519  2804 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:31.809  1519  2804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:31.833  3920  3920 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 12:33:32.071  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:33:32.103  1519  2806 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:33:32.103  1519  2806 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:33:32.103  1519  2806 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:32.103  1519  2806 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:32.128  3920  3920 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
09-07 12:33:32.129  3920  3920 D Finsky  : [1] WearSupportService.startHygiene: disabled
09-07 12:33:32.130  3920  3920 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-07 12:33:32.135  3920  3920 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 749 minutes (failures=5)
,09-07 12:33:32.145  3920  3993 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 12:33:33.007  1519  3979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 12:33:33.007  1519  3979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 12:33:33.008  1519  3979 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:33.008  1519  3979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:33.056  1519  3979 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:33:33.056  1519  3979 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 12:33:33.056  1519  3979 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 12:33:34.724  3441  3998 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-07 12:33:34.725  3441  3989 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-07 12:33:34.725  3441  3998 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-07 12:33:34.726  3441  3989 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 12:33:34.727  3441  3989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:34.727  3441  3998 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:34.729  3441  3989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 12:33:34.730  3441  3998 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:34.730  3441  3989 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 12:33:34.732  3441  3998 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 12:33:34.733  3441  4004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: IncomingSocketThread/Receiver)
,09-07 12:33:34.736  3441  4004 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: IncomingSocketThread/Receiver)
,09-07 12:33:34.736  3441  4003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
,09-07 12:33:34.737  3441  4003 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
,09-07 12:33:34.736  3441  4004 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 12:33:34.737  3441  4003 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-07 12:33:34.737  3441  4004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-07 12:33:34.738  3441  4001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Sender)
09-07 12:33:34.738  3441  4003 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 12:33:34.739  3441  4002 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Sender)
,09-07 12:33:34.742  1519  3979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-07 12:33:34.743  1519  3979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-07 12:33:34.743  1519  3979 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:33:34.743  1519  3979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:34.759  1519  3979 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:33:34.759  1519  3979 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 12:33:34.759  1519  3979 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 12:33:35.408  1519  3979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 12:33:35.409  1519  3979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 12:33:35.409  1519  3979 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:33:35.409  1519  3979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:33:35.433  1519  3979 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:33:35.433  1519  3979 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 12:33:35.433  1519  3979 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 12:33:37.731  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 12:33:37.737  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 12:33:37.744  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@718db37 Bundle[{}]
,09-07 12:33:37.746  3441  3489 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 12:33:37.746  3441  3489 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 12:33:37.749  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 12:33:37.751  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 12:33:37.753  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 12:33:37.756  3441  3489 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 12:33:37.765  3441  4007 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 12:33:37.765  3441  4007 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 12:33:37.777  3441  4009 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-07 12:33:37.778  3441  4009 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 12:33:37.778  3441  4009 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:37.778  3441  4007 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-07 12:33:37.778  3441  4007 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 12:33:37.779  3441  4007 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:37.779  3441  4009 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:37.781  3441  4007 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:37.781  3441  4012 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: IncomingSocketThread/Sender)
09-07 12:33:37.782  3441  4009 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 12:33:37.782  3441  4013 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: OutgoingSocketThread/Sender)
09-07 12:33:37.783  3441  4007 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 12:33:37.783  3441  4014 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: IncomingSocketThread/Receiver)
09-07 12:33:37.784  3441  4014 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: IncomingSocketThread/Receiver)
09-07 12:33:37.784  3441  4014 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 12:33:37.784  3441  4014 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 12:33:37.791  3441  4015 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: OutgoingSocketThread/Receiver)
09-07 12:33:37.792  3441  4015 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: OutgoingSocketThread/Receiver)
09-07 12:33:37.792  3441  4015 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 12:33:37.793  3441  4015 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 12:33:38.693   874  1320 D ConnectivityService: handlePromptUnvalidated 101
,09-07 12:33:39.270   874  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 4, 6 -> obsolete
,09-07 12:33:40.789  3441  3489 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 464)
,09-07 12:33:40.792  3441  3489 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 12:33:40.792  3441  3489 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 465)
,09-07 12:33:40.796  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:33:40.797  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d5791 added. We now have 3 listener(s)
,09-07 12:33:40.798  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 12:33:40.799  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:33:40.799  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:33:40.799  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 12:33:40.799  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62a6f6 added. We now have 3 listener(s)
,09-07 12:33:40.799  3441  3489 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:33:40.800  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:33:40.811  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:40.817  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:33:40.817  3441  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:33:40.818  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:33:40.818  3441  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:33:40.818  3441  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:33:40.819  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:33:40.821  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:40.821  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:40.821  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:33:40.821  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:33:40.821  3441  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d5791 removed from the list
09-07 12:33:40.821  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:33:40.821  3441  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62a6f6 removed from the list
09-07 12:33:40.823  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:40.826  3441  3441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:33:40.827  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:33:40.827  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:33:40.828  3441  3489 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,09-07 12:33:40.828  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-07 12:33:40.830  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 12:33:40.830  3441  3489 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 12:33:40.830  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
09-07 12:33:40.830  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:40.833  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-07 12:33:40.833  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-07 12:33:40.834  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:40.834  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
09-07 12:33:40.834  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 12:33:40.835  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:40.835  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:33:40.838  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 12:33:40.839  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:40.839  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:33:40.840  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 12:33:40.841  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:40.841  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:33:40.841  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 12:33:40.841  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 12:33:40.841  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:33:40.841  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d5791 not in the list
,09-07 12:33:40.841  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:40.841  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:40.841  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 12:33:40.842  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:40.842  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:33:40.842  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:40.843  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:33:40.844  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:40.844  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:40.844  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:33:40.844  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62a6f6 not in the list
09-07 12:33:40.844  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:40.844  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:40.844  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:33:40.845  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:33:40.846  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:33:40.846  3441  3489 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:33:40.846  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 12:33:40.847  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:33:40.847  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:33:40.850  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 12:33:40.851  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:40.851  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:40.851  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 12:33:41.352  3441  3441 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-07 12:33:41.353  3441  3441 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 12:33:43.838   874  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 5, 6 -> obsolete
,09-07 12:33:43.852  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 12:33:43.855  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:33:43.855  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:33:43.856  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 12:33:43.856  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d5791 not in the list
09-07 12:33:43.856  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:43.857  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:43.857  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:33:43.857  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:43.859  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:33:43.860  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:33:43.865  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:33:43.865  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:43.866  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:33:43.866  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:33:43.867  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62a6f6 not in the list
09-07 12:33:43.867  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:33:43.868  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:33:43.868  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:33:43.871  3441  3489 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-07 12:33:43.872  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-07 12:33:43.872  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 12:33:43.873  3441  3489 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 12:33:43.873  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 12:33:43.873  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:43.873  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-07 12:33:43.874  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:33:43.874  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-07 12:33:43.874  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
,09-07 12:33:43.875  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 12:33:43.875  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:33:43.875  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:33:43.879  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 12:33:43.881  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:33:43.881  3441  3489 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:33:43.882  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 12:33:43.883  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:43.883  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:33:43.888  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:33:43.888  3441  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 12:33:43.888  3441  3441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:33:43.889  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d5791 not in the list
09-07 12:33:43.889  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:43.889  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:33:43.889  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:33:43.889  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:33:43.889  3441  3489 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:33:43.890  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:43.891  3441  3489 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:43.891  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:43.891  3441  3441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:33:43.892  3441  3441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:33:43.892  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62a6f6 not in the list
09-07 12:33:43.892  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:43.892  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:43.892  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:43.893  3441  3489 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:33:43.893  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:43.893  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:43.893  3441  3489 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d5791 not in the list
09-07 12:33:43.893  3441  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:33:43.893  3441  3489 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a62a6f6 not in the list
,09-07 12:33:43.894  3441  3489 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:33:43.894  3441  3489 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:33:43.894  3441  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:33:43.894  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 12:33:43.895  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 12:33:43.895  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 12:33:43.895  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:33:43.895  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 12:33:43.895  3441  3489 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 12:33:43.902  3441  4017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 483, name: My test thread name)
,09-07 12:33:44.393  3441  3441 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 12:33:45.514   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 12:33:45.902  3441  3489 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 483
,09-07 12:33:45.902  3441  3489 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 483, name: My test thread name)
,09-07 12:33:45.909  3441  4018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 484, name: My test thread name)
,09-07 12:33:45.909  3441  4018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 484, thread name: My test thread name)
,09-07 12:33:45.910  3441  4018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 484, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-07 12:33:45.914  3441  3489 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 12:33:45.924  3441  4019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: My test thread name)
,09-07 12:33:45.925  3441  4019 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 488, thread name: My test thread name): Test exception.
09-07 12:33:45.925  3441  4019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-07 12:33:45.928  3441  3489 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 12:33:45.928  3441  3489 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner: Proper state of BT is set when switched on
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner: Expected: is <false>
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner:      but: was <true>
,09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner: Returns proper state of BT when switched on
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-07 12:33:45.929  3441  3489 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 12:33:45.930  3441  3489 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-07 12:33:45.930  3441  3489 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-07 12:33:45.930  3441  3489 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should affect listening to advertisements only>
09-07 12:33:45.930  3441  3489 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
,09-07 12:33:45.930  3441  3489 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
09-07 12:33:45.931  3441  3489 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 74
09-07 12:33:45.931  3441  3489 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  8
09-07 12:33:45.931  3441  3489 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 12:33:45.932  3441  3489 D com.test.thalitest.ThaliTestRunner: Total duration: 31729 ms
,09-07 12:33:45.936  3441  3489 I jxcore-log: Total number of executed tests:  82
09-07 12:33:45.936  3441  3489 I jxcore-log: 
,09-07 12:33:45.937  3441  3489 I jxcore-log: Number of passed tests:  74
09-07 12:33:45.937  3441  3489 I jxcore-log: 
09-07 12:33:45.938  3441  3489 I jxcore-log: Number of failed tests:  8
09-07 12:33:45.938  3441  3489 I jxcore-log: 
,09-07 12:33:45.940  3441  3489 I jxcore-log: Number of ignored tests:  0
09-07 12:33:45.940  3441  3489 I jxcore-log: 
09-07 12:33:45.941  3441  3489 I jxcore-log: Total duration:  31729
09-07 12:33:45.941  3441  3489 I jxcore-log: 
,09-07 12:33:45.945  3441  3489 I jxcore-log: Failed to execute UT.
09-07 12:33:45.945  3441  3489 I jxcore-log: 
,09-07 12:33:45.945  3441  3489 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-07 12:33:45.945  3441  3489 I jxcore-log: 
,09-07 12:33:45.948  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.948  3441  3489 I jxcore-log: 
09-07 12:33:45.949  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.949  3441  3489 I jxcore-log: 
09-07 12:33:45.951  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.951  3441  3489 I jxcore-log: 
09-07 12:33:45.952  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.952  3441  3489 I jxcore-log: 
09-07 12:33:45.953  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.953  3441  3489 I jxcore-log: 
09-07 12:33:45.956  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.956  3441  3489 I jxcore-log: 
09-07 12:33:45.957  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:33:45.957  3441  3489 I jxcore-log: 
09-07 12:33:45.958  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:33:45.958  3441  3489 I jxcore-log: 
09-07 12:33:45.959  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:33:45.959  3441  3489 I jxcore-log: 
09-07 12:33:45.960  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:33:45.960  3441  3489 I jxcore-log: 
09-07 12:33:45.961  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:33:45.961  3441  3489 I jxcore-log: 
,09-07 12:33:45.962  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.962  3441  3489 I jxcore-log: 
,09-07 12:33:45.963  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.963  3441  3489 I jxcore-log: 
09-07 12:33:45.964  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.964  3441  3489 I jxcore-log: 
09-07 12:33:45.964  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.964  3441  3489 I jxcore-log: 
09-07 12:33:45.965  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.965  3441  3489 I jxcore-log: 
09-07 12:33:45.966  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.966  3441  3489 I jxcore-log: 
,09-07 12:33:45.967  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:33:45.967  3441  3489 I jxcore-log: 
09-07 12:33:45.968  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:33:45.968  3441  3489 I jxcore-log: 
,09-07 12:33:45.969  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.969  3441  3489 I jxcore-log: 
09-07 12:33:45.969  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:33:45.969  3441  3489 I jxcore-log: 
,09-07 12:33:45.970  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.970  3441  3489 I jxcore-log: 
,09-07 12:33:45.971  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.971  3441  3489 I jxcore-log: 
09-07 12:33:45.972  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:33:45.972  3441  3489 I jxcore-log: 
,09-07 12:33:45.972  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:33:45.972  3441  3489 I jxcore-log: 
09-07 12:33:45.973  3441  3489 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:33:45.973  3441  3489 I jxcore-log: 
,09-07 12:33:46.049  3441  4017 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 483, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-07 12:33:46.605  4020  4020 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-07 12:33:46.610  4020  4020 D AndroidRuntime: CheckJNI is OFF
,09-07 12:33:46.652  4020  4020 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-07 12:33:46.699  4020  4020 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 12:33:46.730  4020  4020 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 12:33:46.739   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-07 12:33:46.740   874   887 I ActivityManager: Killing 3441:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-07 12:33:46.847   874  2020 D GraphicsStats: Buffer count: 2
,09-07 12:33:46.847   874  2020 I WindowState: WIN DEATH: Window{a319eb3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:33:46.848   874  1319 D WifiService: Client connection lost with reason: 4
,09-07 12:33:46.863   874   887 W ActivityManager: Force removing ActivityRecord{110aff8 u0 com.test.thalitest/.MainActivity t4}: app died, no saved state
,09-07 12:33:46.877   874   897 W PackageSettings: Skipping PackageSetting{a5dc45c com.example.hello/10273} due to missing metadata
,09-07 12:33:46.904   874   897 I art     : Starting a blocking GC Explicit
,09-07 12:33:46.913   874  1699 W ActivityManager: Spurious death for ProcessRecord{8d428e2 0:com.test.thalitest/u0a0}, curProc for 3441: null
,09-07 12:33:46.951   874  2218 I ActivityManager: Start proc 4030:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
,09-07 12:33:46.952   874   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3441 uid 10000
,09-07 12:33:46.953  1888  1888 I Keyboard.Facilitator: onFinishInput()
,09-07 12:33:46.993   874   897 I art     : Explicit concurrent mark sweep GC freed 23418(1588KB) AllocSpace objects, 8(248KB) LOS objects, 33% free, 28MB/43MB, paused 1.369ms total 84.050ms
,09-07 12:33:47.018   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 12:33:47.020  4020  4020 I art     : System.exit called, status: 0
09-07 12:33:47.020  4020  4020 I AndroidRuntime: VM exiting with result code 0.
,09-07 12:33:47.034   874   897 I ActivityManager: Start proc 4045:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-07 12:33:47.034   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-07 12:33:47.063   874  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 12:33:47.063  1902  2215 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 12:33:47.063  1888  1888 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-07 12:33:47.064  3320  3320 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-07 12:33:47.074  1888  4057 I Keyboard.Facilitator.DecoderInitializer: run()
,09-07 12:33:47.111  1969  1969 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-07 12:33:47.111  1888  4057 I Decoder : createOrResetDecoder
09-07 12:33:47.126   874   884 I ActivityManager: Start proc 4064:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-07 12:33:47.132   874  1987 I ActivityManager: Killing 3847:com.google.android.deskclock/u0a44 (adj 15): empty #17
09-07 12:33:47.148   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 12:33:47.186   874  2013 I ActivityManager: Start proc 4084:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,09-07 12:33:47.189  1519  1519 I ConfigService: onCreate
,09-07 12:33:47.201  1519  4089 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 12:33:47.201  1519  4089 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 12:33:47.201  1519  4089 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-07 12:33:47.205  1519  4089 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-07 12:33:47.216  1888  4057 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-07 12:33:47.231  4084  4084 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,09-07 12:33:47.237  4064  4064 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 12:33:47.273  1888  4057 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-07 12:33:47.278  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-07 12:33:47.278  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 12:33:47.280  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 12:33:47.280  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 12:33:47.280  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 12:33:47.281  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-07 12:33:47.284  1888  4057 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 12:33:47.284  1888  4057 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 12:33:47.284  1888  4057 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 12:33:47.285  1888  4057 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 12:33:47.285  1888  4057 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 12:33:47.285  1888  4057 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-07 12:33:47.288  4030  4030 D AndroidRuntime: Shutting down VM
,09-07 12:33:47.302   874  1395 I ActivityManager: Start proc 4132:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-07 12:33:47.314  4030  4030 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,--------- beginning of crash
09-07 12:33:47.315  4030  4030 E AndroidRuntime: FATAL EXCEPTION: main
09-07 12:33:47.315  4030  4030 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4030
09-07 12:33:47.315  4030  4030 E AndroidRuntime: java.lang.RuntimeException: com.google.android.libraries.velour.dynloader.a.c: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.a.d: Failed to load JAR startup from assets: extradex_jars/startup.jar
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.search.core.h.f$1.onFailure(ModuleInitWorker.java:243)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.common.util.concurrent.m$4.run(Futures.java:1310)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.concurrent.a.u$1.run(TaskRunnerImpl.java:458)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: Caused by: com.google.android.libraries.velour.dynloader.a.c: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.a.d: Failed to load JAR startup from assets: extradex_jars/startup.jar
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.l.atf(ExtraDexRegistry.java:435)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.l.a(ExtraDexRegistry.java:350)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.l$2.atj(ExtraDexRegistry.java:408)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.l$2.call(ExtraDexRegistry.java:403)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
,09-07 12:33:47.315  4030  4030 E AndroidRuntime: Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.a.d: Failed to load JAR startup from assets: extradex_jars/startup.jar
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.util.concurrent.FutureTask.report(FutureTask.java:94)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.util.concurrent.FutureTask.get(FutureTask.java:164)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.concurrent.d.get(LazyListenableFuture.java:124)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.l.atf(ExtraDexRegistry.java:432)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	... 8 more
09-07 12:33:47.315  4030  4030 E AndroidRuntime: Caused by: com.google.android.libraries.velour.dynloader.a.d: Failed to load JAR startup from assets: extradex_jars/startup.jar
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.d.aZi(JarLoader.java:216)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.l.atf(ExtraDexRegistry.java:446)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	... 8 more
09-07 12:33:47.315  4030  4030 E AndroidRuntime: Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:939)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.d.aZi(JarLoader.java:1277)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	... 9 more
09-07 12:33:47.315  4030  4030 E AndroidRuntime: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at libcore.io.Posix.open(Native Method)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:932)
09-07 12:33:47.315  4030  4030 E AndroidRuntime: 	... 10 more
,09-07 12:33:47.320  4064  4064 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 12:33:47.324   874  4146 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:33:47.324   874  4146 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:47.324   874  4146 E DropBoxManagerService: 	... 5 more
,09-07 12:33:47.331   874  4147 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 12:33:47.337  1986  2080 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-07 12:33:47.338   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-07 12:33:47.338   874   886 E PackageManager: Failed to write settings, restoring backup
09-07 12:33:47.338   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 12:33:47.338   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 12:33:47.338   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 12:33:47.338   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 12:33:47.338   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 12:33:47.338   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.338   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.338   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:33:47.339  1986  2080 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 12:33:47.339  1986  2080 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1986
09-07 12:33:47.339  1986  2080 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.339  1986  2080 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:33:47.340   874  1951 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
09-07 12:33:47.340   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-07 12:33:47.340   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 12:33:47.340   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Metho,d)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:47.340   874   887 E DropBoxManagerService: 	... 13 more
09-07 12:33:47.340   874  1951 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:33:47.341   874  4148 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:33:47.341   874  4148 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:47.341   874  4148 E DropBoxManagerService: 	... 5 more
09-07 12:33:47.347   874  1951 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 12:33:47.350   874  1951 I ActivityManager: Killing 1986:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
09-07 12:33:47.351   874  1395 W WindowManager: Failed looking up window
09-07 12:33:47.351   874  1395 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@cdb8679 does not exist
09-07 12:33:47.351   874  1395 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8736)
09-07 12:33:47.351   874  1395 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8727)
09-07 12:33:47.351   874  1395 W WindowManager: 	at com.android.server.wm.WindowManagerService.relayoutWindow(WindowManagerService.java:3105)
09-07 12:33:47.351   874  1395 W WindowManager: 	at com.android.server.wm.Session.relayout(Session.java:198)
09-07 12:33:47.351   874  1395 W WindowManager: 	at android.view.IWindowSession$Stub.onTransact(IWindowSession.java:284)
09-07 12:33:47.351   874  1395 W WindowManager: 	at com.android.server.wm.Session.onTransact(Session.java:130)
09-07 12:33:47.351   874  1395 W WindowManager: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 12:33:47.380   874  4147 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 12:33:47.380   874  4147 I Adreno  : Build Date                       : 10/20/15
09-07 12:33:47.380   874  4147 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 12:33:47.380   874  4147 I Adreno  : Local Branch                     : M14
09-07 12:33:47.380   874  4147 I Adreno  : Remote Branch                    : 
09-07 12:33:47.380   874  4147 I Adreno  : Remote Branch                    : 
09-07 12:33:47.380   874  4147 I Adreno  : Reconstruct Branch               : 
09-07 12:33:47.385   874  4147 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 12:33:47.389   874  1956 D GraphicsStats: Buffer count: 2
,09-07 12:33:47.404   874  1951 I ActivityManager: Start proc 4152:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:33:47.406   874  1699 W ActivityManager: Spurious death for ProcessRecord{bc6673c 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1986: null
,09-07 12:33:47.445   874  2140 I ActivityManager: Start proc 4167:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-07 12:33:47.451  4152  4152 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:47.451  4152  4152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:33:47.451  4152  4152 D AndroidRuntime: Shutting down VM
09-07 12:33:47.456  4152  4152 E AndroidRuntime: FATAL EXCEPTION: main
09-07 12:33:47.456  4152  4152 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4152
09-07 12:33:47.456  4152 , 4152 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 12:33:47.456  4152  4152 E AndroidRuntime: 	... 10 more
0,9-07 12:33:47.458   874  1395 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:33:47.463   874  4179 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:33:47.463   874  4179 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:47.463   874  4179 E DropBoxManagerService: 	... 5 more
09-07 12:33:47.488  4064  4172 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 12:33:47.512  4167  4167 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-07 12:33:47.529  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-07 12:33:47.530  1519  1519 D AndroidRuntime: Shutting down VM
,09-07 12:33:47.531  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
09-07 12:33:47.531  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
09-07 12:33:47.531  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 12:33:47.531  1519  1519 E AndroidRuntime: 	... 8 more
,09-07 12:33:47.534   874  4183 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:33:47.534   874  4183 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:47.534   874  4183 E DropBoxManagerService: 	... 5 more
,09-07 12:33:47.537  1721  4181 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-07 12:33:47.538  1721  4181 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 12:33:47.542  1721  4181 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 12:33:47.543  1721  4181 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 12:33:47.550  4064  4131 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.550  4064  4131 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.551  4064  4131 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:33:47.556  1721  4181 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-07 12:33:47.559  1721  4181 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 12:33:47.561   874  2140 I ActivityManager: Killing 3866:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-07 12:33:47.589  4064  4131 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-07 12:33:47.594  4064  4172 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.594  4064  4172 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:33:47.594  4064  4172 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 12:33:47.594  4064  4172 E AndroidRuntime: Process: android.process.acore, PID: 4064
09-07 12:33:47.594  4064  4172 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:33:47.594  4064  4172 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:33:47.595  4064  4131 I Process : Sending signal. PID: 4064 SIG: 9
,09-07 12:33:47.605   874  4186 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:33:47.605   874  4186 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:33:47.605   874  4186 E DropBoxManagerService: 	... 5 more
,09-07 12:33:47.623   874  1987 I ActivityManager: Process android.process.acore (pid 4064) has died
,09-07 12:33:47.624   874  1987 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms

```
