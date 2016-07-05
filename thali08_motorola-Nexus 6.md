#### Test 7214543196063dc_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
07-05 14:04:32.655   874  1385 I ActivityManager: Killing 2934:com.google.android.youtube/u0a86 (adj 15): empty #17
--------- beginning of main
07-05 14:04:33.652  1512  1512 I ConfigService: onDestroy
,07-05 14:04:34.370  3349  3349 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:04:34.375  3349  3349 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:34.410  3349  3349 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:04:34.454  3349  3349 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:04:34.475  3349  3349 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:04:34.480   874  1787 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:04:34.506  1829  2126 W SearchService: Abort, client detached.
07-05 14:04:34.516  3349  3349 D AndroidRuntime: Shutting down VM
07-05 14:04:34.524  1829  1829 I HotwordDetector: Closing mic
07-05 14:04:34.525  1829  2128 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2a1e8a6
07-05 14:04:34.526  1829  2148 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-05 14:04:34.539   874  1725 I ActivityManager: Start proc 3358:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-05 14:04:34.550  1829  1829 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-05 14:04:34.575   375  2150 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-05 14:04:34.576   375  2150 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-05 14:04:34.582   375  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-05 14:04:34.586  1829  2146 I MicroRecognitionRnrImpl: Detection finished
07-05 14:04:34.587  1829  2132 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-05 14:04:34.616  3358  3358 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-05 14:04:34.645  3358  3358 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-05 14:04:34.653  3358  3358 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7708-7711)
07-05 14:04:34.653  3358  3358 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:34.666  3358  3358 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ad5e5ef}
07-05 14:04:34.667  3358  3358 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:34.667  3358  3358 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:34.694  3358  3358 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:34.695  3358  3358 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 14:04:34.719  3358  3373 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-05 14:04:34.734  3358  3358 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 14:04:34.762  3358  3358 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 14:04:34.762  3358  3358 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:34.762  3358  3358 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 14:04:34.762  3358  3358 I Adreno  : Build Date                       : 10/20/15
07-05 14:04:34.762  3358  3358 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 14:04:34.762  3358  3358 I Adreno  : Local Branch                     : M14
07-05 14:04:34.762  3358  3358 I Adreno  : Remote Branch                    : 
07-05 14:04:34.762  3358  3358 I Adreno  : Remote Branch                    : 
07-05 14:04:34.762  3358  3358 I Adreno  : Reconstruct Branch               : 
,07-05 14:04:34.832   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d64f69:true
,07-05 14:04:34.892  3358  3358 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 14:04:34.907  3358  3358 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-05 14:04:34.988  3358  3395 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 14:04:35.003  3358  3382 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-05 14:04:35.056  3358  3395 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 14:04:35.180   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +665ms
,07-05 14:04:35.189  1671  1671 I Keyboard.Facilitator: onFinishInput()
,07-05 14:04:35.288  3358  3358 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3358
,07-05 14:04:35.392   874  1725 I ActivityManager: Killing 2327:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,07-05 14:04:35.433   874  1725 I ActivityManager: Killing 3023:com.qualcomm.telephony/1001 (adj 15): empty #18
,07-05 14:04:35.519  3358  3358 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:04:35.652  3358  3397 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1690306256
,07-05 14:04:35.656  3358  3397 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:35.656  3358  3397 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:35.656  3358  3397 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:35.656  3358  3397 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:35.656  3358  3397 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 14:04:35.656  3358  3397 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b1ff43 added. We now have 1 listener(s)
07-05 14:04:35.658  3358  3397 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-05 14:04:35.660  3358  3397 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-05 14:04:35.660  3358  3397 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:04:35.660  3358  3397 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:35.663  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:35.664  3358  3397 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09d63e added. We now have 1 listener(s)
,07-05 14:04:35.664  3358  3397 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 14:04:35.673  3358  3397 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:04:35.676   874  1318 D WifiService: New client listening to asynchronous messages
,07-05 14:04:35.676  3358  3397 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-05 14:04:35.681  3358  3397 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-05 14:04:35.682  3358  3397 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-05 14:04:35.682  3358  3397 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-05 14:04:35.682  3358  3397 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 14:04:35.686  3358  3397 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 14:04:35.686  3358  3397 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-05 14:04:35.692  3358  3397 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:35.692  3358  3397 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-05 14:04:35.693  3358  3397 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:35.693  3358  3397 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 14:04:35.694  3358  3397 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:04:35.860  3358  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:35.863  3358  3358 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:36.875  3358  3405 W jxcore-log: Initializing JXcore engine
07-05 14:04:36.875  3358  3405 W jxcore-log: JXcore engine is ready
,07-05 14:04:36.915  3405  3405 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-05 14:04:36.915  3405  3405 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10548]" dev="sockfs" ino=10548 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-05 14:04:36.915  3405  3405 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:04:36.915  3405  3405 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23542]" dev="sockfs" ino=23542 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-05 14:04:36.927  3358  3405 W jxcore-log: Starting JXcore engine
,07-05 14:04:37.004  3358  3405 W jxcore-log: Platform android
07-05 14:04:37.004  3358  3405 W jxcore-log: 
,07-05 14:04:37.004  3358  3405 W jxcore-log: Process ARCH arm
07-05 14:04:37.004  3358  3405 W jxcore-log: 
,07-05 14:04:37.186  3358  3405 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:37.186  3358  3405 I jxcore-log: 
07-05 14:04:37.187  3358  3405 W jxcore-log: JXcore engine is started
,07-05 14:04:37.198  3358  3397 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:04:37.205  3358  3358 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:42.890   874   887 I ActivityManager: Waited long enough for: ServiceRecord{5d7d3fc u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,07-05 14:04:47.110  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:47.110  3358  3405 I jxcore-log: 
,07-05 14:04:47.112  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:47.112  3358  3405 I jxcore-log: 
,07-05 14:04:47.115  3358  3405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:47.115  3358  3405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:47.116  3358  3405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:47.116  3358  3405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:47.118  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:47.118  3358  3405 I jxcore-log: 
,07-05 14:04:47.120  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:47.120  3358  3405 I jxcore-log: 
,07-05 14:04:47.492  3358  3405 I jxcore-log: Unit Test app is loaded
07-05 14:04:47.492  3358  3405 I jxcore-log: 
,07-05 14:04:47.498  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-05 14:04:47.498  3358  3405 I jxcore-log: 
,07-05 14:04:47.502   874  1787 D WifiService: setWifiEnabled: true pid=3358, uid=10000
07-05 14:04:47.502   874  1787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-05 14:04:47.505   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,07-05 14:04:47.512  3358  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:47.513  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:47.513  3358  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-05 14:04:47.513  3358  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-05 14:04:47.516   874  1317 D WifiConfigStore: loaded 0 passpoint configs
07-05 14:04:47.516   874  1317 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-05 14:04:47.516   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-05 14:04:47.517   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-05 14:04:47.517   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-05 14:04:47.517   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-05 14:04:47.517   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-05 14:04:47.517   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-05 14:04:47.522  3358  3358 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
,07-05 14:04:47.541   874   887 I ActivityManager: Start proc 3410:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-05 14:04:47.546  3358  3405 I jxcore-log: My device name is: motorola-Nexus 6
07-05 14:04:47.546  3358  3405 I jxcore-log: 
07-05 14:04:47.548  3358  3405 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 14:04:47.548  3358  3405 I jxcore-log: 
,07-05 14:04:47.560   874   891 I ActivityManager: Start proc 3421:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-05 14:04:47.578  3410  3410 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-05 14:04:47.595   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-05 14:04:47.596   371   872 D CommandListener: Setting iface cfg
07-05 14:04:47.596   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
07-05 14:04:47.596   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-05 14:04:47.598   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,07-05 14:04:47.598   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-05 14:04:47.615   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:47.617   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:47.645  3410  3410 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-05 14:04:47.660  3421  3421 D AdapterServiceConfig: Adding HeadsetService
,07-05 14:04:47.660  3421  3421 D AdapterServiceConfig: Adding A2dpService
07-05 14:04:47.661  3421  3421 D AdapterServiceConfig: Adding HidService
07-05 14:04:47.661  3421  3421 D AdapterServiceConfig: Adding HealthService
07-05 14:04:47.661  3421  3421 D AdapterServiceConfig: Adding PanService
07-05 14:04:47.661  3421  3421 D AdapterServiceConfig: Adding GattService
07-05 14:04:47.661  3421  3421 D AdapterServiceConfig: Adding BluetoothMapService
,07-05 14:04:47.685   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e2388b:true
,07-05 14:04:47.685  3421  3421 D BluetoothAdapterState: make() - Creating AdapterState
,07-05 14:04:47.687  3421  3421 I bt_bluedroid: init
,07-05 14:04:47.688  3421  3445 I BluetoothAdapterState: Entering OffState
,07-05 14:04:47.692  3421  3446 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-05 14:04:47.693  3421  3446 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-05 14:04:47.693  3421  3446 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-05 14:04:47.693  3421  3446 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-05 14:04:47.695  3421  3421 I bt_bluedroid: get_profile_interface socket
,07-05 14:04:47.696  3421  3421 I bt_bluedroid: get_profile_interface sdp
07-05 14:04:47.696  3421  3449 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-05 14:04:47.697  3421  3449 D BluetoothAdapterProperties: Name is: Nexus 6
07-05 14:04:47.698  3421  3432 I bt_bluedroid: config_hci_snoop_log
,07-05 14:04:47.699   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-05 14:04:47.701  3421  3445 D BluetoothAdapterState: Current state: OFF, message: 0
,07-05 14:04:47.701  3421  3445 D BluetoothAdapterProperties: Setting state to 14
07-05 14:04:47.701  3421  3445 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-05 14:04:47.703  3421  3445 D BluetoothBondStateMachine: make
,07-05 14:04:47.705  3421  3451 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-05 14:04:47.707  3421  3445 I BluetoothAdapterState: Entering PendingCommandState
,07-05 14:04:47.708  3421  3421 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-05 14:04:47.709  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
,07-05 14:04:47.710  3421  3421 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-05 14:04:47.710  3421  3421 D BtGatt.GattService: Received start request. Starting profile...
,07-05 14:04:47.710  3421  3421 D BtGatt.GattService: start()
07-05 14:04:47.710  3421  3421 I bt_bluedroid: get_profile_interface gatt
07-05 14:04:47.711  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
07-05 14:04:47.711  3421  3421 D BtGatt.AdvertiseManager: advertise manager created
,07-05 14:04:47.715   874  1406 I ActivityManager: Killing 2686:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-05 14:04:47.716  3421  3421 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:47.716  3421  3421 V BluetoothAdapterState: isTurningOn()=false
07-05 14:04:47.716  3421  3421 V BluetoothAdapterState: isBleTurningOn()=true
07-05 14:04:47.716  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:47.716  3421  3445 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-05 14:04:47.716  3421  3445 I bt_bluedroid: enable
,07-05 14:04:47.716  3421  3446 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-05 14:04:47.717  3421  3446 I bt_hci  : start_up
,07-05 14:04:47.760  3421  3446 I bt_vendor: alloc value 0xb39ba189
,07-05 14:04:47.761  3421  3446 I bt_vendor: init
07-05 14:04:47.761  3421  3446 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-05 14:04:47.761  3421  3446 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-05 14:04:47.867  3421  3446 D bt_hci  : start_up starting async portion
,07-05 14:04:47.868  3421  3455 I bt_hci  : event_finish_startup
07-05 14:04:47.869  3421  3455 I bt_hci_h4: hal_open
07-05 14:04:47.869  3421  3455 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-05 14:04:47.875  3421  3455 I bt_userial_vendor: device fd = 51 open
,07-05 14:04:47.910  3421  3455 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-05 14:04:47.942  3421  3455 D bt_hwcfg: Chipset BCM4354A2
,07-05 14:04:47.942  3421  3455 D bt_hwcfg: Target name = [BCM4354A2]
,07-05 14:04:47.943  3421  3455 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-05 14:04:48.265  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:48.284  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:48.286  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:48.307  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:04:48.307  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:04:48.307  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:48.308  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:48.320  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:04:48.320  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:04:48.321  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-05 14:04:48.471  3421  3455 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-05 14:04:48.471  3421  3455 D bt_hwcfg: Settlement delay -- 100 ms
,07-05 14:04:48.472  3421  3455 I bt_hwcfg: Setting fw settlement delay to 100 
,07-05 14:04:48.588  3421  3455 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-05 14:04:48.589  3421  3455 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-05 14:04:48.620  3421  3455 I bt_hwcfg: vendor lib fwcfg completed
,07-05 14:04:48.621  3421  3455 I bt_vendor: firmware callback
,07-05 14:04:48.621  3421  3455 I bt_hci  : firmware_config_callback
,07-05 14:04:48.629  3421  3459 I bt_btu  : btu_task pending for preload complete event
,07-05 14:04:48.630  3421  3459 I bt_btu_task: Bluetooth chip preload is complete
,07-05 14:04:48.630  3421  3459 I bt_btu  : btu_task received preload complete event
,07-05 14:04:48.638  3421  3459 I         : BTE_InitTraceLevels -- TRC_HCI
,07-05 14:04:48.638  3421  3459 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-05 14:04:48.638  3421  3459 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-05 14:04:48.638  3421  3459 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-05 14:04:48.639  3421  3459 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-05 14:04:48.639  3421  3459 I         : BTE_InitTraceLevels -- TRC_A2D
,07-05 14:04:48.639  3421  3459 I         : BTE_InitTraceLevels -- TRC_BNEP
07-05 14:04:48.639  3421  3459 I         : BTE_InitTraceLevels -- TRC_BTM
,07-05 14:04:48.639  3421  3459 I         : BTE_InitTraceLevels -- TRC_GAP
,07-05 14:04:48.640  3421  3459 I         : BTE_InitTraceLevels -- TRC_PAN
07-05 14:04:48.640  3421  3459 I         : BTE_InitTraceLevels -- TRC_SDP
07-05 14:04:48.640  3421  3459 I         : BTE_InitTraceLevels -- TRC_GATT
07-05 14:04:48.640  3421  3459 I         : BTE_InitTraceLevels -- TRC_SMP
07-05 14:04:48.640  3421  3459 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-05 14:04:48.641  3421  3459 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-05 14:04:48.770  3421  3459 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3937d9d
,07-05 14:04:48.771  3421  3459 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3937d9d 
,07-05 14:04:48.779  3421  3449 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-05 14:04:48.781  3421  3449 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-05 14:04:48.781  3421  3449 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-05 14:04:48.783  3421  3449 D BluetoothAdapterProperties: Name is: Nexus 6
07-05 14:04:48.784  3421  3449 D BluetoothAdapterProperties: Scan Mode:20
07-05 14:04:48.784  3421  3449 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:48.784  3421  3449 D bt_hci  : do_postload posting postload work item
07-05 14:04:48.784  3421  3455 I bt_hci  : event_postload
07-05 14:04:48.784  3421  3455 I bt_vendor: sco_config_cb
07-05 14:04:48.785  3421  3455 I bt_hci  : sco_config_callback postload finished.
,07-05 14:04:48.790  3421  3449 D bt_bte_conf: Device ID record 1 : primary
,07-05 14:04:48.790  3421  3449 D bt_bte_conf:   vendorId            = 000f
07-05 14:04:48.790  3421  3449 D bt_bte_conf:   vendorIdSource      = 0001
07-05 14:04:48.790  3421  3449 D bt_bte_conf:   product             = 1200
07-05 14:04:48.790  3421  3449 D bt_bte_conf:   version             = 1436
07-05 14:04:48.790  3421  3449 D bt_bte_conf:   clientExecutableURL = 
07-05 14:04:48.790  3421  3449 D bt_bte_conf:   serviceDescription  = 
07-05 14:04:48.790  3421  3449 D bt_bte_conf:   documentationURL    = 
07-05 14:04:48.790  3421  3449 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-05 14:04:48.790  3421  3446 D bt_stack_manager: event_start_up_stack finished
07-05 14:04:48.791  3421  3445 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-05 14:04:48.791  3421  3445 D BluetoothAdapterProperties: Setting state to 15
07-05 14:04:48.791  3421  3445 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-05 14:04:48.792  3358  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 14:04:48.793  3421  3445 I BluetoothAdapterState: Entering BleOnState
07-05 14:04:48.794  3421  3445 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-05 14:04:48.794  3421  3445 D BluetoothAdapterProperties: Setting state to 11
07-05 14:04:48.794  3421  3445 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-05 14:04:48.800  3421  3455 I bt_vendor: low_power_mode_cb
,07-05 14:04:48.802  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
,07-05 14:04:48.806  3421  3421 D HeadsetService: Received start request. Starting profile...
,07-05 14:04:48.810  3421  3421 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-05 14:04:48.810  3421  3421 D HeadsetStateMachine: make
,07-05 14:04:48.821   874   887 I ActivityManager: Start proc 3467:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-05 14:04:48.826  3421  3421 D HeadsetStateMachine: max_hf_connections = 1
07-05 14:04:48.827  3421  3421 I bt_bluedroid: get_profile_interface handsfree
07-05 14:04:48.827  3421  3449 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-05 14:04:48.827  3421  3449 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
07-05 14:04:48.831  3421  3445 I BluetoothAdapterState: Entering PendingCommandState
,07-05 14:04:48.832  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
,07-05 14:04:48.833   874   874 D BluetoothA2dp: Proxy object connected
07-05 14:04:48.834  3421  3421 D A2dpService: Received start request. Starting profile...
07-05 14:04:48.834  3421  3421 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-05 14:04:48.835  3421  3421 I bt_bluedroid: get_profile_interface avrcp
,07-05 14:04:48.842  3421  3421 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-05 14:04:48.842  3421  3421 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-05 14:04:48.842  3421  3421 D A2dpStateMachine: make
07-05 14:04:48.843  3421  3421 I bt_bluedroid: get_profile_interface a2dp
07-05 14:04:48.844  3421  3449 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-05 14:04:48.846  3421  3421 I BluetoothHidServiceJni: classInitNative: succeeds
,07-05 14:04:48.847  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
,07-05 14:04:48.848  3421  3479 D A2dpStateMachine: Enter Disconnected: -2
,07-05 14:04:48.850  1371  1371 D BluetoothInputDevice: Proxy object connected
07-05 14:04:48.850  1371  1371 D HidProfile: Bluetooth service connected
,07-05 14:04:48.851  3421  3421 D HidService: Received start request. Starting profile...
,07-05 14:04:48.851  3421  3421 I bt_bluedroid: get_profile_interface hidhost
07-05 14:04:48.851  3421  3449 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39193e5
,07-05 14:04:48.851  3421  3421 D HidService: setHidService(): set to: null
,07-05 14:04:48.851  3421  3449 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-05 14:04:48.853  3421  3421 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-05 14:04:48.853  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01,
,07-05 14:04:48.854  3421  3421 D HealthService: Received start request. Starting profile...
,07-05 14:04:48.855  3421  3421 I bt_bluedroid: get_profile_interface health
,07-05 14:04:48.855  3421  3421 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-05 14:04:48.856  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
07-05 14:04:48.856  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
,07-05 14:04:48.857  3421  3421 D PanService: Received start request. Starting profile...
,07-05 14:04:48.857  1371  1371 D PanProfile: Bluetooth service connected
,07-05 14:04:48.857  3421  3421 D BluetoothPanServiceJni: initializeNative(L110): pan
07-05 14:04:48.857  3421  3421 I bt_bluedroid: get_profile_interface pan
,07-05 14:04:48.857  3421  3449 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-05 14:04:48.863  3421  3421 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3fb01
,07-05 14:04:48.864  1371  1371 D BluetoothMap: Proxy object connected
,07-05 14:04:48.865  1371  1371 D MapProfile: Bluetooth service connected
07-05 14:04:48.865  1371  1371 D BluetoothMap: getConnectedDevices(),
07-05 14:04:48.865  1371  1371 D BluetoothMap: Bluetooth is Not enabled
,07-05 14:04:48.865  3421  3421 D BluetoothMapService: Received start request. Starting profile...
,07-05 14:04:48.866  3421  3421 D BluetoothMapService: start()
,07-05 14:04:48.868  3421  3421 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-05 14:04:48.868  3421  3421 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-05 14:04:48.869  3421  3421 D BluetoothMapAppObserver: createReceiver()
,07-05 14:04:48.869  3421  3421 D BluetoothMapAppObserver: initObservers()
,07-05 14:04:48.869  3421  3421 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-05 14:04:48.873  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,07-05 14:04:48.874  3421  3421 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:48.874  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:48.874  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,07-05 14:04:48.876  3421  3466 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isTurningOff()=false
07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
,07-05 14:04:48.876  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
,07-05 14:04:48.877  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,07-05 14:04:48.877  3421  3421 V BluetoothAdapterState: isTurningOn()=true
,07-05 14:04:48.877  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:48.877  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:48.877  3467  3467 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-05 14:04:48.877  3421  3421 V BluetoothAdapterState: isTurningOff()=false
,07-05 14:04:48.878  3421  3421 V BluetoothAdapterState: isTurningOn()=true
07-05 14:04:48.878  3421  3421 V BluetoothAdapterState: isBleTurningOn()=false
07-05 14:04:48.878  3421  3421 V BluetoothAdapterState: isBleTurningOff()=false
07-05 14:04:48.879  3421  3445 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-05 14:04:48.879  3421  3445 D BluetoothAdapterProperties: ScanMode =  20
07-05 14:04:48.879  3421  3445 D BluetoothAdapterProperties: State =  11
07-05 14:04:48.880  3421  3449 D BluetoothAdapterProperties: Scan Mode:21
07-05 14:04:48.880  3421  3449 D BluetoothAdapterProperties: Discoverable Timeout:120
07-05 14:04:48.880  3421  3445 D BluetoothAdapterProperties: Setting state to 12
07-05 14:04:48.880  3421  3445 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-05 14:04:48.880  3421  3445 I BluetoothAdapterState: Entering OnState
07-05 14:04:48.881  1371  1386 D BluetoothPbap: onBluetoothStateChange: up=true
07-05 14:04:48.881  1734  1746 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:48.882  3358  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 14:04:48.883  1371  1882 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-05 14:04:48.883   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:48.883   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:48.883   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
07-05 14:04:48.883  1371  1388 D BluetoothPan: onBluetoothStateChange on: true
07-05 14:04:48.884   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-05 14:04:48.884  1371  1386 D BluetoothMap: onBluetoothStateChange: up=true
07-05 14:04:48.886   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
07-05 14:04:48.887  3421  3421 D BluetoothMapService: onReceive
07-05 14:04:48.887  3421  3421 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-05 14:04:48.887  3421  3421 D BluetoothMapService: STATE_ON
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-05 14:04:48.887  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-05 14:04:48.889  3358  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-05 14:04:48.890  1371  1684 D LocalBluetoothProfileManager: Adding local A2DP profile
07-05 14:04:48.893  1371  1371 D BluetoothA2dp: Proxy object connected
07-05 14:04:48.894  3421  3421 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-05 14:04:48.894  3421  3421 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-05 14:04:48.895  1371  1684 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-05 14:04:48.896  3421  3421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-05 14:04:48.898  3421  3421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-05 14:04:48.899  3421  3421 D ObexServerSockets: Succeed to create listening sockets 
07-05 14:04:48.899  3421  3421 D ObexServerSockets0: startAccept()
07-05 14:04:48.899  3421  3421 D ObexServerSockets,0: prepareForNewConnect()
07-05 14:04:48.901  3421  3421 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-05 14:04:48.901  3421  3421 D BluetoothSdpJni: SDP Create record success - handle: 0
07-05 14:04:48.902  3421  3488 D ObexServerSockets0: Accepting socket connection...
07-05 14:04:48.902  3421  3487 D ObexServerSockets0: Accepting socket connection...
07-05 14:04:48.906   874  1753 I ActivityManager: Killing 2830:com.google.android.gm/u0a78 (adj 15): empty #17
07-05 14:04:48.907  3421  3421 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-05 14:04:48.907  3421  3421 D ObexServerSockets0: prepareForNewConnect()
,07-05 14:04:48.969  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:48.987  1734  1745 D BluetoothHeadset: Proxy object connected
,07-05 14:04:48.988   874   891 D BluetoothHeadset: Proxy object connected
,07-05 14:04:48.989   874   891 D BluetoothHeadset: Proxy object connected
07-05 14:04:48.989   874   891 D BluetoothHeadset: Proxy object connected
,07-05 14:04:48.991   874  1747 I ActivityManager: Start proc 3489:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-05 14:04:48.998  1371  1388 D BluetoothHeadset: Proxy object connected
,07-05 14:04:48.999  1371  1371 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:49.038  3489  3489 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-05 14:04:49.092   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-05 14:04:49.094   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
07-05 14:04:49.094   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:49.103   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-05 14:04:49.148   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-05 14:04:49.149  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-05 14:04:49.200  3489  3489 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.200  3489  3489 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.200  3489  3489 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.200  3489  3489 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.e.b(PG:170)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.200  3489  3489 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.k.d(PG:583)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.e.b(PG:170)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.200  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.201  3489  3489 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.201  3489  3489 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.io.File.exists(File.java:361)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.201  3489  3489 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-05 14:04:49.201  3489  3489 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-05 14:04:49.219  3467  3467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-05 14:04:49.229   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3bbe27:true
07-05 14:04:49.234  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-05 14:04:49.244  3467  3467 D LocalBluetoothProfileManager: Adding local A2DP profile
07-05 14:04:49.252  3467  3467 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-05 14:04:49.256  1371  1371 D BluetoothPbap: Proxy object connected
07-05 14:04:49.257  1371  1371 D PbapServerProfile: Bluetooth service connected
07-05 14:04:49.263  3467  3467 D LocalBluetoothProfileManager: Adding local MAP profile
07-05 14:04:49.264  3467  3467 D BluetoothMap: Create BluetoothMap proxy object
07-05 14:04:49.271  3467  3467 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-05 14:04:49.276  3421  3519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:49.279  3467  3467 D DockEventReceiver: finishStartingService: stopping service
,07-05 14:04:49.280  3467  3467 D BluetoothA2dp: Proxy object connected
,07-05 14:04:49.283  3467  3467 D BluetoothInputDevice: Proxy object connected
,07-05 14:04:49.283  3467  3467 D HidProfile: Bluetooth service connected
,07-05 14:04:49.286  3467  3467 D BluetoothPan: BluetoothPAN Proxy object connected
,07-05 14:04:49.287  3467  3467 D PanProfile: Bluetooth service connected
,07-05 14:04:49.288  3467  3467 D BluetoothMap: Proxy object connected
07-05 14:04:49.288  3467  3467 D MapProfile: Bluetooth service connected
07-05 14:04:49.288  3467  3467 D BluetoothMap: getConnectedDevices()
,07-05 14:04:49.291  3467  3467 D BluetoothPbap: Proxy object connected
,07-05 14:04:49.291  3467  3467 D PbapServerProfile: Bluetooth service connected
,07-05 14:04:49.298   874  1725 I ActivityManager: Killing 3045:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-05 14:04:49.355  3467  3478 D BluetoothHeadset: Proxy object connected
,07-05 14:04:49.357  3467  3467 D HeadsetProfile: Bluetooth service connected
,07-05 14:04:49.379  3421  3524 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-05 14:04:49.382  3421  3524 I BtOppRfcommListener: Accept thread started.
,07-05 14:04:49.480  3489  3506 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:49.505   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6045cd2:true
,07-05 14:04:49.597  1449  1449 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-05 14:04:49.629  1449  1449 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-05 14:04:49.629  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-05 14:04:49.635   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:04:49.653   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-05 14:04:49.655   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-05 14:04:49.655   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:49.677   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-05 14:04:49.684   371   872 D CommandListener: Setting iface cfg
,07-05 14:04:49.690   874  1317 D WifiStateMachine: Start Dhcp Watchdog 1
,07-05 14:04:49.703   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:49.703   874  1319 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,07-05 14:04:49.703   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-05 14:04:49.729   874  3530 D DhcpClient: Receive thread started
,07-05 14:04:49.809   874  1317 E native  : do suspend false
,07-05 14:04:49.830   874  3529 D DhcpClient: Broadcasting DHCPDISCOVER
,07-05 14:04:50.517   874  3530 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,07-05 14:04:50.520   874  3529 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-05 14:04:50.524   874  3529 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-05 14:04:50.537   874  3530 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-05 14:04:50.539   874  3529 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-05 14:04:50.544   371   872 D CommandListener: Setting iface cfg
,07-05 14:04:50.553   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-05 14:04:50.553   874  3529 D DhcpClient: Scheduling renewal in 86399s
,07-05 14:04:50.571   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-05 14:04:50.575   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:04:50.576   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-05 14:04:50.580   874  1319 D ConnectivityService: Adding iface wlan0 to network 100
07-05 14:04:50.596   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-05 14:04:50.628   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-05 14:04:50.629   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-05 14:04:50.630   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-05 14:04:50.631   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-05 14:04:50.631   874  1319 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-05 14:04:50.639   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:50.644   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 100
,07-05 14:04:50.644   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-05 14:04:50.645   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:50.645   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-05 14:04:50.645   874  1319 D ConnectivityService:    accepting network in place of null
07-05 14:04:50.645   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-05 14:04:50.645   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-05 14:04:50.655   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123712, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:04:50.671   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:04:50.695   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-05 14:04:50.698   874  1319 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,07-05 14:04:50.709   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-05 14:04:50.710   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-05 14:04:50.716   874   891 D Tethering: MasterInitialState.processMessage what=3
,07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:50.723  3358  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 14:04:50.724   874  3527 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:400d:803::200e
07-05 14:04:50.724  3358  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:50.716   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-05 14:04:50.726   874  1753 V BackupManagerService: Scheduling immediate backup pass
07-05 14:04:50.727   874   874 V BackupManagerService: Running a backup pass
07-05 14:04:50.728   874  1342 V BackupManagerService: clearing pending backups
,07-05 14:04:50.734   874  1342 V PerformBackupTask: Beginning backup of 16 targets
,07-05 14:04:50.740  1829  1829 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-05 14:04:50.759   874  1342 D PerformBackupTask: invokeAgentForBackup on @pm@
,07-05 14:04:50.762   874  1700 D AlarmManagerService: Setting time of day to sec=1467720292
,07-05 14:04:52.037   874  1700 W AlarmManagerService: Unable to set rtc to 1467720292: Invalid argument
,07-05 14:04:52.052   874  1752 I ActivityManager: Start proc 3550:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:04:52.057   874  1342 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,07-05 14:04:52.060   874  3527 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jul 2016 12:04:52 GMT], X-Android-Received-Millis=[1467720292059], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467720290762]}
,07-05 14:04:52.068   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-05 14:04:52.068   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-05 14:04:52.068   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:52.069   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-05 14:04:52.083  1812  3546 I CheckinService: Checking schedule, now: 1467720292078 next: 1467297052589
,07-05 14:04:52.083  1812  3546 I CheckinService: active receiver: enabled
07-05 14:04:52.092  3550  3550 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
07-05 14:04:52.095  1812  3546 I CheckinService: Preparing to send checkin request
07-05 14:04:52.095  1812  3546 I EventLogService: Accumulating logs since 1467719189632
,07-05 14:04:52.142  1812  3571 I iu.SyncManager: SYNC; picasa accounts
,07-05 14:04:52.146  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,07-05 14:04:52.146  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud.
07-05 14:04:52.146  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:52.146  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:52.149  3550  3569 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:04:52.163  1812  1812 D NetworkLogImpl: Loaded NetworkSpeedPredictor
07-05 14:04:52.165  1812  3564 I GcmGroups: Failed to subscribe to group.
07-05 14:04:52.165  1812  3564 I GcmGroups: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:350)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:444)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:334)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:241)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:48)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:52.165  1812  3564 I GcmGroups: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:52.167  1812  3564 I GcmGroups: Groups upload failed, retrying in 24000:00:00
07-05 14:04:52.170  1812  1812 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-05 14:04:52.189  1812  1812 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-05 14:04:52.190  1812  1812 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-05 14:04:52.198  1812  3570 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-05 14:04:52.198  1812  3570 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:04:52.201  1812  3571 I iu.UploadsManager: num queued entries: 0
07-05 14:04:52.201  1812  3571 I iu.UploadsManager: num updated entries: 0
07-05 14:04:52.202   874   885 I ActivityManager: Start proc 3578:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
07-05 14:04:52.202  1812  3571 I iu.SyncManager: NEXT; no task
,07-05 14:04:52.215  1812  3570 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:04:52.219  1812  3546 I EventLogService: Opted in for usage reporting
,07-05 14:04:52.221  3410  3565 V GoogleAuthProtoRequest: [278] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:04:52.245  3578  3578 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-05 14:04:52.247  3578  3578 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-05 14:04:52.253  3550  3569 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:52.260  3578  3578 D SprintDMHelper: simOperator: 
,07-05 14:04:52.261  3578  3578 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-05 14:04:52.269   874  1342 I BackupRestoreController: Getting widget state for user: 0
,07-05 14:04:52.283   874  1725 I ActivityManager: Start proc 3597:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-05 14:04:52.293  3550  3569 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:52.355  1351  3593 D DownloadManager: [116] Starting
,07-05 14:04:52.364  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-05 14:04:52.365  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-05 14:04:52.365  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:52.365  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:52.378  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:04:52.378  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:04:52.378  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:52.378  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:52.392  1351  3593 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 14:04:52.412   874  3618 D GpsLocationProvider: NTP server returned: 1467720292038 (Tue Jul 05 14:04:52 GMT+02:00 2016) reference: 123820 certainty: 4 system time offset: -374
,07-05 14:04:52.412   874  3618 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,07-05 14:04:52.429  1812  3570 E MDM     : [175] SitrepService.a: Error sending sitrep.
,07-05 14:04:52.433  3550  3550 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 14:04:52.470  1512  3612 I GCM     : GCM message com.google.android.gms 0:1467616626996850%136ddda6f9fd7ecd
,07-05 14:04:52.481  1512  3612 I GCM     : GCM message com.google.android.gms 0:1467620259860871%136ddda6f9fd7ecd
,07-05 14:04:52.485  3410  3565 W ExperimentUpdateService: [278] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: [278] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:04:52.491  3410  3565 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:04:52.515  1866  2062 W GmsBackupTransport: Unknown package in backup request: @pm@
,07-05 14:04:52.517  1866  2062 V GmsBackupTransport: starting performBackup for @pm@
,07-05 14:04:52.524  1866  2062 V GmsBackupTransport: performBackup done for @pm@
,07-05 14:04:52.533  1812  3546 W EventLogAggregator: Unknown tag: snet_gcore
,07-05 14:04:52.533  1812  3546 W EventLogAggregator: Unknown tag: snet_launch_service
,07-05 14:04:52.592   874  1787 I ActivityManager: Start proc 3644:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-05 14:04:52.628  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:52.633  3550  3550 W InstanceID/Rpc: Found 10011
,07-05 14:04:52.650  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,07-05 14:04:52.650  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
07-05 14:04:52.650  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:52.650  3550  3662 W YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1035 Unknown task tag innertube_config_fetch_charging; aborting...
,07-05 14:04:52.650  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:52.666  1812  3546 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:04:52.707  1512  2698 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:52.707  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:52.707  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:52.707  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:52.707  1512  2698 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:52.707  1512  2698 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:52.707  1512  2698 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:52.711  1866  1880 W GmsBackupTransport: Error sending final backup to server: 
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:04:52.711  1866  1880 W GmsBackupTransport: 	... 1 more
,07-05 14:04:52.715  3640  3640 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads296642643.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads296642643.dex
,07-05 14:04:52.730   874  1318 D WifiService: New client listening to asynchronous messages
,07-05 14:04:52.731  1866  2302 I GmsBackupTransport: Next backup will happen in 43199978 millis.
,07-05 14:04:52.731   874  1342 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,07-05 14:04:52.743  1812  3613 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:04:52.743  1812  3546 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
07-05 14:04:52.745  3644  3644 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-05 14:04:52.799  1512  1512 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:52.832  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:04:52.832  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-05 14:04:52.832  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:52.836  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:52.865  1812  1812 E ConnectivityChangeReceiver: Ignoring connectivity change
,07-05 14:04:52.866  3164  3615 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:04:52.866  3164  3615 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:04:52.866  3164  3615 E HttpOperation: ,	at java.lang.Thread.run(Thread.java:818)
07-05 14:04:52.866  3164  3615 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	... 12 more
07-05 14:04:52.866  3164  3615 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at fal.a(PG:38)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:04:52.866  3164  3615 E HttpOperation: 	... 14 more
,07-05 14:04:52.878   874  1711 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1812 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 14:04:52.893  2367  3643 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-05 14:04:52.894  3640  3640 I dex2oat : dex2oat took 180.548ms (threads: 4) arena alloc=114KB java alloc=37KB native alloc=1513KB free=1558KB
,07-05 14:04:52.928   874  1342 I BackupManagerService: Backup pass finished.
,07-05 14:04:52.930  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:04:52.930  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:04:52.931  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:52.931  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:52.948  3164  3615 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:04:52.948  3164  3615 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:04:52.948  3164  3615 E HttpOperation: ,	at jdm.a(PG:82)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at hec.a(PG:42)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at hee.a(PG:102)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at czr.a(PG:65)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at kka.a(PG:108)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at czp.a(PG:19176)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:04:52.948  3164  3615 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	... 15 more
07-05 14:04:52.948  3164  3615 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at fal.a(PG:38)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:04:52.948  3164  3615 E HttpOperation: 	... 17 more
07-05 14:04:52.949  3164  3615 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:04:52.949  3164  3615 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	... 15 more
07-05 14:04:52.949  3164  3615 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:04:52.949  3164  3615 E ExperimentLoader: 	... 17 more
,07-05 14:04:53.036  1812  3617 W DriveInitializer: Awaiting to be initialized
,07-05 14:04:53.037  1812  3711 W DriveInitializer: Background init thread started
,07-05 14:04:53.046  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-05 14:04:53.046  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-05 14:04:53.046  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:53.046  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:53.060   874   886 I ActivityManager: Start proc 3712:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,07-05 14:04:53.094  3712  3712 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,07-05 14:04:53.123  1812  3711 W DriveInitializer: Background init thread ended
,07-05 14:04:53.139  1812  3546 W CheckinRequestBuilder: awaiting user notification for token
,07-05 14:04:53.146   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 23955, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:04:53.149   874  1787 I ActivityManager: Killing 2473:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-05 14:04:53.257  1512  3695 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-05 14:04:53.307  3712  3712 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:53.314  3712  3712 I BooksApp: Created application version: 3.6.9 (30609)
,07-05 14:04:53.329   874  1406 I ActivityManager: Start proc 3745:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,07-05 14:04:53.371  3745  3745 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:04:53.379  3745  3745 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:04:53.379  3745  3745 I MultiDex: install
07-05 14:04:53.379  3745  3745 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:53.410  3644  3644 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-05 14:04:53.410  3644  3644 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:53.410  3644  3644 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:53.426  3745  3745 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:53.435  3644  3644 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:53.452  3745  3745 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:53.456  3644  3644 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:53.483  3745  3767 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-05 14:04:53.496  3712  3760 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:04:53.524  3644  3768 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:53.530  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:53.530  3358  3405 I jxcore-log: 
,07-05 14:04:53.534   375   375 D WVCdm   : Instantiating CDM.
07-05 14:04:53.535   375  1325 I WVCdm   : CdmEngine::OpenSession
07-05 14:04:53.535   375  1325 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-05 14:04:53.538   375  1325 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:04:53.542   375  1325 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,07-05 14:04:53.542   375  1325 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:04:53.542   375  1325 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:53.543   375  1325 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:53.556  3745  3758 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:53.569  2907  3759 V KeepSync: Connecting to GoogleApiClient
,07-05 14:04:53.569   874  1711 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 14:04:53.638  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:04:53.638  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:04:53.638  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:53.638  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:53.650  1812  3788 V BaseAuthAsyncOperation: access token request failed
,07-05 14:04:53.651  2907  3759 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:04:53.709  3644  3644 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-05 14:04:53.745   375  1325 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:04:53.745   375  1325 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:04:53.746   375  1325 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b7a000
07-05 14:04:53.746   375  1325 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b7a000
,07-05 14:04:53.752   330   337 D DrmLibTime: got the req here! ret=0
,07-05 14:04:53.752   330   337 D DrmLibTime: command id, time_cmd_id = 770
,07-05 14:04:53.752   330   337 D DrmLibTime: time_getutcsec starts!
07-05 14:04:53.752   330   337 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 14:04:53.752   330   337 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-05 14:04:53.752   330   337 D DrmLibTime: QSEE Time Listener: seconds: 1467720293
07-05 14:04:53.752   330   337 D DrmLibTime: QSEE Time Listener: nano seconds: 752499858
07-05 14:04:53.752   330   337 D DrmLibTime: time_getutcsec returns 0, sec = 1467720293; nsec = 752499858
07-05 14:04:53.752   330   337 D DrmLibTime: time_getutcsec finished! 
07-05 14:04:53.752   330   337 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 14:04:53.752   330   337 D DrmLibTime: before calling ioctl to read the next time_cmd
07-05 14:04:53.757  3644  3644 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-05 14:04:53.760   375  1325 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:04:53.760   375  1325 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 14:04:53.761   375  1325 D DrmWidevineDash: hlos api version =  10
07-05 14:04:53.761   375  1325 D DrmWidevineDash: tz api version =  10
07-05 14:04:53.761   375  1325 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:53.761   375  1325 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:04:53.779  3644  3644 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5560-5563)
07-05 14:04:53.780  3644  3644 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:53.780   375  1325 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:04:53.780   375  1325 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:53.780   375  1325 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2ec1134
,07-05 14:04:53.781   375  1325 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 14:04:53.781   375  1325 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:04:53.781   375  1325 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb3ac2238, dataLength=8
07-05 14:04:53.781   375  1325 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:04:53.788   375  1325 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb6048800, wrapped_rsa_key_length=1280
,07-05 14:04:53.791   375  1325 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 14:04:53.791   375  1325 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:04:53.796   375  1648 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-05 14:04:53.796   375  1648 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:53.796   375  1648 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:53.797   375  1648 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb464f780, idLength=0xb2bfef2c,
,07-05 14:04:53.809   375  1648 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-05 14:04:53.809   375  1648 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:04:53.810   375  1648 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:04:53.810   375  1648 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:04:53.810   375  1648 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:04:53.810   375  1648 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:04:53.811   375  1648 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-05 14:04:53.811   375  1648 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:53.812   375  1648 D DrmWidevineDash: hlos api version =  10
,07-05 14:04:53.812   375  1648 D DrmWidevineDash: tz api version =  10
,07-05 14:04:53.812   375  1648 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-05 14:04:53.812   375  1648 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
07-05 14:04:53.813   375  1648 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-05 14:04:53.813   375  1648 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-05 14:04:53.814   375  1648 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:04:53.814   375  1648 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 14:04:53.814   375  1648 D WVCdm   : PrepareKeyRequest: nonce=4142015516
07-05 14:04:53.814   375  1648 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb17e0000
,07-05 14:04:53.814   375  1648 D DrmWidevineDash: message_length=1624, signature=0xb3adaa00, signature_length=2998923268
,07-05 14:04:53.832  3644  3644 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de9b069}
,07-05 14:04:53.833  3644  3644 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 14:04:53.833  3644  3644 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:53.838  3644  3644 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:53.839  3644  3644 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 14:04:53.888   375  1648 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:04:53.888   375   375 I WVCdm   : CdmEngine::CloseSession
,07-05 14:04:53.888   375   375 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-05 14:04:53.889   375   375 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 14:04:53.889   375   375 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:04:53.890   375   375 D DrmWidevineDash: Service_Uninitialize: starts!
,07-05 14:04:53.890   375   375 D QSEECOMAPI: : QSEECom_dealloc_memory 
,07-05 14:04:53.890   375   375 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,07-05 14:04:53.891   375   375 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-05 14:04:53.891   375   375 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:04:53.925  3644  3644 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-05 14:04:53.963  3644  3644 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 14:04:53.963  3644  3644 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:04:53.963  3644  3644 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 14:04:53.963  3644  3644 I Adreno  : Build Date                       : 10/20/15
07-05 14:04:53.963  3644  3644 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 14:04:53.963  3644  3644 I Adreno  : Local Branch                     : M14
07-05 14:04:53.963  3644  3644 I Adreno  : Remote Branch                    : 
07-05 14:04:53.963  3644  3644 I Adreno  : Remote Branch                    : 
07-05 14:04:53.963  3644  3644 I Adreno  : Reconstruct Branch               : 
,07-05 14:04:53.984   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-05 14:04:54.014  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:54.014  3358  3405 I jxcore-log: 
,07-05 14:04:54.041  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:54.041  3358  3405 I jxcore-log: 
07-05 14:04:54.046  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:54.046  3358  3405 I jxcore-log: 
,07-05 14:04:54.066  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:54.066  3358  3405 I jxcore-log: 
,07-05 14:04:54.071  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:54.071  3358  3405 I jxcore-log: 
,07-05 14:04:54.092  3644  3813 W AudioManagerAndroid: Requires BLUETOOTH permission
07-05 14:04:54.107  3644  3644 I NSApplication: Starting up...
07-05 14:04:54.108  3810  3810 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/the.apk --oat-file=/data/user/0/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/opt/the.dex
,07-05 14:04:54.123   874   884 I ActivityManager: Start proc 3819:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-05 14:04:54.134  3810  3810 I dex2oat : dex2oat took 26.744ms (threads: 4) arena alloc=41KB java alloc=21KB native alloc=1048KB free=743KB
,07-05 14:04:54.151  3819  3819 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-05 14:04:54.286  1351  3593 D DownloadManager: [116] Finished with status SUCCESS
,07-05 14:04:54.354  3712  3837 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 14:04:54.364  3835  3835 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-05 14:04:54.394  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:04:54.394  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:04:54.394  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:54.395  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.417  3835  3835 I dex2oat : dex2oat took 53.889ms (threads: 4) arena alloc=102KB java alloc=47KB native alloc=1539KB free=1788KB
,07-05 14:04:54.423  3745  3758 W System  : ClassLoader referenced unknown path: 
,07-05 14:04:54.437  3745  3758 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 14:04:54.437  3745  3758 I Adreno  : Build Date                       : 10/20/15
07-05 14:04:54.437  3745  3758 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 14:04:54.437  3745  3758 I Adreno  : Local Branch                     : M14
07-05 14:04:54.437  3745  3758 I Adreno  : Remote Branch                    : 
07-05 14:04:54.437  3745  3758 I Adreno  : Remote Branch                    : 
07-05 14:04:54.437  3745  3758 I Adreno  : Reconstruct Branch               : 
,07-05 14:04:54.444  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 14:04:54.445  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:04:54.445  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:54.446  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.461  3712  3837 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:04:54.463  3712  3760 E BooksSync: Soft error
07-05 14:04:54.463  3712  3760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:54.463  3712  3760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:04:54.463  3712  3760 E BooksSync: Sync error
07-05 14:04:54.463  3712  3760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:54.463  3712  3760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:04:54.463  3712  3760 I BooksSync: Finished books sync
,07-05 14:04:54.481   874  1406 I ActivityManager: Killing 2719:android.process.acore/u0a5 (adj 15): empty #17
,07-05 14:04:54.482   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23962, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:04:54.533  3745  3758 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 14:04:54.533  3745  3758 I Adreno  : Build Date                       : 10/20/15
07-05 14:04:54.533  3745  3758 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 14:04:54.533  3745  3758 I Adreno  : Local Branch                     : M14
07-05 14:04:54.533  3745  3758 I Adreno  : Remote Branch                    : 
07-05 14:04:54.533  3745  3758 I Adreno  : Remote Branch                    : 
07-05 14:04:54.533  3745  3758 I Adreno  : Reconstruct Branch               : 
,07-05 14:04:54.626  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-05 14:04:54.626  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:04:54.626  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:54.627  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:54.647   375  1287 I WVCdm   : CdmEngine::OpenSession
07-05 14:04:54.647   375  1287 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
07-05 14:04:54.648  2907  3759 E KeepSync: IOException
07-05 14:04:54.648  2907  3759 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:54.648  2907  3759 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:04:54.648  2907  3759 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:04:54.648  2907  3759 E KeepSync: 	... 10 more
07-05 14:04:54.648  2907  3759 W KeepSync: Sync result 2
07-05 14:04:54.648   375  1287 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-05 14:04:54.649   375  1287 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
07-05 14:04:54.649   375  1287 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:04:54.649   375  1287 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:54.650   375  1287 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:54.670   874  1725 I ActivityManager: Killing 3250:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-05 14:04:54.748   874   886 I ActivityManager: Start proc 3851:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,07-05 14:04:54.766  3851  3851 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
07-05 14:04:54.771   874  1747 I ActivityManager: Start proc 3864:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-05 14:04:54.806  3864  3864 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,07-05 14:04:54.814  3851  3879 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-05 14:04:54.817   874  1385 I ActivityManager: Killing 3264:com.android.musicfx/u0a18 (adj 15): empty #17
,07-05 14:04:54.818   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 23962, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:04:54.829  3851  3878 I Gmail   : getAccountsCursor
,07-05 14:04:54.839   375  1287 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:04:54.840   375  1287 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-05 14:04:54.841   375  1287 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b7a000
07-05 14:04:54.841   375  1287 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1b7a000
,07-05 14:04:54.846   330   337 D DrmLibTime: got the req here! ret=0
,07-05 14:04:54.846   330   337 D DrmLibTime: command id, time_cmd_id = 770
07-05 14:04:54.846   330   337 D DrmLibTime: time_getutcsec starts!
07-05 14:04:54.846   330   337 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 14:04:54.846   330   337 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,07-05 14:04:54.847   330   337 D DrmLibTime: QSEE Time Listener: seconds: 1467720294
07-05 14:04:54.847   330   337 D DrmLibTime: QSEE Time Listener: nano seconds: 847032727
07-05 14:04:54.847   330   337 D DrmLibTime: time_getutcsec returns 0, sec = 1467720294; nsec = 847032727
,07-05 14:04:54.847   330   337 D DrmLibTime: time_getutcsec finished! 
07-05 14:04:54.847   330   337 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 14:04:54.847   330   337 D DrmLibTime: before calling ioctl to read the next time_cmd
,07-05 14:04:54.851   375  1287 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-05 14:04:54.851   375  1287 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 14:04:54.852   375  1287 D DrmWidevineDash: hlos api version =  10
07-05 14:04:54.852   375  1287 D DrmWidevineDash: tz api version =  10
,07-05 14:04:54.852   375  1287 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-05 14:04:54.852   375  1287 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:04:54.862   375  1287 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-05 14:04:54.862   375  1287 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:54.862   375  1287 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2fc0134
07-05 14:04:54.863   375  1287 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 14:04:54.863   375  1287 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:04:54.863   375  1287 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608c9d8, dataLength=8
07-05 14:04:54.864   375  1287 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-05 14:04:54.864   375  1287 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1a07c00, wrapped_rsa_key_length=1280
07-05 14:04:54.865  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:04:54.867   375  1287 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-05 14:04:54.868   375  1287 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-05 14:04:54.869   375   375 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:04:54.869   375   375 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-05 14:04:54.869   375   375 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:54.869   375   375 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb31f5a40, idLength=0xbeda400c
07-05 14:04:54.879   375   375 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 14:04:54.879   375   375 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-05 14:04:54.880   375   375 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-05 14:04:54.880   375   375 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-05 14:04:54.880   375   375 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,07-05 14:04:54.880   375   375 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-05 14:04:54.880   375   375 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-05 14:04:54.880   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 14:04:54.881   375   375 D DrmWidevineDash: hlos api version =  10
,07-05 14:04:54.881   375   375 D DrmWidevineDash: tz api version =  10
07-05 14:04:54.881   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-05 14:04:54.881   375   375 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
07-05 14:04:54.882   375   375 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-05 14:04:54.882   375   375 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
,07-05 14:04:54.882   375   375 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
07-05 14:04:54.882   375   375 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 14:04:54.882   375   375 D WVCdm   : PrepareKeyRequest: nonce=763973520
07-05 14:04:54.882   375   375 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb17e0700
07-05 14:04:54.882   375   375 D DrmWidevineDash: message_length=1655, signature=0xb60b6d40, signature_length=3201974500
07-05 14:04:54.895  3851  3851 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-05 14:04:54.922  3851  3890 E Gmail   : Error finding the version of the Email provider.....
07-05 14:04:54.922  3851  3890 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-05 14:04:54.922  3851  3890 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-05 14:04:54.922  3851  3890 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-05 14:04:54.922  3851  3890 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-05 14:04:54.922  3851  3890 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:54.922  3851  3890 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:54.922  3851  3890 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:54.922  3851  3890 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:54.922  3851  3890 W EmailMigration: We do not support migrating this version of the Email provider.
07-05 14:04:54.936  3644  3892 I SyncAdapterService: Ignoring sync request for non-current account
07-05 14:04:54.937  3851  3891 W Gmail   : Sync started for account: account:61035162
07-05 14:04:54.941   375   375 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
07-05 14:04:54.942   375  1325 I WVCdm   : CdmEngine::CloseSession
07-05 14:04:54.942   375  1325 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-05 14:04:54.943   375  1325 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 14:04:54.943   375  1325 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-05 14:04:54.943   375  1325 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 14:04:54.944   375  1325 D QSEECOMAPI: : QSEECom_dealloc_memory 
,07-05 14:04:54.944   375  1325 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,07-05 14:04:54.944   375  1325 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:04:54.944   375  1325 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
07-05 14:04:54.954   874  1733 I ActivityManager: Start proc 3896:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
07-05 14:04:54.984  3896  3896 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-05 14:04:54.997  1812  3546 I CheckinRequestBuilder: Classify the device as Phone.
,07-05 14:04:55.001  1812  3546 I EventLogService: Opted in for usage reporting
,07-05 14:04:55.034  3896  3896 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@ad5e5ef(com.android.providers.calendar.CalendarProvider2@efbe8fc)
,07-05 14:04:55.091   874  1385 I ActivityManager: Start proc 3918:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-05 14:04:55.093   874  1385 I ActivityManager: Killing 3077:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-05 14:04:55.176   874  1733 I ActivityManager: Start proc 3932:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,07-05 14:04:55.179   874  1753 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-05 14:04:55.206   874   886 I ActivityManager: Start proc 3946:com.google.process.gapps/u0a99 for service com.google.android.syncadapters.contacts/.ContactsSyncAdapterService
,07-05 14:04:55.210  3864  3864 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-05 14:04:55.234  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-05 14:04:55.234  3946  3946 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-05 14:04:55.237  3918  3918 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-05 14:04:55.245  3946  3946 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:04:55.268  1812  3546 W System.err: java.lang.Exception: Error converting session
,07-05 14:04:55.268  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
,07-05 14:04:55.268  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
,07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-05 14:04:55.269  1812  3546 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
,07-05 14:04:55.269  1812  3546 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
07-05 14:04:55.270  1812  3546 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
07-05 14:04:55.270  1812  3546 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
07-05 14:04:55.270  1812  3546 W System.err: 	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
,07-05 14:04:55.270  1812  3546 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
07-05 14:04:55.270  1812  3546 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:04:55.270  1812  3546 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:04:55.270  1812  3546 W System.err: Caused by: java.io.IOException: Invalid session data
07-05 14:04:55.270  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
07-05 14:04:55.270  1812  3546 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
,07-05 14:04:55.270  1812  3546 W System.err: 	... 25 more
,07-05 14:04:55.273   874  1385 I ActivityManager: Start proc 3962:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,07-05 14:04:55.280  3918  3918 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:04:55.280  3918  3918 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:04:55.280  3918  3918 I GAv4    :   adb logcat -s GAv4
,07-05 14:04:55.307  3962  3962 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-05 14:04:55.317  3918  3918 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:55.324  3918  3918 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:55.356  1812  3546 I CheckinTask: Sending checkin request (9264 bytes)
,07-05 14:04:55.370  3918  3976 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:04:55.401  3851  3945 I Gmail   : Observing account changes for notifications
,07-05 14:04:55.435  3932  3932 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:04:55.464   874   885 I ActivityManager: Start proc 3987:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,07-05 14:04:55.481  1812  1812 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-05 14:04:55.480  3962  3962 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-05 14:04:55.486  1812  3999 I ConfigFetchService: running network task: configservice_periodic
,07-05 14:04:55.487  1812  3999 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
07-05 14:04:55.487  1812  3999 E WakeLock: java.lang.IllegalArgumentException
07-05 14:04:55.487  1812  3999 E WakeLock: 	at com.google.android.gms.stats.d.<init>(SourceFile:135)
07-05 14:04:55.487  1812  3999 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:341)
07-05 14:04:55.487  1812  3999 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:159)
07-05 14:04:55.487  1812  3999 E WakeLock: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-05 14:04:55.488  1812  3999 I ConfigFetchService: launchTask
,07-05 14:04:55.503  1512  1512 I ConfigService: onCreate
,07-05 14:04:55.513  1812  1812 I ConfigFetchService: service connected
,07-05 14:04:55.515  1812  1812 D ConfigFetchService: ConfigApi connection successful.
,07-05 14:04:55.524  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-05 14:04:55.533  3987  3987 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467720295533
,07-05 14:04:55.533  3987  3987 D         : TimeServiceNative: User Time to be set is 1467720295533
07-05 14:04:55.533  3987  3987 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-05 14:04:55.533  3987  3987 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-05 14:04:55.533  3987  3987 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467720295533
07-05 14:04:55.533  3987  3987 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-05 14:04:55.533   399   980 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-05 14:04:55.534   399  4002 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467720295533
,07-05 14:04:55.534   399  4002 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467720295533, operation = 0
07-05 14:04:55.534   399  4002 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/21/70 8:15:36
07-05 14:04:55.534   399  4002 D QC-time-services: Daemon:Value read from RTC seconds = 28023336000
07-05 14:04:55.534   399  4002 D QC-time-services: Daemon:new time 1467720295533 
07-05 14:04:55.534   399  4002 D QC-time-services: Daemon: delta 1439696959533 genoff 1439696959533 
07-05 14:04:55.534   399  4002 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696959533 to memory
,07-05 14:04:55.535   399  4002 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-05 14:04:55.535   399  4002 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-05 14:04:55.538   399  4002 D QC-time-services: Updating the TOD offset
,07-05 14:04:55.538   399  4002 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696959533 to memory
07-05 14:04:55.538   399  4002 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-05 14:04:55.538   399  4002 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-05 14:04:55.542   399  4002 E QC-time-services: Daemon:Update to modem bit set
07-05 14:04:55.542  3932  3932 I Exchange: EasService.onCreate
,07-05 14:04:55.542   399  4002 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-05 14:04:55.542   399  4002 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1151755495533
,07-05 14:04:55.546  3987  3987 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-05 14:04:55.547   874  1747 I ActivityManager: Killing 3288:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-05 14:04:55.570  3932  4003 I Exchange: RestartPingTask
,07-05 14:04:55.607   874   885 I ActivityManager: Killing 3215:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-05 14:04:55.610   399   980 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-05 14:04:55.615   399   978 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-05 14:04:55.653  1512  2308 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
07-05 14:04:55.653  3946  3960 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,07-05 14:04:55.665  3932  3932 I Exchange: RestartPingsTask did not start any pings.
07-05 14:04:55.665  3932  3932 I Exchange: PSS stopIfIdle
,07-05 14:04:55.665  3932  3932 I Exchange: PSS has no active accounts; stopping service.
,07-05 14:04:55.669  1812  1812 I GCM     : Message from 745476177629 null
,07-05 14:04:55.678  1812  1812 I GCM     : Message from 745476177629 null
,07-05 14:04:55.686  3946  3960 I GoogleHttpClient: GMS http client unavailable, use old client
,07-05 14:04:55.698  3932  3932 I Exchange: onDestroy
,07-05 14:04:55.703  1812  3546 I CheckinResponseProcessor: From server: 3 gservices updates and 1 deletes
,07-05 14:04:55.730  1512  2316 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 14:04:55.732  1512  1512 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 14:04:55.740  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:55.742  1812  1812 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 14:04:55.761   874  1406 I ActivityManager: Start proc 4012:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,07-05 14:04:55.780  1812  4025 D LocationInitializer: Restart initialization of location
,07-05 14:04:55.804  1866  1990 W GCoreFlp: No location to return for getLastLocation()
,07-05 14:04:55.805  1512  4026 W FusedLocationProvider: location=null
,07-05 14:04:55.808  4012  4012 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:04:55.818  4012  4012 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:04:55.818  4012  4012 I MultiDex: install
07-05 14:04:55.818  4012  4012 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:55.834  1671  4027 I DictionaryProvider:UpdateHandler: downloadFinished() : DownloadId = 116
,07-05 14:04:55.838  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:55.862  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,07-05 14:04:55.862  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
07-05 14:04:55.862  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:55.862  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:55.877  4012  4012 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:55.903  4012  4012 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:55.915  4012  4012 D WearableService: callingUid 10011, callindPid: 4012
,07-05 14:04:55.932  1512  2654 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-05 14:04:55.936  1512  1512 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 14:04:55.937  1812  4031 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:55.947  1866  2258 E MDM     : [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-05 14:04:55.949  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,07-05 14:04:55.949  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
07-05 14:04:55.950  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:55.950  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:55.964  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:55.974  4012  4038 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-05 14:04:56.007   874  1733 I ActivityManager: Killing 2597:com.android.vending/u0a19 (adj 15): empty #17
,07-05 14:04:56.020  3851  3931 I Gmail   : notifyAccountChanged
,07-05 14:04:56.021  3851  3878 I Gmail   : getAccountsCursor
,07-05 14:04:56.029  3851  3931 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:04:56.031  3851  3931 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-05 14:04:56.033  3962  3979 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-05 14:04:56.047  1812  1812 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 14:04:56.062  1866  2293 E MDM     : [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-05 14:04:56.076  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:56.077  1512  3708 I GservicesProvider: main difference update completed
,07-05 14:04:56.082  1812  3546 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-05 14:04:56.085  1512  4044 I VacuumService: Vacuum at: now=1467720296085 tag=VacuumService
,07-05 14:04:56.091  2367  4008 E Babel   : UserRecoverableAuthException.
,07-05 14:04:56.094  1812  3546 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
07-05 14:04:56.094  1512  4035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.me
07-05 14:04:56.094  1512  4035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me without consulting the cloud.
07-05 14:04:56.094  1512  4035 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:56.095  1512  4035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:56.101  2367  4008 E Babel   : efr: BadAuthentication
07-05 14:04:56.101  2367  4008 E Babel   : 	at efp.a(Unknown Source)
07-05 14:04:56.101  2367  4008 E Babel   : 	at efp.a(Unknown Source)
07-05 14:04:56.101  2367  4008 E Babel   : 	at efp.a(Unknown Source)
07-05 14:04:56.101  2367  4008 E Babel   : 	at g.a(Unknown Source)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbh.a(SourceFile:3092)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbh.a(SourceFile:1136)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cyr.a(SourceFile:4333)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cyr.a(SourceFile:1419)
07-05 14:04:56.101  2367  4008 E Babel   : 	at ctk.a(SourceFile:492)
07-05 14:04:56.101  2367  4008 E Babel   : 	at ctk.a(SourceFile:1468)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cst.a(SourceFile:4416)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbv.b(SourceFile:106)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbs.d(SourceFile:335)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbt.run(SourceFile:81)
,07-05 14:04:56.101  2367  4008 E Babel   : Error getting auth token
07-05 14:04:56.101  2367  4008 E Babel   : dxq
07-05 14:04:56.101  2367  4008 E Babel   : 	at g.a(Unknown Source)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbh.a(SourceFile:3092)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbh.a(SourceFile:1136)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cyr.a(SourceFile:4333)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cyr.a(SourceFile:1419)
07-05 14:04:56.101  2367  4008 E Babel   : 	at ctk.a(SourceFile:492)
07-05 14:04:56.101  2367  4008 E Babel   : 	at ctk.a(SourceFile:1468)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cst.a(SourceFile:4416)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbv.b(SourceFile:106)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbs.d(SourceFile:335)
07-05 14:04:56.101  2367  4008 E Babel   : 	at cbt.run(SourceFile:81)
,07-05 14:04:56.106   874  1733 I ActivityManager: Start proc 4047:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,07-05 14:04:56.109  1812  4046 D LocationInitializer: Restart initialization of location
,07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: Failed to update the notification(s) read state.
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:60)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:403)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:284)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:262)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.notifications.a.a(SourceFile:45)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsService.a(SourceFile:199)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at com.google.android.gms.notifications.GunsService.onHandleIntent(SourceFile:73)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:56.136  1512  4035 W GnotsSRSOperation: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:56.137  1512  4035 W WakefulBroadcastReceiver: No active wake lock id #7
,07-05 14:04:56.141  1866  1990 W GCoreFlp: No location to return for getLastLocation()
07-05 14:04:56.141  1512  4059 W FusedLocationProvider: location=null
07-05 14:04:56.149  2367  4008 E Babel   : Account registration failed 1-Redacted-21
07-05 14:04:56.150  2367  4008 E Babel   : dao: null -- null,
07-05 14:04:56.150  2367  4008 E Babel   : 	at cbh.a(SourceFile:3124)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cbh.a(SourceFile:1136)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cyr.a(SourceFile:4333)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cyr.a(SourceFile:1419)
07-05 14:04:56.150  2367  4008 E Babel   : 	at ctk.a(SourceFile:492)
07-05 14:04:56.150  2367  4008 E Babel   : 	at ctk.a(SourceFile:1468)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cst.a(SourceFile:4416)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cbv.b(SourceFile:106)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cbs.d(SourceFile:335)
07-05 14:04:56.150  2367  4008 E Babel   : 	at cbt.run(SourceFile:81)
,07-05 14:04:56.153  1512  4035 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
,07-05 14:04:56.175  1512  4035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.me
,07-05 14:04:56.175  1512  4035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me without consulting the cloud.
07-05 14:04:56.175  1512  4035 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-05 14:04:56.175  1512  4035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 14:04:56.186  2367  4008 I art     : Note: end time exceeds epoch: 
,07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: Failed to fetch notification by identifer.
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:60)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.b(SourceFile:403)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:284)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.common.server.s.a(SourceFile:262)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.notifications.c.a(SourceFile:45)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.notifications.GunsService.a(SourceFile:228)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at com.google.android.gms.notifications.GunsService.onHandleIntent(SourceFile:86)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at android.os.Looper.loop(Looper.java:148)
07-05 14:04:56.188  1512  4035 D GnotsFetchOperation: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:04:56.189  1512  4035 W WakefulBroadcastReceiver: No active wake lock id #8
,07-05 14:04:56.213   874  1406 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:04:56.214  2367  2367 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-05 14:04:56.214  2367  2367 W Babel   : BAM#gBA: invalid account id: -1
07-05 14:04:56.214  2367  2367 W Babel   : BAM#gBA: invalid account id: -1
,07-05 14:04:56.214  2367  2367 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-05 14:04:56.216  3896  3896 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
07-05 14:04:56.217  3896  3896 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-05 14:04:56.219   874  1753 I ActivityManager: Killing 1829:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,07-05 14:04:56.241  4047  4047 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm
,07-05 14:04:56.242  3851  3931 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:04:56.253  3851  3931 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-05 14:04:56.281   874  1318 D WifiService: Client connection lost with reason: 4
,07-05 14:04:56.323  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-05 14:04:56.323  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
07-05 14:04:56.323  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:56.323  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:56.336  1512  4064 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-05 14:04:56.337  1512  4064 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:56.338  4047  4047 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,07-05 14:04:56.348  2367  3152 E Babel   : Unexpected exception while authenticating.
07-05 14:04:56.348  2367  3152 E Babel   : efs: User intervention required. Notification has been pushed.
07-05 14:04:56.348  2367  3152 E Babel   : 	at efp.b(Unknown Source)
07-05 14:04:56.348  2367  3152 E Babel   : 	at efp.b(Unknown Source)
07-05 14:04:56.348  2367  3152 E Babel   : 	at g.a(Unknown Source)
07-05 14:04:56.348  2367  3152 E Babel   : 	at cbh.b(SourceFile:1151)
07-05 14:04:56.348  2367  3152 E Babel   : 	at def.run(SourceFile:5617)
07-05 14:04:56.348  2367  3152 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:04:56.348  2367  3152 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:04:56.348  2367  3152 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
07-05 14:04:56.353  4047  4047 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,07-05 14:04:56.356  4047  4047 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,07-05 14:04:56.358  4047  4047 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,07-05 14:04:56.361  4047  4047 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,07-05 14:04:56.376  3410  3410 W InstanceID/Rpc: Found 10011
,07-05 14:04:56.378  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-05 14:04:56.378  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-05 14:04:56.378  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:56.379  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:56.396   874  1787 I ActivityManager: Start proc 4082:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,07-05 14:04:56.397   874  1787 I ActivityManager: Killing 3467:com.android.settings/1000 (adj 15): empty #17
07-05 14:04:56.410  3851  3891 I Gmail   : notifyAccountChanged
,07-05 14:04:56.463  1812  3546 W CheckinRequestBuilder: awaiting user notification for token
,07-05 14:04:56.477  1812  3546 I CheckinRequestBuilder: Classify the device as Phone.
,07-05 14:04:56.481  1812  3546 I EventLogService: Opted in for usage reporting
,07-05 14:04:56.502  1812  3546 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-05 14:04:56.504  4082  4082 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,07-05 14:04:56.512  1812  3546 I CheckinService: Checking schedule, now: 1467720296512 next: 1467761439502
07-05 14:04:56.512  1812  3546 I CheckinService: active receiver: disabled
,07-05 14:04:56.559   874  1385 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,07-05 14:04:56.566  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:56.566  3358  3405 I jxcore-log: 
,07-05 14:04:56.577  1812  1812 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,07-05 14:04:56.579  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:56.579  3358  3405 I jxcore-log: 
,07-05 14:04:56.580  1812  1812 D SystemUpdateService: onCreate
,07-05 14:04:56.584  1812  1812 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-05 14:04:56.593  1812  1812 D OcrModelManager: Updating downloaded model state (gservices changed)
,07-05 14:04:56.597  1812  1812 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
07-05 14:04:56.597  1812  1812 I OcrUtils: Updating ocr activity enabled=false
07-05 14:04:56.598  1512  4064 W Uploader:  no longer exists, so no auth token.
,07-05 14:04:56.600  1512  2245 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
07-05 14:04:56.600  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:56.600  3358  3405 I jxcore-log: 
,07-05 14:04:56.609  1812  4102 I CheckinService: Checking schedule, now: 1467720296609 next: 1467761439502
,07-05 14:04:56.609  1812  4102 I CheckinService: active receiver: disabled
,07-05 14:04:56.612  1812  1819 E System  : Uncaught exception thrown by finalizer
07-05 14:04:56.612  1812  1819 E System  : java.lang.NullPointerException: ssl_session == null
07-05 14:04:56.612  1812  1819 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-05 14:04:56.612  1812  1819 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-05 14:04:56.612  1812  1819 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-05 14:04:56.612  1812  1819 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-05 14:04:56.612  1812  1819 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-05 14:04:56.623  1866  1866 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,07-05 14:04:56.626  1812  4104 I SystemUpdateService: cancelUpdate (empty URL)
,07-05 14:04:56.626  1812  4104 I SystemUpdateService: active receiver: disabled
,07-05 14:04:56.634  1866  1866 I GCoreUlr: DispatchingService.onCreate()
,07-05 14:04:56.718  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:56.718  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:56.718  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:56.718  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:56.732  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:56.732  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:56.732  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:56.826   874  1733 I ActivityManager: Killing 3489:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,07-05 14:04:56.837  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:56.837  3358  3405 I jxcore-log: 
,07-05 14:04:56.931  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:56.931  3358  3405 I jxcore-log: 
,07-05 14:04:56.932  1671  4027 I DictionaryProvider:UpdateHandler: downloadFinished() : Success = true
,07-05 14:04:56.932  1671  4027 I DictionaryProvider:UpdateHandler: downloadFinished() : Metadata Success
07-05 14:04:56.960  1671  1671 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-05 14:04:56.967  1812  1812 D SystemUpdateService: onDestroy
,07-05 14:04:56.982  1866  4113 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,07-05 14:04:56.983  1671  4115 I Keyboard.Facilitator.DecoderInitializer: run()
,07-05 14:04:56.990  1671  4115 I Decoder : createOrResetDecoder
,07-05 14:04:57.024  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:57.024  3358  3405 I jxcore-log: 
,07-05 14:04:57.029   874  1752 I ActivityManager: Start proc 4120:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,07-05 14:04:57.033  1671  4115 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-05 14:04:57.043  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:57.043  3358  3405 I jxcore-log: 
,07-05 14:04:57.092  3851  3860 W Gmail   : MailSyncAdapterService#onSyncCanceled Thread[SyncAdapterThread-1,5,main]
,07-05 14:04:57.092  3851  3860 W Gmail   : MailEngine != null account: account:61035162
,07-05 14:04:57.094   874  1752 I ActivityManager: Killing 3578:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,07-05 14:04:56.993  3962  3979 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,07-05 14:04:57.114  3962  3979 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-05 14:04:57.136  1671  4115 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-05 14:04:57.147  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-05 14:04:57.147  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-05 14:04:57.158  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,07-05 14:04:57.158  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-05 14:04:57.166  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-05 14:04:57.167  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,07-05 14:04:57.168  1671  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-05 14:04:57.168  1671  4115 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-05 14:04:57.168  1671  4115 I Keyboard.Facilitator.Delight2FileSweeper: run()
,07-05 14:04:57.169  1671  4115 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-05 14:04:57.169  1671  4115 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,07-05 14:04:57.169  1671  4115 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-05 14:04:57.177  1866  4113 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-05 14:04:57.183  1866  4113 I GCoreUlr: Unbound from all location providers
,07-05 14:04:57.197  1866  1866 I GCoreUlr: DispatchingService.onDestroy()
,07-05 14:04:57.197  1866  1866 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-05 14:04:57.200  1866  1866 I GCoreUlr: Unbound from all location providers
,07-05 14:04:57.261   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 24003, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,07-05 14:04:57.285  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:57.285  3358  3405 I jxcore-log: 
,07-05 14:04:57.305  3864  3864 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-05 14:04:57.309  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:57.309  3358  3405 I jxcore-log: 
,07-05 14:04:57.314  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:57.314  3358  3405 I jxcore-log: 
,07-05 14:04:57.319  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:57.319  3358  3405 I jxcore-log: 
,07-05 14:04:57.333  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:57.338  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:57.338  3358  3405 I jxcore-log: 
,07-05 14:04:57.354  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,07-05 14:04:57.355  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> cp without consulting the cloud.
,07-05 14:04:57.355  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:04:57.355  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:57.361  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:57.361  3358  3405 I jxcore-log: 
,07-05 14:04:57.374  1512  2698 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:57.374  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:57.374  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:57.374  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:57.374  1512  2698 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:57.374  1512  2698 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:57.374  1512  2698 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:57.376  3962  3979 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-05 14:04:57.378  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:57.378  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:57.378  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:57.379  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:57.391  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:57.391  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:57.391  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: innerSync failed
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:269)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:169)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:128)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:04:57.412  3946  3960 D ContactsSyncAdapter: 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:04:57.447  3962  3979 I ContactDirectoryManager: Discovered 0 contact directories in 999ms
07-05 14:04:57.455  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:57.455  3358  3405 I jxcore-log: 
,07-05 14:04:57.460  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:57.460  3358  3405 I jxcore-log: 
,07-05 14:04:57.489  3358  3405 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:57.489  3358  3405 I jxcore-log: 
,07-05 14:04:57.492   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 24003, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:57.496   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 159936, reason: Periodic
,07-05 14:04:57.502  3358  3405 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-05 14:04:57.504  3358  3405 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-05 14:04:57.504  3358  3405 I jxcore-log: 
,07-05 14:04:57.564  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-05 14:04:57.564  3358  3405 I jxcore-log: 
,07-05 14:04:57.569  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-05 14:04:57.569  3358  3405 I jxcore-log: 
,07-05 14:04:57.570  3358  3405 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:57.570  3358  3405 I jxcore-log: 
,07-05 14:04:57.571  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:57.571  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:04:57.579  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
07-05 14:04:57.584  3851  3891 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
07-05 14:04:57.600  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:57.610  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:57.624  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:57.643  1812  1812 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:57.656  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:57.671  3851  3879 I Gmail   : getAccountsCursor
,07-05 14:04:57.673  1671  4027 I DictionaryProvider:UpdateHandler: downloadFinished() : Success = true
,07-05 14:04:57.674  1671  4027 I DictionaryProvider:UpdateHandler: downloadFinished() : Metadata Success
,07-05 14:04:57.675  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:57.676  1671  1671 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-05 14:04:57.695   874   886 I ActivityManager: Start proc 4149:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,07-05 14:04:57.711  1671  4147 I Keyboard.Facilitator.DecoderInitializer: run()
,07-05 14:04:57.728  4149  4149 W System  : ClassLoader referenced unknown path: /system/app/Music2/lib/arm
,07-05 14:04:57.728  1671  4147 I Decoder : createOrResetDecoder
,07-05 14:04:57.732  4149  4149 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:04:57.732  4149  4149 I MultiDex: install
,07-05 14:04:57.732  4149  4149 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:57.761  1671  4147 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-05 14:04:57.766  4149  4149 I MusicStore: Database version: 121
,07-05 14:04:57.811  3851  3879 I Gmail   : getAccountsCursor
,07-05 14:04:57.820  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:57.824  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:57.825  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:57.825  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:57.825  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:57.835  1671  4147 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-05 14:04:57.840  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:57.840  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:57.840  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:57.847  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,07-05 14:04:57.847  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-05 14:04:57.848  4149  4149 D MusicLifecycle: com.google.android.music.MusicApplication generated event: Application created
,07-05 14:04:57.853  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,07-05 14:04:57.853  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-05 14:04:57.858  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,07-05 14:04:57.858  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,07-05 14:04:57.861  1671  4147 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,07-05 14:04:57.861  1671  4147 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-05 14:04:57.861  1671  4147 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-05 14:04:57.861  1671  4147 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-05 14:04:57.861  1671  4147 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-05 14:04:57.861  1671  4147 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-05 14:04:57.867  4149  4149 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:04:57.891   874  1406 I ActivityManager: Killing 3597:com.android.chrome/u0a40 (adj 15): empty #17
,07-05 14:04:57.925  4149  4149 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:57.962  1351  4159 V DownloadManager: Deleting /data/data/com.android.providers.downloads/cache/metadata.json#14674240447544.1.23103.2862625.json via provider delete
,07-05 14:04:57.966  4149  4149 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:57.966  4149  4149 D AndroidMusic: GMSCore installation verified
,07-05 14:04:57.979  1512  4180 E GnotsPayloadUtil: Payload contains insufficient data to show the system notification.
,07-05 14:04:57.979  1512  4180 W WakefulBroadcastReceiver: No active wake lock id #9
,07-05 14:04:58.000  4149  4149 I ConfigStore: Config Database version: 1
,07-05 14:04:58.023  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:58.023  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:58.023  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:58.023  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:58.037  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:58.037  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:58.037  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:58.044  3864  4137 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:04:58.070  1812  1812 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-05 14:04:58.074  4149  4149 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
07-05 14:04:58.074  1812  1812 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-05 14:04:58.074  1512  2291 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-05 14:04:58.080  1512  2308 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
07-05 14:04:58.081  1812  1812 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-05 14:04:58.082  1812  1812 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-05 14:04:58.111  4149  4149 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 14:04:58.114  4149  4149 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:58.121  4149  4149 D MusicLifecycle: com.google.android.music.net.NetworkMonitor generated event: Service created
07-05 14:04:58.122  4149  4149 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:58.123  4149  4193 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,07-05 14:04:58.143  4149  4149 D MusicLifecycle: com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,07-05 14:04:58.145  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,07-05 14:04:58.149  4149  4149 D MusicLifecycle: com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,07-05 14:04:58.150  3851  3891 I Gmail   : notifyAccountChanged
,07-05 14:04:58.157  4149  4149 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a49ef4f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-05 14:04:58.158  4149  4149 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-05 14:04:58.163  4149  4149 D MusicLifecycle: com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,07-05 14:04:58.166  4149  4149 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,07-05 14:04:58.168  4149  4149 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:58.169  3851  4004 I Gmail   : getAccountsCursor
,07-05 14:04:58.173  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:58.174  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service created
,07-05 14:04:58.181  4120  4200 I GservicesUpdateTask: Updating Gservices keys
,07-05 14:04:58.187  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,07-05 14:04:58.215  3851  3891 I Gmail   : notifyAccountChanged
,07-05 14:04:58.217  3851  3891 W Gmail   : Sync complete for account: account:61035162
,07-05 14:04:58.218  3851  4005 I Gmail   : getAccountsCursor
,07-05 14:04:58.222  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:58.229   874   886 D SyncManager: handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 126509, mTimeoutStartTime 126509, mHistoryRowId 8, syncOperation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 159343, reason: Periodic
,07-05 14:04:58.306  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:58.329  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.music, service: sj
,07-05 14:04:58.329  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> sj without consulting the cloud.
07-05 14:04:58.329  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:58.329  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:58.331  3712  3742 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:58.339  1512  1918 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:58.339  1512  1918 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:58.339  1512  1918 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:58.339  1512  1918 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:58.339  1512  1918 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:58.339  1512  1918 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:58.339  1512  1918 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:58.345  4149  4149 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@b48c21a and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:04:58.355  4149  4193 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
,07-05 14:04:58.357  4149  4193 W MusicSyncAdapter: Sync failed due to an authentication issue.
,07-05 14:04:58.364   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 24003, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:58.364   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 162965, reason: Periodic
,07-05 14:04:58.365  4149  4149 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:04:58.369  4149  4149 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:04:58.370  4149  4149 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@b48c21a and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:04:58.382  3864  4137 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:04:58.411  3864  4137 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:58.413  3864  4137 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,07-05 14:04:58.420   874   886 I ActivityManager: Start proc 4211:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,07-05 14:04:58.426  4149  4149 D MusicLifecycle: com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
,07-05 14:04:58.426  4149  4149 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
07-05 14:04:58.429  4149  4208 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
07-05 14:04:58.429  4149  4208 I MusicLeanback: Stop autocaching.
,07-05 14:04:58.433  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:04:58.437  4211  4211 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-05 14:04:58.441  4149  4149 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,07-05 14:04:58.441  4149  4149 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
,07-05 14:04:58.444  4149  4149 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:58.445  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:04:58.529  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,07-05 14:04:58.530  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud.
07-05 14:04:58.530  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:58.530  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: Exception in onPerformLoggedSync 
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:153)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:90)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:859)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:419)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:352)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:469)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.Utils.executeAndLog(Utils.java:555)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2853)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:2301)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffsForAccount(CalendarSyncAdapterApiary.java:2182)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:623)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:473)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.android.emailcommon.syncadapter.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:49)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.zzb(Unknown Source)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:141)
07-05 14:04:58.547  3864  4137 E CalendarSyncAdapter: 	... 13 more
,07-05 14:04:58.551   874   885 I ActivityManager: Killing 3550:com.google.android.youtube/u0a86 (adj 15): empty #17
,07-05 14:04:58.625   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 24003, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:58.630   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 162342, reason: Periodic
,07-05 14:04:58.640   874  1406 I ActivityManager: Start proc 4226:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,07-05 14:04:58.652  4149  4149 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@b48c21a and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,07-05 14:04:58.667  4149  4149 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,07-05 14:04:58.671  4149  4149 D MusicLifecycle: com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,07-05 14:04:58.722   874   886 I ActivityManager: Start proc 4239:com.android.chrome/u0a40 for service com.android.chrome/org.chromium.chrome.browser.sync.ChromeBrowserSyncAdapterService
,07-05 14:04:58.755  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:04:58.756  4226  4226 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,07-05 14:04:58.763  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@b48c21a and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:04:58.780   874   885 I ActivityManager: Killing 3712:com.google.android.apps.books/u0a34 (adj 15): empty #17
,07-05 14:04:58.836  4149  4149 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:04:58.843  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:04:58.845  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:04:58.858  4211  4256 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,07-05 14:04:58.860  4149  4149 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:04:58.865  4149  4149 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
07-05 14:04:58.865  4149  4255 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:04:58.867  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:04:58.873  4239  4258 D DelayedSyncController: Delaying sync.
,07-05 14:04:58.882   874   885 I ActivityManager: Killing 3164:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,07-05 14:04:58.956  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:04:58.985   874   885 I ActivityManager: Killing 3644:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,07-05 14:04:59.044   874  1725 I ActivityManager: Killing 3918:com.google.android.deskclock/u0a44 (adj 15): empty #17
,07-05 14:04:59.114  1812  2167 I Icing   : Indexing A8D686BAA20C0E71D7317F57EDDF0E6696D89DD3 from com.google.android.gm
,07-05 14:04:59.141  1812  4264 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:59.166  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:59.171  1812  4263 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-05 14:04:59.186  1812  2167 I Icing   : Indexing done A8D686BAA20C0E71D7317F57EDDF0E6696D89DD3
,07-05 14:04:59.199  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: mail
,07-05 14:04:59.199  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:04:59.199  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:59.199  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:59.212  1512  1525 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:59.212  1512  1525 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:59.212  1512  1525 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:59.212  1512  1525 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:04:59.212  1512  1525 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:59.212  1512  1525 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:59.212  1512  1525 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:59.214  1812  4264 W SubscribedFeeds: Hard error
,07-05 14:04:59.222   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 24003, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:59.222   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 161607, reason: Periodic
,07-05 14:04:59.230  1812  1812 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,07-05 14:04:59.272  1812  4270 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=233:priority=5:group=main]
,07-05 14:04:59.276  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:59.277  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:59.277  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:59.277  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:59.292  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:59.292  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:59.292  1512  4064 E Uploader: 	,at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:59.292  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:59.295  1866  4269 I GCoreUlr: Uploading GCM registration ID for account#2#
,07-05 14:04:59.321  1866  4269 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:59.322  1812  4274 I PeopleSync: onPerformSync() [5005f081]
,07-05 14:04:59.332  1866  4269 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,07-05 14:04:59.341  1866  4269 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,07-05 14:04:59.394  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,07-05 14:04:59.394  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud.
07-05 14:04:59.394  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:59.394  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:59.398  1812  4280 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,07-05 14:04:59.405  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:59.412  1866  4269 E GCoreUlr: 
07-05 14:04:59.412  1866  4269 E GCoreUlr: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.location.reporting.d.c.a(SourceFile:164)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.location.reporting.d.g.a(SourceFile:94)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.location.reporting.service.u.b(SourceFile:220)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.location.reporting.service.u.a(SourceFile:173)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.location.reporting.service.t.a(SourceFile:151)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
07-05 14:04:59.412  1866  4269 E GCoreUlr: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,07-05 14:04:59.429   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 24003, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:59.431   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 163774, reason: Periodic
,07-05 14:04:59.436  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-05 14:04:59.436  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-05 14:04:59.436  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:59.436  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:59.452  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:59.452  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-05 14:04:59.452  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-05 14:04:59.502  1812  4274 I PeopleSync: Setting subscription: result=true [5005f081]
,07-05 14:04:59.510  1812  4274 I PeopleSync: Starting sync, feed=null [5005f081]
,07-05 14:04:59.549  1812  4274 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:59.554  1812  4274 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:59.554  1812  4274 W BaseAppContext: Using Auth Proxy for data requests.
,07-05 14:04:59.555  1812  4274 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,07-05 14:04:59.570   874   886 I ActivityManager: Start proc 4282:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,07-05 14:04:59.599  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,07-05 14:04:59.600  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud.
07-05 14:04:59.600  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:59.600  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:59.605  4282  4282 W System  : ClassLoader referenced unknown path: /system/app/EditorsDocs/lib/arm
,07-05 14:04:59.755  1812  4274 I PeopleSync: Sync finished, successful=false, took 57ms
,07-05 14:04:59.774  1812  4274 I PeopleSync: Cannot authenticate [5005f081]
07-05 14:04:59.774  1812  4274 I PeopleSync: com.google.android.gms.auth.ae: BadAuthentication
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.auth.p.b(SourceFile:480)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:397)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:342)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.people.service.g.b(SourceFile:171)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1190)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.people.sync.aa.g(SourceFile:1085)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.people.sync.aa.a(SourceFile:240)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:274)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:189)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:91)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
07-05 14:04:59.774  1812  4274 I PeopleSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,07-05 14:04:59.805  1812  4274 I PeopleSync: ***Sync finished***, duration: 482 [5005f081]
,07-05 14:04:59.830   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 31501, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:04:59.830   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 164518, reason: Periodic
,07-05 14:04:59.906  3851  3883 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:04:59.919   874  1319 D ConnectivityService: handlePromptUnvalidated 100
,07-05 14:04:59.949  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,07-05 14:04:59.952  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud.
07-05 14:04:59.952  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:04:59.952  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:04:59.964  1812  4295 E RemindersSync: AuthError [T SyncAdapterThread-2:id=237:priority=5:group=main]
,07-05 14:04:59.970   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 31572, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
07-05 14:04:59.971   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 164237, reason: Periodic
,07-05 14:04:59.992   874   886 I ActivityManager: Start proc 4303:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,07-05 14:05:00.008   874  1385 I ActivityManager: Killing 2907:com.google.android.keep/u0a79 (adj 15): empty #17
,07-05 14:05:00.080  3864  3909 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:05:00.085  4303  4303 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,07-05 14:05:00.216  4282  4298 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:05:00.216  4282  4298 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:05:00.216  4282  4298 I GAv4    :   adb logcat -s GAv4
,07-05 14:05:00.240  4282  4298 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:00.250  4282  4298 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:00.282  4282  4329 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:00.283  4282  4298 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.322.09.36
,07-05 14:05:00.305  4303  4317 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:05:00.305  4303  4317 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:05:00.305  4303  4317 I GAv4    :   adb logcat -s GAv4
,07-05 14:05:00.327  4303  4317 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:00.331  4303  4317 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,07-05 14:05:00.343  4303  4317 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.327.05.36
,07-05 14:05:00.354  4303  4342 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:00.455   874  1753 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@43478b8}
,07-05 14:05:00.474   874  1385 I ActivityManager: Killing 3987:com.qualcomm.timeservice/1000 (adj 15): empty #17
,07-05 14:05:00.522  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:00.533  3932  3985 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:05:00.562  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:00.684   874   886 I ActivityManager: Start proc 4366:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,07-05 14:05:00.694  4303  4357 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:05:00.697  4282  4337 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:05:00.792  4303  4357 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:00.794  4282  4337 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:00.843  4282  4337 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:00.844  4303  4357 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:01.070   874  1385 I ActivityManager: Killing 4047:com.google.android.configupdater/u0a42 (adj 15): empty #17
,07-05 14:05:01.102  4303  4357 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
,07-05 14:05:01.103  4303  4357 E BaseSyncManager: ClientFlagSyncException
07-05 14:05:01.103  4303  4357 E BaseSyncManager: cfk$a: IO Exception opening: https://ssl.gstatic.com/docs/android/drive/client_flags?1467720300602= stream was reset: CANCEL
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cfk.a(PG:1108)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at dpe.a(PG:18060)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at dph.run(PG:9612)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at dpf.run(PG:3031)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: Caused by: java.io.IOException: stream was reset: CANCEL
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hun.b(PG:145)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at htk.b(PG:104)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hsx.d(PG:917)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hsx.a(PG:95)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hsx$a.a(PG:902)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hrj.a(PG:50089)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hrj$a.a(PG:230)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at hrj.a(PG:3201)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cpx.a(PG:156)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnk.a(PG:47)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnj.a(PG:22)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnl.a(PG:69)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnp.b(PG:96)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnp.a(PG:84)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnn.b(PG:5140)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cnn.a(PG:1096)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	at cfk.a(PG:2062)
07-05 14:05:01.103  4303  4357 E BaseSyncManager: 	... 3 more
,07-05 14:05:01.231   874  1725 I ActivityManager: Killing 2367:com.google.android.talk/u0a61 (adj 15): empty #17
,07-05 14:05:01.328  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:01.352  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
,07-05 14:05:01.352  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud.
07-05 14:05:01.352  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:05:01.352  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:01.366  1512  1524 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:05:01.366  1512  1524 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:05:01.366  1512  1524 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:05:01.366  1512  1524 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:05:01.366  1512  1524 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:05:01.366  1512  1524 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:05:01.366  1512  1524 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:01.368  4303  4357 E DefaultHttpIssuer: Attempt to consume entity of HttpIssuer when no request is executing.
07-05 14:05:01.368  4303  4357 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
,07-05 14:05:01.370  4303  4357 E BaseSyncManager: AuthenticatorException
07-05 14:05:01.370  4303  4357 E BaseSyncManager: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:05:01.370  4303  4357 E BaseSyncManager: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:05:01.370  4303  4357 E BaseSyncManager: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:05:01.370  4303  4357 E BaseSyncManager: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:05:01.370  4303  4357 E BaseSyncManager: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:05:01.370  4303  4357 E BaseSyncManager: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:01.373   874  1750 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@43478b8}
,07-05 14:05:01.385   874  1786 I ActivityManager: Killing 3410:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,07-05 14:05:01.806  4366  4382 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:05:01.806  4366  4382 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:05:01.806  4366  4382 I GAv4    :   adb logcat -s GAv4
,07-05 14:05:01.831  4366  4382 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:01.836  4366  4382 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:01.847  4366  4395 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:05:01.856  4366  4382 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,07-05 14:05:02.060  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:02.105   874  1747 I ActivityManager: Killing 3932:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,07-05 14:05:02.328  4366  4400 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:05:02.377  4366  4400 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:02.402  4366  4400 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:03.096  4149  4149 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@b48c21a and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,07-05 14:05:03.124  4149  4149 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,07-05 14:05:03.132  4149  4149 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,07-05 14:05:03.132  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@b48c21a and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,07-05 14:05:03.142  4149  4149 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,07-05 14:05:03.151  4149  4413 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,07-05 14:05:03.151  4149  4413 I MusicLeanback: Stop autocaching.
,07-05 14:05:03.157  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,07-05 14:05:03.169  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,07-05 14:05:03.170  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,07-05 14:05:03.180  4149  4149 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:05:03.180  4149  4149 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,07-05 14:05:03.181  4149  4149 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,07-05 14:05:03.189  4149  4416 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-05 14:05:03.192  4149  4149 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,07-05 14:05:03.213   874  1787 I ActivityManager: Killing 3946:com.google.process.gapps/u0a99 (adj 15): empty #17
,07-05 14:05:03.897   874  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,07-05 14:05:05.534  1812  4000 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VagErgJKWj8g7EVMMwyZnjlz8shLggUA0DZXkiqbh_xca3gbrG6AKGDwjX3486pcCLHddDbBf0u_R8xqwKPnO3lIR4DWDst0nzyBDzzich9UKoBTWYkBK9oEJ00Ck8un24bAMqdzZvtuu4h8GgDbQno7_6yz3R8BDjBmcXS-PPFAKlA1gJqF_Nnp8ShmGLz20vc4BIW_8HxwkoN-SngZ8FCHyYTEKmVez6Ff-zovWTBzoCGR8
,07-05 14:05:05.604  1812  4000 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:05:05.948  1812  4000 I ConfigFetchTask: updating config table for com.google.android.gms
,07-05 14:05:06.035  1812  1812 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,07-05 14:05:06.042  1812  1812 I ConfigFetchService: fetch service done; releasing wakelock
,07-05 14:05:06.043  1812  1812 I ConfigFetchService: stopping self
,07-05 14:05:06.045  1812  1812 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-05 14:05:06.046  1812  1812 I ConfigFetchService: GmsCore config value changed; rescheduling
,07-05 14:05:06.054   874  1787 I ActivityManager: Killing 4082:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-05 14:05:06.715   874   897 W PackageSettings: Skipping PackageSetting{e19e2aa com.example.hello/10273} due to missing metadata
,07-05 14:05:06.766   874  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:05:06.792   874  1750 I ActivityManager: Start proc 4421:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,07-05 14:05:06.830  4421  4421 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-05 14:05:06.860  1866  1866 V GmsNetworkLocationProvi: DISABLE
,07-05 14:05:06.866  1866  1866 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 14:05:07.053  4421  4439 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-05 14:05:07.054  4421  4439 I Babel_SMS: MmsConfig.loadMmsSettings
,07-05 14:05:07.058  4421  4439 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-05 14:05:07.058  4421  4439 I Babel_SMS: MmsConfig.loadFromDatabase
,07-05 14:05:07.080  4421  4439 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-05 14:05:07.080  4421  4439 I Babel_SMS: MmsConfig.loadFromResources
,07-05 14:05:07.085  4421  4439 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-05 14:05:07.089  4421  4439 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-05 14:05:07.122  4421  4421 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 14:05:07.124  4421  4421 I Babel_Crash: startup - clean
,07-05 14:05:07.143  4421  4421 I Babel_telephony: TeleModule.launchCompleted
,07-05 14:05:07.156   874  1733 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:05:07.167  4421  4421 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-05 14:05:07.177  4421  4421 W Babel   : BAM#gBA: invalid account id: -1
,07-05 14:05:07.177  4421  4421 W Babel   : BAM#gBA: invalid account id: -1
,07-05 14:05:07.177  4421  4421 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-05 14:05:07.182  4421  4444 I Babel   : deleted: false for 0
,07-05 14:05:07.191   874   884 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-05 14:05:07.255   874  1747 I ActivityManager: Start proc 4446:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,07-05 14:05:07.280  4421  4421 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:05:07.342  4446  4446 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,07-05 14:05:07.347  4421  4421 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-05 14:05:07.368  4421  4421 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:05:07.371  4421  4421 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:05:07.378  4421  4421 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:05:07.394  4421  4421 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-05 14:05:07.525  4421  4421 I vclib   : onServiceConnected
,07-05 14:05:07.596  4421  4421 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:05:07.618  4446  4446 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-05 14:05:07.756  4421  4421 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:07.764  4446  4446 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,07-05 14:05:07.789  4446  4446 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 14:05:07.790  4446  4446 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 14:05:07.806  4421  4421 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:07.868  4446  4484 D Ads     : Skipping gmscore version check
,07-05 14:05:07.873  1812  4485 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-05 14:05:07.878  4446  4446 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-05 14:05:07.879  4446  4446 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,07-05 14:05:07.882  1812  4485 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-05 14:05:07.898  4446  4484 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-05 14:05:07.904  4120  4487 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-05 14:05:07.930   874  1406 I ActivityManager: Start proc 4488:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,07-05 14:05:07.935  1812  2167 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-05 14:05:07.978  4446  4446 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-05 14:05:08.014  4446  4446 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-05 14:05:08.054  4120  4487 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
,07-05 14:05:08.313   874  1733 I ActivityManager: Killing 3819:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,07-05 14:05:11.058  1512  1512 I ConfigService: onDestroy
,07-05 14:05:11.904   874  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-05 14:05:11.930   874  1787 I ActivityManager: Killing 3896:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-05 14:05:12.790  4446  4446 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-05 14:05:12.847  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:12.859  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:12.863  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:12.912  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:05:12.912  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:05:12.912  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:12.912  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:12.951  4446  4446 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:05:12.970  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:13.016  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:05:13.016  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-05 14:05:13.017  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:05:13.017  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.076  4446  4513 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-05 14:05:13.078  4446  4446 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,07-05 14:05:13.079  4446  4446 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,07-05 14:05:13.142  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:13.174  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:05:13.174  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:05:13.174  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.174  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.210  4446  4446 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:05:13.300  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-05 14:05:13.300  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:05:13.301  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.301  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.344  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:05:13.346  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:05:13.346  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-05 14:05:13.410  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:13.474  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-05 14:05:13.475  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-05 14:05:13.475  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:13.475  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:13.509  4446  4446 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:05:13.513  4446  4446 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-05 14:05:13.518  4446  4446 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-05 14:05:13.533  4446  4446 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,07-05 14:05:13.538  4446  4515 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-05 14:05:13.545  4446  4446 D Finsky  : [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,07-05 14:05:13.554  4446  4446 D Finsky  : [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,07-05 14:05:13.660  4446  4516 D Finsky  : [418] VerifyInstalledPackagesTask.doInBackground$4f3371dc: Adding com.google.earth for verification
,07-05 14:05:13.672  4446  4513 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-05 14:05:14.000  4446  4468 I qtaguid : Failed write_ctrl(u 31) res=-1 errno=22
07-05 14:05:14.000  4446  4468 I qtaguid : Untagging socket 31 failed errno=-22
07-05 14:05:14.000  4446  4468 W NetworkManagementSocketTagger: untagSocket(31) failed with errno -22
,07-05 14:05:14.021   874   884 I ActivityManager: Killing 3864:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-05 14:05:18.350   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:05:18.360  1671  1671 I Keyboard.Facilitator: onFinishInput()
,07-05 14:05:18.368   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-05 14:05:18.368   874   894 I Adreno  : Build Date                       : 10/20/15
07-05 14:05:18.368   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-05 14:05:18.368   874   894 I Adreno  : Local Branch                     : M14
07-05 14:05:18.368   874   894 I Adreno  : Remote Branch                    : 
07-05 14:05:18.368   874   894 I Adreno  : Remote Branch                    : 
07-05 14:05:18.368   874   894 I Adreno  : Reconstruct Branch               : 
,07-05 14:05:18.401   280  1309 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (170 us)
,07-05 14:05:19.043  3358  3358 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:05:19.044  3358  3358 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:05:19.080   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 14:05:19.085  3358  3358 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ee4463d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4a2130a, 16908290=android.view.AbsSavedState$1@4a2130a}, android:focusedViewId=100}]}]
,07-05 14:05:19.086  3358  3358 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-05 14:05:19.086  3358  3358 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-05 14:05:19.086  3358  3358 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:05:19.086   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-05 14:05:19.090   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:05:19.091   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,07-05 14:05:19.091   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0,
,07-05 14:05:19.127   874   883 I art     : Background partial concurrent mark sweep GC freed 23136(1886KB) AllocSpace objects, 3(56KB) LOS objects, 33% free, 28MB/43MB, paused 959us total 107.671ms
,07-05 14:05:19.330   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 14:05:19.333   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
07-05 14:05:19.334   874  1343 D SurfaceControl: Excessive delay in setPowerMode(): 244ms
,07-05 14:05:19.338   874   894 I DreamManagerService: Entering dreamland.
,07-05 14:05:19.341   874   894 I PowerManagerService: Dozing...
07-05 14:05:19.342   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-05 14:05:19.383   375  1648 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:05:19.383   375  1648 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,07-05 14:05:19.392  1719  4521 D NfcService: Discovery configuration equal, not updating.
,07-05 14:05:19.393   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:05:19.406   874  1317 E native  : do suspend false
,07-05 14:05:19.423   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,07-05 14:05:19.436   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,07-05 14:05:19.439   874  1317 E native  : do suspend true
,07-05 14:05:19.524   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-05 14:05:19.525   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,07-05 14:05:23.507  1866  2325 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:05:31.908   874  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 4, 6 -> obsolete
,07-05 14:05:32.284   874   886 I ActivityManager: Start proc 4528:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,07-05 14:05:32.385  4528  4528 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,07-05 14:05:32.474  4528  4528 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-05 14:05:32.489  4528  4528 I BooksApp: Created application version: 3.6.9 (30609)
,07-05 14:05:32.595  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:32.598  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:32.624  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:05:32.624  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:05:32.624  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:32.624  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:32.643  4488  4541 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:05:32.643  4488  4541 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at czp.a(PG:9087)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:05:32.643  4488  4541 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	... 12 more
07-05 14:05:32.643  4488  4541 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at fal.a(PG:38)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:05:32.643  4488  4541 E HttpOperation: 	... 14 more
,07-05 14:05:32.669  4528  4548 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:05:32.966  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:05:32.967  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:05:32.967  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:32.967  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:32.991  4528  4558 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 14:05:32.996  4488  4554 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:05:32.996  4488  4554 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:05:32.996  4488  4554 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	,at jdj.a(PG:1125)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	... 12 more
07-05 14:05:32.996  4488  4554 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at fal.a(PG:38)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:05:32.996  4488  4554 E HttpOperation: 	... 14 more
,07-05 14:05:33.113  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-05 14:05:33.113  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:05:33.113  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:33.113  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:33.120  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 14:05:33.120  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:05:33.120  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:33.120  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:33.176  4488  4554 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:05:33.176  4488  4554 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at hec.a(PG:42)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at hee.a(PG:102)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at czr.a(PG:65)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at kka.a(PG:108)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at czp.a(PG:19176)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:05:33.176  4488  4554 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	... 15 more
07-05 14:05:33.176  4488  4554 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at fal.a(PG:38)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:05:33.176  4488  4554 E HttpOperation: 	... 17 more
07-05 14:05:33.176  4488  4554 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:05:33.176  4488  4554 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	... 15 more
07-05 14:05:33.176  4488  4554 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:05:33.176  4488  4554 E ExperimentLoader: 	... 17 more
,07-05 14:05:33.211  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:05:33.211  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:05:33.211  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:33.212  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:33.236  4528  4558 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:05:33.238  4528  4548 E BooksSync: Soft error
07-05 14:05:33.238  4528  4548 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:05:33.238  4528  4548 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:05:33.238  4528  4548 E BooksSync: Sync error
07-05 14:05:33.238  4528  4548 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:05:33.238  4528  4548 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:05:33.239  4528  4548 I BooksSync: Finished books sync
,07-05 14:05:33.288   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157406, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:05:33.338   874   886 I ActivityManager: Start proc 4559:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,07-05 14:05:33.343   874  1725 I ActivityManager: Killing 4226:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,07-05 14:05:33.344   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 124931, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:05:33.422  3851  4571 W Gmail   : Sync started for account: account:61035162
,07-05 14:05:33.424  3851  4571 I Gmail   : notifyAccountChanged
,07-05 14:05:33.426  3851  3878 I Gmail   : getAccountsCursor
,07-05 14:05:33.429  4559  4559 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,07-05 14:05:33.433  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:33.451  3851  4571 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,07-05 14:05:33.483  3851  4571 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:05:33.524  3851  4571 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:33.614  3851  4571 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:33.627  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:33.677  4559  4576 V KeepSync: Connecting to GoogleApiClient
,07-05 14:05:33.678   874  1406 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 14:05:33.739  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
,07-05 14:05:33.740  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:05:33.741  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:33.741  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:33.778  1512  2698 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:05:33.778  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:05:33.778  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:05:33.778  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:05:33.778  1512  2698 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:05:33.778  1512  2698 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:05:33.778  1512  2698 W GLSActivity: ,	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:33.804  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:33.838  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:05:33.838  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:05:33.838  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:33.839  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:33.862  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
,07-05 14:05:33.862  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
07-05 14:05:33.862  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:33.862  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:33.867  1812  4581 V BaseAuthAsyncOperation: access token request failed
07-05 14:05:33.868  4559  4576 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:05:33.897  1512  2698 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:05:33.897  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:05:33.897  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:05:33.897  1512  2698 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:05:33.897  1512  2698 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:05:33.897  1512  2698 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:05:33.897  1512  2698 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:33.934  3851  4571 I Gmail   : notifyAccountChanged
,07-05 14:05:33.937  3851  3889 I Gmail   : getAccountsCursor
,07-05 14:05:33.947  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:33.996  3851  4571 I Gmail   : notifyAccountChanged
,07-05 14:05:34.002  3851  3879 I Gmail   : getAccountsCursor
,07-05 14:05:34.003  3851  4571 W Gmail   : Sync complete for account: account:61035162
,07-05 14:05:34.020  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:34.029   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 159343, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,07-05 14:05:34.031   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 226408, reason: Periodic
,07-05 14:05:34.052  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:05:34.052  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:05:34.052  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:34.052  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:34.092  4559  4576 E KeepSync: IOException
07-05 14:05:34.092  4559  4576 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:05:34.092  4559  4576 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:05:34.092  4559  4576 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:05:34.092  4559  4576 E KeepSync: 	... 10 more
,07-05 14:05:34.093  4559  4576 W KeepSync: Sync result 2
,07-05 14:05:34.125   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 158085, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:05:34.409   874  1711 I ActivityManager: Killing 4211:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,07-05 14:05:36.176  1812  4420 I ConfigFetchService: self-hosted config:fetch_interval = 43200
,07-05 14:05:36.224  1812  4420 I ConfigFetchService: stopping self
,07-05 14:05:36.269   874  1753 I ActivityManager: Start proc 4584:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,07-05 14:05:36.314   874  1752 I ActivityManager: Start proc 4596:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-05 14:05:36.337  4584  4584 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-05 14:05:36.388  4584  4584 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-05 14:05:36.399  4596  4596 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-05 14:05:36.454  4584  4619 V GoogleAuthProtoRequest: [417] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:05:36.522  4596  4620 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-05 14:05:36.608  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:05:36.608  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:05:36.608  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:05:36.608  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:36.682  4596  4620 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:05:36.709  4584  4619 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:05:36.786  4596  4620 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:05:36.863  4596  4596 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-05 14:05:36.986  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:37.038  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:05:37.038  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-05 14:05:37.039  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:37.039  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:37.097  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:05:37.097  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:05:37.097  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-05 14:05:37.140  4596  4596 W InstanceID/Rpc: Found 10011
,07-05 14:05:37.227   874  1752 I ActivityManager: Killing 4239:com.android.chrome/u0a40 (adj 15): empty #17
,07-05 14:05:37.279  4648  4648 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1263290443.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1263290443.dex
,07-05 14:05:37.313   874  1752 I ActivityManager: Killing 3745:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,07-05 14:05:37.406  4648  4648 I dex2oat : dex2oat took 127.724ms (threads: 4) arena alloc=241KB java alloc=29KB native alloc=1513KB free=1558KB
,07-05 14:05:37.476  4528  4546 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-05 14:05:38.479  4559  4566 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@944b5b)
,07-05 14:05:42.586  4446  4457 D Finsky  : [389] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-05 14:05:42.609  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:42.625  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:42.630  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:42.695  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:05:42.696  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-05 14:05:42.696  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:05:42.697  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:42.758  4446  4457 D Finsky  : [389] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-05 14:05:57.429  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:57.441  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:57.445  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:57.490  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:05:57.490  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:05:57.491  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:05:57.491  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:05:57.542  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:05:57.542  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:05:57.543  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-05 14:06:06.447  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:06.450  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:06.486  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:06:06.486  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:06:06.486  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:06.487  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:06.504  4488  4698 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:06:06.504  4488  4698 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:06:06.504  4488  4698 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	... 12 more
07-05 14:06:06.504  4488  4698 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at fal.a(PG:38)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:06:06.504  4488  4698 E HttpOperation: 	... 14 more
,07-05 14:06:06.554  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:06:06.554  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:06:06.554  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:06.554  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:06.578  4488  4698 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:06:06.578  4488  4698 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at hec.a(PG:42)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at hee.a(PG:102)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at czr.a(PG:65)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at kka.a(PG:108)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at czp.a(PG:19176)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at czq.run(PG:1686),
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:06:06.578  4488  4698 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	... 15 more
07-05 14:06:06.578  4488  4698 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at fal.a(PG:38)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:06:06.578  4488  4698 E HttpOperation: 	... 17 more
,07-05 14:06:06.578  4488  4698 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:06:06.578  4488  4698 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	... 15 more
07-05 14:06:06.578  4488  4698 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:06:06.578  4488  4698 E ExperimentLoader: 	... 17 more
,07-05 14:06:06.800   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 197891, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:06:17.858  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:17.871  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:17.876  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:17.927  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:06:17.928  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:06:17.928  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:17.928  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:17.956  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:06:17.957  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:06:17.957  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-05 14:06:18.374  1671  4147 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-05 14:06:18.374  1671  4147 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-05 14:06:18.430  1512  1512 I ConfigService: onCreate
,07-05 14:06:23.515  1512  1512 I ConfigService: onDestroy,
,07-05 14:06:36.811  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:36.813  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:36.826  4584  4703 V GoogleAuthProtoRequest: [418] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:06:36.852  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:06:36.852  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:06:36.853  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:06:36.853  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:36.874  4528  4704 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: [418] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: [418] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:06:36.876  4584  4703 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:06:36.902  4528  4705 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 14:06:36.931  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-05 14:06:36.931  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:06:36.931  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:36.931  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:36.961  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:06:36.961  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:06:36.961  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:06:36.961  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:06:36.991  4528  4705 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:36.992  4528  4704 E BooksSync: Soft error
07-05 14:06:36.992  4528  4704 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:36.992  4528  4704 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:06:36.992  4528  4704 E BooksSync: Sync error
07-05 14:06:36.992  4528  4704 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:36.992  4528  4704 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:06:36.992  4528  4704 I BooksSync: Finished books sync
,07-05 14:06:37.003   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 227353, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:06:44.961   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=236744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:06:59.493  1512  2027 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:07:07.135  4559  4708 V KeepSync: Connecting to GoogleApiClient
,07-05 14:07:07.135   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 14:07:07.177  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:07:07.179  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:07:07.200  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:07:07.200  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-05 14:07:07.200  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:07:07.200  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:07:07.217  1812  4709 V BaseAuthAsyncOperation: access token request failed
,07-05 14:07:07.218  4559  4708 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:07:07.271  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:07:07.272  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-05 14:07:07.272  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:07:07.272  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:07:07.289  4559  4708 E KeepSync: IOException
07-05 14:07:07.289  4559  4708 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:07:07.289  4559  4708 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:07:07.289  4559  4708 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:07:07.289  4559  4708 E KeepSync: 	... 10 more
,07-05 14:07:07.289  4559  4708 W KeepSync: Sync result 2
,07-05 14:07:07.296   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 228877, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:07:37.624  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:07:37.626  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:07:37.654  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:07:37.654  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:07:37.654  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:07:37.654  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:07:37.669  4488  4716 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:07:37.669  4488  4716 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:07:37.669  4488  4716 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	... 12 more
07-05 14:07:37.669  4488  4716 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at fal.a(PG:38)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:07:37.669  4488  4716 E HttpOperation: 	... 14 more
,07-05 14:07:37.726  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:07:37.726  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:07:37.726  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:07:37.726  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:07:37.741  4488  4716 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:07:37.741  4488  4716 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at hec.a(PG:42)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at hee.a(PG:102)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at czr.a(PG:65)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at kka.a(PG:108)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	,at czp.a(PG:19176)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:07:37.741  4488  4716 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	... 15 more
07-05 14:07:37.741  4488  4716 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at fal.a(PG:38)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:07:37.741  4488  4716 E HttpOperation: 	... 17 more
07-05 14:07:37.741  4488  4716 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:07:37.741  4488  4716 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: ,	at jcn.a(PG:1379)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	... 15 more
07-05 14:07:37.741  4488  4716 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:07:37.741  4488  4716 E ExperimentLoader: 	... 17 more
,07-05 14:07:37.924   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 264111, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:08:37.084  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:37.086  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:37.100  4584  4720 V GoogleAuthProtoRequest: [419] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:08:37.130  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:08:37.130  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:08:37.130  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:37.130  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: [419] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: [419] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:08:37.152  4584  4720 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:08:41.654  4528  4721 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:08:41.684  4528  4722 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 14:08:41.722  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:08:41.722  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:08:41.722  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:08:41.722  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:41.782  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:08:41.782  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:08:41.782  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:08:41.782  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:08:41.805  4528  4722 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:08:41.807  4528  4721 E BooksSync: Soft error
07-05 14:08:41.807  4528  4721 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:08:41.807  4528  4721 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:08:41.808  4528  4721 E BooksSync: Sync error
07-05 14:08:41.808  4528  4721 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:08:41.808  4528  4721 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:08:41.808  4528  4721 I BooksSync: Finished books sync
,07-05 14:08:41.816   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 353351, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:08:57.268   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=369051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:09:13.406  4559  4725 V KeepSync: Connecting to GoogleApiClient
,07-05 14:09:13.407   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 14:09:13.457  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:13.458  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:13.486  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:09:13.486  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-05 14:09:13.486  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:09:13.486  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:09:13.502  1812  4726 V BaseAuthAsyncOperation: access token request failed
,07-05 14:09:13.503  4559  4725 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:09:13.549  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:09:13.549  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 14:09:13.549  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:09:13.549  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:09:13.567  4559  4725 E KeepSync: IOException
07-05 14:09:13.567  4559  4725 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,07-05 14:09:13.567  4559  4725 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:09:13.567  4559  4725 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:09:13.567  4559  4725 E KeepSync: 	... 10 more
07-05 14:09:13.567  4559  4725 W KeepSync: Sync result 2
,07-05 14:09:13.581   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 385016, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:09:40.001   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:09:49.357  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:49.363  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:09:49.392  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:09:49.392  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-05 14:09:49.392  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:09:49.392  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-05 14:09:49.412  4488  4729 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:09:49.412  4488  4729 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:09:49.412  4488  4729 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	... 12 more
07-05 14:09:49.412  4488  4729 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at fal.a(PG:38)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:09:49.412  4488  4729 E HttpOperation: 	... 14 more
,07-05 14:09:49.463  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:09:49.464  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:09:49.464  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:09:49.464  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:09:49.489  4488  4729 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:09:49.489  4488  4729 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at hec.a(PG:42)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at hee.a(PG:102)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at czr.a(PG:65)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at kka.a(PG:108)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at czp.a(PG:19176)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:09:49.489  4488  4729 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	... 15 more
07-05 14:09:49.489  4488  4729 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at fal.a(PG:38)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:09:49.489  4488  4729 E HttpOperation: 	... 17 more
,07-05 14:09:49.489  4488  4729 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:09:49.489  4488  4729 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	... 15 more
07-05 14:09:49.489  4488  4729 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:09:49.489  4488  4729 E ExperimentLoader: 	... 17 more
,07-05 14:09:49.602   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 420764, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:09:57.068   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=428850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:10:07.922  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:10:07.932  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:10:07.934  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:10:07.977  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:10:07.977  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:10:07.977  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:10:07.978  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:10:08.019  1512  1918 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-05 14:10:08.019  1512  1918 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-05 14:10:08.019  1512  1918 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-05 14:10:08.019  1512  1918 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-05 14:10:08.019  1512  1918 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:10:08.019  1512  1918 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:10:08.019  1512  1918 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:10:08.032  4446  4479 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:10:08.032  4446  4479 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:10:08.032  4446  4479 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-05 14:10:08.032  4446  4479 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-05 14:10:08.032  4446  4479 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-05 14:10:08.032  4446  4479 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:10:08.032  4446  4479 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:11:22.901   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514684, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:12:37.360  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:37.361  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:37.373  4584  4758 V GoogleAuthProtoRequest: [420] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:12:37.399  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-05 14:12:37.399  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-05 14:12:37.399  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:12:37.400  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: [420] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: [420] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:12:37.418  4584  4758 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:12:50.986  4528  4760 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:12:51.019  4528  4761 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 14:12:51.030  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:51.034  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:51.068  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:12:51.069  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-05 14:12:51.069  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:12:51.069  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:12:51.100  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:51.105  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:12:51.141  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:12:51.141  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-05 14:12:51.141  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:12:51.141  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:12:51.168  4528  4761 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:12:51.169  4528  4760 E BooksSync: Soft error
07-05 14:12:51.169  4528  4760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:12:51.169  4528  4760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:12:51.172  4528  4760 E BooksSync: Sync error
07-05 14:12:51.172  4528  4760 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:12:51.172  4528  4760 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:12:51.173  4528  4760 I BooksSync: Finished books sync
,07-05 14:12:51.187   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 602728, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:13:25.600  4559  4770 V KeepSync: Connecting to GoogleApiClient
07-05 14:13:25.601   874  1406 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 14:13:25.664  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:13:25.666  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:13:25.706  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-05 14:13:25.706  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-05 14:13:25.706  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:13:25.706  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:13:25.731  1812  4771 V BaseAuthAsyncOperation: access token request failed
,07-05 14:13:25.732  4559  4770 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:13:25.802  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-05 14:13:25.802  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 14:13:25.803  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:13:25.803  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:13:25.827  4559  4770 E KeepSync: IOException
07-05 14:13:25.827  4559  4770 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:13:25.827  4559  4770 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:13:25.827  4559  4770 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:13:25.827  4559  4770 E KeepSync: 	... 10 more
,07-05 14:13:25.827  4559  4770 W KeepSync: Sync result 2
,07-05 14:13:25.838   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 637237, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:14:12.072  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:14:12.078  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:14:12.142  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:14:12.142  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:14:12.143  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:14:12.143  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:14:12.171  4488  4774 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:14:12.171  4488  4774 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:14:12.171  4488  4774 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	... 12 more
07-05 14:14:12.171  4488  4774 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at fal.a(PG:38)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:14:12.171  4488  4774 E HttpOperation: 	... 14 more
,07-05 14:14:12.253  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:14:12.253  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:14:12.253  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:14:12.254  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-05 14:14:12.286  4488  4774 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:14:12.286  4488  4774 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at hec.a(PG:42)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at hee.a(PG:102)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at czr.a(PG:65)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at kka.a(PG:108)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at czp.a(PG:19176)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588),
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:14:12.286  4488  4774 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	... 15 more
07-05 14:14:12.286  4488  4774 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at fal.a(PG:38)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:14:12.286  4488  4774 E HttpOperation: 	... 17 more
,07-05 14:14:12.286  4488  4774 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:14:12.286  4488  4774 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	... 15 more
07-05 14:14:12.286  4488  4774 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:14:12.286  4488  4774 E ExperimentLoader: 	... 17 more
,07-05 14:14:12.380   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 683498, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:14:13.374   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=685157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:14:56.054   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=727837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:15:05.387   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=737170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-05 14:15:44.801   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=776583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:19:05.841   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:19:20.854   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=992637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:19:50.129   874  1786 I ActivityManager: Start proc 4802:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-05 14:19:50.200  4802  4802 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-05 14:19:50.225  4802  4802 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-05 14:19:50.225  4802  4802 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 14:19:50.225  4802  4802 I GAv4    :   adb logcat -s GAv4
,07-05 14:19:50.235  4802  4802 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:19:50.238  4802  4802 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:19:50.247  4802  4817 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-05 14:19:50.340   874  1406 I ActivityManager: Killing 4282:com.google.android.apps.docs.editors.docs/u0a47 (adj 15): empty #17
,07-05 14:19:55.401   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1027184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:20:10.400   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1042183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:20:27.467   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:20:37.431  4446  4446 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-05 14:20:37.442  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:37.475  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:20:37.477  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:37.509  1812  4821 I EventLogService: Opted in for usage reporting
,07-05 14:20:37.511  1812  4821 I EventLogService: Aggregate from 1467720292533 (log), 1467719189632 (data)
,07-05 14:20:37.524  1812  4821 W EventLogAggregator: Unknown tag: snet_gcore
,07-05 14:20:37.524  1812  4821 W EventLogAggregator: Unknown tag: snet_launch_service
,07-05 14:20:37.574  1812  4821 I ServiceDumpSys: dumping service [account]
,07-05 14:20:37.638  4584  4825 V GoogleAuthProtoRequest: [421] a.<init>: mAccountName set to: thalitester@gmail.com
,07-05 14:20:37.657  1812  1812 I GCM     : Message from null null
,07-05 14:20:37.657  1812  1812 E GCM     : Dropping message from null
,07-05 14:20:37.712  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-05 14:20:37.712  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-05 14:20:37.713  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:37.714  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:37.715  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-05 14:20:37.715  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-05 14:20:37.716  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:37.716  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:37.776  4584  4825 W ExperimentUpdateService: [421] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: [421] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-05 14:20:37.777  4584  4825 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-05 14:20:37.791  4446  4446 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:20:37.816  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:37.919  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:20:37.919  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:20:37.919  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:37.920  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:37.999  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:38.087  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:20:38.088  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:20:38.088  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:38.088  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:38.148  4446  4446 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:20:38.345  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:38.382  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-05 14:20:38.383  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-05 14:20:38.383  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:38.383  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:38.408  4446  4446 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:20:38.409  4446  4446 D Finsky  : [1] WearSupportService.startHygiene: disabled
07-05 14:20:38.409  4446  4446 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-05 14:20:38.412  4446  4446 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,07-05 14:20:38.414  4446  4515 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-05 14:20:52.534   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1084317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:20:53.439  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:53.456  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:53.461  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:20:53.534  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:20:53.534  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:20:53.535  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:20:53.536  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:20:53.588  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:20:53.589  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:20:53.589  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-05 14:20:59.574   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1091357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-05 14:21:09.557  4528  4829 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:21:09.589  4528  4830 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-05 14:21:09.606  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:09.611  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:09.652  1512  1918 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:21:09.652  1512  1918 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:21:09.652  1512  1918 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:21:09.653  1512  1918 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:09.693  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:09.700  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:09.739  1512  1946 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-05 14:21:09.739  1512  1946 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-05 14:21:09.739  1512  1946 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:09.739  1512  1946 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:09.787  4528  4830 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:21:09.791  4528  4829 E BooksSync: Soft error
07-05 14:21:09.791  4528  4829 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:21:09.791  4528  4829 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-05 14:21:09.791  4528  4829 E BooksSync: Sync error
07-05 14:21:09.791  4528  4829 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:21:09.791  4528  4829 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-05 14:21:09.791  4528  4829 I BooksSync: Finished books sync
,07-05 14:21:09.801   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1101227, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:21:13.930  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:13.937  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:13.939  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:13.979  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-05 14:21:13.979  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-05 14:21:13.979  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:13.979  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:14.018  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:21:14.018  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:21:14.018  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-05 14:21:14.827   874  3528 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1106610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-05 14:21:34.283  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:34.294  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:34.298  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:34.358  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:21:34.359  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:21:34.359  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:34.359  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:34.408  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:21:34.408  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:21:34.409  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-05 14:21:49.750  4559  4833 V KeepSync: Connecting to GoogleApiClient
07-05 14:21:49.750   874  1753 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-05 14:21:49.803  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:49.804  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:49.828  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-05 14:21:49.828  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-05 14:21:49.828  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:21:49.828  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:49.848  1812  4834 V BaseAuthAsyncOperation: access token request failed
,07-05 14:21:49.849  4559  4833 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-05 14:21:49.893  1512  3708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-05 14:21:49.893  1512  3708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-05 14:21:49.893  1512  3708 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:49.893  1512  3708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:49.907  4559  4833 E KeepSync: IOException
07-05 14:21:49.907  4559  4833 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-05 14:21:49.907  4559  4833 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-05 14:21:49.907  4559  4833 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-05 14:21:49.907  4559  4833 E KeepSync: 	... 10 more
,07-05 14:21:49.907  4559  4833 W KeepSync: Sync result 2
,07-05 14:21:49.918   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1141366, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:21:54.656  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:21:54.731  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:21:54.732  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:21:54.732  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:21:54.733  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:21:54.800  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:21:54.801  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:21:54.801  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-05 14:22:15.064  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:15.079  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:15.085  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:15.155  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-05 14:22:15.156  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:22:15.156  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:22:15.156  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:22:15.207  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:22:15.208  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:22:15.208  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-05 14:22:35.445  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:35.468  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:35.475  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:35.570  1512  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-05 14:22:35.571  1512  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-05 14:22:35.571  1512  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:22:35.572  1512  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:22:35.643  4446  4446 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:22:35.644  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:22:35.646  4446  4446 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-05 14:22:56.895  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:56.897  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:22:56.929  1512  2698 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:22:56.929  1512  2698 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:22:56.929  1512  2698 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 14:22:56.929  1512  2698 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:22:56.949  4488  4839 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-05 14:22:56.949  4488  4839 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at blb.a(PG:3937)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at czp.a(PG:18188)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:22:56.949  4488  4839 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	... 12 more
07-05 14:22:56.949  4488  4839 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at fal.a(PG:38)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:22:56.949  4488  4839 E HttpOperation: 	... 14 more
,07-05 14:22:57.014  1512  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-05 14:22:57.014  1512  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-05 14:22:57.014  1512  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 14:22:57.014  1512  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 14:22:57.093  4488  4839 E HttpOperation: [getmobileexperiments] Unexpected exception
07-05 14:22:57.093  4488  4839 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jdm.a(PG:82)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jcs.o(PG:406)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jcn.a(PG:1379)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jcs.i(PG:143)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at hec.a(PG:42)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at hee.a(PG:102)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at czr.a(PG:65)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at kka.a(PG:108)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at czp.a(PG:19176)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at czp.a(PG:9081)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at czq.run(PG:1686)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:22:57.093  4488  4839 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jdj.a(PG:4091)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jdj.a(PG:1125)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jdm.a(PG:77)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	... 15 more
07-05 14:22:57.093  4488  4839 E HttpOperation: Caused by: faj: BadAuthentication
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at fal.a(PG:38)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	at jdj.a(PG:4089)
07-05 14:22:57.093  4488  4839 E HttpOperation: 	... 17 more
,07-05 14:22:57.093  4488  4839 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-05 14:22:57.093  4488  4839 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jdm.a(PG:82)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jcs.o(PG:406)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jcn.a(PG:1379)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jcs.i(PG:143)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at hec.a(PG:42)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at hee.a(PG:102)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at czr.a(PG:65)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at kka.a(PG:108)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at czp.a(PG:19176)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at czp.a(PG:9081)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at czq.run(PG:1686)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jdj.a(PG:4091)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jdj.a(PG:1125)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jdm.a(PG:77)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	... 15 more
07-05 14:22:57.093  4488  4839 E ExperimentLoader: Caused by: faj: BadAuthentication
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at fal.a(PG:38)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	at jdj.a(PG:4089)
07-05 14:22:57.093  4488  4839 E ExperimentLoader: 	... 17 more
,07-05 14:22:57.269   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1208388, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:23:06.933   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms)
```
