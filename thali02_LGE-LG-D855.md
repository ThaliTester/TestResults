#### Test 846390993028cf2_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-09 14:52:51.107  1589  1589 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-09 14:52:51.108  1589  1589 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-09 14:52:51.124  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:52:51.124  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
--------- beginning of system
09-09 14:52:51.127  1031  1530 D WifiController: battery changed pluggedType: 2
09-09 14:52:51.130  1927  2097 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-09 14:52:51.130  1927  2097 D LEDHandler: Battery Level Remaining: 100%
09-09 14:52:51.130  1927  2097 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
09-09 14:52:51.131  3844  3964 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 14:52:51.132  1589  1589 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
09-09 14:52:51.132  1589  1589 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-09 14:52:51.134  1589  1589 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-09 14:52:51.140  6637  6637 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 14:52:51.416  6730  6730 D AndroidRuntime: 
09-09 14:52:51.416  6730  6730 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 14:52:51.420  6730  6730 D AndroidRuntime: CheckJNI is OFF
09-09 14:52:51.628  6730  6730 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 14:52:51.639  1031  2036 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 14:52:51.654  1927  1944 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-09 14:52:51.660  1031  2036 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-09 14:52:51.661  1031  2036 D ActivityManager: setTaskToReturnTo : TaskRecord{3abc94cc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 14:52:51.661  1031  2036 D ActivityManager: setTaskToReturnTo : TaskRecord{3abc94cc #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 14:52:51.663  1031  2036 D WindowStateEx: AppWindowTokenEx init.. 
09-09 14:52:51.664   337   346 E GBMv2   : DFP En is all cleared set to be enabled
09-09 14:52:51.692  1031  2036 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6745 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 14:52:51.695  6730  6730 D AndroidRuntime: Shutting down VM
09-09 14:52:51.752  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-09 14:52:51.752  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29f29840 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 14:52:51.753  1927  3948 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-09 14:52:51.753  1927  3948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{82e8379 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 14:52:51.808  6745  6745 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-09 14:52:51.911  6745  6745 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 14:52:51.918  6745  6745 I LibraryLoader: Loading: webviewchromium
09-09 14:52:51.921  6745  6745 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9172-9176)
09-09 14:52:51.921  6745  6745 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:52:51.936  6745  6745 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bbbc7ee}
,09-09 14:52:51.937  6745  6745 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:52:51.938  6745  6745 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 14:52:51.947  6745  6745 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 14:52:51.948  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:52:51.974  6745  6745 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-09 14:52:51.975  6745  6745 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-09 14:52:51.975  6745  6745 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-09 14:52:51.977   314  1364 V AudioPolicyService: registerClient() client 0xb102bee0, uid 10118
09-09 14:52:51.982  1031  1102 D BluetoothManagerService: Message: 20
09-09 14:52:51.982  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d6d2af6:true
09-09 14:52:51.991  6745  6745 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:52:51.991  6745  6745 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:52:51.991  6745  6745 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:52:51.991  6745  6745 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:52:51.991  6745  6745 I Adreno-EGL: Remote Branch: 
09-09 14:52:51.991  6745  6745 I Adreno-EGL: Local Patches: 
09-09 14:52:51.991  6745  6745 I Adreno-EGL: Reconstruct Branch: 
,09-09 14:52:52.103  6745  6790 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-09 14:52:52.108  6745  6745 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-09 14:52:52.127  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:52:52.132  6745  6745 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 14:52:52.136  6745  6745 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 14:52:52.139  6745  6745 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 14:52:52.139  6745  6745 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-09 14:52:52.154  6745  6745 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-09 14:52:52.161  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 14:52:52.161  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:52:52.208  6745  6806 D OpenGLRenderer: Render dirty regions requested: true
09-09 14:52:52.208  6745  6806 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 14:52:52.218  6745  6806 D OpenGLRenderer: Enabling debug mode 0
,09-09 14:52:52.237  6745  6745 D Atlas   : Validating map...
,09-09 14:52:52.242  1031  1769 D SplitWindow: check instance of lgWin Window{3a6a7d00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 14:52:52.252  1031  1098 W ActivityManager: Activity pause timeout for ActivityRecord{1969b315 u0 com.test.thalitest/.MainActivity t6}
,09-09 14:52:52.293  6745  6804 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:52:52.293  6745  6804 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:52:52.398  1031  1103 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +647ms (total +734ms)
09-09 14:52:52.399  6745  6745 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22244795 time:189654
09-09 14:52:52.400  1031  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1969b315 u0 com.test.thalitest/.MainActivity t6} time:189655
09-09 14:52:52.514  6745  6745 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 14:52:52.532  6745  6745 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-09 14:52:52.532  6745  6745 I chromium: 
,09-09 14:52:52.567  6745  6804 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-09 14:52:52.567  6745  6804 I chromium: 
,09-09 14:52:52.716  6745  6820 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435173888
,09-09 14:52:52.737  6745  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 14:52:52.737  6745  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 14:52:52.737  6745  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 14:52:52.737  6745  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 14:52:52.737  6745  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 14:52:52.737  6745  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab96849 added. We now have 1 listener(s)
09-09 14:52:52.743  1031  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:52:52.745  6745  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-09 14:52:52.747  6745  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:52:52.748  6745  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 14:52:52.749  6745  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 14:52:52.757  6745  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30557f7c added. We now have 1 listener(s)
09-09 14:52:52.757  6745  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:52:52.762  1031  1530 D WifiService: New client listening to asynchronous messages
,09-09 14:52:52.767  6745  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:52:52.768  6745  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 14:52:52.768  6745  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 14:52:52.768  6745  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 14:52:52.768  6745  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 14:52:52.771  6745  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:52:52.772  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:52:52.773  6745  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-09 14:52:52.784  6745  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:52:52.784  6745  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:52:52.784  6745  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 14:52:52.785  6745  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:52:52.787  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:52.789  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:52:52.792  6745  6820 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 14:52:52.832  6745  6745 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 14:52:53.537   337   348 E GBMv2   : DFP En is all cleared set to be enabled
09-09 14:52:53.538   337   348 E GBMv2   : Set value is all cleared set the max
09-09 14:52:53.538   337   348 I GBMv2   : DFP Enabled. Ignore VFP set
,09-09 14:52:54.001  6745  6823 W jxcore-log: Initializing JXcore engine
09-09 14:52:54.001  6745  6823 W jxcore-log: JXcore engine is ready
,09-09 14:52:54.054  6823  6823 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7452]" dev="sockfs" ino=7452 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-09 14:52:54.054  6823  6823 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-09 14:52:54.054  6823  6823 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10627]" dev="sockfs" ino=10627 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 14:52:54.054  6823  6823 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-09 14:52:54.054  6823  6823 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30165]" dev="sockfs" ino=30165 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-09 14:52:54.076  6745  6823 W jxcore-log: Starting JXcore engine
,09-09 14:52:54.172  6745  6823 W jxcore-log: Platform android
09-09 14:52:54.172  6745  6823 W jxcore-log: 
09-09 14:52:54.173  6745  6823 W jxcore-log: Process ARCH arm
09-09 14:52:54.173  6745  6823 W jxcore-log: 
,09-09 14:52:54.368  6745  6823 I jxcore-log: JXcore Cordova bridge is ready!
09-09 14:52:54.368  6745  6823 I jxcore-log: 
09-09 14:52:54.369  6745  6823 W jxcore-log: JXcore engine is started
,09-09 14:52:54.379  6745  6820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 14:52:54.381  6745  6745 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 14:53:00.055  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-09 14:53:00.055  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
09-09 14:53:00.055  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-09 14:53:00.055  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,09-09 14:53:00.060  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
09-09 14:53:00.060  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
09-09 14:53:00.061  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
09-09 14:53:00.062  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 14:53:13.007  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 14:53:13.007  6745  6823 I jxcore-log: 
09-09 14:53:13.010  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 14:53:13.010  6745  6823 I jxcore-log: 
,09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:13.017  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:13.020  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:13.024  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 14:53:13.024  6745  6823 I jxcore-log: 
,09-09 14:53:13.032  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 14:53:13.032  6745  6823 I jxcore-log: 
09-09 14:53:13.997  6745  6823 D executeNativeTests: Running unit tests
,09-09 14:53:14.133  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:14.133  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 added. We now have 2 listener(s)
,09-09 14:53:14.136  1031  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:14.139  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:14.139  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:14.139  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:14.139  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:14.139  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e added. We now have 2 listener(s)
09-09 14:53:14.139  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:14.140  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:53:14.144  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.147  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:53:14.152  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:53:14.153  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:53:14.154  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.156  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.160  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 14:53:14.163  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:53:14.163  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 14:53:14.168  6745  6823 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 14:53:14.169  6745  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:53:14.169  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:53:14.169  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:53:14.169  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:53:14.170  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.171  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.171  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.172  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.172  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.172  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.172  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:14.172  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 removed from the list
09-09 14:53:14.174  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.174  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e removed from the list
09-09 14:53:14.174  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.174  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.175  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.175  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:14.180  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.180  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.180  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.181  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.183  6745  6823 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 14:53:14.184  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.184  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.184  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.187  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.187  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.187  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.187  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.187  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.187  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.187  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.187  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.187  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.187  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.187  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:14.190  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.190  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.190  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.190  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.197  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:53:14.198  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:53:14.199  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:53:14.199  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.199  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.199  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.202  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.202  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.202  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.202  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.202  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.202  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.202  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.202  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:53:14.202  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.202  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.202  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:14.209  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.209  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.209  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.209  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.210  6745  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:53:14.213  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.217  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:53:14.220  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.220  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:53:14.222  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.223  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.224  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:14.224  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:53:14.224  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:53:14.224  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:14.224  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:53:14.230  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 14:53:14.232  1031  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:14.238  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:53:14.246  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:53:14.250  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 14:53:14.252  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:53:14.252  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.254  6745  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:53:14.254  6745  6823 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:53:14.258  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.258  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.258  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:53:14.261  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.261  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.261  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.261  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.261  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.261  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.261  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.261  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.262  6745  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:53:14.265  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.269  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:14.270  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.270  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:53:14.275  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.277  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.277  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:14.277  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:53:14.277  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:53:14.277  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:14.277  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:53:14.282  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 14:53:14.284  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.290  6745  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:53:14.290  6745  6823 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:53:14.295  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.295  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.295  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 14:53:14.298  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.299  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.299  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.299  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.299  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.299  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.299  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.299  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.301  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.301  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.303  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.303  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.307  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.307  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.307  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.307  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.308  6745  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 14:53:14.310  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.316  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:14.318  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.318  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:53:14.320  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.322  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:14.323  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 14:53:14.323  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:53:14.323  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:53:14.324  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:14.324  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 14:53:14.462  1031  1769 I art     : Explicit concurrent mark sweep GC freed 35660(1701KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.661ms total 137.289ms
,09-09 14:53:14.467  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:53:14.468  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.469  6745  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:53:14.469  6745  6823 I io.jxcore.node.ConnectionHelper: start: OK
09-09 14:53:14.469  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.469  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.469  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.470  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.470  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.470  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.471  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.471  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.471  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:14.471  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.471  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.471  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.471  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.471  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.473  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.474  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.476  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.477  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 14:53:14.483  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.483  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.483  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.483  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.485  6745  6823 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 14:53:14.486  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.486  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.486  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.486  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.486  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.486  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.486  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.486  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.486  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.487  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.487  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.487  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.487  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.487  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.489  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.489  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.489  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.489  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 14:53:14.489  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.489  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.490  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:53:14.490  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.490  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.490  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.491  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.491  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.491  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.491  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.491  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.491  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.491  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 14:53:14.491  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.491  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.491  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.491  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:14.492  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.492  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.492  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.492  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.492  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.493  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.493  6745  6823 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 14:53:14.493  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 14:53:14.493  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.493  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.494  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.494  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.494  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.494  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.494  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.494  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.494  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.494  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.494  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.494  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.494  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.499  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.499  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.500  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.500  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.500  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.500  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
,09-09 14:53:14.500  6745  6823 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 14:53:14.500  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.500  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.500  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.501  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.501  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.501  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.501  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.501  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.501  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.501  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.501  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:53:14.501  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.501  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.501  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.502  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.502  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.503  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.503  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.503  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.503  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.503  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-09 14:53:14.503  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:53:14.503  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:53:14.503  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:53:14.503  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 14:53:14.504  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 14:53:14.504  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.504  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.504  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.504  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.504  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.504  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:14.504  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.504  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.504  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.504  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.504  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.504  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.504  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.504  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.506  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.506  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.506  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.506  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.506  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.506  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.507  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:53:14.507  6745  6823 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:53:14.507  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 14:53:14.509  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:53:14.509  6745  6823 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: ,Peer: [<no peer name> 19:910:910:910:910:910]
09-09 14:53:14.509  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 14:53:14.510  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 14:53:14.510  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 14:53:14.510  6745  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:53:14.510  6745  6823 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 14:53:14.510  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:53:14.510  6745  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:53:14.510  6745  6823 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 14:53:14.511  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:53:14.511  6745  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 14:53:14.511  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 14:53:14.513  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 14:53:14.514  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 14:53:14.514  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 14:53:14.514  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 14:53:14.515  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 14:53:14.515  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 14:53:14.515  6745  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 14:53:14.515  6745  6823 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 14:53:14.515  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.515  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.515  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.516  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.516  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.516  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.516  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 14:53:14.516  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.516  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.516  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.516  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.516  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.516  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.516  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.516  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.517  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.517  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.518  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.518  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.518  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.518  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.521  6745  6841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
09-09 14:53:14.522  6745  6823 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 14:53:14.523  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.523  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.523  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.524  6745  6842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
09-09 14:53:14.526  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.526  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.526  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.526  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.526  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.526  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.526  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.526  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.526  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.526  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.526  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.527  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.527  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.528  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.528  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.528  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.528  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.529  6745  6823 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 14:53:14.529  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.529  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.529  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.535  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.535  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.535  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.535  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.535  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.535  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.535  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.535  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.535  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.535  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.535  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.536  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.536  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.536  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.536  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.536  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.536  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.537  6745  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 14:53:14.537  6745  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 14:53:14.537  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:53:14.538  6745  6823 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 14:53:14.538  6745  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:53:14.538  6745  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 14:53:14.538  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:53:14.538  6745  6823 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 14:53:14.538  6745  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 14:53:14.538  6745  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 14:53:14.538  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:53:14.538  6745  6823 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 14:53:14.538  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.538  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.538  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.539  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.539  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.539  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.540  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.540  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.540  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.540  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.540  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.540  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.540  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.540  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.541  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.541  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.542  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.542  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.542  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.542  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.542  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.542  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.542  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.542  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.542  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.542  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.542  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.542  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.542  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.544  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.545  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.545  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.545  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.545  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.545  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.545  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.545  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.545  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.546  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.546  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.546  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.546  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.546  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.546  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.546  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.546  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.546  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.546  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.546  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:14.547  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.547  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.548  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.548  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.548  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.548  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.550  6745  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 14:53:14.550  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:14.551  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 14:53:14.551  6745  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 14:53:14.552  6745  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 14:53:14.552  6745  6745 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 14:53:14.552  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 14:53:14.552  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 14:53:14.553  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.553  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 14:53:14.553  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 14:53:14.553  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 14:53:14.553  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.553  6745  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 14:53:14.553  6745  6745 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 14:53:14.553  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.553  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.553  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 14:53:14.553  6745  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 14:53:14.553  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 14:53:14.554  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 14:53:14.556  6745  6852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 14:53:14.556  6745  6852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 14:53:14.557  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:14.557  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:14.557  6745  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 14:53:14.557  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.557  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.565  6745  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:53:14.565  6745  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:53:14.565  6745  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 14:53:14.565  6745  6745 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 14:53:14.565  6745  6745 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 14:53:14.566  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.566  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.566  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.566  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.566  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.566  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.566  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.566  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.566  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.566  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.566  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.566  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.566  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.566  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.566  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.567  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.567  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.567  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.567  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.568  6745  6823 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 14:53:14.568  6745  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 14:53:14.568  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 14:53:14.569  6745  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 14:53:14.570  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.570  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.570  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.570  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.570  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.570  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.570  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.570  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.570  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.570  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.570  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.570  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.570  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.570  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.571  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.571  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.571  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.571  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.572  1031  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:14.572  1031  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:14.573  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:14.573  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.573  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.573  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.573  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.573  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.573  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.573  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.573  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.574  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.574  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.574  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.574  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.574  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.574  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.574  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.574  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.574  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.574  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.575  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:14.575  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:14.575  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:14.575  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:14.575  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.575  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.575  6745  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a4c1ad9 not in the list
09-09 14:53:14.575  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.575  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.575  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:14.575  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.575  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.575  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:14.576  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:14.577  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:14.577  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:14.577  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:14.577  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6bbc9e not in the list
09-09 14:53:14.579  6745  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 14:53:14.579  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:53:14.582  6745  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 14:53:14.582  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 14:53:14.582  6745  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 14:53:14.582  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 14:53:14.586  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 14:53:14.586  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 14:53:14.586  6745  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 14:53:14.587  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:53:14.587  6745  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 14:53:14.587  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 14:53:14.587  6745  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 14:53:14.587  6745  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 14:53:14.587  6745  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 14:53:14.587  6745  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 14:53:14.588  6745  6823 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 14:53:14.588  6745  6823 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 14:53:14.588  6745  6823 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 14:53:14.588  6745  6823 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 14:53:14.589  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:14.589  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c2c8377 added. We now have 2 listener(s)
09-09 14:53:14.590  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:14.592  6745  6823 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 14:53:14.595  1031  1962 D WifiServiceImplEx: setWifiEnabled: true pid=6745, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:53:14.595  1031  1962 D WifiService: setWifiEnabled: true pid=6745, uid=10118
09-09 14:53:14.595  1031  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:53:14.596  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:14.596  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@40c6be4 added. We now have 3 listener(s)
09-09 14:53:14.596  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:14.599  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:14.599  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1881984d added. We now have 4 listener(s)
09-09 14:53:14.599  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:14.601  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:14.601  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4237f02 added. We now have 5 listener(s)
09-09 14:53:14.601  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:14.602  1031  1962 D WifiServiceImplEx: setWifiEnabled: false pid=6745, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:53:14.603  1031  1962 D WifiService: setWifiEnabled: false pid=6745, uid=10118
09-09 14:53:14.603  1031  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:53:14.622  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:14.622  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:14.622  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:53:14.624  1031  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:53:14.624  1031  1723 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1417363 mBinding = false
09-09 14:53:14.624  1031  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:14.625  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:14.625  1031  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:14.626  1031  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:14.626  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:14.626  1031  1524 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 14:53:14.626  1031  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:53:14.627  1031  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:53:14.627  6745  6841 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-09 14:53:14.627  6745  6841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:14.627  1031  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:53:14.627  1031  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:53:14.627  3844  3863 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:14.627  3844  4038 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-09 14:53:14.629  3844  3863 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
09-09 14:53:14.638  1031  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:53:14.639  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.639  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.639  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-09 14:53:14.640  2645  2645 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:53:14.640  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:53:14.640  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:14.641  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:14.641  1031  2808 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.642   310   875 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:53:14.644  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:14.648  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:14.648  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-09 14:53:14.648  1031  1102 D BluetoothManagerService: Message: 2
09-09 14:53:14.648  1031  1102 D BluetoothManagerService: Sending off request.
09-09 14:53:14.649  3844  3863 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 14:53:14.649  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:53:14.649  3844  3936 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 14:53:14.649  3844  3936 D BluetoothAdapterProperties: Setting state to 13
09-09 14:53:14.649  3844  3936 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 14:53:14.650  3844  3936 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:53:14.650  3844  3936 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 14:53:14.651  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:14.651  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 14:53:14.651  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 14:53:14.653  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.653  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:14.653  3844  3940 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:53:14.654  3844  3936 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 14:53:14.654  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.654  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.654  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 14:53:14.654  3844  4228 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 14:53:14.655  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.656  3844  3936 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 14:53:14.656  6745  6841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
09-09 14:53:14.659  3844  4229 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:14.660  3844  4265 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:14.661  3844  4266 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:14.662  3844  4268 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:14.664  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 14:53:14.664  3844  4038 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 14:53:14.665  1031  1047 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-09 14:53:14.666  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.666  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.666  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 14:53:14.666  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.666  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 14:53:14.670  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 14:53:14.670  3844  4038 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:53:14.672  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.676  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.676  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:14.681   310  6863 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 14:53:14.681  1031  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6860 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-09 14:53:14.683  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 14:53:14.683  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:14.684  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:14.686  3844  3844 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:14.686  3844  3844 D BluetoothMapService: STATE_TURNING_OFF
09-09 14:53:14.687  3844  3844 V BluetoothMapService: Handler(): got msg=4
09-09 14:53:14.687  3844  3844 D BluetoothMapService: MAP Service closeService in
09-09 14:53:14.687  3844  3844 D BluetoothMapMasInstance: MAP Service shutdown
09-09 14:53:14.687  3844  3844 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:53:14.687  3844  3844 V BluetoothMapService: MAP Service closeService out
09-09 14:53:14.687  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.687  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 14:53:14.688  3844  3844 V BtOppService: Receiver DISABLED_ACTION 
09-09 14:53:14.688  3844  3844 I BtOppRfcommListener: stopping Accept Thread
09-09 14:53:14.688  3844  3844 V BtOppRfcommListener: close mBtServerSocket
09-09 14:53:14.688  3844  3844 V BtOppRfcommListener: waiting for thread to terminate
09-09 14:53:14.688  3844  4265 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:53:14.688  3844  3844 V BtOppRfcommListener: done waiting for thread to terminate
09-09 14:53:14.689  1031  1100 D DSQN    : Dns fail occured do internet check.
09-09 14:53:14.689  1031  1031 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-09 14:53:14.690  1031  1031 D DSQN    : try Internet connection check
09-09 14:53:14.690  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:14.690  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 14:53:14.691  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-09 14:53:14.693  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:14.693  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:14.693  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.693  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:14.695  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:14.695  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:14.695  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.695  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT,_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:14.721  1031  1098 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6882 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:53:14.724  3844  3844 V BtOppService: onDestroy
09-09 14:53:14.727  3844  3844 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 14:53:14.727  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.727  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.727  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.727  1031  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1adb963c
09-09 14:53:14.732  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.733  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.733  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-09 14:53:14.733  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.733   310  6901 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 14:53:14.733  1031  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 14:53:14.733  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.733  1031  1531 D DSQN    : disableDataServiceNotify
09-09 14:53:14.733  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.734  1031  1524 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:53:14.734  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.734  1031  1531 D DSQN    : stop dsqn bin
09-09 14:53:14.734  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.735  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:14.735  1031  6871 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
09-09 14:53:14.735  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 14:53:14.735  1031  6867 D DSQN    : ThreadInternetCheck internet check NOK 
09-09 14:53:14.735  1031  6867 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
,09-09 14:53:14.737  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 14:53:14.740  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.740  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.740  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:14.740  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-09 14:53:14.744  1031  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 14:53:14.744  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:14.744  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:14.744  1031  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:14.745  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 14:53:14.745  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.745  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.745  1031  2802 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 14:53:14.745  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 14:53:14.746  1031  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 14:53:14.746  1031  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 14:53:14.746  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:53:14.747  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.747  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.747  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:14.747  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 14:53:14.747  1031  1031 D RttService: SCAN_AVAILABLE : 1
09-09 14:53:14.748  1031  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.748  1031  1543 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:53:14.748  1031  1521 D LGWifiP2pService: P2pDisablingState
09-09 14:53:14.749  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:14.749  1031  1521 D LGWifiP2pService: P2pDisablingState{ when=-21ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.749  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:53:14.749  1031  1521 D LGWifiP2pService: p2p socket connection lost
09-09 14:53:14.749  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:14.749  1031  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:14.749  1031  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:14.749  1031  1531 D NetworkManagementService: Removing idletimer
09-09 14:53:14.749  1840  1840 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:14.749  1031  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.749  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:53:14.750  1031  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 14:53:14.750  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 14:53:14.750  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:53:14.750  2645  2645 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:53:14.750  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:53:14.750  1927  1927 D WfdsService: WifiP2pState is changed : false
09-09 14:53:14.751  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:53:14.751  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:14.751  1927  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 14:53:14.751  1927  2345 D WfdsService: Set the WFDS Monitor: false
09-09 14:53:14.751  1031  1521 D LGWifiP2pService: P2pDisabledState
09-09 14:53:14.751  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:14.751  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.751  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:14.751   310   875 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:53:14.752  1927  2345 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:53:14.752  1927  2345 D WfdsService: STATE : WfdsDisabledState - enter
09-09 14:53:14.752  1927  2717 D CtrlSupplicant: Received on exit socket, terminate
09-09 14:53:14.752  1927  2717 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 14:53:14.752  1927  2717 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 14:53:14.752  1927  2717 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 14:53:14.752  1927  2347 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 14:53:14.752  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:53:14.752  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:53:14.752  1927  2345 W WfdsService: D,efaultState - msg [9445378] is not handled
09-09 14:53:14.752  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:53:14.752  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:53:14.752  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:53:14.752  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:53:14.752  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:53:14.752  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:53:14.753  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:53:14.753  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:53:14.756  1031  1524 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 14:53:14.757  1031  1524 D WifiNative-p2p0: TERMINATE: returned true
09-09 14:53:14.757  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:14.757  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:14.757  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:53:14.757  1031  1524 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:14.758  1031  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:14.764  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:14.764  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:14.764  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 14:53:14.764  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:14.764  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-09 14:53:14.765  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.765  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:14.765  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:14.765  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 14:53:14.765  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:14.765  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,09-09 14:53:14.769  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:14.769  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:14.769  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.769  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:14.771  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:14.771  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:14.771  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:14.771  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:14.778  6882  6882 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:53:14.778  6882  6882 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 14:53:14.778  6882  6882 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:53:14.778  6882  6882 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-09 14:53:14.779  6882  6882 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 14:53:14.779  6882  6882 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 14:53:14.782  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:14.782  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:14.782  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:14.794  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:14.794  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:14.795  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:14.804  6860  6860 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 14:53:14.805  6860  6860 W LG Account v2.2: No ProfileInfo entries
09-09 14:53:14.805  6860  6860 I LG Account v2.2: isEnabled: false
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Country: EU
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Operator: OPEN
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Ranking support: false
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Comfort support: false
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Accessory: true
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Health device: true
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Extra Pedometer: false
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Blood glucose device: false
09-09 14:53:14.805  6860  6860 I Feature : [Lifetracker]Device Number: 3
09-09 14:53:14.807  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 14:53:14.809  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:14.809  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:14.811  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:14.814  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 14:53:14.814  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:14.816  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:14.817  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:14.830  1031  1901 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6905 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 14:53:14.831  1031  1901 I ActivityManager: Killing 6194:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-09 14:53:14.853  1031  2808 D DhcpStateMachine: StoppedState
09-09 14:53:14.853  1031  2808 D DhcpStateMachine: StoppedState{ when=-102ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:53:14.855  2645  2645 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 14:53:14.856  2645  2645 I wpa_supplicant: monitor socket send errors count : 1
09-09 14:53:14.856  2645  2645 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
09-09 14:53:14.856  1031  2710 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 14:53:14.856  1031  2710 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 14:53:14.866  1031  1561 W libprocessgroup: failed to open /acct/uid_10014/pid_6194/cgroup.procs: No such file or directory
,09-09 14:53:14.873  1031  1524 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 14:53:14.873  1031  1524 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 14:53:14.923  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 14:53:14.928  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 14:53:14.930  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:14.934  1031  1926 I ActivityManager: Killing 6325:com.android.defcontainer/u0a4 (adj 15): empty #17
09-09 14:53:14.951  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-09 14:53:14.977  1031  1047 W libprocessgroup: failed to open /acct/uid_10004/pid_6325/cgroup.procs: No such file or directory
,09-09 14:53:14.981  2645  2645 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:53:14.981  1031  2710 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 14:53:14.981  1031  2710 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:53:14.982  1031  2710 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:53:14.982  1031  1102 D Tethering: InitialState.processMessage what=4
09-09 14:53:14.982  2645  2645 W wpa_supplicant: USIM:  scard_deinit function
09-09 14:53:14.982  1031  2710 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 14:53:14.982  1031  2710 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:14.983  1031  2710 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:14.983  1031  1524 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=212225
09-09 14:53:14.984  1031  1524 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=212225
09-09 14:53:14.984  1031  1524 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=212225  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:53:14.985  1031  1524 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=212226  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:53:14.986  3844  3844 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:14.987  3844  3844 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:14.987  3844  3844 V BluetoothPbapReceiver: ***********state = 13
09-09 14:53:14.988  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:53:14.988  3844  3844 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 14:53:14.990  3844  3844 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:14.990  3844  3844 V BluetoothPbapService: state: 13
09-09 14:53:14.990  3844  3844 V BluetoothPbapService: Pbap Service closeService in
,09-09 14:53:14.992  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:53:14.993  1031  1524 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:14.993  1031  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:14.995  3844  3844 V BluetoothPbapService: successfully stopped pbap service
09-09 14:53:14.995  3844  3844 V BluetoothPbapService: Pbap Service closeService out
09-09 14:53:14.995  3844  3844 V BluetoothPbapService: Pbap Service onDestroy
09-09 14:53:14.995  3844  3844 V BluetoothPbapService: Pbap Service closeService in
09-09 14:53:14.995  3844  3844 V BluetoothPbapService: Pbap Service closeService out
09-09 14:53:14.996  3844  3844 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 14:53:14.996  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:15.024  6882  6882 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 14:53:15.024  6882  6882 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:53:15.033  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:15.040  1031  1102 D BluetoothManagerService: Message: 20
09-09 14:53:15.041  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11dcbcea:true
,09-09 14:53:15.050  1031  1102 D BluetoothManagerService: Message: 30
,09-09 14:53:15.054  1031  1102 D BluetoothManagerService: Message: 30
,09-09 14:53:15.057  6882  6882 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 14:53:15.059  6882  6882 D BluetoothMap: Create BluetoothMap proxy object
09-09 14:53:15.059  1031  1102 D BluetoothManagerService: Message: 30
09-09 14:53:15.063  1031  1102 D BluetoothManagerService: Message: 30
09-09 14:53:15.064  6882  6882 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 14:53:15.066  6882  6882 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-09 14:53:15.066  6745  6745 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 14:53:15.067  2645  2645 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 14:53:15.069  1031  2710 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 14:53:15.069  1031  2710 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 14:53:15.073  1031  1524 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-09 14:53:15.074  1031  2710 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 14:53:15.076  6882  6882 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-09 14:53:15.080  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,09-09 14:53:15.092  6882  6882 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:53:15.110  6882  6882 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 14:53:15.115  6882  6882 D BluetoothInputDevice: Proxy object connected
,09-09 14:53:15.119  6882  6882 D HidProfile: Bluetooth service connected
09-09 14:53:15.120  6882  6882 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:53:15.122  6882  6882 D PanProfile: Bluetooth service connected
09-09 14:53:15.124  6882  6882 D BluetoothMap: Proxy object connected
09-09 14:53:15.125  6882  6882 D MapProfile: Bluetooth service connected
09-09 14:53:15.126  6882  6882 D BluetoothMap: getConnectedDevices()
,09-09 14:53:15.127  6882  6882 D BluetoothMap: Bluetooth is Not enabled
09-09 14:53:15.127  6882  6882 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 14:53:15.131  6882  6882 D BluetoothPermissionRequest: onReceive
09-09 14:53:15.136  6882  6882 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 14:53:15.143  1031  1722 I ActivityManager: Killing 6492:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-09 14:53:15.150  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 14:53:15.179  3844  3844 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 14:53:15.179  3844  3844 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-09 14:53:15.180  3844  3844 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 14:53:15.181  1031  1926 W libprocessgroup: failed to open /acct/uid_10008/pid_6492/cgroup.procs: No such file or directory
09-09 14:53:15.196  1031  1524 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 14:53:15.196  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:15.196  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:15.196  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 14:53:15.200  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-09 14:53:15.201  1927  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 14:53:15.201  1927  2345 D WfdsService: Set the WFDS Monitor: false
09-09 14:53:15.201  1927  2345 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:53:15.214  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:53:15.215  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:15.218  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:15.220  3844  3844 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:15.220  3844  3844 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:53:15.221  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:15.222  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 14:53:15.222  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 14:53:15.222  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 14:53:15.223  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:15.224  3844  3844 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:53:15.224  3844  3844 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:15.225  3844  3844 V BluetoothFtpService: Ftp Service closeService
09-09 14:53:15.225  3844  3844 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 14:53:15.281  1031  1942 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6937 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 14:53:15.283  3844  3844 V BluetoothFtpService: successfully stopped ftp service
09-09 14:53:15.283  3844  3844 V BluetoothFtpService: Ftp Service onDestroy
09-09 14:53:15.283  3844  3844 V BluetoothFtpService: Ftp Service closeService
09-09 14:53:15.292  3844  3844 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:15.292  3844  3844 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:15.292  3844  3844 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:15.292  3844  3844 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:15.293  3844  3844 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 14:53:15.293  3844  3844 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-09 14:53:15.296  3844  3844 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:15.296  3844  3844 V BluetoothSapService: state: 13
09-09 14:53:15.296  3844  3844 V BluetoothSapService: Stopping SAP server process
09-09 14:53:15.297  3844  3844 V BluetoothSapService: Sap Service closeSapService in
09-09 14:53:15.297  3844  3844 V BluetoothSapService: Close listen Socket : 
,09-09 14:53:15.297  3844  3844 V BluetoothSapService: Close rfcomm Socket : 
09-09 14:53:15.298  3844  3844 V BluetoothSapService: Close sapd  Socket : 
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Sap Service closeSapService out
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Sap Service onDestroy
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Sap Service closeSapService in
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Close listen Socket : 
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Close rfcomm Socket : 
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Close sapd  Socket : 
09-09 14:53:15.299  3844  3844 V BluetoothSapService: Sap Service closeSapService out
09-09 14:53:15.339  1031  1942 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6954 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:53:15.362   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 22.233ms
,09-09 14:53:15.383   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.498ms
09-09 14:53:15.396  6937  6937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:53:15.400  6954  6954 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:53:15.405   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 20.073ms
09-09 14:53:15.415  1031  1962 I ActivityManager: Killing 5947:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-09 14:53:15.437  1031  1942 W libprocessgroup: failed to open /acct/uid_10011/pid_5947/cgroup.procs: No such file or directory
,09-09 14:53:15.438  6937  6937 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-09 14:53:15.471  6937  6937 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-09 14:53:15.471  6937  6937 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 14:53:15.471  6937  6937 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 14:53:15.472  6937  6937 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 14:53:15.472  6937  6937 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 14:53:15.474  6937  6937 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-09 14:53:15.480  6937  6937 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-09 14:53:15.487  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:15.491  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:15.512  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:53:15.518  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:15.518  6937  6937 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 14:53:15.522  6937  6937 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 14:53:15.525  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:53:15.525  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:53:15.526  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:15.534  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:15.540  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:15.550  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:15.550  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:53:15.552  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:53:15.556  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:15.561  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:53:15.561  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:53:15.561  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:15.566  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:15.574  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:15.583  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:15.584  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:15.586  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:53:15.656  1031  1046 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6980 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-09 14:53:15.678  3844  4038 W bt-btif : ag scb idx 1 not allocated
09-09 14:53:15.679  3844  3940 D bt_hci_bdroid: cleanup
09-09 14:53:15.679  3844  4038 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:15.679  3844  4040 I bt_lpm  : LPM is already off!!!
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:15.679  3844  4199 I bt_userial_mct: exiting userial_read_thread
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:15.679  3844  4199 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:15.679  3844  4038 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:15.679  3844  4038 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:53:15.679  3844  3940 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 14:53:15.679  3844  4040 I bt_vendor: hw_epilog_process
09-09 14:53:15.680  3844  3940 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 14:53:15.680  3844  3940 D bt_userial_mct: userial_close
09-09 14:53:15.680  3844  3940 E bt_userial_mct: pthread_join() FAILED result:3
09-09 14:53:15.680  3844  3940 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-09 14:53:15.737  1031  1031 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,09-09 14:53:15.745  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:15.749  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:53:15.759  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:15.773  3844  3940 D bt_hci_bdroid: set_power 0
09-09 14:53:15.773  3844  3940 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 14:53:15.774  3844  3940 I bt_vendor: bluetooth satus is on
09-09 14:53:15.774  3844  3940 I bt_vendor: bt-vendor : resetting BT status
09-09 14:53:15.774  3844  3940 I bt_vendor: Starting hciattach daemon
09-09 14:53:15.774  3844  3940 I bt_vendor: try to set false
,09-09 14:53:15.776  3844  3940 I bt_vendor: Starting hciattach daemon
09-09 14:53:15.776  3844  3940 I bt_vendor: try to set false
09-09 14:53:15.776  3844  3940 I bt_vendor: cleanup
09-09 14:53:15.779  3844  4038 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 14:53:15.780  3844  3940 I GKI_LINUX: GKI_exit_task 0 done
09-09 14:53:15.780  3844  3940 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 14:53:15.782  3844  3936 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 14:53:15.782  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:53:15.783  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:53:15.784  3844  3844 D HeadsetService: Received stop request...Stopping profile...
09-09 14:53:15.784  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:53:15.784  3844  3844 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 14:53:15.784  3844  3844 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:53:15.785  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
09-09 14:53:15.785  3844  3964 D HeadsetStateMachine: Exit Disconnected: -1
09-09 14:53:15.785  6882  6882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-09 14:53:15.787  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:15.787  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:15.787  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:15.789  1031  1031 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:15.789  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 14:53:15.789  3844  3844 D A2dpService: Received stop request...Stopping profile...
09-09 14:53:15.789  3844  4002 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:53:15.790  3844  3844 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 14:53:15.792  3844  3844 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 14:53:15.792  3844  3844 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:53:15.792  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
09-09 14:53:15.791  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:53:15.793  3844  3936 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 14:53:15.794  1031  1031 D BluetoothA2dp: Proxy object disconnected
09-09 14:53:15.794  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 14:53:15.794  3844  3844 D HidService: Received stop request...Stopping profile...
09-09 14:53:15.794  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
09-09 14:53:15.796  3844  3844 D HeadsetStateMachine: Unbinding service...
09-09 14:53:15.797  3844  3844 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:53:15.797  3844  3844 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:53:15.797  3844  3844 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:53:15.797  3844  3844 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:53:15.797  3844  3844 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:53:15.797  3844  3844 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:53:15.797  3844  3844 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-09 14:53:15.801  3844  3844 D HealthService: Received stop request...Stopping profile...
09-09 14:53:15.801  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
09-09 14:53:15.802  3844  3844 D PanService: Received stop request...Stopping profile...
09-09 14:53:15.803  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
09-09 14:53:15.804  3844  3844 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:53:15.804  6980  7003 W FormManager: Network not available. Please check & try again.
09-09 14:53:15.805  3844  3844 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:53:15.805  3844  3844 D BtGatt.GattService: stop()
09-09 14:53:15.805  3844  3844 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 14:53:15.806  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
09-09 14:53:15.807  3844  3844 I BluetoothA2dpServiceJni: cleanupNative
09-09 14:53:15.807  3844  4003 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 14:53:15.807  3844  3844 I GKI_LINUX: GKI_exit_task 2 done
09-09 14:53:15.807  3844  3844 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 14:53:15.808  3844  3844 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:53:15.808  3844  3844 D BluetoothMapService: stop()
09-09 14:53:15.808  3844  3844 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 14:53:15.808  3844  3844 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 14:53:15.809  3844  3844 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f2d48f
,09-09 14:53:15.810  3844  3844 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:53:15.810  3844  3844 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 14:53:15.810  3844  3844 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:53:15.810  3844  3844 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:53:15.810  3844  3844 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:53:15.811  3844  3844 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:53:15.811  3844  3844 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:53:15.812  3844  3844 V BluetoothMapService: Handler(): got msg=4
09-09 14:53:15.812  3844  3844 D BluetoothMapService: MAP Service closeService in
09-09 14:53:15.812  3844  3844 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:53:15.812  3844  3844 V BluetoothMapService: MAP Service closeService out
,09-09 14:53:15.813  3844  3844 D BluetoothMapService: cleanup()
09-09 14:53:15.813  3844  3844 D BluetoothMapService: MAP Service closeService in
09-09 14:53:15.813  3844  3844 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:53:15.813  3844  3844 V BluetoothMapService: MAP Service closeService out
09-09 14:53:15.813  3844  3936 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 14:53:15.813  3844  3936 D BluetoothAdapterProperties: Setting state to 10
09-09 14:53:15.813  3844  3936 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 14:53:15.813  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:15.813  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 14:53:15.813  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 14:53:15.813  6882  6899 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:53:15.814  3844  3936 I BluetoothAdapterState: Entering OffState
09-09 14:53:15.815  6882  6900 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:53:15.817  6980  7004 V FormManager: Network unavailable.
09-09 14:53:15.817  6882  6899 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:53:15.817  6882  6882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:53:15.817  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:53:15.817  1840  2417 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:15.817  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:53:15.817  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:53:15.817  6882  6882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:53:15.818  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:53:15.818  6882  6882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:53:15.819  6882  6882 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 14:53:15.819  6882  6882 D PanProfile: Bluetooth service disconnected
09-09 14:53:15.820  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:15.822  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:15.822  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:15.824  6882  6900 D BluetoothPan: onBluetoothStateChange on: false
,09-09 14:53:15.824  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:15.824  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:15.825  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:15.828  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 14:53:15.828  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 14:53:15.828  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:15.829  6980  7004 V FormManager: Network unavailable.
09-09 14:53:15.833  1031  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 14:53:15.833  1031  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 14:53:15.834  1031  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1417363 mBinding = false
09-09 14:53:15.834  4275  7007 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:15.834  1031  1102 D BluetoothManagerService: Sending unbind request.
,09-09 14:53:15.837  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 14:53:15.843  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:15.845  6905  6905 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 14:53:15.846  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:15.847  3844  3940 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-09 14:53:15.847  1927  2115 D LGBluetoothAPIService: Message: 2
09-09 14:53:15.847  3844  3844 I GKI_LINUX: GKI_exit_task 1 done
09-09 14:53:15.847  3844  3844 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 14:53:15.847  1927  2115 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@107308be mBinding = false
09-09 14:53:15.847  1927  2115 D LGBluetoothAPIService: Sending unbind request.
09-09 14:53:15.848  3844  3844 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 14:53:15.848  1589  1589 D BluetoothAdapter: 321484614: getState() :  mService = null. Returning STATE_OFF
09-09 14:53:15.848  3844  3844 I art     : --- WEIRD: removing null entry 246
09-09 14:53:15.848  1589  1589 D BluetoothAdapter: 321484614: getState() :  mService = null. Returning STATE_OFF
09-09 14:53:15.848  3844  3844 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-09 14:53:15.848  3844  3844 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 14:53:15.848  6882  6882 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:53:15.849  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 14:53:15.849  6882  6882 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 14:53:15.849  3844  3844 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 14:53:15.851  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:15.852  3844  3844 I art     : System.exit called, status: 0
09-09 14:53:15.852  3844  3844 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 14:53:15.853  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:15.853  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:53:15.854  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:53:15.854  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:15.858  4275  7008 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:15.858  4275  7008 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:53:15.872  6882  6882 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:53:15.876  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:53:15.877   314   314 V AudioFlinger: 3844 died, releasing its sessions
09-09 14:53:15.877   314   314 V AudioFlinger:  pid 1840 @ 0
09-09 14:53:15.877   314   314 V AudioFlinger:  pid 3407 @ 1
09-09 14:53:15.877   314   314 V AudioFlinger:  pid 3407 @ 2
09-09 14:53:15.877  1031  1726 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-09 14:53:15.877  1031  1726 W BroadcastQueue: android.os.DeadObjectException
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
09-09 14:53:15.877  1031  1726 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 14:53:15.882  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:15.882  6882  6882 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 14:53:15.905  1031  1726 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-09 14:53:15.982  1031  1726 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7017 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-09 14:53:15.983  1031  1963 W ActivityManager: Spurious death for ProcessRecord{876a2a 7017:com.android.bluetooth/1002}, curProc for 3844: null
,09-09 14:53:15.986  1031  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=844314170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
09-09 14:53:15.987  1031  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39c389b5 type 2 when 213143 com.google.android.gms} when 213143
09-09 14:53:15.991  6980  7015 W FormManager: Network not available. Please check & try again.
09-09 14:53:16.003  6980  7016 V FormManager: Network unavailable.
,09-09 14:53:16.010  6980  7016 V FormManager: Network unavailable.
,09-09 14:53:16.027  6937  6937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 14:53:16.029  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 14:53:16.030  6937  6937 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-09 14:53:16.031  1031  2000 I ActivityManager: Killing 5969:com.android.contacts/u0a19 (adj 15): empty #17
09-09 14:53:16.070  6937  6937 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:16.070  6937  6937 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:16.078  6937  6937 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 14:53:16.080  6937  6937 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 14:53:16.080  6937  6937 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-09 14:53:16.080  6937  6937 V SoundPool: doLoad: loading sample sampleID=1
09-09 14:53:16.081  6937  6937 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:53:16.081  6937  7038 V SoundPool: Start decode
09-09 14:53:16.081  6937  7038 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-09 14:53:16.081   314  1365 V MediaPlayerService: decode(23, 10857164, 17813)
09-09 14:53:16.082   314  1365 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,09-09 14:53:16.082   314  1365 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
,09-09 14:53:16.082   314  1365 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 14:53:16.082   314  1365 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 14:53:16.082   314  1365 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
,09-09 14:53:16.082   314  1365 V MediaPlayerService: player type = 3
09-09 14:53:16.082   314  1365 V AwesomePlayer: AwesomePlayer create()
09-09 14:53:16.083   314  1365 V AwesomePlayer: reset_l() 
09-09 14:53:16.083   314  1365 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:16.083   314  1365 V AwesomePlayer: setAudioSink() 
09-09 14:53:16.083   314  1365 V AwesomePlayer: reset_l() 
09-09 14:53:16.083   314  1365 V AudioCache: notify(0xb1432180, 8, 0, 0)
09-09 14:53:16.083   314  1365 V AudioCache: ignored
09-09 14:53:16.083   314  1365 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:16.084   314  1365 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 14:53:16.084   314  1365 V AwesomePlayer: setDataSource_l dataSource
,09-09 14:53:16.084   314  1365 V LGParserOSAL: SniffLGParser start
09-09 14:53:16.084   314  1365 V LGParserOSAL: MainType:5, SubType=0
09-09 14:53:16.084   314  1365 V LGParserOSAL: #### check Mime : application/ogg
,09-09 14:53:16.084   314  1365 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 14:53:16.084   314  1365 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 14:53:16.110  1031  2037 W libprocessgroup: failed to open /acct/uid_10019/pid_5969/cgroup.procs: No such file or directory
,09-09 14:53:16.117  6654  6654 D UEI.SmartControl: QS Service created
09-09 14:53:16.126  6937  6937 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 14:53:16.136  6937  6937 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:53:16.137  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:53:16.140   314  1365 V LGParserOSAL: supported mime: application/ogg
09-09 14:53:16.140   314  1365 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 14:53:16.140   314  1365 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 14:53:16.140   314  1365 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 14:53:16.140   314  1365 V AwesomePlayer: AudioTrack Setting
09-09 14:53:16.140   314  1365 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 14:53:16.140   314  1365 V AwesomePlayer: setAudioSource() 
09-09 14:53:16.140   314  1365 V MediaPlayerService: prepare
09-09 14:53:16.140   314  1365 V AwesomePlayer: prepareAsync_l() 
09-09 14:53:16.140   314  1365 V MediaPlayerService: wait for prepare
09-09 14:53:16.141   314  7039 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 14:53:16.141   314  7039 V AwesomePlayer: initAudioDecoder() 
09-09 14:53:16.141   314  7039 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:53:16.141   314  7039 V AudioSystem: isOffloadSupported()
09-09 14:53:16.141   314  7039 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:53:16.141   314  7039 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:53:16.141   314  7039 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:53:16.141   314  7039 V AwesomePlayer: getUseOffload() = 0 
09-09 14:53:16.141   314  7039 V OMXCodec: OMXCodec::Create
09-09 14:53:16.141   314  7039 V OMXCodec: findMatchingCodecs()
09-09 14:53:16.141   314  7039 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 14:53:16.142   314  7039 V OMXCodec: matchingCodecs.size()=1
09-09 14:53:16.142   314  7039 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,09-09 14:53:16.145  6654  6654 I UEI.SmartControl: Service initServices...
09-09 14:53:16.145  6654  6654 D UEI.SmartControl: QS start get config
09-09 14:53:16.146   314  7039 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 14:53:16.146   314  7039 V LGCodecAdapter: LG Codec Adapter start
09-09 14:53:16.146   314  7039 V OMXCodec: OMXCodec Createtor
09-09 14:53:16.146   314  7039 V OMXCodec: setComponentRole
09-09 14:53:16.146   314  7039 V OMXCodec: configureCodec protected=0
09-09 14:53:16.147   314  7039 V LGCodecAdapter: called getLGCodecSpecificData
09-09 14:53:16.147   314  7039 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 14:53:16.147   314  7039 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 14:53:16.147   314  7039 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 14:53:16.147   314  7039 V LGCodecOSAL: Not support LGCodec
09-09 14:53:16.147   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:53:16.147   314  7039 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 14:53:16.147   314  7039 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 14:53:16.147   314  7039 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 14:53:16.147   314  7039 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:53:16.148   314  7039 V AudioSystem: isOffloadSupported()
09-09 14:53:16.148   314  7039 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:53:16.148   314  7039 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:53:16.148   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 14:53:16.148   314  7039 V OMXCodec: init()
09-09 14:53:16.148   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 14:53:16.148   314  7039 V OMXCodec: allocateBuffers
09-09 14:53:16.148   314  7039 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 14:53:16.148   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 14:53:16.149   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
09-09 14:53:16.149   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-09 14:53:16.149   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-09 14:53:16.149   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-09 14:53:16.149   314  7039 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:53:16.149   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:53:16.149   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 14:53:16.150   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-09 14:53:16.150   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-09 14:53:16.150   314  7039 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd290 on output port
09-09 14:53:16.150   314  7039 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 14:53:16.150   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:53:16.150   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:53:16.150   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 14:53:16.150   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 14:53:16.150   314  7041 V OMXCod,ec: [OMX.google.vorbis.decoder] Now Executing.
09-09 14:53:16.150   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 14:53:16.150   314  7039 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 14:53:16.150   314  7039 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 14:53:16.150   314  7039 V AudioCache: notify(0xb1432180, 5, 0, 0)
09-09 14:53:16.150   314  7039 V AudioCache: ignored
09-09 14:53:16.150   314  7039 V AudioCache: notify(0xb1432180, 1, 0, 0)
09-09 14:53:16.150   314  7039 V AudioCache: prepared
09-09 14:53:16.150   314  1365 V AudioCache: wait - success
09-09 14:53:16.150   314  1365 V MediaPlayerService: start
,09-09 14:53:16.150   314  1365 V AwesomePlayer: play_l() 
09-09 14:53:16.150   314  1365 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 14:53:16.150   314  1365 V AwesomePlayer: createAudioPlayer_l
09-09 14:53:16.151   314  1365 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 14:53:16.151   314  1365 V AwesomePlayer: startAudioPlayer_l() 
09-09 14:53:16.151   314  1365 D AudioPlayer: start of Playback, useOffload 0
09-09 14:53:16.151   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:53:16.151   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:53:16.153   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 14:53:16.153   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 14:53:16.153   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 14:53:16.153   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 14:53:16.153   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 14:53:16.153   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790928
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:53:16.155   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 14:53:16.156   314  7041 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd600 on output port
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 14:53:16.156   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 14:53:16.157   314  1365 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 14:53:16.158   314  1365 V AudioCache: notify(0xb1432180, 6, 0, 0)
09-09 14:53:16.158   314  1365 V AudioCache: ignored
09-09 14:53:16.158   314  1365 V MediaPlayerService: wait for playback complete
09-09 14:53:16.158   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.158   314  7042 V AudioCache: memcpy(0xaf004000, 0xb1017000, 4096)
09-09 14:53:16.159  7017  7017 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist o,r contains no resources.
09-09 14:53:16.160   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.160   314  7042 V AudioCache: memcpy(0xaf005000, 0xb1017000, 4096)
09-09 14:53:16.160  7017  7017 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:53:16.160   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.160   314  7042 V AudioCache: memcpy(0xaf006000, 0xb1017000, 4096)
09-09 14:53:16.161  7017  7017 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 14:53:16.161   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.161   314  7042 V AudioCache: memcpy(0xaf007000, 0xb1017000, 4096)
09-09 14:53:16.161   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.161   314  7042 V AudioCache: memcpy(0xaf008000, 0xb1017000, 4096)
09-09 14:53:16.162   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.162   314  7042 V AudioCache: memcpy(0xaf009000, 0xb1017000, 4096)
09-09 14:53:16.162  7017  7017 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 14:53:16.163   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.163   314  7042 V AudioCache: memcpy(0xaf00a000, 0xb1017000, 4096)
09-09 14:53:16.164   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.164   314  7042 V AudioCache: memcpy(0xaf00b000, 0xb1017000, 4096)
09-09 14:53:16.164   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.164   314  7042 V AudioCache: memcpy(0xaf00c000, 0xb1017000, 4096)
09-09 14:53:16.165   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.165   314  7042 V AudioCache: memcpy(0xaf00d000, 0xb1017000, 4096)
09-09 14:53:16.166   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.166   314  7042 V AudioCache: memcpy(0xaf00e000, 0xb1017000, 4096)
09-09 14:53:16.167   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.167   314  7042 V AudioCache: memcpy(0xaf00f000, 0xb1017000, 4096)
09-09 14:53:16.167   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.167   314  7042 V AudioCache: memcpy(0xaf010000, 0xb1017000, 4096)
09-09 14:53:16.168   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.168   314  7042 V AudioCache: memcpy(0xaf011000, 0xb1017000, 4096)
09-09 14:53:16.169   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.169   314  7042 V AudioCache: memcpy(0xaf012000, 0xb1017000, 4096)
09-09 14:53:16.169   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.169  6937  6937 V LGMDMManager: Create singleton instance
09-09 14:53:16.169   314  7042 V AudioCache: memcpy(0xaf013000, 0xb1017000, 4096)
09-09 14:53:16.170   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.170   314  7042 V AudioCache: memcpy(0xaf014000, 0xb1017000, 4096)
09-09 14:53:16.171   314  7042 V AudioCache: write(0xb1017000, 4096)
,09-09 14:53:16.171   314  7042 V AudioCache: memcpy(0xaf015000, 0xb1017000, 4096)
09-09 14:53:16.172   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.172   314  7042 V AudioCache: memcpy(0xaf016000, 0xb1017000, 4096)
09-09 14:53:16.172   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.172   314  7042 V AudioCache: memcpy(0xaf017000, 0xb1017000, 4096)
09-09 14:53:16.173   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.173   314  7042 V AudioCache: memcpy(0xaf018000, 0xb1017000, 4096)
09-09 14:53:16.174   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.174   314  7042 V AudioCache: memcpy(0xaf019000, 0xb1017000, 4096)
09-09 14:53:16.174   314  7042 V AudioCache: write(0xb1017000, 4096)
,09-09 14:53:16.174   314  7042 V AudioCache: memcpy(0xaf01a000, 0xb1017000, 4096)
09-09 14:53:16.175   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.175   314  7042 V AudioCache: memcpy(0xaf01b000, 0xb1017000, 4096)
09-09 14:53:16.176   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.176   314  7042 V AudioCache: memcpy(0xaf01c000, 0xb1017000, 4096)
09-09 14:53:16.176   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.177   314  7042 V AudioCache: memcpy(0xaf01d000, 0xb1017000, 4096)
09-09 14:53:16.177   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.177   314  7042 V AudioCache: memcpy(0xaf01e000, 0xb1017000, 4096)
,09-09 14:53:16.178   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.178   314  7042 V AudioCache: memcpy(0xaf01f000, 0xb1017000, 4096)
09-09 14:53:16.179   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.179   314  7042 V AudioCache: memcpy(0xaf020000, 0xb1017000, 4096)
09-09 14:53:16.179   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.179   314  7042 V AudioCache: memcpy(0xaf021000, 0xb1017000, 4096)
09-09 14:53:16.180   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.180   314  7042 V AudioCache: memcpy(0xaf022000, 0xb1017000, 4096)
09-09 14:53:16.181   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.181   314  7042 V AudioCache: memcpy(0xaf023000, 0xb1017000, 4096)
,09-09 14:53:16.181   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.181   314  7042 V AudioCache: memcpy(0xaf024000, 0xb1017000, 4096)
09-09 14:53:16.182   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.182   314  7042 V AudioCache: memcpy(0xaf025000, 0xb1017000, 4096)
,09-09 14:53:16.183   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.183   314  7042 V AudioCache: memcpy(0xaf026000, 0xb1017000, 4096)
09-09 14:53:16.183  7017  7017 D BluetoothAdapterApp: Loading JNI Library
09-09 14:53:16.183   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.183   314  7042 V AudioCache: memcpy(0xaf027000, 0xb1017000, 4096)
09-09 14:53:16.184   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.184   314  7042 V AudioCache: memcpy(0xaf028000, 0xb1017000, 4096)
09-09 14:53:16.185   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.185   314  7042 V AudioCache: memcpy(0xaf029000, 0xb1017000, 4096)
09-09 14:53:16.186   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.186   314  7042 V AudioCache: memcpy(0xaf02a000, 0xb1017000, 4096)
09-09 14:53:16.186   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.186   314  7042 V AudioCache: memcpy(0xaf02b000, 0xb1017000, 4096)
09-09 14:53:16.187   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.187   314  7042 V AudioCache: memcpy(0xaf02c000, 0xb1017000, 4096)
09-09 14:53:16.188   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.188   314  7042 V AudioCache: memcpy(0xaf02d000, 0xb1017000, 4096)
09-09 14:53:16.188   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.188   314  7042 V AudioCache: memcpy(0xaf02e000, 0xb1017000, 4096)
09-09 14:53:16.189   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.189   314  7042 V AudioCache: memcpy(0xaf02f000, 0xb1017000, 4096)
09-09 14:53:16.190   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.190   314  7042 V AudioCache: memcpy(0xaf030000, 0xb1017000, 4096)
09-09 14:53:16.190   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.190   314  7042 V AudioCache: memcpy(0xaf031000, 0xb1017000, 4096)
09-09 14:53:16.191   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.191   314  7042 V AudioCache: memcpy(0xaf032000, 0xb1017000, 4096)
09-09 14:53:16.192   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.192   314  7042 V AudioCache: memcpy(0xaf033000, 0xb1017000, 4096)
09-09 14:53:16.192   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.192   314  7042 V AudioCache: memcpy(0xaf034000, 0xb1017000, 4096)
09-09 14:53:16.193   314  7042 V AudioCache: write(0xb1017000, 4096)
09-09 14:53:16.193   314  7042 V AudioCache: memcpy(0xaf035000, 0xb1017000, 4096)
09-09 14:53:16.193   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 14:53:16.193   314  7042 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:53:16.193   314  7042 V AwesomePlayer: postAudioEOS() 
09-09 14:53:16.193   314  7042 V AudioCache: write(0xb1017000, 280)
09-09 14:53:16.193   314  7042 V AudioCache: memcpy(0xaf036000, 0xb1017000, 280)
09-09 14:53:16.205   314  7039 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 14:53:16.205   314  7039 V AwesomePlayer: onStreamDone
09-09 14:53:16.205   314  7039 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 14:53:16.205   314  7039 V AudioCache: notify(0xb1432180, 2, 0, 0)
09-09 14:53:16.205   314  7039 V AudioCache: playback complete
09-09 14:53:16.205   314  7039 V AwesomePlayer: pause_l() 
09-09 14:53:16.205   314  7039 V AudioCache: notify(0xb1432180, 7, 0, 0)
09-09 14:53:16.205   314  7039 V AudioCache: ignored
09-09 14:53:16.205   314  7039 V AwesomePlayer: cancelPlayerEvents
,09-09 14:53:16.205   314  1365 V AudioCache: wait - success
09-09 14:53:16.205   314  1365 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 14:53:16.205   314  7039 D AudioPlayer: Pause Playback at 1068125
09-09 14:53:16.205   314  1365 V AwesomePlayer: reset_l() 
09-09 14:53:16.206   314  1365 V AudioCache: notify(0xb1432180, 8, 0, 0)
09-09 14:53:16.206   314  1365 V AudioCache: ignored
09-09 14:53:16.206   314  1365 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:16.206   314  1365 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 14:53:16.206   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 14:53:16.206   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,09-09 14:53:16.206   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 14:53:16.206   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
,09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd600 on port 1
,09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 14:53:16.206   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 14:53:16.207   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 14:53:16.207   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 14:53:16.207   314  7041 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 14:53:16.207   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,09-09 14:53:16.207   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 14:53:16.207   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 14:53:16.208   314  1365 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 14:53:16.208   314  1365 D AudioPlayer: AudioPlayer releasing audio source
09-09 14:53:16.208   314  1365 D AudioPlayer: AudioPlayer done releasing audio source
09-09 14:53:16.209   314  1365 V AwesomePlayer: reset_l() 
09-09 14:53:16.209   314  1365 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:16.209   314  1365 V AwesomePlayer: ~AwesomePlayer call
,09-09 14:53:16.209   314  1365 V AwesomePlayer: reset_l() 
09-09 14:53:16.209   314  1365 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:16.209  6937  7038 V SoundPool: close(31)
09-09 14:53:16.209  6937  7038 V SoundPool: pointer = 0xa0040000, size = 205080, sampleRate = 48000, numChannels = 2
,09-09 14:53:16.220  7017  7017 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b338784 Instance Count = 1
,09-09 14:53:16.227  7017  7017 D BluetoothAdapterApp: onCreate
,09-09 14:53:16.250  7017  7017 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 14:53:16.250  7017  7017 D ProfileConfigQcom: Adding HeadsetService
09-09 14:53:16.250  7017  7017 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 14:53:16.250  7017  7017 D ProfileConfigQcom: Adding A2dpService
09-09 14:53:16.250  7017  7017 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 14:53:16.251  7017  7017 D ProfileConfigQcom: Adding HidService
09-09 14:53:16.251  7017  7017 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 14:53:16.251  7017  7017 D ProfileConfigQcom: Adding HealthService
09-09 14:53:16.251  7017  7017 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 14:53:16.252  7017  7017 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 14:53:16.252  7017  7017 D ProfileConfigQcom: Adding PanService
09-09 14:53:16.253  7017  7017 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 14:53:16.253  7017  7017 D ProfileConfigQcom: Adding GattService
09-09 14:53:16.253  7017  7017 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 14:53:16.253  7017  7017 D ProfileConfigQcom: Adding BluetoothMapService
09-09 14:53:16.254  7017  7017 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 14:53:16.254  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:16.256  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:53:16.256  7017  7017 V BluetoothPbapReceiver: ***********state = 10
09-09 14:53:16.257  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:53:16.258  7017  7017 V LGMDMManagerInternal: Create singleton instance
09-09 14:53:16.258  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-09 14:53:16.261  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2772
09-09 14:53:16.267   310  7045 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 14:53:16.270  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-09 14:53:16.344  6882  6882 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 14:53:16.346  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:53:16.375  6882  6882 D BluetoothPermissionRequest: onReceive
,09-09 14:53:16.379  6882  6882 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 14:53:16.380  6882  6882 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 14:53:16.383  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:53:16.394  7017  7017 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-09 14:53:16.401  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:16.404  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:16.405  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:16.406  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
,09-09 14:53:16.409  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:16.409  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 14:53:16.423  6954  6954 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-09 14:53:16.456  2622  2622 D [Concierge]Service: onStartCommand(). Type : 9
,09-09 14:53:16.480  1031  1031 D PowerManagerServiceEx: releaseWakeLockInternal: lock=844314170 [*alarm*], flags=0x0
,09-09 14:53:16.499  6654  6654 I UEI.SmartControl: Supports setup maps: true
,09-09 14:53:16.501  6654  6654 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 14:53:16.501  6654  6654 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-09 14:53:16.501  6654  6654 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:53:16.501  6654  6654 I UEI.SmartControl: ### init IR Blaster...
,09-09 14:53:16.504  6654  6654 D serial_port: Configuring serial port
09-09 14:53:16.505  6654  6654 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:53:16.505  6654  6654 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 14:53:16.505  6654  6654 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:53:16.505  6654  6654 I UEI.SmartControl: Get version...
09-09 14:53:16.523  6654  7047 D UEI.SmartControl: serial port data available: 21
,09-09 14:53:16.549  6654  6654 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 14:53:16.550  6654  6654 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-09 14:53:16.550  6654  6654 I UEI.SmartControl: QS saving settings...
,09-09 14:53:16.552  6654  6654 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 14:53:16.569  6654  7047 D UEI.SmartControl: serial port data available: 4
,09-09 14:53:16.603  6654  7050 I UEI.SmartControl: Device manager: loading config....
09-09 14:53:16.604  6654  7050 D UEI.SmartControl: ----------- loading internal config...
,09-09 14:53:16.605  6654  6654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 14:53:16.610  6654  6654 E UEI.SmartControl: Services init done
09-09 14:53:16.611  6654  6654 D UEI.SmartControl: QS Service init finished
09-09 14:53:16.615  6654  6654 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 14:53:16.615  6654  6654 D UEI.SmartControl: QS Service version code: 201091
09-09 14:53:16.616  6654  6654 D UEI.SmartControl: Service requested: Control
09-09 14:53:16.617  6654  7050 E UEI.SmartControl: Loading SETTINGS...
09-09 14:53:16.621  6654  6654 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 14:53:16.623  6937  6937 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 14:53:16.624  6654  6654 D UEI.SmartControl: Internal service binding...
09-09 14:53:16.625  6654  6669 I UEI.SmartControl: ------ IControl API: 11
09-09 14:53:16.625  6654  6669 D UEI.SmartControl: File observer start...
09-09 14:53:16.626  6654  6669 E UEI.SmartControl: IR Port is disabled: false
09-09 14:53:16.626  6654  6669 D UEI.SmartControl: Starting file observer...
09-09 14:53:16.627  6654  6669 I UEI.SmartControl: Registering callback...
09-09 14:53:16.628  6654  6670 I UEI.SmartControl: ------ IControl API: 19
09-09 14:53:16.629  6654  7050 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 14:53:16.630  6654  6670 I UEI.SmartControl: Registering Services Ready callback...
09-09 14:53:16.640  6654  7049 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 14:53:16.640  6654  7049 D UEI.SmartControl: -----service ready thread exits
09-09 14:53:16.641  6937  6953 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 14:53:16.642  6937  7036 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 14:53:16.642  6937  7036 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-09 14:53:16.643  6937  6937 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 14:53:16.644  6937  6937 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 14:53:16.644  6654  6669 I UEI.SmartControl: ------ IControl API: 8
09-09 14:53:16.646  6937  6937 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 14:53:16.646  6937  6937 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 14:53:16.647  6937  6937 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 14:53:16.647  6937  6937 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 14:53:16.648  6937  6937 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 14:53:16.648  6937  6937 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 14:53:16.650  6937  6937 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 14:53:16.656  6937  6937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 14:53:16.657  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-09 14:53:16.660  6937  6937 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:53:16.660  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:53:16.661  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:53:16.663  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 14:53:16.663  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 14:53:16.665  6937  6937 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473425596664]
,09-09 14:53:16.668  6937  6937 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-09 14:53:16.670  1031  1726 I ActivityManager: Killing 6000:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-09 14:53:16.706  6937  7052 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 14:53:16.715  1031  1726 I ActivityManager: Killing 6544:com.lge.email/u0a23 (adj 15): empty #18
09-09 14:53:16.808  1031  1723 W libprocessgroup: failed to open /acct/uid_10027/pid_6000/cgroup.procs: No such file or directory
,09-09 14:53:16.815  1031  2037 W libprocessgroup: failed to open /acct/uid_10023/pid_6544/cgroup.procs: No such file or directory
09-09 14:53:16.828  6937  6937 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-09 14:53:16.830  6937  6937 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,09-09 14:53:16.831  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 14:53:16.832  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 14:53:16.833  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 14:53:16.834  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 14:53:16.836  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 14:53:16.846  6937  6937 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 14:53:17.659  1031  1901 D WifiServiceImplEx: setWifiEnabled: true pid=6745, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:53:17.661  1031  1901 D WifiService: setWifiEnabled: true pid=6745, uid=10118
09-09 14:53:17.661  1031  1901 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:53:17.689  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 14:53:17.690  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:17.690  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-09 14:53:17.691  1031  1524 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 14:53:17.691  1031  1524 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 14:53:17.694  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 14:53:17.694  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 14:53:17.694  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 14:53:17.694  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 14:53:17.694  1031  1524 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 14:53:17.694  1031  1524 E WifiHW  : unknown target_country: EU , set to default
09-09 14:53:17.694  1031  1524 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 14:53:17.694  1031  1524 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 14:53:17.694  1031  1524 I WifiUtil: gEnableBmps=1
09-09 14:53:17.751  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:17.770  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-09 14:53:17.782  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:17.786  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:17.788  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:17.790  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-09 14:53:17.799  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:17.802  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:17.803  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:17.805  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:53:17.813  6456  6904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 14:53:17.826  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 14:53:17.834  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 14:53:17.858  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:17.889  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:17.938  1031  2037 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7077 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 14:53:17.946  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:17.947  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 14:53:18.022  7077  7077 I AppUp4:AppBoxCP: onCreate
09-09 14:53:18.023  7077  7077 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 14:53:18.035  7077  7077 I AppUp4:DB:  setFingerPrint start
09-09 14:53:18.035  7077  7077 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-09 14:53:18.044  7077  7077 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-09 14:53:18.044  7077  7077 I AppUp4:DB:  SDK version = 21
,09-09 14:53:18.044  7077  7077 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 14:53:18.047  7077  7077 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 14:53:18.048  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:53:18.049  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:18.051  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:53:18.051  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 14:53:18.058  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 14:53:18.100  7077  7077 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:18.100  7077  7077 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:18.109  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bbbc7ee
,09-09 14:53:18.109  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:53:18.109  7077  7077 D AppUp4:CustFacade: isPhone : true
09-09 14:53:18.111  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:53:18.112  7077  7077 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 14:53:18.112  7077  7077 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 14:53:18.115  7077  7097 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 14:53:18.115  7077  7097 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 14:53:18.115  7077  7097 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 14:53:18.117  1031  1901 I ActivityManager: Killing 2116:com.lge.music/u0a34 (adj 15): empty #17
09-09 14:53:18.139   314  1364 V AudioFlinger: 2116 died, releasing its sessions
09-09 14:53:18.139   314  1364 V AudioFlinger:  pid 1840 @ 0
09-09 14:53:18.139   314  1364 V AudioFlinger:  pid 3407 @ 1
09-09 14:53:18.139   314  1364 V AudioFlinger:  pid 3407 @ 2
,09-09 14:53:18.167  1031  1926 W libprocessgroup: failed to open /acct/uid_10034/pid_2116/cgroup.procs: No such file or directory
,09-09 14:53:18.170  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:18.171  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:18.175  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:18.179  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:53:18.190  4275  7101 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:18.196  4275  7102 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:18.197  4275  7102 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 14:53:18.271  1031  1942 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7111 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 14:53:18.336  7111  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:53:18.336  7111  7111 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:53:18.338  7111  7111 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 14:53:18.339  7111  7111 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 14:53:18.428  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:53:18.428  1031  1102 D Tethering: InitialState.processMessage what=4
,09-09 14:53:18.429  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:53:18.438   310   875 D SoftapController: Softap fwReload - Ok
09-09 14:53:18.446  1031  1524 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (745ms)
09-09 14:53:18.450   310   875 D CommandListener: Setting iface cfg
09-09 14:53:18.450   310   875 D CommandListener: Trying to bring down wlan0
09-09 14:53:18.450   310   875 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:53:18.452  1031  1524 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-09 14:53:18.455  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:18.455  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:18.455  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:53:18.454  7130  7130 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:18.454  7130  7130 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:18.459  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 14:53:18.460  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:18.462  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:18.462  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:18.475  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 14:53:18.477  1031  1524 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 14:53:18.477  1031  1524 D WifiMonitor: connecting to supplicant
09-09 14:53:18.482  7130  7130 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 14:53:18.483  7111  7111 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 14:53:18.498  7111  7111 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-09 14:53:18.517  7130  7130 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 14:53:18.517  7130  7130 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-09 14:53:18.538  7111  7111 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 14:53:18.573  7111  7111 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:18.574  7111  7111 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:18.618  7130  7130 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 14:53:18.678  7130  7130 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 14:53:18.689  7130  7130 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 14:53:18.691  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:53:18.691  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 14:53:18.691  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,09-09 14:53:18.692  1031  1524 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:53:18.692  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:18.693  1031  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:18.693  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 14:53:18.693  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 14:53:18.693  1031  1524 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 14:53:18.693  1031  1524 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 14:53:18.693  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:53:18.693  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:53:18.694  1031  1524 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 14:53:18.694  1031  1524 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 14:53:18.695  1031  1524 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-09 14:53:18.696  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:18.696  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:18.696  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:18.696  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:18.696  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:18.696  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:18.696  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:18.696  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:53:18.700  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,09-09 14:53:18.700  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 14:53:18.701  1031  1524 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 14:53:18.701  1031  1524 D WifiNative-wlan0: SET update_config 1: returned true
,09-09 14:53:18.701  1031  1524 D WifiConfigStore: Loading config and enabling all networks 
09-09 14:53:18.701  1031  1524 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 14:53:18.702  1031  1524 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-09 14:53:18.706  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:18.706  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:18.706  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:18.706  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:53:18.706  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-09 14:53:18.707  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:18.708  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:18.708  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:18.708  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:18.708  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:18.709  1031  1524 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-09 14:53:18.716  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:53:18.718  1031  1524 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 14:53:18.719  1031  1524 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 14:53:18.720  1031  1524 D WifiStateMachine: enableVerboseLogging : level 2
09-09 14:53:18.720  1031  1524 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 14:53:18.721  1031  1524 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 14:53:18.721  1031  1524 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 14:53:18.721  1031  1524 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 14:53:18.721  1031  1524 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 14:53:18.721  1031  1524 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 14:53:18.722  1031  1524 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 14:53:18.722  1031  1524 D WifiNative-wlan0: SET model_number LG-D855: returned true
,09-09 14:53:18.722  1031  1524 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 14:53:18.723  1031  1524 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 14:53:18.723  1031  1524 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 14:53:18.723  1031  1524 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 14:53:18.723  1031  1524 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 14:53:18.724  1031  1524 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 14:53:18.725  1031  1524 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:53:18.726  1031  1524 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 14:53:18.726  1031  1524 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 14:53:18.726  1031  1524 D WifiNative-HAL: Setting external_sim to 1
09-09 14:53:18.726  1031  1524 D WifiNative-wlan0: doBoolean: SET external_sim 1
,09-09 14:53:18.727  1031  1524 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 14:53:18.727  1031  1524 I WifiNative-HAL: startHal
09-09 14:53:18.727  1031  1524 D wifi    : setting scan oui 0xaf6bd040
09-09 14:53:18.727  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-09 14:53:18.727  1031  1524 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:53:18.727  1031  1524 I WifiNative-HAL: startHal
09-09 14:53:18.727  1031  1524 D wifi    : setting scan oui 0xaf6bd040
09-09 14:53:18.727  1927  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 14:53:18.727  1927  2345 D WfdsService: Set the WFDS Monitor: true
09-09 14:53:18.727  1927  2345 D WfdsMonitor: WfdsMonitorThread create
09-09 14:53:18.727  1031  1524 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 14:53:18.728  1927  2345 D WfdsMonitor: WFDS Monitor is created and started
09-09 14:53:18.728  1927  2345 D WfdsService: WiFi: Supplicant connection re-established
09-09 14:53:18.728  1031  1524 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 14:53:18.728  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 14:53:18.728  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 14:53:18.729  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 14:53:18.729  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:53:18.729  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:53:18.730  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:53:18.730  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 14:53:18.730  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 14:53:18.730  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 14:53:18.730  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:53:18.730  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:53:18.731  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:53:18.731  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:53:18.731  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:53:18.731  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:53:18.731  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 14:53:18.732  7130  7130 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 14:53:18.732  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 14:53:18.732  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:53:18.732  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:53:18.733  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:53:18.733  1031  1524 E WifiNative: : [215,974,479 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 14:53:18.734  1031  1524 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 14:53:18.734  1031  1524 D WifiNative-wlan0: RECONNECT: returned true
09-09 14:53:18.734  1927  7141 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 14:53:18.734  1031  1524 D WifiNative-wlan0: doString: [STATUS]
09-09 14:53:18.734  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:53:18.734  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 14:53:18.736  1031  1524 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:53:18.736  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:18.736  1927  7141 E CtrlSupplicant: Succeed to open contr,ol connection
09-09 14:53:18.736  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:18.737  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.737  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 14:53:18.737  1031  1031 D RttService: SCAN_AVAILABLE : 3
09-09 14:53:18.737  1031  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.737  1031  1542 I WifiNative-HAL: startHal
09-09 14:53:18.737  1031  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6bd040
09-09 14:53:18.737  1031  1542 D wifi    : failed to get capabilities : -3
09-09 14:53:18.737  1031  1542 E WifiScanningService: could not get scan capabilities
09-09 14:53:18.738  1031  1543 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.738  1031  1524 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:53:18.738  1031  1524 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 14:53:18.738  1031  1524 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 14:53:18.739  1031  1524 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 14:53:18.739  1031  1524 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 14:53:18.739  1031  1524 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 14:53:18.740  1031  1524 E WifiStateMachine:  DriverStartedState what:132106 1 0
,09-09 14:53:18.740  1031  1524 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 14:53:18.740  7130  7130 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 14:53:18.740  1031  1524 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 14:53:18.741  1031  1524 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 14:53:18.741  1031  1524 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 14:53:18.741  1031  1524 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 14:53:18.741  7130  7130 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 14:53:18.742  1031  1524 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 14:53:18.742  1031  1524 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 14:53:18.742  1031  1524 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
,09-09 14:53:18.742  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 14:53:18.743   310   875 D CommandListener: Setting iface cfg
09-09 14:53:18.743  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:53:18.743  1927  7141 E CtrlSupplicant: Succeed to open monitor connection
09-09 14:53:18.744  7130  7130 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.744   310   875 D CommandListener: Trying to bring up p2p0
09-09 14:53:18.745  7130  7130 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:53:18.745  1031  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,09-09 14:53:18.745  7130  7130 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.745  1031  1521 D LGWifiP2pService: P2pEnablingState
09-09 14:53:18.745  1031  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:53:18.745  1031  1521 D LGWifiP2pService: P2p socket connection successful
09-09 14:53:18.745  1031  1521 D LGWifiP2pService: P2pEnabledState
09-09 14:53:18.746  7130  7130 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.746  1031  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 14:53:18.747  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:53:18.747  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.747  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.747  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.747  1031  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-09 14:53:18.747  1031  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.747  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.747  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.747  1031  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.747  1031  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.747  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.747  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.747  1927  7141 D WfdsMonitor: Supplicant connection established
09-09 14:53:18.747  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 14:53:18.747  1927  1927 D WfdsService: WifiP2pState is changed : true
,09-09 14:53:18.747  1031  1524 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 14:53:18.747  1927  2345 D WfdsService: Connected to the supplicant for wfds
09-09 14:53:18.748  1927  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 14:53:18.748  1927  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.748  7130  7130 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 14:53:18.748  1927  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.748  1031  1524 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:53:18.748  1927  2345 D WfdsService: selectPreferredScanChannel [36]
09-09 14:53:18.748  1927  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 14:53:18.748  1927  2345 D WfdsService: DefaultState - WFDS_ENABLE(DISABLE)
09-09 14:53:18.748  1031  1524 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-09 14:53:18.748  1031  1524 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:53:18.748  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 14:53:18.748  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 14:53:18.749  7130  7130 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:18.749  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 14:53:18.749  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:18.749  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:18.749  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:18.750  1031  1524 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 14:53:18.750  1031  1524 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 14:53:18.751  1031  1524 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,09-09 14:53:18.751  1031  1524 D WifiNative-wlan0: doBoolean: SCAN
09-09 14:53:18.751  1031  1524 D WifiNative-wlan0: SCAN: returned false
09-09 14:53:18.751  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=215993  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:53:18.752  7111  7111 I HubEmail: JNI_OnLoad()
09-09 14:53:18.752  7111  7111 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 14:53:18.752  7111  7111 I HubEmail: registerNatives()
09-09 14:53:18.752  7111  7111 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 14:53:18.752  7111  7111 I HubEmail: registerNativeMethods()
09-09 14:53:18.752  7111  7111 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 14:53:18.753  7111  7111 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 14:53:18.754  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,09-09 14:53:18.754  1927  1927 D WfdsService: isConnected: false
09-09 14:53:18.756  1031  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 14:53:18.757  1031  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 14:53:18.757  1031  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 14:53:18.758  1031  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-09 14:53:18.758  1031  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 14:53:18.758  1031  1521 D LGWifiP2pService: before postfix = G3
09-09 14:53:18.758  1031  1521 D WifiServerServiceExt: postfix byte check : 2
09-09 14:53:18.758  1031  1521 D LGWifiP2pService: after postfix = G3
09-09 14:53:18.758  1031  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-09 14:53:18.758  1031  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 14:53:18.758  1031  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 14:53:18.759  1031  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 14:53:18.759  1031  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 14:53:18.759  1031  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 14:53:18.759  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,09-09 14:53:18.760  1031  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 14:53:18.760  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-09 14:53:18.760  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,09-09 14:53:18.760  1031  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 14:53:18.760  1031  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 14:53:18.761  1031  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
,09-09 14:53:18.761  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 14:53:18.761  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=216002  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:53:18.761  1031  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 14:53:18.761  1031  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 14:53:18.761  1031  1524 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:18.762  1031  1524 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:18.762  1031  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 14:53:18.762  1031  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 14:53:18.762  1031  1524 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:18.762  1031  1524 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:18.762  1031  1524 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:18.763  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 14:53:18.764  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 14:53:18.764  1927  1927 D WfdsService: Update P2p Interface State: 3
09-09 14:53:18.767  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:18.767  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:18.767  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:18.769  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:18.769  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:18.769  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:53:18.769  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:18.769  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 14:53:18.769  1031  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 14:53:18.769  1031  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 14:53:18.770  1031  1521 D LGWifiP2pService: InactiveState
09-09 14:53:18.770  1031  1521 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.770  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.770  1031  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 14:53:18.770  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:53:18.770  7130  7130 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.771  1031  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:53:18.771  1031  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.771  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.771  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:18.771  7130  7130 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:53:18.771  1927  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE ,init=USER type=COUNTRY alpha2=CZ]
09-09 14:53:18.771  7130  7130 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.771  1927  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.771  1031  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.771  1031  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.771  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.771  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.771  1031  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 14:53:18.771  1031  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  7130  7130 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.772  1927  7141 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.772  1031  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:18.772  1031  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.772  1031  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.772  1031  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.772  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1031  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:18.773  1927  2345 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 14:53:18.773  1031  1031 E WifiServerServiceExt: No p2p device connected
09-09 14:53:18.774  7111  7143 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:53:18.782  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:53:18.782  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:18.782  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 14:53:18.782  6980  7145 W FormManager: Network not available. Please check & try again.
09-09 14:53:18.821  1031  1942 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7148 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-09 14:53:18.827  6980  7146 V FormManager: Network unavailable.
09-09 14:53:18.831  6980  7146 V FormManager: Network unavailable.
09-09 14:53:18.841  1031  1963 I ActivityManager: Killing 6069:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-09 14:53:18.903  1031  1047 W libprocessgroup: failed to open /acct/uid_10080/pid_6069/cgroup.procs: No such file or directory
09-09 14:53:18.980  7148  7148 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:18.980  7148  7148 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:18.984  7148  7148 D PhoneMonitor: Register our PhoneStateListener
09-09 14:53:19.007  7148  7148 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 14:53:19.012  7148  7148 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 14:53:19.051  7148  7148 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 14:53:19.053  7148  7148 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-09 14:53:19.054  7148  7148 D TelephonyAutoProfiling: [parse] Load xml
09-09 14:53:19.062  7148  7148 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 14:53:19.062  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-09 14:53:19.062  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 14:53:19.063  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
,09-09 14:53:19.064  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 14:53:19.064  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 14:53:19.064  7148  7148 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 14:53:19.064  7148  7148 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 14:53:19.079  7148  7148 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 14:53:19.079  1031  1942 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7170 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:53:19.080  1031  1942 I ActivityManager: Killing 6579:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-09 14:53:19.137  1031  2036 W libprocessgroup: failed to open /acct/uid_10061/pid_6579/cgroup.procs: No such file or directory
,09-09 14:53:19.381  7130  7130 E wpa_supplicant: USIM:  scard_init function
09-09 14:53:19.381  7130  7130 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 14:53:19.383  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 14:53:19.383  1031  7140 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 14:53:19.383  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 14:53:19.383  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-09 14:53:19.383  1031  7140 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 14:53:19.383  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:53:19.383  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-09 14:53:19.386  1031  1524 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 14:53:19.387  1031  1524 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 14:53:19.387  1031  1524 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 14:53:19.387  1031  1524 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-09 14:53:19.387  1031  1524 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 14:53:19.389  1031  1769 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7191 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 14:53:19.396  1031  1769 I ActivityManager: Killing 6089:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-09 14:53:19.456  1031  1926 W libprocessgroup: failed to open /acct/uid_10097/pid_6089/cgroup.procs: No such file or directory
,09-09 14:53:19.457  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=216698  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 14:53:19.468  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=216709  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 14:53:19.476  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.476  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.478  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.479  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.479  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.479  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:53:19.480  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.480  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.480  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:53:19.480  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:19.480  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 14:53:19.501  7130  7130 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 14:53:19.506  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 14:53:19.506  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 14:53:19.506  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 14:53:19.506  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 14:53:19.506  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:19.507  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=216748  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:53:19.508  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:19.509  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 14:53:19.510  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=216751  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:53:19.511  7130  7130 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:53:19.512  7130  7130 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:53:19.513  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:19.513  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:19.513  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.514  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.514  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 14:53:19.514  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 14:53:19.514  1031  7140 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:53:19.515  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 14:53:19.516  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:53:19.516  1031  7140 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:53:19.516  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:19.516  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:19.516  1031  1524 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216758
09-09 14:53:19.517  1031  1524 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216758
09-09 14:53:19.517  1031  1524 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216759
09-09 14:53:19.518  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216759
09-09 14:53:19.518  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.521  1031  1524 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=216762
09-09 14:53:19.522  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=216763  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 14:53:19.525  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.525  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:53:19.526  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:53:19.526  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=216767  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 14:53:19.527  1031  1524 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:19.527  1031  1524 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:19.527  1031  1524 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:19.528  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:19.528  1031  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:19.532  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.532  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.533  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 14:53:19.534  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:19.534  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 14:53:19.534  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=216775  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:53:19.534  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=216776  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:53:19.535  1031  1524 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216776
09-09 14:53:19.536  1031  1524 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216777
09-09 14:53:19.536  1031  1524 D WifiNative-wlan0: doString: [STATUS]
09-09 14:53:19.537  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:19.537  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:19.537  1031  1524 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:53:19.539  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.539  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.539  1031  1524 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 14:53:19.541  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:19.546  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.546  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.548  1031  1524 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 14:53:19.548  1031  1524 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 14:53:19.549  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.557  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:53:19.557  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.557  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:53:19.562  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.562  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.563  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:53:19.565  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.565  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.566  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.568  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.568  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.569  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.572  1031  1524 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 14:53:19.572  1031  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:53:19.572  1031  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:53:19.572  1031  1531 D ConnectivityService: Got NetworkAgent Messenger
09-09 14:53:19.572  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 14:53:19.572  1031  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:53:19.572  1031  1531 D ConnectivityService: NetworkAgent connected
09-09 14:53:19.572  1031  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 14:53:19.578  1031  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:53:19.578  1031  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:53:19.578  1031  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:53:19.579  1031  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:53:19.579  1031  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:53:19.584  1031  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:53:19.586   310   875 D CommandListener: Setting iface cfg
,09-09 14:53:19.614  1031  1999 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7221 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 14:53:19.616  1031  1999 I ActivityManager: Killing 6617:com.lge.eula/1000 (adj 15): empty #17
09-09 14:53:19.656  1031  1524 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 14:53:19.656  1031  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-09 14:53:19.657  1031  7219 D DhcpStateMachine: StoppedState
09-09 14:53:19.657  1031  7219 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.657  1031  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:19.658  1031  7219 D DhcpStateMachine: WaitBeforeStartState
09-09 14:53:19.658  1031  1963 W libprocessgroup: failed to open /acct/uid_1000/pid_6617/cgroup.procs: No such file or directory
09-09 14:53:19.658  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:19.666  1031  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=216907  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:19.667  1031  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=216909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-09 14:53:19.670  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=216910  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:19.673  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:161713] from screen [on:0 period:251817145] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 14:53:19.676  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:251817148] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 14:53:19.676  1031  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 14:53:19.683  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 14:53:19.683  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:19.683  1031  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:19.684  1031  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:19.684  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:19.684  1031  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 14:53:19.684  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:19.685  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
09-09 14:53:19.686  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=125,0,0
09-09 14:53:19.686  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 14:53:19.686  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 14:53:19.686  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 14:53:19.686  1031  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 14:53:19.687  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 14:53:19.687  1031  1524 D WifiNative-wlan0: SET ps 0: returned true
09-09 14:53:19.687  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 14:53:19.687  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 14:53:19.687  7221  7221 I art     : Almond Protected OAT
09-09 14:53:19.687  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 14:53:19.688  1031  1524 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 14:53:19.688  1031  1524 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:53:19.688  1031  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7b49c2d target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.688  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7b49c2d target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.688  1031  1524 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:53:19.688  1031  7219 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.688  1031  7219 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 14:53:19.689   310   875 D CommandListener: Setting iface cfg
09-09 14:53:19.690   310   875 D CommandListener: Trying to bring up wlan0
09-09 14:53:19.690  1031  1524 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 14:53:19.691  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 14:53:19.691  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 14:53:19.691  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:53:19.691  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.692  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.692  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:53:19.692  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:53:19.692  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 14:53:19.692  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 14:53:19.692  1031  1524 ,D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 14:53:19.693  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:19.712  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:19.712  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 14:53:19.713  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:19.714  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.714  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:19.714  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-09 14:53:19.714  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:19.714  1031  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:19.715  1031  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:19.716  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:19.716  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:19.717  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 14:53:19.717  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:53:19.718  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:53:19.718  1031  1524 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 14:53:19.719  1031  1531 D ConnectivityService: ignoring duplicate network state non-change
09-09 14:53:19.722  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.722  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.722  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:53:19.722  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.722  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.725  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 14:53:19.726  1031  1531 D ConnectivityService: Adding iface wlan0 to network 101
09-09 14:53:19.728  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.729  1031  1524 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 14:53:19.733  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 14:53:19.737  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.737  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.737  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:53:19.738  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:53:19.738  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.738  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.738  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:53:19.738  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:53:19.738  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.738  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:19.738  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-09 14:53:19.748  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.748  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.748  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.748  1031  1521 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.748  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:19.748  7221  7221 D WeatherApplication: removeAccount
09-09 14:53:19.749  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.749  7221  7221 D WeatherApplication: Account.length = 0
09-09 14:53:19.749  7221  7221 E WeatherApplication: OPERATOR:OPEN
09-09 14:53:19.751  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.751  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:53:19.751  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.753  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:19
09-09 14:53:19.755  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-09 14:53:19.755  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:53:19.756  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:53:19.756  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:19.757  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:53:19.757  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.757  1031  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:53:19.757  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:53:19.758  1031  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:53:19.758  1031  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:53:19.758  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:53:19.759  1031  1524 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 14:53:19.759  7221  7221 D WeatherAncestor: connectivity changed - connection : true
09-09 14:53:19.759  1031  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 14:53:19.759  1031  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 14:53:19.759  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-09 14:53:19.760  1031  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 14:53:19.761   310   875 E Netd    : netlink response contains error (File exists)
09-09 14:53:19.761  1031  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 14:53:19.763  1031  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 14:53:19.763  1031  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 14:53:19.763  1031  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 14:53:19.764  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 14:53:19.764  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.764  1031  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.764  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.764  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.764  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 14:53:19.764  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:19.764  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 14:53:19.764  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:19.764  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:19.764  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:53:19.764  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.765  1031  1531 D ConnectivityService:     satisfied: Netwo,rkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 14:53:19.765  1031  1531 D ConnectivityService: currentScore = 0, newScore = 20
09-09 14:53:19.765  1031  1531 D ConnectivityService:    accepting network in place of null
09-09 14:53:19.765  1031  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.766  1031  1524 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.766  1031  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:19.766  1031  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 14:53:19.766  1031  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 14:53:19.767  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:53:19.767  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:19.768   310  7242 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 14:53:19.768  1031  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 14:53:19.769  1031  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-09 14:53:19.769  1840  1840 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.769  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:53:19.770  1031  1531 D ConnectivityService: validation of new default Network = false
09-09 14:53:19.770  1031  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 14:53:19.770  1031  1531 D DSQN    : enableDataServiceNotify 
09-09 14:53:19.770  1031  1531 D DSQN    : start dsqn bin
09-09 14:53:19.771  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1,
09-09 14:53:19.771  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:53:19.771  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:53:19.771  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:53:19.774  7244  7244 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:19.774  7244  7244 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:19.778  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:53:19.778  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:53:19.778  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.778  7221  7221 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-09 14:53:19.778  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.778  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:19.778  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:19.779  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 14:53:19.790  7244  7244 E DSQN    : DSQN ssw
,09-09 14:53:19.794  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:53:19.794  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:19
,09-09 14:53:19.817   310  7242 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 14:53:19.830  1031  1722 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7249 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 14:53:19.831  1031  1722 I ActivityManager: Killing 6637:com.lge.bnr/1000 (adj 15): empty #17
09-09 14:53:19.850   310  7242 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 14:53:19.867  1031  1726 W libprocessgroup: failed to open /acct/uid_1000/pid_6637/cgroup.procs: No such file or directory
,09-09 14:53:19.876  1805  7248 I CheckinService: active receiver: enabled
09-09 14:53:19.879   310   874 D LGDataListener: argv[0]=dsqncommand
09-09 14:53:19.879   310   874 D LGDataListener: argv[1]=wlan0
09-09 14:53:19.879   310   874 D LGDataListener: argv[2]=1
09-09 14:53:19.879   310   874 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 14:53:19.880  1031  1100 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 14:53:19.880  1031  1100 D DSQN    : start to monitor internet connection
09-09 14:53:19.890  1031  7219 D DhcpStateMachine: DHCPV4 request on wlan0
,09-09 14:53:19.891  1031  7219 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 14:53:19.891  1031  7219 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 14:53:19.884  7268  7268 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:19.884  7268  7268 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:19.896  1805  7248 I CheckinService: Preparing to send checkin request
09-09 14:53:19.896  1805  7248 I EventLogService: Accumulating logs since 1473425439416
09-09 14:53:19.898  1031  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 14:53:19.900  7268  7268 I dhcpcd  : version 5.5.6 starting
09-09 14:53:19.901  7268  7268 E dhcpcd  : get_duid: m
09-09 14:53:19.901  7268  7268 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 14:53:19.901  7268  7268 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-09 14:53:19.903  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:53:19 GMT], X-Android-Received-Millis=[1473425599903], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473425599878]}
09-09 14:53:19.904  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 14:53:19.904  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 14:53:19.904  1031  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.904  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.904  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:19.904  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:19.904  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:53:19.904  1031  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 14:53:19.904  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 14:53:19.904  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.904  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:19.905  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:19.905  1031  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.905  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 14:53:19.905  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:53:19.907  1840  1840 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.907  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:53:19.908  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:19.909  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.909  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.913  1031  1524 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:19.913  1031  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 14:53:19.921  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:19.922  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.922  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:19.936  1805  7248 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 14:53:19.970  7268  7268 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:53:19.970  7268  7268 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-09 14:53:19.970  7268  7268 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:53:19.970  7268  7268 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,09-09 14:53:19.971  7268  7268 D dhcpcd  : wlan0: sending REQUEST (xid 0xab3aa545), next in 4.64 seconds
09-09 14:53:19.993   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 14:53:19.993   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 14:53:19.993   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:53:19.993  7249  7277 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 14:53:19.995   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 14:53:19.995   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 14:53:19.995   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:53:19.995  7249  7277 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 14:53:20.004  7268  7268 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-09 14:53:20.007   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 14:53:20.007   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 14:53:20.007   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:53:20.008  7249  7281 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 14:53:20.010   278   440 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 14:53:20.010   278   440 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 14:53:20.010   278   440 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 14:53:20.011  7249  7281 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 14:53:20.017  7268  7268 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 14:53:20.017  7268  7268 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 14:53:20.017  7268  7268 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 14:53:20.017  7268  7268 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 14:53:20.018  7268  7268 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:53:20.018  7268  7268 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:53:20.018  7268  7268 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:53:20.018  7268  7268 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 14:53:20.020  1031  1942 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7282 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-09 14:53:20.061  7282  7282 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 14:53:20.061  7282  7282 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 14:53:20.082  7282  7282 I MultiDex: VM with version 2.1.0 has multidex support
09-09 14:53:20.082  7282  7282 I MultiDex: install
09-09 14:53:20.082  7282  7282 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 14:53:20.089  7282  7282 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-09 14:53:20.219  7249  7249 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 14:53:20.227  7249  7249 I LibraryLoader: Loading: webviewchromium
09-09 14:53:20.230  7249  7249 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7481-7485)
09-09 14:53:20.230  7249  7249 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 14:53:20.236  7249  7249 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dcec811}
09-09 14:53:20.239  7249  7249 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 14:53:20.239  7249  7249 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 14:53:20.255  7249  7249 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 14:53:20.257  7249  7249 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 14:53:20.267  7249  7249 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-09 14:53:20.268  7249  7249 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 14:53:20.269  7249  7249 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-09 14:53:20.273   314  1703 V AudioPolicyService: registerClient() client 0xb102bdc0, uid 10093
09-09 14:53:20.274  7249  7339 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 14:53:20.283  7249  7249 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:53:20.283  7249  7249 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:53:20.283  7249  7249 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:53:20.283  7249  7249 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:53:20.283  7249  7249 I Adreno-EGL: Remote Branch: 
09-09 14:53:20.283  7249  7249 I Adreno-EGL: Local Patches: 
09-09 14:53:20.283  7249  7249 I Adreno-EGL: Reconstruct Branch: 
,09-09 14:53:20.295  1031  7219 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 14:53:20.299  1031  7219 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 14:53:20.300  1031  7219 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:53:20.300  1031  7219 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 14:53:20.301  1031  7219 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 14:53:20.301  1031  7219 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:53:20.301  1031  7219 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 14:53:20.301  1031  7219 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 14:53:20.301  1031  7219 D DhcpStateMachine: RunningState
,09-09 14:53:20.418  7349  7349 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 14:53:20.459  7349  7349 I dex2oat : dex2oat took 40.792ms (threads: 4)
,09-09 14:53:20.470  7282  7299 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:53:20.470  7282  7299 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:53:20.470  7282  7299 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:53:20.470  7282  7299 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:53:20.470  7282  7299 I Adreno-EGL: Remote Branch: 
09-09 14:53:20.470  7282  7299 I Adreno-EGL: Local Patches: 
09-09 14:53:20.470  7282  7299 I Adreno-EGL: Reconstruct Branch: 
09-09 14:53:20.470  1031  1726 I art     : Explicit concurrent mark sweep GC freed 105229(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.211ms total 141.682ms
09-09 14:53:20.486  7249  7249 I NSApplication: Starting up...
,09-09 14:53:20.545  1031  1047 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7359 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 14:53:20.546  1031  1047 I ActivityManager: Killing 6030:com.android.vending/u0a44 (adj 15): empty #17
,09-09 14:53:20.567   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 22.791ms
,09-09 14:53:20.588   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 19.793ms
,09-09 14:53:20.599  7282  7299 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:20.599  7282  7299 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:20.608   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 19.417ms
,09-09 14:53:20.625  1031  1901 W libprocessgroup: failed to open /acct/uid_10044/pid_6030/cgroup.procs: No such file or directory
,09-09 14:53:20.674  7359  7359 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:53:20.694  1031  2036 D WifiServiceImplEx: setWifiEnabled: false pid=6745, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-09 14:53:20.694  1031  2036 D WifiService: setWifiEnabled: false pid=6745, uid=10118
09-09 14:53:20.694  1031  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:53:20.713  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:20.713  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:20.713  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-09 14:53:20.715  1031  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:20.715  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,09-09 14:53:20.715  1031  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:20.715  1031  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:20.715  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 14:53:20.716  1031  1524 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 14:53:20.716  1031  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:53:20.716  1031  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:53:20.716  1031  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:53:20.716  1031  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:53:20.722  7282  7299 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:53:20.722  7282  7299 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:53:20.722  7282  7299 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:53:20.722  7282  7299 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:53:20.722  7282  7299 I Adreno-EGL: Remote Branch: 
09-09 14:53:20.722  7282  7299 I Adreno-EGL: Local Patches: 
09-09 14:53:20.722  7282  7299 I Adreno-EGL: Reconstruct Branch: 
09-09 14:53:20.724  1031  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:53:20.724  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:53:20.724  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:53:20.725  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:53:20.725  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:20.725  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:20.725  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.725  1031  7219 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.725   310   875 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:53:20.755  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:53:20.766  7282  7299 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 14:53:20.766  7282  7299 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 14:53:20.766  7282  7299 I Adreno-EGL: Build Date: 12/12/14 금
09-09 14:53:20.766  7282  7299 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 14:53:20.766  7282  7299 I Adreno-EGL: Remote Branch: 
09-09 14:53:20.766  7282  7299 I Adreno-EGL: Local Patches: 
09-09 14:53:20.766  7282  7299 I Adreno-EGL: Reconstruct Branch: 
09-09 14:53:20.778  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:20.778  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:20.778  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:20.779  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,09-09 14:53:20.779  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:20.779  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:20.779  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 14:53:20.780  1031  1531 D ConnectivityService: ignoring duplicate network state non-change
09-09 14:53:20.780  1031  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.780  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.780  1031  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1adb963c
09-09 14:53:20.781  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-09 14:53:20.781  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 14:53:20.782  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.782  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.782  1031  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-09 14:53:20.782  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:20.782  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-09 14:53:20.782  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-09 14:53:20.783  1031  1524 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 14:53:20.797  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.797  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.797  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:20.797  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 14:53:20.797  1031  1031 D RttService: SCAN_AVAILABLE : 1
,09-09 14:53:20.799  1031  1521 D LGWifiP2pService: P2pDisablingState
09-09 14:53:20.799  1031  1521 D LGWifiP2pService: P2pDisablingState{ when=-19ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.799  1031  1521 D LGWifiP2pService: p2p socket connection lost
09-09 14:53:20.800  1031  1521 D LGWifiP2pService: P2pDisabledState
09-09 14:53:20.800  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:20.800  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:20.801  1031  1542 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.801  1031  1543 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.802  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:53:20.802  1927  1927 D WfdsService: WifiP2pState is changed : false
09-09 14:53:20.802  1927  2345 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 14:53:20.802  1927  2345 D WfdsService: Set the WFDS Monitor: false
09-09 14:53:20.803  1927  2345 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:53:20.803  1927  2345 D WfdsService: STATE : WfdsDisabledState - enter
09-09 14:53:20.803  1927  7141 D CtrlSupplicant: Received on exit socket, terminate
09-09 14:53:20.803  1927  7141 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 14:53:20.803  1927  2347 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 14:53:20.803  1927  7141 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 14:53:20.803  1927  7141 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 14:53:20.803  1927  2345 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 14:53:20.804  1031  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 14:53:20.805  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.806  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.806  1031  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.806  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:53:20.806  7130  7130 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:53:20.807  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:20.807  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:20.808  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:53:20.808  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:20.808  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.810  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
,09-09 14:53:20.824   310   875 D CommandListener: Clearing all IP addresses on wlan0
,09-09 14:53:20.824  1031  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 14:53:20.824  1031  1531 D DSQN    : disableDataServiceNotify
09-09 14:53:20.824  1031  1531 D DSQN    : stop dsqn bin
09-09 14:53:20.825   310  7385 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 14:53:20.827  1805  7248 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-09 14:53:20.827  1031  1100 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 14:53:20.829  1031  1524 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 14:53:20.829  1031  1524 D WifiNative-p2p0: TERMINATE: returned true
09-09 14:53:20.829  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:20.829  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:20.829  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:53:20.830  1031  1031 D WifiHS20: hidePasspointNotification off =false
09-09 14:53:20.830  1031  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 14:53:20.830  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:20.830  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:20.830  1031  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:20.830  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 14:53:20.831  1031  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 14:53:20.831  1031  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 14:53:20.831  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:53:20.831  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 14:53:20.831  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:20.831  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:53:20.831  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 14:53:20.831  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:20.831  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:20.832  1031  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:20.832  1031  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=,1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:20.832  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.832  1031  1531 D NetworkManagementService: Removing idletimer
09-09 14:53:20.832  1031  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.832  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.832  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.832  1031  7217 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 14:53:20.833  1840  1840 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:20.833  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:53:20.833  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:53:20.833  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.833  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:20.833  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:53:20.834  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.834  1031  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 14:53:20.835  1031  1524 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:20.835  1031  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:20.836  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-09 14:53:20.836  1031  1031 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 14:53:20.837  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 14:53:20.837  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:53:20.837  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:53:20.837  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:53:20.838  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:20.838  1031  1031 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 14:53:20.838  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:53:20.838  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:53:20.838  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:53:20.839  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:20.839  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:20.839  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:20.839  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:20.840  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:20.840  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:20.840  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement:, Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:20.841  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:20.844  1805  7248 I CheckinService: active receiver: disabled
,09-09 14:53:20.866  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:20.866  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.867  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.881  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:20.882  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.882  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:20.882  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:20.886  7130  7130 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 14:53:20.886  7130  7130 I wpa_supplicant: monitor socket send errors count : 1
09-09 14:53:20.886  7130  7130 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
09-09 14:53:20.887  1031  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 14:53:20.887  1031  7140 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 14:53:20.907  7130  7130 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 14:53:20.907  7130  7130 W wpa_supplicant: USIM:  scard_deinit function
09-09 14:53:20.908  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 14:53:20.908  1031  1102 D Tethering: InitialState.processMessage what=4
09-09 14:53:20.908  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:53:20.908  1031  7140 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 14:53:20.908  1031  7140 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 14:53:20.908  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:20.908  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:20.909  1031  1524 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=218150
09-09 14:53:20.909  1031  1524 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=218150
09-09 14:53:20.909  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:53:20.909  1031  1524 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=218151  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:53:20.910  1031  1524 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=218151  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 14:53:20.910  1031  1524 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:20.911  1031  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:20.911  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:53:20.912  6456  6904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:53:20.920  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:20.926  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:53:20.926  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:20.926  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:53:20.926  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 14:53:20.927  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:53:20.930  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bbbc7ee
09-09 14:53:20.930  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:53:20.930  7077  7077 D AppUp4:CustFacade: isPhone : true
09-09 14:53:20.930  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:53:20.930  7077  7077 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:53:20.932  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:20.932  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:20.933  1031  7219 D DhcpStateMachine: StoppedState
09-09 14:53:20.933  1031  7219 D DhcpStateMachine: StoppedState{ when=-123ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:20.933  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:20.933  1031  1524 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,09-09 14:53:20.934  1031  1524 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 14:53:20.935  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:20.938  4275  7392 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:20.940  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:53:20.945  4275  7393 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:20.945  4275  7393 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 14:53:20.955  7111  7397 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:20.960  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-09 14:53:20.960  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:20.960  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 14:53:20.962  7148  7148 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:53:20.962  7148  7148 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 14:53:20.968  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:20
09-09 14:53:20.970  6980  7400 W FormManager: Network not available. Please check & try again.
09-09 14:53:20.971  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:53:20.971  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:53:20.971  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:53:20.971  7221  7221 D WeatherAncestor: connectivity changed - connection : true
09-09 14:53:20.971  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3ac2431c
,09-09 14:53:20.972  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:53:20.972  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:53:20.973  6980  7401 V FormManager: Network unavailable.
09-09 14:53:20.973  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:53:20.973  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:53:20.973  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:20
09-09 14:53:20.978  6980  7401 V FormManager: Network unavailable.
09-09 14:53:20.986  7130  7130 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 14:53:20.987  1031  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 14:53:20.987  1031  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 14:53:20.987  1031  7140 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 14:53:20.988  1031  1524 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-09 14:53:20.991  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:53:20.992  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:53:20.992  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:53:20.992  6882  6882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:53:20.992  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:53:20.993  6882  6882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:53:20.993  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:53:20.993  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:53:20.993  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:53:20.993  6882  6882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:53:20.993  6882  6882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:53:20.999  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:21.002  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:53:21.005  6980  7403 W FormManager: Network not available. Please check & try again.
09-09 14:53:21.007  6980  7404 V FormManager: Network unavailable.
09-09 14:53:21.009  6980  7404 V FormManager: Network unavailable.
09-09 14:53:21.009  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.022  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:21.025  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:53:21.028  6980  7406 W FormManager: Network not available. Please check & try again.
09-09 14:53:21.030  6980  7407 V FormManager: Network unavailable.
09-09 14:53:21.031  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.034  6980  7407 V FormManager: Network unavailable.
,09-09 14:53:21.045  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:21.046  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:21.047  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:21.049  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:53:21.054  4275  7408 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:21.058  4275  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:21.058  4275  7409 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:53:21.094  1031  1942 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7410 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 14:53:21.095  1031  1524 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 14:53:21.095  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:21.095  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:21.095  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:53:21.098  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 14:53:21.098  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:21.098  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:21.098  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 14:53:21.098  1927  1927 D WfdsService: Supplicant Connection state is changed : false
09-09 14:53:21.098  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 14:53:21.098  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 14:53:21.099  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:21.099  1927  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 14:53:21.099  1927  2345 D WfdsService: Set the WFDS Monitor: false
,09-09 14:53:21.099  1927  2345 D WfdsMonitor: WFDS Monitor is stopped
09-09 14:53:21.099  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:21.099  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:21.099  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:53:21.179  7410  7410 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 14:53:21.179  7410  7410 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 14:53:21.184  7410  7410 V [BNRBootReceiver]: Boot Receiver Return
,09-09 14:53:21.184  7410  7410 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 14:53:21.190  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.199  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.204  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.229  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.229  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.232  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:53:21.236  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 14:53:21.241  6882  6882 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 14:53:21.247  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:53:21.257  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.268  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.281  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:21.282  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.286  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:53:21.293  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.315  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.332  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.355  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:21.356  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.359  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:21.372  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:53:21.388  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.396  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.406  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.407  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.407  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:53:21.415  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.428  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.437  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:53:21.446  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:21.447  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.448  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:21.453  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.465  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.476  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.486  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.487  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:53:21.488  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:21.496  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.509  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.520  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:53:21.532  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.533  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.534  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:53:21.547  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.568  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.578  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.589  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.590  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.597  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:53:21.605  6654  7051 D UEI.SmartControl: Internal timer expired: 4
09-09 14:53:21.605  6654  7051 D UEI.SmartControl: unbind internal service
09-09 14:53:21.606  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.616  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.624  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.635  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:21.635  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.636  6937  6937 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:21.645  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.654  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 14:53:21.665  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:21.665  1031  1530 D WifiService: New client listening to asynchronous messages
09-09 14:53:21.675  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.690  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.706  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.707  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.709  6937  6937 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 14:53:21.711  6937  6937 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 14:53:21.712  6937  6937 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-09 14:53:21.723  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.724  6654  7048 D serial_port: close(fd = 24)
09-09 14:53:21.728  6654  7048 I UEI.SmartControl: Serial port is closed.
,09-09 14:53:21.732  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 14:53:21.734  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:21.743  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.750  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.761  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.762  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.764  6937  6937 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-09 14:53:21.765  6937  6937 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 14:53:21.766  6937  6937 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 14:53:21.769  1031  1046 I ActivityManager: Killing 6860:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-09 14:53:21.858  1031  1769 W libprocessgroup: failed to open /acct/uid_10037/pid_6860/cgroup.procs: No such file or directory
,09-09 14:53:21.867  2199  2199 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-09 14:53:21.890  2199  2199 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-09 14:53:21.891  2199  2199 D c       : Getting all permits...
09-09 14:53:21.891  2199  2199 D a       : Opening database...
09-09 14:53:21.899  2199  2199 D a       : Opening database auth.proximity.permit_store...
09-09 14:53:21.900  2199  2199 D a       : Closing database...
09-09 14:53:21.910  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:53:21.914  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:53:21.914  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 14:53:21.914  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:21.917  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:21.924  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.930  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.931  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:53:21.933  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:53:21.936  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.940  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 14:53:21.940  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:53:21.940  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:21.943  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:21.950  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:21.957  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:21.959  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.961  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:53:21.964  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:21.969  6905  6905 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 14:53:21.969  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:53:21.969  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:21.975  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:21.983  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:53:21.994  6937  6937 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:21.994  6937  6937 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:21.997  6937  6937 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 14:53:22.010  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:22.016  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:53:22.026  6980  7435 W FormManager: Network not available. Please check & try again.
09-09 14:53:22.029  6980  7436 V FormManager: Network unavailable.
09-09 14:53:22.032  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:22.033  6980  7436 V FormManager: Network unavailable.
09-09 14:53:22.053  2199  2199 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 14:53:22.078  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 14:53:22.078  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:22.082  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:22.085  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:22.092  4275  7437 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 14:53:22.094  4275  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:22.095  4275  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:53:22.108  6905  6905 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 14:53:22.108  6905  6905 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 14:53:22.108  6905  6905 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:22.116  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 14:53:22.123  6980  7440 W FormManager: Network not available. Please check & try again.
09-09 14:53:22.124  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:22.131  6980  7441 V FormManager: Network unavailable.
09-09 14:53:22.141  6980  7441 V FormManager: Network unavailable.
,09-09 14:53:22.686  1031  1524 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:251820157] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:53:22.688  1031  1524 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:251820160] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 14:53:22.770  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:22.784  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-09 14:53:22.794  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:22.798  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:22.800  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:22.803  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:53:22.805  6456  6904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:53:22.820  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 14:53:22.843  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 14:53:22.870  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:53:22.870  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:22.870  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:53:22.870  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 14:53:22.876  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:53:22.880  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bbbc7ee
09-09 14:53:22.880  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:53:22.880  7077  7077 D AppUp4:CustFacade: isPhone : true
09-09 14:53:22.880  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:53:22.881  7077  7077 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:53:22.886  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:22.886  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:22.888  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:53:22.894  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:22.904  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 14:53:22.933  4275  7450 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 14:53:22.943  7111  7449 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:22.948  4275  7456 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:22.948  4275  7456 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 14:53:22.955  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:22.960  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:53:22.960  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:22.962  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 14:53:22.962  3407  3407 D PhoneState: setPdpRejectCasuse : false
,09-09 14:53:22.968  6980  7467 V FormManager: Network unavailable.
,09-09 14:53:22.968  6980  7465 W FormManager: Network not available. Please check & try again.
09-09 14:53:22.968  7148  7148 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:53:22.968  7148  7148 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 14:53:22.973  6980  7467 V FormManager: Network unavailable.
09-09 14:53:22.979  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:22
,09-09 14:53:22.980  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:53:22.980  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:53:22.981  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:53:22.981  7221  7221 D WeatherAncestor: connectivity changed - connection : true
09-09 14:53:22.981  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3ac2431c
09-09 14:53:22.983  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:53:22.983  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:53:22.983  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:53:22.983  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:53:22.983  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:22
09-09 14:53:23.717  1031  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:53:23.718  1031  1999 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-09 14:53:23.746  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:23.747  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:23.747  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:53:23.750  1031  1102 D BluetoothManagerService: Message: 1
09-09 14:53:23.750  1031  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-09 14:53:23.780  1031  1102 D BluetoothManagerService: Message: 20
09-09 14:53:23.780  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10154422:true
,09-09 14:53:23.783  7017  7017 D BluetoothAdapterState: make
09-09 14:53:23.788  7017  7017 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 14:53:23.788  7017  7017 I bluedroid-qcom: init
09-09 14:53:23.790  7017  7481 I BluetoothAdapterState: Entering OffState
09-09 14:53:23.790  7017  7017 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 14:53:23.790  7017  7017 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 14:53:23.790  7017  7017 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 14:53:23.790  7017  7017 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 14:53:23.790  7017  7017 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 14:53:23.792  7017  7017 I bluedroid-qcom: get_profile_interface socket
09-09 14:53:23.792  7017  7017 I bluedroid-qcom: get_profile_interface map_client
,09-09 14:53:23.797  7017  7485 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 14:53:23.800  7017  7485 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 14:53:23.794  7484  7484 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:23.794  7484  7484 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:23.812  7484  7484 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 14:53:23.812  7484  7484 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
,09-09 14:53:23.812  7484  7484 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-09 14:53:23.816  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:53:23.816  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:53:23.818  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 14:53:23.819  1031  1102 D BluetoothManagerService: Message: 40
09-09 14:53:23.819  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 14:53:23.819  7017  7035 I bluedroid-qcom: config_hci_snoop_log
09-09 14:53:23.821  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 14:53:23.821  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 14:53:23.822  7484  7484 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 14:53:23.829  7484  7484 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 14:53:23.829  7484  7484 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-09 14:53:23.834  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:23.836  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:23.836  7017  7481 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-09 14:53:23.845  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:23.849  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:23.858  1031  1102 D Tethering: MasterInitialState.processMessage what=3
09-09 14:53:23.858  1031  1102 D Tethering: MasterInitialState.processMessage what=3
,09-09 14:53:23.861  7017  7485 D BluetoothAdapterProperties: Name is: G3
09-09 14:53:23.862  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:23.863  7017  7481 D BluetoothAdapterProperties: Setting state to 11
09-09 14:53:23.864  7017  7481 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 14:53:23.865  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:23.865  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 14:53:23.865  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 14:53:23.866  7017  7481 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 14:53:23.872  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:23.878  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:23.887  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:53:23.892  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:23.898  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:53:23.900  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:23.900  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 14:53:23.901  7017  7481 D BluetoothBondStateMachine: make
,09-09 14:53:23.906  7017  7481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:23.906  7017  7481 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 14:53:23.906  7017  7481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:23.906  7017  7481 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 14:53:23.907  7017  7481 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 14:53:23.908  7017  7500 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 14:53:23.908  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 14:53:23.913  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:23.913  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:23.913  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:23.913  7017  7017 V BluetoothPbapReceiver: ***********state = 11
09-09 14:53:23.915  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:23.924  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 14:53:23.924  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:53:23.926  6456  6904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:53:23.931  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:53:23.932  7017  7017 D HeadsetService: Received start request. Starting profile...
09-09 14:53:23.933  7017  7017 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:53:23.933  7017  7017 D LGBluetoothHfpAdapter: Version 1.6
09-09 14:53:23.936  7017  7017 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:53:23.938  7017  7017 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:53:23.938  7017  7017 D HeadsetStateMachine: make
09-09 14:53:23.970  1031  1963 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7505 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 14:53:23.979  7017  7017 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:23.979  7017  7017 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:53:23.982  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:23.985  7017  7017 D HeadsetStateMachine: max_hf_connections = 1
09-09 14:53:23.985  7017  7017 I bluedroid-qcom: get_profile_interface handsfree
09-09 14:53:23.987  7017  7017 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-09 14:53:23.988   314  1364 V AudioPolicyService: registerClient() client 0xb558a9c0, uid 1002
09-09 14:53:23.988   314  1703 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:53:23.988   314  1703 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,09-09 14:53:23.988   314  1703 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:53:23.988  7017  7017 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 14:53:23.989   314   314 V AudioFlinger: registerClient() client 0xb55815e0, pid 7017
09-09 14:53:23.989   314  1360 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:23.989   314  1360 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:23.989  7017  7017 V ToneGenerator: Create Track: 0xb4928080
09-09 14:53:23.990  7017  7017 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 14:53:23.990  7017  7017 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 14:53:23.990   314  1364 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:53:23.990   314  1364 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:53:23.990   314  1364 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:53:23.990   314  1364 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:53:23.990  7017  7017 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 14:53:23.990  1031  1722 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:23.990  1031  1722 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:23.990  7017  7486 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:23.990  7017  7486 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 14:53:23.990   314   314 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:53:23.991   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:53:23.991   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 14:53:23.991   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:53:23.991   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:53:23.991  3407  3423 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:23.991  3407  3423 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:23.991   314  1359 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:23.991   314  1359 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:23.991  1031  2000 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:23.991  1031  2000 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:23.992  7017  7486 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:23.992  7017  7486 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 14:53:23.992  3407  4804 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:23.992  3407  4804 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:23.992  1589  2079 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:23.992  1589  2079 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:23.992  1589  2079 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:23.992  1589  2079 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:23.992  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:23.992  1840  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:23.992  1840  1855 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:23.992  ,7017  7017 V AudioSystem: getLatency() output 2, latency 50
09-09 14:53:23.992  7017  7017 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 14:53:23.992  7017  7017 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 14:53:23.993   314  1703 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:53:23.993   314  1703 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:53:23.993   314  1703 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:53:23.993   314  1703 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:53:23.993   314  1703 V AudioFlinger: createTrack() lSessionId: 22
09-09 14:53:23.993  1840  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:23.993  1840  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:23.994  7017  7017 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 14:53:23.995   314  1364 V AudioFlinger: acquiring 22 from 7017, for 7017
09-09 14:53:23.995   314  1364 V AudioFlinger:  added new entry for 22
09-09 14:53:23.995  7017  7017 V ToneGenerator: ToneGenerator INIT OK, time: 221250
09-09 14:53:23.995  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:23.995  7017  7504 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 14:53:23.995  7017  7504 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:53:23.995  7017  7504 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:53:23.996  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:23.996  7017  7504 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 14:53:23.996   314   314 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7017
09-09 14:53:23.996   314   314 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 14:53:23.996   314   314 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 14:53:23.996   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 14:53:23.996   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 14:53:23.996   314   314 V voice   : voice_set_parameters: exit with code(0)
09-09 14:53:23.996   314   314 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 14:53:23.996   314   314 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 14:53:23.997  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:23.999  7017  7017 D A2dpService: Received start request. Starting profile...
,09-09 14:53:23.999  7017  7017 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 14:53:24.000  7017  7017 V Avrcp   : make
09-09 14:53:24.001  7017  7017 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 14:53:24.001  7017  7017 I bluedroid-qcom: get_profile_interface avrcp
09-09 14:53:24.001  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:53:24.001  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.001  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:53:24.002  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 14:53:23.999   314   314 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 14:53:24.002   314   314 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 14:53:24.002   314   314 V audio_hw_primary: adev_set_parameters: exit with code(0),
09-09 14:53:24.002   314   314 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 14:53:24.002  7017  7504 V ToneGenerator: ToneGenerator destructor
09-09 14:53:24.002  7017  7504 V ToneGenerator: stopTone
09-09 14:53:24.002  7017  7504 V ToneGenerator: Delete Track: 0xb4928080
,09-09 14:53:24.003  7017  7504 V AudioTrack: ~AudioTrack, releasing session id from 7017 on behalf of 7017
09-09 14:53:24.003   314  1364 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 14:53:24.003   314  1364 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 14:53:24.003   314  1364 V AudioFlinger: PlaybackThread::Track destructor
09-09 14:53:24.003   314  1110 V AudioPolicyService: AudioCommandThread() waking up
09-09 14:53:24.004   314  1110 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 14:53:24.004   314  1364 V AudioFlinger: removeClient_l() pid 7017, calling pid 314
09-09 14:53:24.004   314  1110 V AudioPolicyManager: releaseOutput() 2
09-09 14:53:24.004   314  1110 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 14:53:24.004   314  1365 V AudioFlinger: releasing 22 from 7017 for 7017
09-09 14:53:24.004   314  1365 V AudioFlinger:  decremented refcount to 0
09-09 14:53:24.004   314  1365 V AudioFlinger: purging stale effects
09-09 14:53:24.006  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:53:24.008  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:24.010  7017  7017 V AudioManager: registerRemoteController: size of Media player list: 0
09-09 14:53:24.011  1031  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.011  7017  7017 E AudioManager: No RCC entry present to update
09-09 14:53:24.011  7017  7017 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 14:53:24.013  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:24.013  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:24.013  1031  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:24.014  7017  7017 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 14:53:24.014  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 14:53:24.014  7017  7017 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-09 14:53:24.018  7017  7481 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:24.019  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 14:53:24.020  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bbbc7ee
09-09 14:53:24.020  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:53:24.020  7077  7077 D AppUp4:CustFacade: isPhone : true
09-09 14:53:24.020  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:53:24.020  7077  7077 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:53:24.057  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.057  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:24.058  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:53:24.062  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:24.069  7017  7481 V LGMDMManager: Create singleton instance
09-09 14:53:24.070  4275  7526 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:24.072  7017  7481 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 14:53:24.076  4275  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.076  4275  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:53:24.078  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:53:24.099  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:53:24.099  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.099  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 14:53:24.101  1031  1962 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:53:24.101  1031  1962 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:53:24.103  7148  7148 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:53:24.103  7148  7148 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 14:53:24.116  6980  7531 W FormManager: Network not available. Please check & try again.
,09-09 14:53:24.120  7505  7505 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 14:53:24.120  7505  7505 W LG Account v2.2: No ProfileInfo entries
09-09 14:53:24.120  7505  7505 I LG Account v2.2: isEnabled: false
09-09 14:53:24.120  7505  7505 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 14:53:24.120  7505  7505 I Feature : [Lifetracker]Country: EU
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Operator: OPEN
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Ranking support: false
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Comfort support: false
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Accessory: true
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Health device: true
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Extra Pedometer: false
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Blood glucose device: false
09-09 14:53:24.121  7505  7505 I Feature : [Lifetracker]Device Number: 3
09-09 14:53:24.125  7111  7530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:24.125  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:24
09-09 14:53:24.127  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:53:24.127  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:53:24.127  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:53:24.127  7221  7221 D WeatherAncestor: connectivity changed - connection : true
09-09 14:53:24.127  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3ac2431c
,09-09 14:53:24.130  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:53:24.130  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:53:24.130  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:53:24.131  6980  7532 V FormManager: Network unavailable.
09-09 14:53:24.131  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:53:24.131  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:24
09-09 14:53:24.136  6882  6882 D BluetoothPermissionRequest: onReceive
09-09 14:53:24.141  6980  7532 V FormManager: Network unavailable.
,09-09 14:53:24.146  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:53:24.153  1031  1999 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 14:53:24.158  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 14:53:24.161  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 14:53:24.162  6456  6904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 14:53:24.163  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:53:24.164  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 14:53:24.164  7017  7017 I BluetoothA2dpServiceJni: classInitNative
09-09 14:53:24.165  7017  7017 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:53:24.165  7017  7017 D A2dpStateMachine: make
,09-09 14:53:24.166  7017  7017 I bluedroid-qcom: get_profile_interface a2dp
09-09 14:53:24.167  7017  7537 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 14:53:24.172  7017  7017 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:53:24.172  7017  7017 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 14:53:24.173  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.173  7017  7017 D HeadsetStateMachine: Proxy object connected
09-09 14:53:24.173  7017  7536 D A2dpStateMachine: Enter Disconnected: -2
09-09 14:53:24.173  7017  7017 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 14:53:24.174  7017  7017 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 14:53:24.175  7017  7017 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 14:53:24.176  7017  7017 D HidService: Received start request. Starting profile...
09-09 14:53:24.177  7017  7017 I bluedroid-qcom: get_profile_interface hidhost
09-09 14:53:24.177  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.181  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:24.181  2199  2199 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.181  7017  7504 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 14:53:24.182  7017  7504 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 14:53:24.182  7017  7017 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:53:24.182  7017  7504 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 14:53:24.185  7017  7017 D HealthService: Received start request. Starting profile...
09-09 14:53:24.186  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 14:53:24.186  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.187  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 14:53:24.187  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 14:53:24.187  7017  7017 I bluedroid-qcom: get_profile_interface health
09-09 14:53:24.187  7017  7017 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:53:24.188  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.188  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
09-09 14:53:24.188  7017  7017 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 14:53:24.190  7017  7017 D PanService: Received start request. Starting profile...
09-09 14:53:24.190  7017  7017 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:53:24.190  7017  7017 I bluedroid-qcom: get_profile_interface pan
09-09 14:53:24.192  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bbbc7ee
09-09 14:53:24.192  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:53:24.192  7077  7077 D AppUp4:CustFacade: isPhone : true
09-09 14:53:24.192  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:53:24.192  7077  7077 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 14:53:24.194  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.195  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:24.195  7017  7017 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 14:53:24.195  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.196  7017  7017 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 14:53:24.196  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:24.198  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 14:53:24.199  7017  7017 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:53:24.200  7017  7017 D BtGatt.GattService: Received start request. Starting profile...
09-09 14:53:24.200  7017  7017 D BtGatt.GattService: start()
09-09 14:53:24.200  4275  7542 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:24.200  7017  7017 I bluedroid-qcom: get_profile_interface gatt
09-09 14:53:24.200  7017  7017 D BtGatt.AdvertiseManager: advertise manager created
09-09 14:53:24.203  7111  7111 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 14:53:24.205  4275  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.205  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.206  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.207  7017  7017 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 14:53:24.208  7017  7017 V BluetoothMapService: BluetoothMapBinder()
09-09 14:53:24.208  4275  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:53:24.209  7017  7017 D BluetoothMapService: Received start request. Starting profile...
09-09 14:53:24.209  7017  7017 D BluetoothMapService: start()
09-09 14:53:24.216  7017  7017 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 14:53:24.216  7017  7017 D BluetoothMapEmailAppObserver: createReceiver()
,09-09 14:53:24.219  6980  7548 W FormManager: Network not available. Please check & try again.
09-09 14:53:24.220  7017  7017 D BluetoothMapEmailAppObserver: initObservers()
,09-09 14:53:24.220  7017  7017 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 14:53:24.222  7111  7547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:24.227  3407  3407 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 14:53:24.227  3407  3407 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:24.227  3407  3407 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 14:53:24.228  6980  7549 V FormManager: Network unavailable.
09-09 14:53:24.229  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:24.230  7148  7148 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 14:53:24.230  7148  7148 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 14:53:24.233  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:24.235  6980  7549 V FormManager: Network unavailable.
09-09 14:53:24.235  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:24.238  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:24.238  7017  7017 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 14:53:24.241  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:24.243  7017  7017 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 14:53:24.243  7017  7017 V BluetoothMapService: Handler(): got msg=1
,09-09 14:53:24.244  7017  7481 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 14:53:24.244  7017  7481 I bluedroid-qcom: enable
09-09 14:53:24.244  7017  7481 I bt_hci_bdroid: init
09-09 14:53:24.245  7017  7551 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 14:53:24.245  7017  7551 I bt-btu  : btu_task pending for preload complete event
09-09 14:53:24.246  7017  7481 I bt_vendor: bt-vendor : init
09-09 14:53:24.246  7017  7481 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 14:53:24.246  7017  7481 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 14:53:24.246  7017  7481 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 14:53:24.246  7017  7481 D bt_userial_mct: userial_init
09-09 14:53:24.246  7017  7481 D bt_hci_bdroid: set_power 1
09-09 14:53:24.246  7017  7481 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 14:53:24.246  7017  7481 I bt_vendor: Starting hciattach daemon
09-09 14:53:24.246  7017  7481 I bt_vendor: try to set true
09-09 14:53:24.247  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.244  7554  7554 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:24.244  7554  7554 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:24.251  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:24.251  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:24.251  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:24.251  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.252  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 14:53:24.254  7221  7221 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:24
,09-09 14:53:24.258  7221  7221 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 14:53:24.258  7221  7221 D Weather.Utils: 2 : All the weather widget is gone.
09-09 14:53:24.261  7221  7221 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 14:53:24.261  7221  7221 D WeatherAncestor: connectivity changed - connection : true
09-09 14:53:24.261  7221  7221 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3ac2431c
09-09 14:53:24.262  7221  7221 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 14:53:24.262  7221  7221 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 14:53:24.262  7221  7221 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 14:53:24.262  7221  7221 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 14:53:24.262  7221  7221 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:53:24
09-09 14:53:24.264  7555  7555 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-09 14:53:24.324  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 14:53:24.340  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:53:24.392  7564  7564 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:53:24.406  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-09 14:53:24.435  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:53:24.454  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 14:53:24.495  7569  7569 I libmdmdetect: ESOC framework not supported
09-09 14:53:24.496  7569  7569 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 14:53:24.504  7569  7569 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-09 14:53:24.504  7569  7569 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 14:53:24.504  7569  7569 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 14:53:24.504  7569  7569 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 14:53:24.504  7569  7569 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 14:53:24.504  7569  7569 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 14:53:24.504  7569  7569 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 14:53:24.548  7569  7570 E QC-QMI  : qmi_client [7569] 14: failed to locate client data
09-09 14:53:24.551   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 14:53:24.551   450   450 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-09 14:53:24.603  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 14:53:24.618  7578  7578 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-09 14:53:24.651  7017  7481 I bt_vendor: bluetooth satus is on
09-09 14:53:24.651  7017  7481 D bt_hci_bdroid: preload
,09-09 14:53:24.655  7017  7553 D bt_userial_mct: userial_open(port:0)
,09-09 14:53:24.655  7017  7553 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 14:53:24.659  7017  7553 I bt_vendor: Done intiailizing UART
,09-09 14:53:24.662  7017  7553 I bt_vendor: Done intiailizing UART
09-09 14:53:24.662  7017  7553 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 14:53:24.662  7017  7553 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-09 14:53:24.663  7017  7551 I bt-btu  : btu_task received preload complete event
09-09 14:53:24.664  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 14:53:24.664  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 14:53:24.675  7017  7580 D bt_userial_mct: Entering userial_read_thread()
,09-09 14:53:24.679  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:53:24.691  7017  7551 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 14:53:24.749  7017  7551 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-09 14:53:24.749  7017  7551 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c9061 
09-09 14:53:24.749  7017  7551 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c9061 
,09-09 14:53:24.762  7017  7485 E bt-btif : Calling BTA_HhEnable
09-09 14:53:24.762  7017  7485 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 14:53:24.763  7017  7485 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 14:53:24.764  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:53:24.764  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:53:24.765  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 14:53:24.765  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 14:53:24.765  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 14:53:24.765  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,09-09 14:53:24.765  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 14:53:24.765  7017  7485 D BluetoothAdapterProperties: Name is: G3
09-09 14:53:24.766  7017  7485 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:53:24.767  7017  7485 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:53:24.767  7017  7485 D bt_hci_bdroid: postload
09-09 14:53:24.767  7017  7553 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:24.768  7017  7485 D bte_conf: Device ID record 1 : primary
09-09 14:53:24.768  7017  7485 D bte_conf:   vendorId            = 00c4
09-09 14:53:24.768  7017  7485 D bte_conf:   vendorIdSource      = 0001
09-09 14:53:24.768  7017  7485 D bte_conf:   product             = 13a1
09-09 14:53:24.768  7017  7485 D bte_conf:   version             = 1000
09-09 14:53:24.768  7017  7485 D bte_conf:   clientExecutableURL = 
09-09 14:53:24.768  7017  7485 D bte_conf:   serviceDescription  = 
09-09 14:53:24.768  7017  7485 D bte_conf:   documentationURL    = 
09-09 14:53:24.768  7017  7485 D bte_conf: bte_load_did_conf no section named DID2.
09-09 14:53:24.768  7017  7551 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 14:53:24.769  7017  7553 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:24.771  7017  7481 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 14:53:24.771  7017  7481 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:53:24.771  7017  7481 D BluetoothAdapterProperties: State =  11
09-09 14:53:24.771  7017  7481 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 14:53:24.771  7017  7485 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 14:53:24.771  7017  7481 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 14:53:24.772  7017  7481 D BluetoothAdapterProperties: Setting state to 12
09-09 14:53:24.772  7017  7481 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 14:53:24.772  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:24.772  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:24.772  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 14:53:24.772  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-09 14:53:24.773  7017  7485 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 14:53:24.773  7017  7553 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:24.774  7017  7481 I BluetoothAdapterState: Entering On State
09-09 14:53:24.774  7582  7582 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:24.774  7582  7582 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:53:24.783  7017  7553 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:24.783  7017  7553 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:24.787  7017  7580 E bt_mct  : hci lib postload completed
09-09 14:53:24.791  7017  7481 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 14:53:24.791  7017  7481 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 14:53:24.791  7017  7481 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-09 14:53:24.794  7017  7481 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 14:53:24.794  6882  6900 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 14:53:24.797  6882  6899 D BluetoothMap: onBluetoothStateChange: up=true
09-09 14:53:24.797  7017  7551 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:24.797  7017  7551 W bt-smp  : Plain text(LSB ~ MSB) = 13 f5 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:24.797  7017  7551 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 fa 01 3c 60 c1 af 39 c3 f7 c8 ee 09 8a 1a be 
09-09 14:53:24.797  7017  7551 W bt-btm  : Stopping oneshot timer
09-09 14:53:24.802  7017  7485 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:53:24.803  7017  7485 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 14:53:24.806  6882  6882 D BluetoothInputDevice: Proxy object connected
09-09 14:53:24.806  6882  6882 D HidProfile: Bluetooth service connected
,09-09 14:53:24.809  6882  6900 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 14:53:24.814  1840  2609 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:24.818  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 14:53:24.820  1840  2417 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:24.822  6882  7584 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:53:24.822  6882  7584 D BluetoothPan: onBluetoothStateChange call bindService
09-09 14:53:24.823  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:24.824  7017  7481 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 14:53:24.824  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:24.828  1840  1840 D BluetoothHeadset: Proxy object connected
09-09 14:53:24.829  1031  1031 D BluetoothHeadset: Proxy object connected
09-09 14:53:24.829  1840  1840 D BluetoothHeadset: Proxy object connected
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:24.833  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:53:24.837  1031  1031 D BluetoothA2dp: Proxy object connected
09-09 14:53:24.837  7017  7551 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:24.837  7017  7551 W bt-smp  : Plain text(LSB ~ MSB) = fc 36 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:24.837  7017  7551 W bt-smp  : Encrypted text(LSB ~ MSB) = 82 18 ab ef 58 47 b1 67 9f 19 c6 ab ca 64 1d cc 
09-09 14:53:24.837  7017  7551 W bt-btm  : Stopping oneshot timer
09-09 14:53:24.838  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:24.841  1840  1840 D BluetoothHeadset: Proxy object connected
09-09 14:53:24.845  6882  6882 D BluetoothMap: Proxy object connected
09-09 14:53:24.845  6882  6882 D MapProfile: Bluetooth service connected
09-09 14:53:24.845  6882  6882 D BluetoothMap: getConnectedDevices()
,09-09 14:53:24.850  7588  7588 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-09 14:53:24.852  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 14:53:24.853  7017  7551 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:24.854  7017  7551 W bt-smp  : Plain text(LSB ~ MSB) = 4e 93 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:24.854  7017  7551 W bt-smp  : Encrypted text(LSB ~ MSB) = d9 92 09 69 c2 f1 c0 8d a2 73 83 11 e8 84 29 98 
09-09 14:53:24.854  7017  7551 W bt-btm  : Stopping oneshot timer
09-09 14:53:24.855  7017  7034 V BluetoothMapService: getConnectedDevices()
09-09 14:53:24.856  1031  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 14:53:24.856  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-09 14:53:24.857  6882  6882 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:53:24.857  6882  6882 D PanProfile: Bluetooth service connected
,09-09 14:53:24.859  1031  1102 D BluetoothManagerService: Message: 40
09-09 14:53:24.859  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 14:53:24.860  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.860  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:24.860  1927  2115 D LGBluetoothAPIService: Message: 1
09-09 14:53:24.860  1927  2115 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 14:53:24.865  6745  6745 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 14:53:24.871  7017  7551 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:24.871  7017  7551 W bt-smp  : Plain text(LSB ~ MSB) = bd 7f 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
,09-09 14:53:24.871  7017  7551 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 88 fe 7f f5 9c 20 81 43 76 88 68 04 c2 2a db 
09-09 14:53:24.871  7017  7551 W bt-btm  : Stopping oneshot timer
,09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:24.874  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:24.876  1927  2115 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-09 14:53:24.879  7017  7017 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.880  7017  7017 D BluetoothMapService: STATE_ON
09-09 14:53:24.880  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:24.882  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:24.883  7017  7017 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 14:53:24.883  7017  7017 D LGBluetoothAPIServer: [BTUI] onBind()
,09-09 14:53:24.885  6882  6882 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 14:53:24.886  7017  7017 V BluetoothMapService: Handler(): got msg=1
09-09 14:53:24.886  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 14:53:24.886  1927  2115 D LGBluetoothAPIService: Message: 100
09-09 14:53:24.886  1927  2115 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 14:53:24.887  1031  1102 D BluetoothManagerService: Message: 30
09-09 14:53:24.888  7017  7017 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 14:53:24.889  7017  7551 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:24.889  7017  7551 W bt-smp  : Plain text(LSB ~ MSB) = 8c 0a 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:24.889  7017  7551 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 98 0d 6e a7 ba 1d de d2 1f 70 b7 8e 34 ac 36 
09-09 14:53:24.889  7017  7551 W bt-btm  : Stopping oneshot timer
09-09 14:53:24.891  6882  6882 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 14:53:24.895  1031  1102 D BluetoothManagerService: Message: 30
09-09 14:53:24.896  7017  7602 D BluetoothMapMasInstance: MAS initSocket()
,09-09 14:53:24.896  7017  7602 D BluetoothMapMasInstance:   masId = 00
09-09 14:53:24.896  7017  7602 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 14:53:24.896  7017  7602 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 14:53:24.896  7017  7602 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 14:53:24.902  1031  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:24.906  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
,09-09 14:53:24.906  7017  7017 V BluetoothPbapService: Pbap Service onCreate
09-09 14:53:24.906  7017  7017 V BluetoothPbapService: Starting PBAP service
09-09 14:53:24.906  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-09 14:53:24.907  7017  7017 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 14:53:24.907  7017  7017 V BluetoothPbapService: Pbap Service onBind
09-09 14:53:24.908  7017  7017 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.908  7017  7017 V BluetoothPbapService: state: 12
09-09 14:53:24.908  7017  7017 V BluetoothPbapService: Handler(): got msg=1
09-09 14:53:24.910  7017  7017 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 14:53:24.911  7017  7603 V BluetoothPbapService: Pbap Service initSocket
09-09 14:53:24.912  1031  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:24.912  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:53:24.915  7017  7602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:24.915  7017  7603 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:24.916  7017  7602 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 14:53:24.916  7017  7602 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 14:53:24.916  7017  7602 D BluetoothMapMasInstance: Accepting socket connection...
09-09 14:53:24.916  6882  6882 D BluetoothA2dp: Proxy object connected
09-09 14:53:24.917  6882  6882 D A2dpProfile: Bluetooth service connected
09-09 14:53:24.917  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:24.917  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.917  7017  7017 V BluetoothPbapReceiver: ***********state = 12
09-09 14:53:24.918  7017  7485 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:53:24.918  7017  7485 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 14:53:24.918  7017  7603 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 14:53:24.918  7017  7603 V BluetoothPbapService: Succeed to create listening socket 
09-09 14:53:24.918  7017  7603 V BluetoothPbapService: Accepting socket connection...
09-09 14:53:24.921  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:53:24.921  6882  6882 D BluetoothHeadset: Proxy object connected
09-09 14:53:24.922  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:24.923  6882  6882 D HeadsetProfile: Bluetooth service connected
09-09 14:53:24.924  2199  2199 D c       : Getting all permits...
09-09 14:53:24.924  2199  2199 D a       : Opening database...
09-09 14:53:24.925  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:24.927  6882  6882 D BluetoothPbap: Proxy object connected
09-09 14:53:24.927  6882  6882 D PbapServerProfile: Bluetooth service connected
09-09 14:53:24.928  2199  2199 D a       : Opening database auth.proximity.permit_store...
09-09 14:53:24.929  2199  2199 D a       : Closing database...
09-09 14:53:24.932  6882  6882 D DockEventReceiver: finishStartingService: stopping service
09-09 14:53:24.938  6882  6882 D BluetoothPermissionRequest: onReceive
,09-09 14:53:24.940  6882  6882 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 14:53:24.941  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:53:24.944  7017  7017 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 14:53:24.945  7017  7017 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 14:53:24.950  7017  7017 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 14:53:24.968  7017  7017 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-09 14:53:24.969  7017  7017 V BtOppService: onCreate
09-09 14:53:24.973  7017  7017 V BluetoothOppNotification: send message
09-09 14:53:24.977  7017  7017 V BtOppService: Starting RfcommListener
09-09 14:53:24.983  7017  7608 V BtOppService: Deleted complete outbound shares, number =  0
,09-09 14:53:24.985  7017  7017 D BluetoothOppPreference: Dumping Names:  
09-09 14:53:24.985  7017  7017 D BluetoothOppPreference: {}
09-09 14:53:24.985  7017  7017 D BluetoothOppPreference: Dumping Channels:  
09-09 14:53:24.985  7017  7017 D BluetoothOppPreference: {}
09-09 14:53:24.986  7017  7608 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 14:53:24.987  7017  7017 V BtOppService: onStartCommand
09-09 14:53:24.988  7017  7608 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 14:53:24.988  7017  7611 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:53:24.989  7017  7611 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:53:24.990  7017  7608 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f0da2f1 on behalf of 
09-09 14:53:24.991  7017  7611 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27d9fed6 on behalf of 
09-09 14:53:24.992  7017  7611 V BluetoothOppNotification: update too frequent, put in queue
09-09 14:53:24.993  7017  7611 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:53:24.993  7017  7611 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:53:24.993  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:24.993  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:53:24.995  7017  7611 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12fae557 on behalf of 
,09-09 14:53:24.996  7017  7611 V BluetoothOppNotification: update too frequent, put in queue
09-09 14:53:24.997  7017  7611 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 14:53:24.998  7017  7017 V BluetoothOppNotification: new notify threadi!
09-09 14:53:24.998  7017  7017 V BluetoothOppNotification: send delay message
09-09 14:53:24.999  7017  7017 V BtOppService: start RfcommListener
09-09 14:53:25.000  7017  7612 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 14:53:25.001  7017  7612 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3efe5844 on behalf of 
09-09 14:53:25.002  7017  7612 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 14:53:25.003  7017  7017 V BtOppService: RfcommListener started
09-09 14:53:25.003  7017  7017 V BtOppService: ContentObserver received notification
09-09 14:53:25.004  7017  7612 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 14:53:25.005  7017  7612 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19c87d2d on behalf of 
09-09 14:53:25.006  7017  7017 V BtOppService: ContentObserver received notification
09-09 14:53:25.006  7017  7612 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 14:53:25.008  7017  7616 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:53:25.009  7017  7616 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:53:25.011  7249  7279 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-09 14:53:25.011  7017  7616 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e4f3262 on behalf of 
09-09 14:53:25.012  7017  7612 V BluetoothOppNotification: outbound notification was removed.
09-09 14:53:25.013  7017  7616 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-09 14:53:25.013  7017  7612 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:53:25.015  7017  7612 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12de7ff3 on behalf of 
09-09 14:53:25.016  7017  7612 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 14:53:25.016  7017  7615 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 14:53:25.016  1031  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:25.017  7017  7612 V BluetoothOppNotification: inbound notification was removed.
09-09 14:53:25.017  7017  7612 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:53:25.018  7017  7615 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:25.019  7017  7612 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3caab4b0 on behalf of 
09-09 14:53:25.019  7017  7615 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 14:53:25.019  7017  7615 V BtOppRfcommListener: Started RFCOMM listener....
09-09 14:53:25.019  7017  7615 I BtOppRfcommListener: Accept thread started.
09-09 14:53:25.019  7017  7615 V BtOppRfcommListener: Accepting connection...
09-09 14:53:25.033  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
,09-09 14:53:25.033  7017  7017 V BluetoothFtpService: Ftp Service onCreate
09-09 14:53:25.033  7017  7017 I BluetoothFtpService: Ftp Service onCreate
09-09 14:53:25.033  7017  7017 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:53:25.033  7017  7017 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:25.033  7017  7017 V BluetoothFtpService: Starting Listening on sockets
09-09 14:53:25.034  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:25.034  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:25.034  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:25.034  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:25.034  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 14:53:25.034  7017  7017 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:53:25.036  7017  7017 V BluetoothFtpService: Handler(): got msg=1
09-09 14:53:25.037  7017  7017 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 14:53:25.037  7017  7017 V BluetoothFtpService: Ftp Service initSocket
09-09 14:53:25.043  1031  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:25.043  7017  7017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:25.044  7017  7017 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-09 14:53:25.044  7017  7017 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-09 14:53:25.046  7017  7618 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 14:53:25.060  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:25.060  7017  7017 V BluetoothSapService: Sap Service onCreate
,09-09 14:53:25.062  7017  7017 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:25.062  7017  7017 V BluetoothSapService: state: 12
09-09 14:53:25.063  7017  7017 V BluetoothSapService: Starting SAP server process
09-09 14:53:25.064  7619  7619 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:25.065  7017  7017 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 14:53:25.064  7619  7619 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:25.069  7017  7620 V BluetoothSapService: Sap Service initRfcommSocket
09-09 14:53:25.070  1031  1046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:25.072  7017  7620 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:25.074  7017  7620 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,09-09 14:53:25.076  7017  7620 V BluetoothSapService: Succeed to create listening socket 
09-09 14:53:25.076  7017  7620 V BluetoothSapService: Accepting socket connection...
09-09 14:53:25.078  7619  7619 V BT_SAP  : Event pipe created
09-09 14:53:25.078  7619  7619 V BT_SAP  : create_server_socket qcom.sap.server
09-09 14:53:25.078  7619  7619 V BT_SAP  : created socket fd 6
,09-09 14:53:25.804  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 14:53:25.816  1031  1521 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:25.828  1031  1963 I ActivityManager: Killing 7410:com.lge.bnr/1000 (adj 15): empty #17
,09-09 14:53:25.831  1031  1524 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 14:53:25.832  1031  1524 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 14:53:25.860  1031  1723 W libprocessgroup: failed to open /acct/uid_1000/pid_7410/cgroup.procs: No such file or directory
,09-09 14:53:25.927  1031  2037 I ActivityManager: Killing 6654:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-09 14:53:25.950  6937  6937 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 14:53:25.951  6937  6937 W System.err: android.os.DeadObjectException
09-09 14:53:25.951  6937  6937 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:53:25.951  6937  6937 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:53:25.951  6937  6937 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 14:53:25.951  6937  6937 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 14:53:25.951  6937  6937 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 14:53:25.951  6937  6937 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 14:53:25.951  6937  6937 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:53:25.951  6937  6937 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:53:25.952  6937  6937 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:25.952  6937  6937 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:53:25.952  6937  6937 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:53:25.952  6937  6937 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:53:25.952  6937  6937 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:53:25.952  6937  6937 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:53:25.952  6937  6937 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 14:53:25.952  6937  6937 W System.err: android.os.DeadObjectException
09-09 14:53:25.952  6937  6937 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 14:53:25.952  6937  6937 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 14:53:25.953  6937  6937 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 14:53:25.953  6937  6937 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 14:53:25.953  6937  6937 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 14:53:25.953  6937  6937 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 14:53:25.953  6937  6937 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:53:25.953  6937  6937 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:53:25.953  6937  6937 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:25.953  6937  6937 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:53:25.953  6937  6937 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:53:25.953  6937  6937 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:53:25.953  6937  6937 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:53:25.953  6937  6937 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:53:25.953  6937  6937 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 14:53:25.954  6937  6937 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-09 14:53:25.988  1031  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6654/cgroup.procs: No such file or directory
09-09 14:53:25.989  1031  1942 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-09 14:53:25.995  6937  6937 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 14:53:25.996  6937  6937 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:53:26.006  7017  7017 V BluetoothOppNotification: new notify threadi!
09-09 14:53:26.006  7017  7017 V BluetoothOppNotification: send delay message
,09-09 14:53:26.016  7017  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 14:53:26.053  1031  1963 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7631 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:53:26.083  6937  6937 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 14:53:26.094  7017  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37d924e5 on behalf of 
,09-09 14:53:26.116  7017  7630 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 14:53:26.136  7017  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-09 14:53:26.161  7017  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ed0abba on behalf of 
09-09 14:53:26.162  7017  7630 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-09 14:53:26.166  7017  7630 V BluetoothOppNotification: outbound notification was removed.
09-09 14:53:26.167  7017  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:53:26.168  7017  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f07fa6b on behalf of 
09-09 14:53:26.169  7017  7630 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 14:53:26.170  7017  7630 V BluetoothOppNotification: inbound notification was removed.
,09-09 14:53:26.171  7017  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:53:26.171  7017  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e7469c8 on behalf of 
09-09 14:53:26.278  1031  1722 I art     : Explicit concurrent mark sweep GC freed 93648(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.608ms total 178.582ms
,09-09 14:53:26.314  7631  7631 D UEI.SmartControl: Quickset Services start...
,09-09 14:53:26.316  7631  7631 I UEI.SmartControl: Manufacture = LGE
09-09 14:53:26.317  7631  7631 D UEI.SmartControl: Id = LGNevo
09-09 14:53:26.318  7631  7631 D UEI.SmartControl: File observer start...
09-09 14:53:26.319  7631  7631 E UEI.SmartControl: IR Port is disabled: false
,09-09 14:53:26.319  7631  7631 D UEI.SmartControl: Starting file observer...
09-09 14:53:26.319  7631  7631 D UEI.SmartControl: Extracting JNI libs...
09-09 14:53:26.319  7631  7631 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 14:53:26.394  7631  7631 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 14:53:26.394  7631  7631 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 14:53:26.394  7631  7631 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 14:53:26.452  7631  7631 I UEI.SmartControl: --- Selecting new region: 6
,09-09 14:53:26.455  7631  7631 I UEI.SmartControl: Model = LG-D855
,09-09 14:53:26.457  7631  7631 D UEI.SmartControl: QS Service created
,09-09 14:53:26.476  7631  7631 I UEI.SmartControl: Service initServices...
,09-09 14:53:26.482  7631  7631 D UEI.SmartControl: QS start get config
,09-09 14:53:26.549  7631  7631 D UEI.SmartControl: Loading JNI Libs...
,09-09 14:53:26.767  1031  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:26.768  1031  1942 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2e9174bc mBinding = false
,09-09 14:53:26.798  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:26.798  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:26.798  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-09 14:53:26.799  1031  1102 D BluetoothManagerService: Message: 2
09-09 14:53:26.799  1031  1102 D BluetoothManagerService: Sending off request.
09-09 14:53:26.799  7017  7600 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 14:53:26.800  7017  7481 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 14:53:26.800  7017  7481 D BluetoothAdapterProperties: Setting state to 13
09-09 14:53:26.800  7017  7481 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 14:53:26.800  7017  7481 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 14:53:26.800  7017  7481 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 14:53:26.801  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:26.801  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 14:53:26.801  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 14:53:26.801  7017  7485 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:53:26.802  7017  7481 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 14:53:26.802  7017  7603 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:26.802  7017  7481 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 14:53:26.803  7017  7602 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 14:53:26.804  7017  7615 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:26.804  7017  7618 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:26.807  7017  7620 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 14:53:26.808  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 14:53:26.808  7017  7551 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,09-09 14:53:26.812  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:26.812  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:26.812  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:26.812  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:26.813  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 14:53:26.813  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 14:53:26.813  7017  7551 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 14:53:26.814  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:26.814  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:26.814  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 14:53:26.814  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_H,ERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:26.817  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:26.818  7017  7017 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.818  7017  7017 D BluetoothMapService: STATE_TURNING_OFF
09-09 14:53:26.818  7017  7017 V BtOppService: Receiver DISABLED_ACTION 
09-09 14:53:26.819  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.819  7017  7017 V BluetoothMapService: Handler(): got msg=4
09-09 14:53:26.820  7017  7017 D BluetoothMapService: MAP Service closeService in
09-09 14:53:26.820  7017  7017 D BluetoothMapMasInstance: MAP Service shutdown
09-09 14:53:26.820  7017  7017 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:53:26.820  7017  7017 V BluetoothMapService: MAP Service closeService out
09-09 14:53:26.820  7017  7017 I BtOppRfcommListener: stopping Accept Thread
09-09 14:53:26.820  7017  7017 V BtOppRfcommListener: close mBtServerSocket
09-09 14:53:26.821  7017  7017 V BtOppRfcommListener: waiting for thread to terminate
09-09 14:53:26.821  7017  7615 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 14:53:26.821  7017  7017 V BtOppRfcommListener: done waiting for thread to terminate
,09-09 14:53:26.823  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:26.823  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:26.824  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-09 14:53:26.829  7017  7017 V BtOppService: onDestroy
09-09 14:53:26.830  7017  7017 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 14:53:26.831  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:53:26.834  7017  7017 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:26.834  7017  7017 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.834  7017  7017 V BluetoothPbapReceiver: ***********state = 13
,09-09 14:53:26.837  7017  7017 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 14:53:26.840  7017  7017 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.840  7017  7017 V BluetoothPbapService: state: 13
09-09 14:53:26.840  7017  7017 V BluetoothPbapService: Pbap Service closeService in
09-09 14:53:26.842  7017  7017 V BluetoothPbapService: successfully stopped pbap service
09-09 14:53:26.842  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:53:26.842  7017  7017 V BluetoothPbapService: Pbap Service closeService out
09-09 14:53:26.843  7017  7017 V BluetoothPbapService: Pbap Service onDestroy
09-09 14:53:26.843  7017  7017 V BluetoothPbapService: Pbap Service closeService in
09-09 14:53:26.843  7017  7017 V BluetoothPbapService: Pbap Service closeService out
09-09 14:53:26.843  7017  7017 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 14:53:26.848  6882  6882 D DockEventReceiver: finishStartingService: stopping service
,09-09 14:53:26.850  6882  6882 D BluetoothPbap: Proxy object disconnected
09-09 14:53:26.850  6882  6882 D PbapServerProfile: Bluetooth service disconnected
09-09 14:53:26.852  6882  6882 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 14:53:26.854  6882  6882 D BluetoothPermissionRequest: onReceive
09-09 14:53:26.854  6882  6882 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 14:53:26.859  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:53:26.861  7017  7017 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 14:53:26.861  7017  7017 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-09 14:53:26.862  7017  7017 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 14:53:26.866  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.866  7017  7017 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:53:26.868  7017  7017 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:53:26.868  7017  7017 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.868  7017  7017 V BluetoothFtpService: Ftp Service closeService
09-09 14:53:26.868  7017  7017 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 14:53:26.869  7017  7017 V BluetoothFtpService: successfully stopped ftp service
09-09 14:53:26.869  7017  7017 V BluetoothFtpService: Ftp Service onDestroy
09-09 14:53:26.869  7017  7017 V BluetoothFtpService: Ftp Service closeService
09-09 14:53:26.870  7017  7017 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:26.870  7017  7017 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:26.870  7017  7017 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:26.870  7017  7017 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.870  7017  7017 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 14:53:26.870  7017  7017 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:53:26.875  7017  7017 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:26.875  7017  7017 V BluetoothSapService: state: 13
09-09 14:53:26.875  7017  7017 V BluetoothSapService: Stopping SAP server process
,09-09 14:53:26.877  7017  7017 V BluetoothSapService: Sap Service closeSapService in
09-09 14:53:26.877  7017  7017 V BluetoothSapService: Close listen Socket : 
09-09 14:53:26.877  7017  7017 V BluetoothSapService: Close rfcomm Socket : 
09-09 14:53:26.877  7017  7017 V BluetoothSapService: Close sapd  Socket : 
09-09 14:53:26.881  7017  7017 V BluetoothSapService: Sap Service closeSapService out
09-09 14:53:26.881  7017  7017 V BluetoothSapService: Sap Service onDestroy
09-09 14:53:26.881  7017  7017 V BluetoothSapService: Sap Service closeSapService in
,09-09 14:53:26.881  7017  7017 V BluetoothSapService: Close listen Socket : 
09-09 14:53:26.881  7017  7017 V BluetoothSapService: Close rfcomm Socket : 
09-09 14:53:26.881  7017  7017 V BluetoothSapService: Close sapd  Socket : 
09-09 14:53:26.884  7017  7017 V BluetoothSapService: Sap Service closeSapService out
09-09 14:53:26.914  7631  7631 I UEI.SmartControl: Supports setup maps: true
,09-09 14:53:26.920  7631  7631 D UEI.SmartControl: QS start statue = true Error code = 0
,09-09 14:53:26.920  7631  7631 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 14:53:26.920  7631  7631 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 14:53:26.921  7631  7631 I UEI.SmartControl: ### init IR Blaster...
09-09 14:53:26.926  7631  7631 D serial_port: Configuring serial port
09-09 14:53:26.931  7631  7631 E UEI.SmartControl: UEIBLaster setting for 616
09-09 14:53:26.931  7631  7631 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 14:53:26.931  7631  7631 I UEI.SmartControl: configuring settings for MAXQ616
09-09 14:53:26.931  7631  7631 I UEI.SmartControl: Get version...
,09-09 14:53:26.948  7631  7683 D UEI.SmartControl: serial port data available: 21
,09-09 14:53:26.976  7631  7631 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 14:53:26.976  7631  7631 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-09 14:53:26.976  7631  7631 I UEI.SmartControl: QS saving settings...
,09-09 14:53:26.980  7631  7631 D UEI.SmartControl: IR Blaster version: 25672567
09-09 14:53:26.997  7631  7683 D UEI.SmartControl: serial port data available: 4
,09-09 14:53:27.040  7631  7687 I UEI.SmartControl: Device manager: loading config....
,09-09 14:53:27.041  7631  7687 D UEI.SmartControl: ----------- loading internal config...
09-09 14:53:27.044  7631  7631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 14:53:27.048  7631  7631 E UEI.SmartControl: Services init done
09-09 14:53:27.048  7631  7631 D UEI.SmartControl: QS Service init finished
09-09 14:53:27.051  7631  7631 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 14:53:27.051  7631  7631 D UEI.SmartControl: QS Service version code: 201091
09-09 14:53:27.053  7631  7631 D UEI.SmartControl: Service requested: Control
09-09 14:53:27.062  7631  7687 E UEI.SmartControl: Loading SETTINGS...
09-09 14:53:27.064  7631  7631 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 14:53:27.074  1031  1047 I ActivityManager: Killing 6937:com.lge.qremote/u0a112 (adj 15): empty #17
09-09 14:53:27.074  6937  6937 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 14:53:27.080  7631  7687 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-09 14:53:27.094  7631  7686 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 14:53:27.094  7631  7686 D UEI.SmartControl: -----service ready thread exits
,09-09 14:53:27.116  1031  1561 W libprocessgroup: failed to open /acct/uid_10112/pid_6937/cgroup.procs: No such file or directory
09-09 14:53:27.116  7631  7631 D UEI.SmartControl: Internal service binding...
,09-09 14:53:27.717  7017  7485 D bt_hci_bdroid: cleanup
,09-09 14:53:27.724  7017  7553 I bt_lpm  : LPM is already off!!!
,09-09 14:53:27.726  7017  7580 I bt_userial_mct: exiting userial_read_thread
09-09 14:53:27.727  7017  7580 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 14:53:27.728  7017  7551 W bt-btif : ag scb idx 1 not allocated
09-09 14:53:27.728  7017  7551 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 14:53:27.728  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 14:53:27.729  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 14:53:27.729  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017,
09-09 14:53:27.729  7017  7551 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 14:53:27.729  7017  7551 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b,
09-09 14:53:27.729  7017  7551 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 14:53:27.729  7017  7551 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-09 14:53:27.732  7017  7485 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 14:53:27.735  7017  7553 I bt_vendor: hw_epilog_process
,09-09 14:53:27.750  7017  7485 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 14:53:27.750  7017  7485 D bt_userial_mct: userial_close
09-09 14:53:27.750  7017  7485 E bt_userial_mct: pthread_join() FAILED result:3
09-09 14:53:27.750  7017  7485 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 14:53:27.755  7017  7485 D bt_hci_bdroid: set_power 0
09-09 14:53:27.755  7017  7485 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 14:53:27.755  7017  7485 I bt_vendor: bluetooth satus is on
09-09 14:53:27.755  7017  7485 I bt_vendor: bt-vendor : resetting BT status
09-09 14:53:27.755  7017  7485 I bt_vendor: Starting hciattach daemon
09-09 14:53:27.755  7017  7485 I bt_vendor: try to set false
,09-09 14:53:27.758  7017  7485 I bt_vendor: Starting hciattach daemon
09-09 14:53:27.758  7017  7485 I bt_vendor: try to set false
09-09 14:53:27.759  7017  7485 I bt_vendor: cleanup
09-09 14:53:27.760  7017  7551 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 14:53:27.760  7017  7485 I GKI_LINUX: GKI_exit_task 0 done
09-09 14:53:27.760  7017  7485 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 14:53:27.762  7017  7481 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 14:53:27.769  7017  7481 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-09 14:53:27.773  7017  7017 D HeadsetService: Received stop request...Stopping profile...
09-09 14:53:27.774  7017  7017 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 14:53:27.774  7017  7017 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:53:27.774  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.775  7017  7504 D HeadsetStateMachine: Exit Disconnected: -1
09-09 14:53:27.778  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:27.778  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:27.778  1840  1840 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:27.778  1031  1031 D BluetoothHeadset: Proxy object disconnected
09-09 14:53:27.778  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 14:53:27.779  7017  7017 D A2dpService: Received stop request...Stopping profile...
09-09 14:53:27.780  7017  7536 D A2dpStateMachine: Exit Disconnected: -1
09-09 14:53:27.781  7017  7017 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-09 14:53:27.786  7017  7017 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 14:53:27.786  7017  7017 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:53:27.786  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.788  7017  7017 D HidService: Received stop request...Stopping profile...
09-09 14:53:27.788  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.789  1031  1031 D BluetoothA2dp: Proxy object disconnected
09-09 14:53:27.789  1031  1031 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 14:53:27.791  7017  7017 D HealthService: Received stop request...Stopping profile...
09-09 14:53:27.791  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.794  7017  7017 D PanService: Received stop request...Stopping profile...
,09-09 14:53:27.797  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.799  7017  7017 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:53:27.800  7017  7017 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 14:53:27.800  7017  7017 D BtGatt.GattService: stop()
09-09 14:53:27.800  7017  7017 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 14:53:27.801  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.802  7017  7017 D BluetoothMapService: Received stop request...Stopping profile...
09-09 14:53:27.802  7017  7017 D BluetoothMapService: stop()
09-09 14:53:27.803  7017  7017 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 14:53:27.803  7017  7017 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 14:53:27.804  7017  7017 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ac2431c
09-09 14:53:27.805  7017  7017 V BluetoothMapService: Handler(): got msg=4
09-09 14:53:27.805  7017  7017 D BluetoothMapService: MAP Service closeService in
09-09 14:53:27.805  7017  7017 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:53:27.805  7017  7017 V BluetoothMapService: MAP Service closeService out
09-09 14:53:27.807  7017  7481 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 14:53:27.807  7017  7481 D BluetoothAdapterProperties: Setting state to 10
09-09 14:53:27.807  7017  7481 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-09 14:53:27.810  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:27.810  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 14:53:27.810  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-09 14:53:27.811  7017  7481 I BluetoothAdapterState: Entering OffState
09-09 14:53:27.812  6882  6899 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 14:53:27.813  6882  6899 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:27.816  6882  6899 D BluetoothMap: onBluetoothStateChange: up=false
09-09 14:53:27.817  6882  6899 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:53:27.819  7017  7017 D HeadsetStateMachine: Unbinding service...
,09-09 14:53:27.822  7017  7017 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:53:27.822  7017  7017 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:53:27.822  7017  7017 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:53:27.822  7017  7017 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:53:27.822  7017  7017 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 14:53:27.822  7017  7017 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 14:53:27.822  7017  7017 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 14:53:27.823  6882  6899 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 14:53:27.824  7017  7017 I BluetoothA2dpServiceJni: cleanupNative
09-09 14:53:27.825  7017  7537 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 14:53:27.825  7017  7017 I GKI_LINUX: GKI_exit_task 2 done
09-09 14:53:27.825  7017  7017 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 14:53:27.826  1840  1856 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:27.827  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 14:53:27.827  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:27.828  6882  6899 D BluetoothPan: onBluetoothStateChange on: false
09-09 14:53:27.829  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:27.830  1840  2609 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 14:53:27.831  7017  7017 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 14:53:27.831  7017  7017 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 14:53:27.834  7017  7017 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 14:53:27.835  7017  7017 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:53:27.835  7017  7017 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 14:53:27.836  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 14:53:27.836  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 14:53:27.838  7017  7017 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 14:53:27.838  7017  7017 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 14:53:27.840  1031  1102 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 14:53:27.840  1031  1102 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 14:53:27.840  1031  1102 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2e9174bc mBinding = false
09-09 14:53:27.842  7017  7017 D BluetoothMapService: cleanup()
09-09 14:53:27.842  7017  7017 D BluetoothMapService: MAP Service closeService in
09-09 14:53:27.842  7017  7017 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 14:53:27.842  7017  7017 V BluetoothMapService: MAP Service closeService out
,09-09 14:53:27.845  1031  1102 D BluetoothManagerService: Sending unbind request.
09-09 14:53:27.850  7017  7485 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-09 14:53:27.850  7017  7017 I GKI_LINUX: GKI_exit_task 1 done
09-09 14:53:27.850  7017  7017 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 14:53:27.850  7017  7017 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 14:53:27.850  7017  7017 I art     : --- WEIRD: removing null entry 248
09-09 14:53:27.851  7017  7017 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-09 14:53:27.851  7017  7017 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 14:53:27.852  7017  7017 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 14:53:27.854  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-09 14:53:27.858  7017  7017 I art     : System.exit called, status: 0
09-09 14:53:27.858  7017  7017 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 14:53:27.879   314  1364 V AudioFlinger: 7017 died, releasing its sessions
09-09 14:53:27.879   314  1364 V AudioFlinger:  pid 1840 @ 0
09-09 14:53:27.879   314  1364 V AudioFlinger:  pid 3407 @ 1
09-09 14:53:27.879   314  1364 V AudioFlinger:  pid 3407 @ 2
,09-09 14:53:27.882  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-09 14:53:27.883  1927  2115 D LGBluetoothAPIService: Message: 101
09-09 14:53:27.883  1927  2115 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-09 14:53:27.883  1927  2115 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-09 14:53:27.883  1927  2115 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-09 14:53:27.884  6882  6882 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 14:53:27.886  1031  2036 I ActivityManager: Process com.android.bluetooth (pid 7017) has died
09-09 14:53:27.886  1031  2036 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-09 14:53:27.887  1031  2036 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
09-09 14:53:27.892  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:53:27.895  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:27.896  1927  2115 D LGBluetoothAPIService: Message: 2
09-09 14:53:27.896  1927  2115 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-09 14:53:27.897  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:27.898  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:27.905  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 14:53:27.905  6882  6882 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-09 14:53:27.910  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:53:27.923  1589  1589 D BluetoothAdapter: 321484614: getState() :  mService = null. Returning STATE_OFF
09-09 14:53:27.923  1589  1589 D BluetoothAdapter: 321484614: getState() :  mService = null. Returning STATE_OFF
,09-09 14:53:27.969  1031  1901 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7717 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 14:53:27.974  6882  6882 D DockEventReceiver: finishStartingService: stopping service,
,09-09 14:53:28.030  7717  7717 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 14:53:28.031  7717  7717 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:53:28.031  7717  7717 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 14:53:28.032  7717  7717 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 14:53:28.051  7717  7717 D BluetoothAdapterApp: Loading JNI Library
,09-09 14:53:28.087  7717  7717 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b338784 Instance Count = 1
,09-09 14:53:28.093  7717  7717 D BluetoothAdapterApp: onCreate
,09-09 14:53:28.119  7717  7717 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 14:53:28.119  7717  7717 D ProfileConfigQcom: Adding HeadsetService
09-09 14:53:28.119  7717  7717 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 14:53:28.119  7717  7717 D ProfileConfigQcom: Adding A2dpService
09-09 14:53:28.120  7717  7717 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 14:53:28.120  7717  7717 D ProfileConfigQcom: Adding HidService
09-09 14:53:28.120  7717  7717 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 14:53:28.120  7717  7717 D ProfileConfigQcom: Adding HealthService
09-09 14:53:28.121  7717  7717 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 14:53:28.122  7717  7717 D ProfileConfigQcom: [BTUI] PanService is supported
,09-09 14:53:28.122  7717  7717 D ProfileConfigQcom: Adding PanService
,09-09 14:53:28.122  7717  7717 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 14:53:28.123  7717  7717 D ProfileConfigQcom: Adding GattService
09-09 14:53:28.123  7717  7717 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 14:53:28.123  7717  7717 D ProfileConfigQcom: Adding BluetoothMapService
,09-09 14:53:28.124  7717  7717 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 14:53:28.125  7717  7717 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:28.127  7717  7717 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:28.127  7717  7717 V BluetoothPbapReceiver: ***********state = 10
,09-09 14:53:28.129  7717  7717 V LGMDMManagerInternal: Create singleton instance
,09-09 14:53:28.234  7717  7717 D LGBluetoothAPIServer: [BTUI] onCreate()
,09-09 14:53:28.235  7717  7717 D LGBluetoothAPIServer: [BTUI] onBind()
,09-09 14:53:28.323  1031  1098 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7743 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 14:53:28.324  1031  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d58b66 type 2 when 225509 android} when 225509
,09-09 14:53:28.330  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 14:53:28.331  1927  2115 D LGBluetoothAPIService: Message: 100
09-09 14:53:28.331  1927  2115 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 14:53:28.331  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 14:53:28.338  6882  6882 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-09 14:53:28.355  6882  6882 D BluetoothPermissionRequest: onReceive
09-09 14:53:28.358  6882  6882 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 14:53:28.358  6882  6882 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 14:53:28.361  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 14:53:28.367  7717  7717 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-09 14:53:28.374  7717  7717 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:53:28.377  7717  7717 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:28.378  7717  7717 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:28.378  7717  7717 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:28.379  7717  7717 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:28.379  7717  7717 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 14:53:28.388  6954  6954 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-09 14:53:28.412  7743  7743 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:53:28.438  7743  7743 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 14:53:28.475  7743  7743 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-09 14:53:28.475  7743  7743 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 14:53:28.476  7743  7743 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 14:53:28.476  7743  7743 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 14:53:28.476  7743  7743 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,09-09 14:53:28.478  7743  7743 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-09 14:53:28.484  7743  7743 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-09 14:53:28.492  7743  7743 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,09-09 14:53:28.492  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2772
09-09 14:53:28.494  7743  7743 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-09 14:53:28.502  7743  7743 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-09 14:53:28.513  7743  7743 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 14:53:28.514  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 14:53:28.514  7743  7743 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-09 14:53:28.558  7743  7743 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 14:53:28.558  7743  7743 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:28.568  7743  7743 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 14:53:28.569  7743  7743 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 14:53:28.569  7743  7743 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-09 14:53:28.569  7743  7743 V SoundPool: doLoad: loading sample sampleID=1
09-09 14:53:28.570  7743  7743 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 14:53:28.574  7743  7775 V SoundPool: Start decode
09-09 14:53:28.574  7743  7775 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-09 14:53:28.574  7743  7743 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 14:53:28.576   314  1364 V MediaPlayerService: decode(23, 10857164, 17813)
,09-09 14:53:28.576   314  1364 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,09-09 14:53:28.576   314  1364 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
,09-09 14:53:28.576   314  1364 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,09-09 14:53:28.576   314  1364 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 14:53:28.577   314  1364 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 14:53:28.577   314  1364 V MediaPlayerService: player type = 3
09-09 14:53:28.577   314  1364 V AwesomePlayer: AwesomePlayer create()
09-09 14:53:28.577  7743  7743 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:53:28.577  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:53:28.578   314  1364 V AwesomePlayer: reset_l() 
09-09 14:53:28.578   314  1364 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:28.578   314  1364 V AwesomePlayer: setAudioSink() 
09-09 14:53:28.578   314  1364 V AwesomePlayer: reset_l() 
,09-09 14:53:28.578   314  1364 V AudioCache: notify(0xb1432200, 8, 0, 0)
09-09 14:53:28.578   314  1364 V AudioCache: ignored
,09-09 14:53:28.578   314  1364 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:28.578   314  1364 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 14:53:28.579   314  1364 V AwesomePlayer: setDataSource_l dataSource
,09-09 14:53:28.579   314  1364 V LGParserOSAL: SniffLGParser start
09-09 14:53:28.579   314  1364 V LGParserOSAL: MainType:5, SubType=0
09-09 14:53:28.579   314  1364 V LGParserOSAL: #### check Mime : application/ogg
,09-09 14:53:28.579   314  1364 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 14:53:28.579   314  1364 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 14:53:28.591  7743  7743 V LGMDMManager: Create singleton instance
,09-09 14:53:28.637   314  1364 V LGParserOSAL: supported mime: application/ogg
,09-09 14:53:28.637   314  1364 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 14:53:28.637   314  1364 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 14:53:28.637   314  1364 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 14:53:28.637   314  1364 V AwesomePlayer: AudioTrack Setting
09-09 14:53:28.637   314  1364 V AwesomePlayer: AudioTrack Setting channelCount = 2
,09-09 14:53:28.637   314  1364 V AwesomePlayer: setAudioSource() 
09-09 14:53:28.637   314  1364 V MediaPlayerService: prepare
09-09 14:53:28.637   314  1364 V AwesomePlayer: prepareAsync_l() 
09-09 14:53:28.637   314  1364 V MediaPlayerService: wait for prepare
09-09 14:53:28.638   314  7777 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 14:53:28.638   314  7777 V AwesomePlayer: initAudioDecoder() 
09-09 14:53:28.638   314  7777 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:53:28.638   314  7777 V AudioSystem: isOffloadSupported()
09-09 14:53:28.638   314  7777 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:53:28.638   314  7777 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:53:28.638   314  7777 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:53:28.639   314  7777 V AwesomePlayer: getUseOffload() = 0 
09-09 14:53:28.639   314  7777 V OMXCodec: OMXCodec::Create
09-09 14:53:28.639   314  7777 V OMXCodec: findMatchingCodecs()
09-09 14:53:28.639   314  7777 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 14:53:28.639   314  7777 V OMXCodec: matchingCodecs.size()=1
09-09 14:53:28.639   314  7777 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 14:53:28.644   314  7777 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 14:53:28.644   314  7777 V LGCodecAdapter: LG Codec Adapter start
,09-09 14:53:28.645   314  7777 V OMXCodec: OMXCodec Createtor
09-09 14:53:28.645   314  7777 V OMXCodec: setComponentRole
09-09 14:53:28.646   314  7777 V OMXCodec: configureCodec protected=0
09-09 14:53:28.646   314  7777 V LGCodecAdapter: called getLGCodecSpecificData
09-09 14:53:28.646   314  7777 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 14:53:28.646   314  7777 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 14:53:28.646   314  7777 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 14:53:28.647   314  7777 V LGCodecOSAL: Not support LGCodec
09-09 14:53:28.648   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:53:28.648   314  7777 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 14:53:28.648   314  7777 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 14:53:28.648   314  7777 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 14:53:28.649   314  7777 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 14:53:28.649   314  7777 V AudioSystem: isOffloadSupported()
09-09 14:53:28.649   314  7777 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 14:53:28.649   314  7777 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 14:53:28.649   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 14:53:28.649   314  7777 V OMXCodec: init()
09-09 14:53:28.650   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 14:53:28.650   314  7777 V OMXCodec: allocateBuffers
09-09 14:53:28.650   314  7777 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 14:53:28.650   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 14:53:28.650   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
09-09 14:53:28.650   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-09 14:53:28.650   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
09-09 14:53:28.651   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-09 14:53:28.651   314  7777 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:53:28.651   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:53:28.651   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 14:53:28.651   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-09 14:53:28.651   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-09 14:53:28.651   314  7777 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
09-09 14:53:28.651   314  7777 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 14:53:28.651   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:53:28.651   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:53:28.652   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 14:53:28.652   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 14:53:28.652   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 14:53:28.652   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 14:53:28.652   314  7777 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 14:53:28.652   314  7777 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 14:53:28.652   ,314  7777 V AudioCache: notify(0xb1432200, 5, 0, 0)
09-09 14:53:28.652   314  7777 V AudioCache: ignored
09-09 14:53:28.652   314  7777 V AudioCache: notify(0xb1432200, 1, 0, 0)
09-09 14:53:28.652   314  7777 V AudioCache: prepared
09-09 14:53:28.652   314  1364 V AudioCache: wait - success
09-09 14:53:28.653   314  1364 V MediaPlayerService: start
09-09 14:53:28.653   314  1364 V AwesomePlayer: play_l() 
09-09 14:53:28.653   314  1364 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 14:53:28.653   314  1364 V AwesomePlayer: createAudioPlayer_l
09-09 14:53:28.653   314  1364 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 14:53:28.653   314  1364 V AwesomePlayer: startAudioPlayer_l() 
09-09 14:53:28.653   314  1364 D AudioPlayer: start of Playback, useOffload 0
09-09 14:53:28.653   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:53:28.653   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 14:53:28.658  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:53:28.660  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-09 14:53:28.661   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 14:53:28.661   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 14:53:28.661   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 14:53:28.661   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 14:53:28.661   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 14:53:28.661   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:53:28.662  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3935
09-09 14:53:28.663  7743  7743 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 14:53:28.664  7631  7646 I UEI.SmartControl: ------ IControl API: 11
09-09 14:53:28.665  7631  7646 I UEI.SmartControl: Registering callback...
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
,09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:28.666  7631  7689 I UEI.SmartControl: ------ IControl API: 19
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 14:53:28.666   314  7779 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 14:53:28.666   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 14:53:28.667   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
09-09 14:53:28.667   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-09 14:53:28.667   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 14:53:28.667   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd3d0 on output port
09-09 14:53:28.667  7631  7689 I UEI.SmartControl: Registering Services Ready callback...
09-09 14:53:28.667   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 14:53:28.667   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 14:53:28.667  7631  7689 I UEI.SmartControl: Notify client services are ready...
09-09 14:53:28.668   314  1364 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 14:53:28.668  7743  7759 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 14:53:28.668  7743  7773 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 14:53:28.668   314  1364 V AudioCache: notify(0xb1432200, 6, 0, 0)
09-09 14:53:28.668   314  1364 V AudioCache: ignored
09-09 14:53:28.668  7743  7773 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-09 14:53:28.668   314  1364 V MediaPlayerService: wait for playback complete
09-09 14:53:28.669   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.669   314  7780 V AudioCache: memcpy(0xac200000, 0xb57d8000, 4096)
09-09 14:53:28.669  7743  7743 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 14:53:28.669  7743  7743 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 14:53:28.669  7631  7647 I UEI.SmartControl: ------ IControl API: 8
09-09 14:53:28.671  7743  7743 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 14:53:28.671  7743  7743 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 14:53:28.671   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.671   314  7780 V AudioCache: memcpy(0xac201000, 0xb57d8000, 4096)
09-09 14:53:28.671  7743  7743 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 14:53:28.671   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.671  7743  7743 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp,
09-09 14:53:28.671   314  7780 V AudioCache: memcpy(0xac202000, 0xb57d8000, 4096)
09-09 14:53:28.672   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.672   314  7780 V AudioCache: memcpy(0xac203000, 0xb57d8000, 4096)
09-09 14:53:28.673  7743  7743 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 14:53:28.673   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.673   314  7780 V AudioCache: memcpy(0xac204000, 0xb57d8000, 4096)
09-09 14:53:28.673   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.673   314  7780 V AudioCache: memcpy(0xac205000, 0xb57d8000, 4096)
09-09 14:53:28.673  7743  7743 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 14:53:28.674   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.674   314  7780 V AudioCache: memcpy(0xac206000, 0xb57d8000, 4096)
,09-09 14:53:28.675  7743  7743 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 14:53:28.677   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.677   314  7780 V AudioCache: memcpy(0xac207000, 0xb57d8000, 4096)
09-09 14:53:28.677  7743  7743 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 14:53:28.677   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.677   314  7780 V AudioCache: memcpy(0xac208000, 0xb57d8000, 4096)
09-09 14:53:28.678  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 14:53:28.678   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.678   314  7780 V AudioCache: memcpy(0xac209000, 0xb57d8000, 4096)
09-09 14:53:28.679  7743  7743 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:53:28.679  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 14:53:28.680   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.680   314  7780 V AudioCache: memcpy(0xac20a000, 0xb57d8000, 4096)
09-09 14:53:28.680   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.680   314  7780 V AudioCache: memcpy(0xac20b000, 0xb57d8000, 4096)
09-09 14:53:28.680  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 14:53:28.681   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.681   314  7780 V AudioCache: memcpy(0xac20c000, 0xb57d8000, 4096)
09-09 14:53:28.681  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 14:53:28.681   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.682   314  7780 V AudioCache: memcpy(0xac20d000, 0xb57d8000, 4096)
09-09 14:53:28.682  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 14:53:28.682   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.682   314  7780 V AudioCache: memcpy(0xac20e000, 0xb57d8000, 4096)
09-09 14:53:28.682  7743  7743 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473425608682]
09-09 14:53:28.683   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.683   314  7780 V AudioCache: memcpy(0xac20f000, 0xb57d8000, 4096)
09-09 14:53:28.683   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.683   314  7780 V AudioCache: memcpy(0xac210000, 0xb57d8000, 4096)
09-09 14:53:28.684   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.684   314  7780 V AudioCache: memcpy(0xac211000, 0xb57d8000, 4096)
09-09 14:53:28.685  7743  7743 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-09 14:53:28.686   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.686   314  7780 V AudioCache: memcpy(0xac212000, 0xb57d8000, 4096)
09-09 14:53:28.687  1031  1722 I ActivityManager: Killing 6905:com.lge.sync/1000 (adj 15): empty #17
09-09 14:53:28.687   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.687   314  7780 V AudioCache: memcpy(0xac213000, 0xb57d8000, 4096)
09-09 14:53:28.688   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.688   314  7780 V AudioCache: memcpy(0xac214000, 0xb57d8000, 4096)
09-09 14:53:28.689   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.689   314  7780 V AudioCache: memcpy(0xac215000, 0xb57d8000, 4096)
09-09 14:53:28.690   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.690   314  7780 V AudioCache: memcpy(0xac216000, 0xb57d8000, 4096)
09-09 14:53:28.690   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.690   314  7780 V AudioCache: memcpy(0xac217000, 0xb57d8000, 4096)
09-09 14:53:28.691   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.691   314  7780 V AudioCache: memcpy(0xac218000, 0xb57d8000, 4096)
09-09 14:53:28.692   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.692   314  7780 V AudioCache: memcpy(0xac219000, 0xb57d8000, 4096)
09-09 14:53:28.693   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.693   314  7780 V AudioCache: memcpy(0xac21a000, 0xb57d8000, 4096)
09-09 14:53:28.693   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.693   314  7780 V AudioCache: memcpy(0xac21b000, 0xb57d8000, 4096)
09-09 14:53:28.694   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.694   314  7780 V AudioCache: memcpy(0xac21c000, 0xb57d8000, 4096)
09-09 14:53:28.694   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.694   314  7780 V AudioCache: memcpy(0xac21d000, 0xb57d8000, 4096)
09-09 14:53:28.695   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.695   314  7780 V AudioCache: memcpy(0xac21e000, 0xb57d8000, 4096)
09-09 14:53:28.695   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.695   314  7780 V AudioCache: memcpy(0xac21f000, 0xb57d8000, 4096)
09-09 14:53:28.696   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.696   314  7780 V AudioCache: memcpy(0xac220000, 0xb57d8000, 4096)
09-09 14:53:28.697   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.697   314  7780 V AudioCache: memcpy(0xac221000, 0xb57d8000, 4096)
09-09 14:53:28.697   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.697  1031  1530 D WifiService: Client connection lost with reason: 4
09-09 14:53:28.697   314  7780 V AudioCache: memcpy(0xac222000, 0xb57d8000, 4096)
09-09 14:53:28.698   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.698   314  7780 V AudioCache: memcpy(0xac223000, 0xb57d8000, 4096)
09-09 14:53:28.698   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.698   314  7780 V AudioCache: memcpy(0xac224000, 0xb57d8000, 4096)
,09-09 14:53:28.699   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.699   314  7780 V AudioCache: memcpy(0xac225000, 0xb57d8000, 4096)
09-09 14:53:28.699   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.699   314  7780 V AudioCache: memcpy(0xac226000, 0xb57d8000, 4096)
09-09 14:53:28.700   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.700   314  7780 V AudioCache: memcpy(0xac227000, 0xb57d8000, 4096)
09-09 14:53:28.701   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.701   314  7780 V AudioCache: memcpy(0xac228000, 0xb57d8000, 4096)
09-09 14:53:28.701   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.701   314  7780 V AudioCache: memcpy(0xac229000, 0xb57d8000, 4096)
09-09 14:53:28.702   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.702   314  7780 V AudioCache: memcpy(0xac22a000, 0xb57d8000, 4096)
09-09 14:53:28.703   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.703   314  7780 V AudioCache: memcpy(0xac22b000, 0xb57d8000, 4096)
09-09 14:53:28.703   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.703   314  7780 V AudioCache: memcpy(0xac22c000, 0xb57d8000, 4096)
09-09 14:53:28.704   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.704   314  7780 V AudioCache: memcpy(0xac22d000, 0xb57d8000, 4096)
09-09 14:53:28.705   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.705   314  7780 V AudioCache: memcpy(0xac22e000, 0xb57d8000, 4096)
09-09 14:53:28.707   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.708   314  7780 V AudioCache: memcpy(0xac22f000, 0xb57d8000, 4096)
09-09 14:53:28.708   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.708   314  7780 V AudioCache: memcpy(0xac230000, 0xb57d8000, 4096)
09-09 14:53:28.708   314  7780 V AudioCache: write(0xb57d8000, 4096)
09-09 14:53:28.708   314  7780 V AudioCache: memcpy(0xac231000, 0xb57d8000, 4096)
09-09 14:53:28.708   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 14:53:28.708   314  7780 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 14:53:28.708   314  7780 V AwesomePlayer: postAudioEOS() 
09-09 14:53:28.708   314  7780 V AudioCache: write(0xb57d8000, 280)
09-09 14:53:28.708   314  7780 V AudioCache: memcpy(0xac232000, 0xb57d8000, 280)
09-09 14:53:28.710   314  7777 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 14:53:28.710   314  7777 V AwesomePlayer: onStreamDone
09-09 14:53:28.710   314  7777 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 14:53:28.710   314  7777 V AudioCache: notify(0xb1432200, 2, 0, 0)
09-09 14:53:28.710   314  7777 V AudioCache: playback complete
09-09 14:53:28.710   314  7777 V AwesomePlayer: pause_l() 
09-09 14:53:28.710   314  7777 V AudioCache: notify(0xb1432200, 7, 0, 0)
09-09 14:53:28.710   314  7777 V AudioCache: ignored
09-09 14:53:28.710   314  7777 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:28.710   314  1364 V AudioCache: wait - success
09-09 14:53:28.710   314  1364 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 14:53:28.710  7743  7781 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 14:53:28.711   314  7777 D AudioPlayer: Pause Playback at 1068125
09-09 14:53:28.712   314  1364 V AwesomePlayer: reset_l() 
09-09 14:53:28.712   314  1364 V AudioCache: notify(0xb1432200, 8, 0, 0)
09-09 14:53:28.712   314  1364 V AudioCache: ignored
09-09 14:53:28.712   314  1364 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:28.712   314  1364 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 14:53:28.712   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 14:53:28.712   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 14:53:28.712   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 14:53:28.712   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-09 14:53:28.712   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd3d0 on port 1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 14:53:28.713   314  7779 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 14:53:28.713   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 14:53:28.713   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 14:53:28.713   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 14:53:28.714   314  1364 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 14:53:28.714   314  1364 D AudioPlayer: AudioPlayer releasing audio source
09-09 14:53:28.714   314  1364 D AudioPlayer: AudioPlayer done releasing audio source
09-09 14:53:28.714   314  1364 V AwesomePlayer: reset_l() 
09-09 14:53:28.714   314  1364 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:28.714   314  1364 V AwesomePlayer: ~AwesomePlayer call
09-09 14:53:28.715   314  1364 V AwesomePlayer: reset_l() 
09-09 14,:53:28.715   314  1364 V AwesomePlayer: cancelPlayerEvents
09-09 14:53:28.715  7743  7775 V SoundPool: close(31)
09-09 14:53:28.715  7743  7775 V SoundPool: pointer = 0x9fe36000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 14:53:28.756  1031  2000 W libprocessgroup: failed to open /acct/uid_1000/pid_6905/cgroup.procs: No such file or directory
,09-09 14:53:28.770  7743  7743 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-09 14:53:28.771  7743  7743 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 14:53:28.772  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 14:53:28.773  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 14:53:28.774  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 14:53:28.774  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 14:53:28.775  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-09 14:53:28.785  7743  7743 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 14:53:29.800  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:29.800  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:29.943  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 14:53:30.005  1031  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 14:53:30.055  1031  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7798 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 14:53:30.061  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 14:53:30.062  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 14:53:30.072  1031  1031 D administrator: Handling package changes for user 0
,09-09 14:53:30.091  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 14:53:30.157  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 14:53:30.160  7798  7798 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 14:53:30.197  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 14:53:30.197  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 14:53:30.243  7798  7798 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:30.243  7798  7798 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:30.263  1031  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:53:30.270  1031  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 14:53:30.279  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 14:53:30.281  2491  2491 V GmsNetworkLocationProvi: DISABLE
,09-09 14:53:30.314  1031  1097 D LocationProviderProxy: applying state to connected service
,09-09 14:53:30.317  2491  2491 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-09 14:53:30.363  7798  7842 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 14:53:30.363  7798  7842 I Babel   : MmsConfig.loadMmsSettings
,09-09 14:53:30.372  7798  7842 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 14:53:30.372  7798  7842 I Babel   : MmsConfig.loadFromDatabase
,09-09 14:53:30.401  7798  7842 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-09 14:53:30.401  7798  7842 I Babel   : MmsConfig.loadFromResources
09-09 14:53:30.403  7798  7842 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-09 14:53:30.404  7798  7842 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 14:53:30.417  7798  7798 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:30.417  7798  7840 W AudioCapabilities: Unsupported mime audio/evrc
09-09 14:53:30.419  7798  7840 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 14:53:30.421  7798  7840 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 14:53:30.438  7798  7840 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-09 14:53:30.441  7798  7840 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 14:53:30.444  7798  7840 W AudioCapabilities: Unsupported mime audio/evrc
09-09 14:53:30.446  1805  7844 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 14:53:30.447  1805  7844 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-09 14:53:30.453  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 14:53:30.461  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@bbbc7ee
09-09 14:53:30.461  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 14:53:30.461  7077  7077 D AppUp4:CustFacade: isPhone : true
09-09 14:53:30.461  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
09-09 14:53:30.461  7077  7077 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 14:53:30.464  1805  4689 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-09 14:53:30.474  7798  7840 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-09 14:53:30.486  7798  7840 W VideoCapabilities: Unsupported mime video/divx
,09-09 14:53:30.490  7798  7840 W VideoCapabilities: Unsupported mime video/divx311
09-09 14:53:30.492  7798  7840 W VideoCapabilities: Unsupported mime video/divx4
09-09 14:53:30.500  7798  7840 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 14:53:30.505  1031  1561 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7848 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-09 14:53:30.511  1031  1726 I ActivityManager: Killing 7111:com.lge.email/u0a23 (adj 15): empty #17
09-09 14:53:30.545  7798  7840 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 14:53:30.549  7798  7840 W AudioCapabilities: Unsupported mime audio/eac3
09-09 14:53:30.550  7798  7840 W AudioCapabilities: Unsupported mime audio/ac3
09-09 14:53:30.551  7798  7840 W AudioCapabilities: Unsupported mime audio/g726
09-09 14:53:30.552  7798  7840 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 14:53:30.553  7798  7840 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 14:53:30.554  7798  7840 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 14:53:30.555  7798  7840 W VideoCapabilities: Unsupported mime video/theora
09-09 14:53:30.557  7798  7840 W VideoCapabilities: Unsupported mime video/mjpg
09-09 14:53:30.595  1031  2037 W libprocessgroup: failed to open /acct/uid_10023/pid_7111/cgroup.procs: No such file or directory
,09-09 14:53:30.631  7848  7848 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:53:30.632  7848  7848 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 14:53:30.632  7848  7848 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 14:53:30.633  7848  7848 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 14:53:30.633  7848  7848 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 14:53:30.693  7848  7848 I SystemConfig: BUILD Country: EU
09-09 14:53:30.693  7848  7848 I SystemConfig: BUILD Operator: OPEN
,09-09 14:53:30.735  1031  1722 I ActivityManager: Killing 6980:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-09 14:53:30.844  1031  1531 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-09 14:53:30.854  1031  1962 W libprocessgroup: failed to open /acct/uid_10026/pid_6980/cgroup.procs: No such file or directory
,09-09 14:53:30.908  1031  1722 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7869 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 14:53:30.913  7848  7867 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,09-09 14:53:30.913  7848  7867 I SystemConfig: existFile = false
09-09 14:53:30.914  7848  7867 I SystemConfig: canReadFile = false
09-09 14:53:30.914  7848  7867 I SystemConfig: systemFeature RCS result false
09-09 14:53:30.914  7848  7867 D SystemConfig: refreshRcsSupport() :false
,09-09 14:53:30.961  7869  7869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 14:53:30.961  7869  7869 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 14:53:30.961  7869  7869 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 14:53:30.962  7869  7869 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:53:31.042  7869  7869 I AppConfig: Total System Memory = 2995761152
,09-09 14:53:31.049  7869  7869 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 14:53:31.151  1031  1726 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7888 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 14:53:31.153  1031  1726 I ActivityManager: Killing 6456:com.wsandroid.suite.lge/1000 (adj 15): empty #17
09-09 14:53:31.226  1031  1999 W libprocessgroup: failed to open /acct/uid_1000/pid_6456/cgroup.procs: No such file or directory
,09-09 14:53:31.462  7888  7888 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-09 14:53:31.583  7888  7888 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:31.584  7888  7888 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 14:53:31.638  7888  7888 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-09 14:53:31.658  7888  7888 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 14:53:31.659  7888  7888 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 14:53:31.679  7888  7888 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-09 14:53:31.679  7888  7888 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-09 14:53:31.709  1031  1901 I ActivityManager: Killing 7148:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-09 14:53:31.748  1031  2037 W libprocessgroup: failed to open /acct/uid_10046/pid_7148/cgroup.procs: No such file or directory
,09-09 14:53:31.758  4551  7931 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-09 14:53:31.759  2836  2852 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-09 14:53:31.761  2836  2852 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29426abd on behalf of 7888
09-09 14:53:31.823  1031  1047 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7932 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 14:53:31.869  7888  7888 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-09 14:53:31.889  7888  7888 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-09 14:53:31.924  7932  7932 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 14:53:31.947  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-09 14:53:31.947  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 14:53:31.947  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 14:53:31.947  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 14:53:31.947  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-09 14:53:31.947  7932  7932 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-09 14:53:31.973  1031  1722 I ActivityManager: Killing 7170:com.android.chrome/u0a57 (adj 15): empty #17
,09-09 14:53:32.018  1031  1901 W libprocessgroup: failed to open /acct/uid_10057/pid_7170/cgroup.procs: No such file or directory
,09-09 14:53:32.039  7631  7688 D UEI.SmartControl: Internal timer expired: 1
09-09 14:53:32.039  7631  7688 D UEI.SmartControl: unbind internal service
,09-09 14:53:32.233  1031  2036 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:53:32.273  4551  7931 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 515 ms] updated apps [took 515 ms] 
,09-09 14:53:32.292  7631  7685 D serial_port: close(fd = 25)
,09-09 14:53:32.297  7631  7685 I UEI.SmartControl: Serial port is closed.
,09-09 14:53:32.821  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 14:53:32.822  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4166250 added. We now have 6 listener(s)
09-09 14:53:32.822  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 14:53:32.839  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:32.839  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@295c6c49 added. We now have 7 listener(s)
09-09 14:53:32.839  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:32.843  6745  6823 I System.out: IsBluetoothEnabled
,09-09 14:53:32.848  1031  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:32.848  1031  1723 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-09 14:53:32.849  1031  1102 D BluetoothManagerService: Message: 2
09-09 14:53:32.852  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:32.854  1031  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:32.854  1031  1726 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 14:53:32.870  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:32.870  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:32.870  1031  1031 D Ulp_jni : JNI:system_update. Event-4
09-09 14:53:32.871  1031  1102 D BluetoothManagerService: Message: 1
09-09 14:53:32.871  1031  1102 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 14:53:32.897  1031  1102 D BluetoothManagerService: Message: 20
09-09 14:53:32.897  1031  1102 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10db9572:true
,09-09 14:53:32.902  7717  7717 D BluetoothAdapterState: make
09-09 14:53:32.907  7717  7717 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 14:53:32.907  7717  7717 I bluedroid-qcom: init
09-09 14:53:32.909  7717  7976 I BluetoothAdapterState: Entering OffState
09-09 14:53:32.909  7717  7717 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 14:53:32.909  7717  7717 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 14:53:32.909  7717  7717 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 14:53:32.909  7717  7717 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 14:53:32.909  7717  7717 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 14:53:32.911  7717  7717 I bluedroid-qcom: get_profile_interface socket
09-09 14:53:32.911  7717  7717 I bluedroid-qcom: get_profile_interface map_client
,09-09 14:53:32.916  7717  7980 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 14:53:32.919  7717  7980 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 14:53:32.914  7979  7979 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:32.914  7979  7979 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:32.931  7979  7979 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 14:53:32.931  7979  7979 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 14:53:32.931  7979  7979 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-09 14:53:32.935  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 14:53:32.935  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:53:32.936  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:53:32.936  1031  1102 D BluetoothManagerService: Message: 40
09-09 14:53:32.936  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 14:53:32.937  7717  7732 I bluedroid-qcom: config_hci_snoop_log
09-09 14:53:32.938  1031  1102 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 14:53:32.938  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 14:53:32.940  7979  7979 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 14:53:32.946  7717  7976 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-09 14:53:32.949  7979  7979 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 14:53:32.949  7979  7979 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 14:53:32.965  7717  7980 D BluetoothAdapterProperties: Name is: G3
,09-09 14:53:32.968  7717  7976 D BluetoothAdapterProperties: Setting state to 11
09-09 14:53:32.969  7717  7976 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 14:53:32.970  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:32.970  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 14:53:32.970  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 14:53:32.974  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:32.974  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:32.978  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:32.982  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 14:53:32.990  7717  7717 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:32.990  7717  7717 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:32.990  7717  7717 V BluetoothPbapReceiver: ***********state = 11
,09-09 14:53:32.997  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:53:33.016  7717  7976 I LGBluetoothServiceJni: classInitNative: succeeds
,09-09 14:53:33.028  6882  6882 D BluetoothPermissionRequest: onReceive
09-09 14:53:33.033  7717  7976 D BluetoothBondStateMachine: make
09-09 14:53:33.033  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 14:53:33.040  7717  7976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.040  7717  7976 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 14:53:33.040  7717  7976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.040  7717  7976 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 14:53:33.041  7717  7976 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 14:53:33.041  7717  7717 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:33.041  7717  7994 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 14:53:33.043  7717  7717 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:33.043  7717  7717 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:33.043  7717  7717 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:33.043  7717  7717 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:33.043  7717  7717 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 14:53:33.045  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:53:33.051  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:33.054  7717  7717 D HeadsetService: Received start request. Starting profile...
09-09 14:53:33.055  7717  7717 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:53:33.055  7717  7717 D LGBluetoothHfpAdapter: Version 1.6
,09-09 14:53:33.058  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:33.058  7717  7717 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 14:53:33.059  7717  7717 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 14:53:33.060  7717  7717 D HeadsetStateMachine: make
,09-09 14:53:33.064  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:33.069  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:33.074  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 14:53:33.080  7717  7976 E BluetoothAdapterService: File transfer profiles supported!!
09-09 14:53:33.097  7717  7976 V LGMDMManager: Create singleton instance
,09-09 14:53:33.100  7717  7976 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 14:53:33.101  7717  7717 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:33.101  7717  7717 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:53:33.107  7717  7717 D HeadsetStateMachine: max_hf_connections = 1
09-09 14:53:33.107  7717  7717 I bluedroid-qcom: get_profile_interface handsfree
09-09 14:53:33.109  7717  7717 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-09 14:53:33.110   314  1364 V AudioPolicyService: registerClient() client 0xb558a8e0, uid 1002
09-09 14:53:33.111   314  1365 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:53:33.111   314  1365 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:53:33.111   314  1365 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:53:33.111  7717  7717 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 14:53:33.111   314  1703 V AudioFlinger: registerClient() client 0xb1433148, pid 7717
09-09 14:53:33.112   314  1359 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:33.112   314  1359 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:33.112  7717  7717 V ToneGenerator: Create Track: 0xb4928a80
09-09 14:53:33.112  7717  7717 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 14:53:33.112  7717  7717 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 14:53:33.112  1589  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:33.112  1589  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:33.112  1840  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:33.112  1840  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:33.112   314  1360 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:33.112   314  1360 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:33.112  3407  4804 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:33.112  3407  4804 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:33.113  3407  4804 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:33.113  3407  4804 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:33.113  7717  7733 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:33.113  7717  7733 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 14:53:33.113  1589  2079 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:33.113  1589  2079 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:33.113  7717  7733 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:33.113  7717  7733 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 14:53:33.113  1840  2609 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:33.113  1840  2609 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:33.113  1031  1046 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 14:53:33.113  1031  1046 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 14:53:33.113  1031  1046 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 14:53:33.113   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:53:33.113  1031  1046 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 14:53:33.113   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 14:53:33.113   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:53:33.113   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:53:33.114   314  1703 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 14:53:33.114   314  1365 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 14:53:33.114   314  1365 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 14:53:33.114   31,4  1365 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 14:53:33.114   314  1365 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 14:53:33.114  7717  7717 V AudioSystem: getLatency() output 2, latency 50
09-09 14:53:33.114  7717  7717 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 14:53:33.114  7717  7717 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 14:53:33.114   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:53:33.114   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:53:33.114   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 14:53:33.114   314   314 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 14:53:33.114   314   314 V AudioFlinger: createTrack() lSessionId: 23
09-09 14:53:33.115  7717  7717 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 14:53:33.116   314  1364 V AudioFlinger: acquiring 23 from 7717, for 7717
09-09 14:53:33.116   314  1364 V AudioFlinger:  added new entry for 23
09-09 14:53:33.116  7717  7717 V ToneGenerator: ToneGenerator INIT OK, time: 230371
09-09 14:53:33.116  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.116  7717  7997 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 14:53:33.117  7717  7997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 14:53:33.117  7717  7997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 14:53:33.117  7717  7997 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 14:53:33.117   314  1703 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7717
09-09 14:53:33.118   314  1703 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 14:53:33.118   314  1703 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 14:53:33.118   314  1703 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 14:53:33.118   314  1703 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 14:53:33.118   314  1703 V voice   : voice_set_parameters: exit with code(0)
09-09 14:53:33.118   314  1703 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 14:53:33.118   314  1703 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 14:53:33.118   314  1703 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 14:53:33.118   314  1703 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 14:53:33.118   314  1703 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 14:53:33.118   314  1703 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 14:53:33.118  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.118  7717  7997 V ToneGenerator: ToneGenerator destructor
09-09 14:53:33.118  7717  7997 V ToneGenerator: stopTone
09-09 14:53:33.118  7717  7997 V ToneGenerator: Delete Track: 0xb4928a80
09-09 14:53:33.119  7717  7997 V AudioTrack: ~AudioTrack, releasing session id from 7717 on behalf of 7717
09-09 14:53:33.119   314  1364 V AudioFlinger: releasing 23 from 7717 for 7717
09-09 14:53:33.119   314  1364 V AudioFlinger:  decremented refcount to 0
09-09 14:53:33.119   314  1364 V AudioFlinger: purging stale effects
09-09 14:53:33.119   314  1364 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 14:53:33.119   314  1364 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 14:53:33.119   314  1110 V AudioPolicyService: AudioCommandThread() waking up
09-09 14:53:33.119   314  1110 V AudioPolicyService: AudioComm,andThread() processing release output 2
09-09 14:53:33.119   314  1110 V AudioPolicyManager: releaseOutput() 2
09-09 14:53:33.119   314  1110 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 14:53:33.119   314  1364 V AudioFlinger: PlaybackThread::Track destructor
09-09 14:53:33.119   314  1364 V AudioFlinger: removeClient_l() pid 7717, calling pid 314
09-09 14:53:33.120  7717  7717 D A2dpService: Received start request. Starting profile...
09-09 14:53:33.121  7717  7717 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 14:53:33.122  7717  7717 V Avrcp   : make
09-09 14:53:33.122  7717  7717 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 14:53:33.122  7717  7717 I bluedroid-qcom: get_profile_interface avrcp
09-09 14:53:33.123  1031  1963 W Process : Unable to open /proc/7999/status
09-09 14:53:33.132  7717  7717 V AudioManager: registerRemoteController: size of Media player list: 0
09-09 14:53:33.135  7717  7717 E AudioManager: No RCC entry present to update
09-09 14:53:33.135  7717  7717 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 14:53:33.139  7717  7717 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 14:53:33.140  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 14:53:33.141  7717  7717 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-09 14:53:33.145  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 14:53:33.274  1031  1962 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:53:33.274  1031  1962 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:53:33.378  1031  1963 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 14:53:33.386  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 14:53:33.391  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 14:53:33.391  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:53:33.392  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 14:53:33.393  7717  7717 I BluetoothA2dpServiceJni: classInitNative
09-09 14:53:33.393  7717  7717 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:53:33.393  7717  7717 D A2dpStateMachine: make
09-09 14:53:33.394  7717  7717 I bluedroid-qcom: get_profile_interface a2dp
09-09 14:53:33.395  7717  8009 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 14:53:33.401  7717  7717 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 14:53:33.401  7717  7717 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 14:53:33.402  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.402  7717  7717 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 14:53:33.404  7717  7717 D HidService: Received start request. Starting profile...
09-09 14:53:33.404  7717  7717 I bluedroid-qcom: get_profile_interface hidhost
09-09 14:53:33.404  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.405  7717  7717 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 14:53:33.415  7717  8008 D A2dpStateMachine: Enter Disconnected: -2
,09-09 14:53:33.415  7717  7717 D HealthService: Received start request. Starting profile...
09-09 14:53:33.417  7717  7717 I bluedroid-qcom: get_profile_interface health
09-09 14:53:33.417  7717  7717 I LGBluetoothHealthServiceJni: classInitNative: succeeds
,09-09 14:53:33.417  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.417  7717  7717 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 14:53:33.419  7717  7717 D PanService: Received start request. Starting profile...
09-09 14:53:33.419  7717  7717 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 14:53:33.419  7717  7717 I bluedroid-qcom: get_profile_interface pan,
,09-09 14:53:33.425  7717  7717 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 14:53:33.425  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.426  7717  7717 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 14:53:33.431  7717  7717 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 14:53:33.432  7717  7717 D BtGatt.GattService: Received start request. Starting profile...
,09-09 14:53:33.432  7717  7717 D BtGatt.GattService: start()
09-09 14:53:33.432  7717  7717 I bluedroid-qcom: get_profile_interface gatt
09-09 14:53:33.433  7717  7717 D BtGatt.AdvertiseManager: advertise manager created
09-09 14:53:33.438  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.440  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.440  7717  7717 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 14:53:33.441  7717  7717 V BluetoothMapService: BluetoothMapBinder()
09-09 14:53:33.441  7717  7717 D BluetoothMapService: Received start request. Starting profile...
09-09 14:53:33.441  7717  7717 D BluetoothMapService: start()
09-09 14:53:33.444  7717  7717 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 14:53:33.444  7717  7717 D BluetoothMapEmailAppObserver: createReceiver()
,09-09 14:53:33.446  7717  7717 D BluetoothMapEmailAppObserver: initObservers()
09-09 14:53:33.446  7717  7717 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 14:53:33.454  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:33.455  7717  7717 D HeadsetStateMachine: Proxy object connected
,09-09 14:53:33.456  7717  7717 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 14:53:33.457  7717  7717 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 14:53:33.461  7717  7717 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:33.461  7717  7997 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 14:53:33.462  7717  7997 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 14:53:33.462  7717  7997 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 14:53:33.464  7717  7717 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:33.466  7717  7717 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:33.470  7717  7717 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 14:53:33.475  7717  7717 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 14:53:33.476  7717  7717 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 14:53:33.480  7717  7717 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 14:53:33.480  7717  7717 V BluetoothMapService: Handler(): got msg=1
09-09 14:53:33.482  7717  7976 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 14:53:33.482  7717  7976 I bluedroid-qcom: enable
,09-09 14:53:33.482  7717  7976 I bt_hci_bdroid: init
09-09 14:53:33.482  7717  8024 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 14:53:33.483  7717  8024 I bt-btu  : btu_task pending for preload complete event
09-09 14:53:33.484  7717  7976 I bt_vendor: bt-vendor : init
09-09 14:53:33.484  7717  7976 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 14:53:33.484  7717  7976 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 14:53:33.484  7717  7976 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 14:53:33.484  7717  7976 D bt_userial_mct: userial_init
09-09 14:53:33.485  7717  7976 D bt_hci_bdroid: set_power 1
09-09 14:53:33.485  7717  7976 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 14:53:33.485  7717  7976 I bt_vendor: Starting hciattach daemon
09-09 14:53:33.485  7717  7976 I bt_vendor: try to set true
09-09 14:53:33.484  8028  8028 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:33.484  8028  8028 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:33.534  8031  8031 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 14:53:33.646  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 14:53:33.660  8038  8038 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:53:33.690  8040  8040 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:53:33.717  8041  8041 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 14:53:33.744  8043  8043 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 14:53:33.769  8047  8047 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 14:53:33.793  8049  8049 I libmdmdetect: ESOC framework not supported
,09-09 14:53:33.794  8049  8049 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 14:53:33.803  8049  8049 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-09 14:53:33.803  8049  8049 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 14:53:33.803  8049  8049 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 14:53:33.803  8049  8049 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 14:53:33.803  8049  8049 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 14:53:33.803  8049  8049 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 14:53:33.803  8049  8049 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 14:53:33.846  8049  8050 E QC-QMI  : qmi_client [8049] 15: failed to locate client data
09-09 14:53:33.847   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 14:53:33.847   450   450 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-09 14:53:33.877  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 14:53:33.892  8055  8055 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 14:53:33.948  7717  7976 I bt_vendor: bluetooth satus is on
,09-09 14:53:33.948  7717  7976 D bt_hci_bdroid: preload
09-09 14:53:33.949  7717  8027 D bt_userial_mct: userial_open(port:0)
09-09 14:53:33.949  7717  8027 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-09 14:53:33.954  7717  8027 I bt_vendor: Done intiailizing UART
09-09 14:53:33.958  7717  8027 I bt_vendor: Done intiailizing UART
09-09 14:53:33.958  7717  8027 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 14:53:33.958  7717  8027 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 14:53:33.959  7717  8057 D bt_userial_mct: Entering userial_read_thread()
09-09 14:53:33.960  7717  8024 I bt-btu  : btu_task received preload complete event
09-09 14:53:33.961  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 14:53:33.961  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 14:53:33.968  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-09 14:53:33.977  7717  8024 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 14:53:33.978  7717  8024 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 14:53:34.079  7717  8024 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-09 14:53:34.079  7717  8024 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c9061 
09-09 14:53:34.079  7717  8024 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c9061 
,09-09 14:53:34.117  7717  7980 E bt-btif : Calling BTA_HhEnable
09-09 14:53:34.117  7717  7980 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 14:53:34.117  7717  7980 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 14:53:34.124  1031  1031 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 14:53:34.125  7717  7980 D BluetoothAdapterProperties: Name is: G3
09-09 14:53:34.128  1031  1031 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 14:53:34.129  7717  7980 D BluetoothAdapterProperties: Scan Mode:20
09-09 14:53:34.129  7717  7980 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:53:34.129  7717  7980 D bt_hci_bdroid: postload
09-09 14:53:34.131  7717  7980 D bte_conf: Device ID record 1 : primary
09-09 14:53:34.131  7717  7980 D bte_conf:   vendorId            = 00c4
09-09 14:53:34.131  7717  7980 D bte_conf:   vendorIdSource      = 0001
09-09 14:53:34.131  7717  7980 D bte_conf:   product             = 13a1
09-09 14:53:34.131  7717  7980 D bte_conf:   version             = 1000
09-09 14:53:34.131  7717  7980 D bte_conf:   clientExecutableURL = 
09-09 14:53:34.132  7717  7980 D bte_conf:   serviceDescription  = 
09-09 14:53:34.132  7717  7980 D bte_conf:   documentationURL    = 
,09-09 14:53:34.139  7717  8027 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:34.139  7717  7980 D bte_conf: bte_load_did_conf no section named DID2.
09-09 14:53:34.146  7717  8027 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 14:53:34.147  7717  7976 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 14:53:34.147  7717  7976 D BluetoothAdapterProperties: ScanMode =  20
09-09 14:53:34.147  7717  7976 D BluetoothAdapterProperties: State =  11
09-09 14:53:34.147  7717  7976 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 14:53:34.147  7717  7976 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 14:53:34.148  7717  7976 D BluetoothAdapterProperties: Setting state to 12
09-09 14:53:34.148  7717  7976 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 14:53:34.151  7717  7980 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 14:53:34.144  8062  8062 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:34.154  1031  1102 D BluetoothManagerService: Message: 60
09-09 14:53:34.154  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 14:53:34.154  1031  1102 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-09 14:53:34.154  8062  8062 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:34.163  7717  8057 E bt_mct  : hci lib postload completed
,09-09 14:53:34.177  7717  7976 I BluetoothAdapterState: Entering On State
,09-09 14:53:34.183  7717  7980 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 14:53:34.183  7717  7980 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:34.195  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:53:34.200  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:34.204  7717  7976 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 14:53:34.204  7717  7976 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 14:53:34.204  7717  7976 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 14:53:34.207  7717  7976 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-09 14:53:34.213  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 14:53:34.213  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 14:53:34.213  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 14:53:34.214  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-09 14:53:34.214  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 14:53:34.214  7717  8024 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 14:53:34.214  7717  7980 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 14:53:34.224  6882  6899 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 14:53:34.231  7717  7976 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 14:53:34.241  7717  8024 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:34.241  7717  8024 W bt-smp  : Plain text(LSB ~ MSB) = 85 df 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:34.241  7717  8024 W bt-smp  : Encrypted text(LSB ~ MSB) = b7 06 d4 1e b0 e3 8f 4a 7a 02 2d 4c 85 6d d5 28 
09-09 14:53:34.241  7717  8024 W bt-btm  : Stopping oneshot timer
,09-09 14:53:34.253  6882  6899 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:34.273  8067  8067 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-09 14:53:34.279  6882  7584 D BluetoothMap: onBluetoothStateChange: up=true
09-09 14:53:34.283  6882  6900 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:53:34.287  6882  6899 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 14:53:34.289  7717  8024 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:34.289  7717  8024 W bt-smp  : Plain text(LSB ~ MSB) = 9b e0 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:34.289  7717  8024 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 2f f1 e0 dd e2 de 9a 8c 49 af 4a 96 13 9c 40 
09-09 14:53:34.289  7717  8024 W bt-btm  : Stopping oneshot timer
09-09 14:53:34.292  1840  2417 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:34.294  1840  1840 D BluetoothHeadset: Proxy object connected
09-09 14:53:34.294  1031  1102 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 14:53:34.295  6882  6882 D BluetoothInputDevice: Proxy object connected
09-09 14:53:34.295  6882  6882 D HidProfile: Bluetooth service connected
09-09 14:53:34.296  1031  1031 D BluetoothA2dp: Proxy object connected
09-09 14:53:34.300  1840  2609 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:53:34.321  7717  8024 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:34.321  7717  8024 W bt-smp  : Plain text(LSB ~ MSB) = 2b 4f 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:34.321  7717  8024 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f bb ed 30 38 29 6e b1 74 37 63 a6 30 c8 f0 40 
09-09 14:53:34.321  7717  8024 W bt-btm  : Stopping oneshot timer
,09-09 14:53:34.324  6882  6882 D BluetoothHeadset: Proxy object connected
,09-09 14:53:34.325  6882  6882 D HeadsetProfile: Bluetooth service connected
09-09 14:53:34.328  6882  6882 D BluetoothMap: Proxy object connected
09-09 14:53:34.328  6882  6882 D MapProfile: Bluetooth service connected
,09-09 14:53:34.328  6882  6882 D BluetoothMap: getConnectedDevices()
09-09 14:53:34.329  7717  7732 V BluetoothMapService: getConnectedDevices()
09-09 14:53:34.330  6882  6882 D BluetoothA2dp: Proxy object connected
09-09 14:53:34.330  6882  6882 D A2dpProfile: Bluetooth service connected
09-09 14:53:34.335  7717  8024 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 14:53:34.335  7717  8024 W bt-smp  : Plain text(LSB ~ MSB) = 08 27 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:34.335  7717  8024 W bt-smp  : Encrypted text(LSB ~ MSB) = 14 d3 1a fa 00 f0 40 51 ce e7 ab a8 97 26 0e ac 
09-09 14:53:34.335  7717  8024 W bt-btm  : Stopping oneshot timer
,09-09 14:53:34.347  7717  8024 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-09 14:53:34.347  7717  8024 W bt-smp  : Plain text(LSB ~ MSB) = 49 4b 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 14:53:34.347  7717  8024 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d 06 9a 96 1b b2 9a d5 8e b3 2c 74 e2 cc 6c 5b 
09-09 14:53:34.347  7717  8024 W bt-btm  : Stopping oneshot timer
,09-09 14:53:34.436  1031  1102 I art     : Explicit concurrent mark sweep GC freed 27550(1353KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.902ms total 128.033ms
09-09 14:53:34.437  1840  1840 D BluetoothHeadset: Proxy object connected
09-09 14:53:34.437  6882  7584 D BluetoothPan: onBluetoothStateChange on: true
09-09 14:53:34.437  6882  7584 D BluetoothPan: onBluetoothStateChange call bindService
,09-09 14:53:34.441  1031  1102 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 14:53:34.443  1031  1031 D BluetoothHeadset: Proxy object connected
09-09 14:53:34.443  1840  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 14:53:34.446  6882  6882 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 14:53:34.446  6882  6882 D PanProfile: Bluetooth service connected
09-09 14:53:34.447  1840  1840 D BluetoothHeadset: Proxy object connected
09-09 14:53:34.449  1031  1102 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 14:53:34.449  1031  1102 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-09 14:53:34.451  1031  1031 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 14:53:34.455  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.456  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 14:53:34.456  1927  2115 D LGBluetoothAPIService: Message: 1
09-09 14:53:34.456  1927  2115 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 14:53:34.456  1927  2115 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-09 14:53:34.456  1927  2115 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-09 14:53:34.460  1031  1102 D BluetoothManagerService: Message: 40
09-09 14:53:34.460  1031  1102 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 14:53:34.463  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:34.465  7717  7717 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.466  7717  7717 D BluetoothMapService: STATE_ON
09-09 14:53:34.467  6882  6882 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 14:53:34.468  6882  6882 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 14:53:34.475  6882  6882 D DockEventReceiver: finishStartingService: stopping service
09-09 14:53:34.481  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:34.481  7717  7717 V BluetoothPbapService: Pbap Service onCreate
09-09 14:53:34.481  7717  7717 V BluetoothPbapService: Starting PBAP service
09-09 14:53:34.483  7717  7717 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 14:53:34.483  7717  7717 V BluetoothPbapService: Pbap Service onBind
,09-09 14:53:34.484  6882  6882 D BluetoothPbap: Proxy object connected
09-09 14:53:34.484  6882  6882 D PbapServerProfile: Bluetooth service connected
09-09 14:53:34.485  7717  7717 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.485  7717  7717 V BluetoothPbapService: state: 12
09-09 14:53:34.485  7717  7717 V BluetoothMapService: Handler(): got msg=1
09-09 14:53:34.486  7717  7717 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 14:53:34.486  7717  7717 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 14:53:34.486  7717  7717 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.486  7717  7717 V BluetoothPbapReceiver: ***********state = 12
09-09 14:53:34.488  7717  7717 V BluetoothPbapService: Handler(): got msg=1
09-09 14:53:34.488  7717  7717 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 14:53:34.489  2199  2199 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 14:53:34.489  2199  2199 D c       : Getting all permits...
09-09 14:53:34.490  2199  2199 D a       : Opening database...
09-09 14:53:34.490  7717  8088 D BluetoothMapMasInstance: MAS initSocket()
09-09 14:53:34.491  7717  8089 V BluetoothPbapService: Pbap Service initSocket
09-09 14:53:34.492  7717  8088 D BluetoothMapMasInstance:   masId = 00
09-09 14:53:34.492  7717  8088 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 14:53:34.492  7717  8088 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 14:53:34.492  7717  8088 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 14:53:34.492  1031  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:34.492  1031  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:34.493  2199  2199 D a       : Opening database auth.proximity.permit_store...
09-09 14:53:34.494  2199  2199 D a       : Closing database...
09-09 14:53:34.494  7717  8089 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:34.494  7717  8088 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:53:34.499  7717  8089 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 14:53:34.500  7717  8089 V BluetoothPbapService: Succeed to create listening socket 
09-09 14:53:34.500  7717  8089 V BluetoothPbapService: Accepting socket connection...
09-09 14:53:34.500  7717  8088 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 14:53:34.500  7717  8088 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 14:53:34.500  7717  8088 D BluetoothMapMasInstance: Accepting socket connection...
09-09 14:53:34.500  7717  7980 D BluetoothAdapterProperties: Scan Mode:21
09-09 14:53:34.501  7717  7980 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 14:53:34.504  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:34.505  6882  6882 D BluetoothPermissionRequest: onReceive
09-09 14:53:34.507  6882  6882 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-09 14:53:34.508  6882  6882 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 14:53:34.511  7717  7717 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 14:53:34.512  7717  7717 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 14:53:34.518  7717  7717 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 14:53:34.551  7717  7717 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-09 14:53:34.552  7717  7717 V BtOppService: onCreate
,09-09 14:53:34.558  7717  7717 V BluetoothOppNotification: send message
09-09 14:53:34.563  7717  7717 V BtOppService: Starting RfcommListener
09-09 14:53:34.573  7717  7717 D BluetoothOppPreference: Dumping Names:  
09-09 14:53:34.573  7717  7717 D BluetoothOppPreference: {}
,09-09 14:53:34.573  7717  7717 D BluetoothOppPreference: Dumping Channels:  
09-09 14:53:34.573  7717  7717 D BluetoothOppPreference: {}
09-09 14:53:34.575  7717  7717 V BtOppService: onStartCommand
,09-09 14:53:34.582  7717  7717 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 14:53:34.583  7717  7717 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 14:53:34.589  7717  8093 V BtOppService: Deleted complete outbound shares, number =  0
,09-09 14:53:34.591  7717  8096 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:53:34.593  7717  8096 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:53:34.594  7717  8093 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 14:53:34.594  7717  7717 V BluetoothOppNotification: new notify threadi!
09-09 14:53:34.595  7717  8093 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 14:53:34.596  7717  7717 V BluetoothOppNotification: send delay message
09-09 14:53:34.598  7717  7717 V BtOppService: start RfcommListener
09-09 14:53:34.599  7717  8093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f0da2f1 on behalf of 
09-09 14:53:34.603  7717  8096 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27d9fed6 on behalf of 
09-09 14:53:34.603  7717  7717 V BtOppService: RfcommListener started
09-09 14:53:34.604  7717  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-09 14:53:34.607  7717  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12fae557 on behalf of 
09-09 14:53:34.608  7717  8097 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 14:53:34.608  7717  8098 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 14:53:34.609  1031  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:34.610  7717  8098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 14:53:34.611  7717  8096 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 14:53:34.611  7717  8098 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 14:53:34.611  7717  8098 V BtOppRfcommListener: Started RFCOMM listener....
09-09 14:53:34.611  7717  8098 I BtOppRfcommListener: Accept thread started.
09-09 14:53:34.611  7717  8098 V BtOppRfcommListener: Accepting connection...
09-09 14:53:34.612  7717  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 14:53:34.613  7717  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3efe5844 on behalf of 
09-09 14:53:34.614  7717  8097 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 14:53:34.615  7717  8097 V BluetoothOppNotification: outbound notification was removed.
09-09 14:53:34.615  7717  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:53:34.617  7717  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19c87d2d on behalf of 
09-09 14:53:34.618  7717  8097 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 14:53:34.619  7717  8097 V BluetoothOppNotification: inbound notification was removed.
09-09 14:53:34.619  7717  8097 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:53:34.620  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:34.620  7717  7717 V BluetoothFtpService: Ftp Service onCreate
09-09 14:53:34.620  7717  7717 I BluetoothFtpService: Ftp Service onCreate
09-09 14:53:34.620  7717  8097 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12de7ff3 on behalf of 
09-09 14:53:34.620  7717  7717 V BtOppService: ContentObserver received notification
09-09 14:53:34.621  7717  7717 V BluetoothFtpService: Ftp Service onStartCommand
09-09 14:53:34.621  7717  7717 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.621  7717  7717 V BluetoothFtpService: Starting Listening on sockets
09-09 14:53:34.622  7717  7717 V BtOppService: ContentObserver received notification
09-09 14:53:34.622  7717  7717 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 14:53:34.622  7717  7717 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 14:53:34.622  7717  7717 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 14:53:34.622  7717  7717 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.622  7717  7717 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 14:53:34.622  7717  7717 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 14:53:34.623  7717  8099 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 14:53:34.623  7717  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 14:53:34.624  7717  7717 V BluetoothFtpService: Handler(): got msg=1
09-09 14:53:34.625  7717  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3caab4b0 on behalf of 
09-09 14:53:34.625  7717  7717 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 14:53:34.625  7717  7717 V BluetoothFtpService: Ftp Service initSocket
09-09 14:53:34.626  7717  8099 V BluetoothOppNotification: update too frequent, put in queue
09-09 14:53:34.628  7717  8099 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 14:53:34.630  1031  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:34.631  7717  7717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:53:34.632  7717  7717 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-09 14:53:34.632  7717  7717 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 14:53:34.636  7717  8100 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 14:53:34.668  7717  7717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38d14b25
09-09 14:53:34.668  7717  7717 V BluetoothSapService: Sap Service onCreate
,09-09 14:53:34.670  7717  7717 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 14:53:34.671  7717  7717 V BluetoothSapService: state: 12
09-09 14:53:34.671  7717  7717 V BluetoothSapService: Starting SAP server process
09-09 14:53:34.673  7717  7717 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 14:53:34.664  8101  8101 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:34.664  8101  8101 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:34.677  7717  8102 V BluetoothSapService: Sap Service initRfcommSocket
09-09 14:53:34.679  1031  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:34.681  7717  8102 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 14:53:34.685  7717  8102 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-09 14:53:34.685  7717  8102 V BluetoothSapService: Succeed to create listening socket 
09-09 14:53:34.685  7717  8102 V BluetoothSapService: Accepting socket connection...
09-09 14:53:34.687  8101  8101 V BT_SAP  : Event pipe created
09-09 14:53:34.687  8101  8101 V BT_SAP  : create_server_socket qcom.sap.server
09-09 14:53:34.687  8101  8101 V BT_SAP  : created socket fd 6
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:34.904  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 14:53:34.909  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 14:53:34.914  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:34.914  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ece894e added. We now have 8 listener(s)
,09-09 14:53:34.914  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:34.927  1031  2037 D WifiServiceImplEx: setWifiEnabled: false pid=6745, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:53:34.928  1031  2037 D WifiService: setWifiEnabled: false pid=6745, uid=10118
09-09 14:53:34.928  1031  2037 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 14:53:34.939  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:34.941  1031  1722 D WifiServiceImplEx: setWifiEnabled: true pid=6745, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 14:53:34.941  1031  1722 D WifiService: setWifiEnabled: true pid=6745, uid=10118
09-09 14:53:34.941  1031  1722 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 14:53:34.954  1031  1524 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 14:53:34.954  1031  1524 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 14:53:34.956  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 14:53:34.956  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,09-09 14:53:34.956  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 14:53:34.956  1031  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 14:53:34.956  1031  1524 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 14:53:34.956  1031  1524 E WifiHW  : unknown target_country: EU , set to default
09-09 14:53:34.956  1031  1524 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 14:53:34.956  1031  1524 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 14:53:34.956  1031  1524 I WifiUtil: gEnableBmps=1
09-09 14:53:34.957  1031  1031 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 14:53:34.957  1031  1031 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 14:53:34.960  1031  1031 D Ulp_jni : JNI:system_update. Event-4
,09-09 14:53:35.544   310   875 D SoftapController: Softap fwReload - Ok
,09-09 14:53:35.554  1031  1524 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (591ms)
09-09 14:53:35.556  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:53:35.556  1031  1102 D Tethering: InitialState.processMessage what=4
09-09 14:53:35.557  1031  1102 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 14:53:35.565   310   875 D CommandListener: Setting iface cfg
09-09 14:53:35.565   310   875 D CommandListener: Trying to bring down wlan0
,09-09 14:53:35.569   310   875 D CommandListener: Clearing all IP addresses on wlan0
09-09 14:53:35.577  1031  1524 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-09 14:53:35.584  8122  8122 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:35.595  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:35.595  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:35.595  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 14:53:35.599  7717  7717 V BluetoothOppNotification: new notify threadi!
09-09 14:53:35.599  7717  7717 V BluetoothOppNotification: send delay message
09-09 14:53:35.594  8122  8122 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 14:53:35.661  7717  8123 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 14:53:35.662  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-09 14:53:35.662  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:53:35.662  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:53:35.663  6882  6882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:53:35.666  1031  1524 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 14:53:35.666  1031  1524 D WifiMonitor: connecting to supplicant
09-09 14:53:35.668  8122  8122 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 14:53:35.672  7717  8123 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@297e6bdc on behalf of 
09-09 14:53:35.673  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:35.674  7717  8123 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 14:53:35.676  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 14:53:35.684  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:35.684  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-09 14:53:35.688  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:53:35.689  6882  6882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:53:35.689  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:53:35.689  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:53:35.689  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:53:35.689  6882  6882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:53:35.690  6882  6882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:53:35.692  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:53:35.692  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:53:35.692  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:53:35.692  6882  6882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:53:35.693  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:53:35.693  6882  6882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:53:35.693  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 14:53:35.693  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:53:35.693  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:53:35.693  6882  6882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:53:35.694  6882  6882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:53:35.702  7717  8123 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-09 14:53:35.703  7717  8123 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37d924e5 on behalf of 
09-09 14:53:35.704  7717  8123 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 14:53:35.708  7717  8123 V BluetoothOppNotification: outbound notification was removed.
09-09 14:53:35.708  7717  8123 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 14:53:35.709  8122  8122 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 14:53:35.710  8122  8122 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 14:53:35.715  7717  8123 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ed0abba on behalf of 
09-09 14:53:35.716  7717  8123 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 14:53:35.718  7717  8123 V BluetoothOppNotification: inbound notification was removed.
09-09 14:53:35.718  7717  8123 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 14:53:35.720  7717  8123 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f07fa6b on behalf of 
,09-09 14:53:35.742  1031  1726 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8140 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 14:53:35.761   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 347us total 19.738ms
,09-09 14:53:35.777   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 383us total 15.471ms
09-09 14:53:35.790   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 332us total 12.700ms
,09-09 14:53:35.802  8122  8122 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 14:53:35.851  1031  1963 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8161 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 14:53:35.868  8122  8122 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 14:53:35.871  8140  8159 W FormManager: Network not available. Please check & try again.
09-09 14:53:35.873  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-09 14:53:35.874  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 14:53:35.874  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:53:35.875  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 14:53:35.875  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:53:35.875  1031  8180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 14:53:35.875  1031  1524 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 14:53:35.876  1031  8180 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 14:53:35.876  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 14:53:35.876  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 14:53:35.876  1031  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:35.876  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:53:35.876  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 14:53:35.876  1031  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:35.876  1031  1524 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 14:53:35.876  1031  1524 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 14:53:35.877  1031  1524 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 14:53:35.877  1031  1524 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 14:53:35.877  1031  1524 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 14:53:35.878  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:35.878  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:35.879  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:35.879  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:35.879  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 14:53:35.879  1031  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 14:53:35.879  1031  1524 E WifiStateMachine: useWiFiOffloading() : false
09-09 14:53:35.879  1031  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 14:53:35.879  1031  1524 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 14:53:35.880  1031  1524 D WifiNative-wlan0: SET update_config 1: returned true
09-09 14:53:35.880  1031  1524 D WifiConfigStore: Loading config and enabling all networks 
09-09 14:53:35.880  1031  1524 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 14:53:35.880  1031  1524 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 14:53:35.881  1927  1927 D WfdService: Waiting for WifiP2p enabling
09-09 14:53:35.881  1031  1031 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 14:53:35.882  1031  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 14:53:35.882  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:35.885  6745  6745 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:35.889  8140  8160 V FormManager: Network unavailable.
09-09 14:53:35.889  6745  6745 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:35.890  1031  1524 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 14:53:35.894  8140  8160 V FormManager: Network unavailable.
,09-09 14:53:35.900  1031  1524 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 14:53:35.900  1031  1524 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 14:53:35.901  1031  1524 D WifiStateMachine: enableVerboseLogging : level 2
09-09 14:53:35.901  1031  1524 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 14:53:35.902  1031  1524 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 14:53:35.902  1031  1524 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 14:53:35.902  1031  1524 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 14:53:35.902  1031  1524 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 14:53:35.902  1031  1524 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 14:53:35.903  1031  1524 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 14:53:35.903  1031  1524 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 14:53:35.903  1031  1524 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 14:53:35.903  1031  1524 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 14:53:35.903  1031  1524 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 14:53:35.904  1031  1524 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 14:53:35.904  1031  1524 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 14:53:35.905  1031  1524 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 14:53:35.905  1031  1769 I ActivityManager: Killing 7191:com.lge.drmservice/u0a62 (adj 15): empty #17
09-09 14:53:35.924  8161  8161 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:35.938  1031  1524 D WifiStateMachine: Setting OUI to DA-A1-19
,09-09 14:53:35.938  1031  1524 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-09 14:53:35.938  1031  1524 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 14:53:35.938  1031  1524 D WifiNative-HAL: Setting external_sim to 1
09-09 14:53:35.938  1031  1524 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 14:53:35.938  1031  1962 W libprocessgroup: failed to open /acct/uid_10062/pid_7191/cgroup.procs: No such file or directory
09-09 14:53:35.938  1031  1524 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 14:53:35.939  1031  1524 I WifiNative-HAL: startHal
09-09 14:53:35.939  1031  1524 D wifi    : setting scan oui 0xaf6bd040
09-09 14:53:35.939  1927  1927 D WfdsService: Supplicant Connection state is changed : true
09-09 14:53:35.939  1031  1524 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 14:53:35.939  1031  1524 I WifiNative-HAL: startHal
09-09 14:53:35.939  1031  1524 D wifi    : setting scan oui 0xaf6bd040
09-09 14:53:35.939  1927  2345 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 14:53:35.939  1927  2345 D WfdsService: Set the WFDS Monitor: true
09-09 14:53:35.939  1031  1524 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 14:53:35.939  1927  2345 D WfdsMonitor: WfdsMonitorThread create
09-09 14:53:35.939  7798  7798 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:35.939  1927  2345 D WfdsMonitor: WFDS Monitor is created and started
,09-09 14:53:35.939  1927  2345 D WfdsService: WiFi: Supplicant connection re-established
09-09 14:53:35.940  1031  1524 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 14:53:35.940  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 14:53:35.940  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 14:53:35.940  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 14:53:35.940  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:53:35.940  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:53:35.941  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:53:35.941  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 14:53:35.941  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 14:53:35.941  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 14:53:35.941  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:53:35.941  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:53:35.941  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:53:35.942  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 14:53:35.942  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 14:53:35.943  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 14:53:35.943  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 14:53:35.943  1927  8183 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 14:53:35.943  8122  8122 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 14:53:35.943  1927  8183 E CtrlSupplicant: Succeed to open control connection
09-09 14:53:35.944  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 14:53:35.944  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 14:53:35.944  1927  8183 E CtrlSupplicant: Succeed to open monitor connection
09-09 14:53:35.944  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 14:53:35.944  1031  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 14:53:35.944  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:53:35.945  1927  8183 D WfdsMonitor: Supplicant connection established
09-09 14:53:35.945  1031  1524 E WifiNative: : [233,185,887 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 14:53:35.945  1031  1524 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 14:53:35.945  1031  1524 D WifiNative-wlan0: RECONNECT: returned true
09-09 14:53:35.945  1031  1524 D WifiNative-wlan0: doString: [STATUS]
09-09 14:53:35.946  1927  2345 D WfdsService: Connected to the supplicant for wfds
09-09 14:53:35.946  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:53:35.946  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 14:53:35.946  1031  1524 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 14:53:35.946  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:35.947  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:35.947  1031  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:35.948  1031  1031 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 14:53:35.948  1031  1031 D RttService: SCAN_AVAILABLE : 3
09-09 14:53:35.948  1031  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:35.948  1031,  1542 I WifiNative-HAL: startHal
09-09 14:53:35.948  1031  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6bd040
09-09 14:53:35.948  1031  1542 D wifi    : failed to get capabilities : -3
09-09 14:53:35.948  1031  1542 E WifiScanningService: could not get scan capabilities
09-09 14:53:35.948  1031  1524 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 14:53:35.948  1031  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:35.948  1031  1524 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 14:53:35.949   310   875 D CommandListener: Setting iface cfg
09-09 14:53:35.949  1031  1524 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 14:53:35.949   310   875 D CommandListener: Trying to bring up p2p0
09-09 14:53:35.949  1031  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 14:53:35.949  1031  1521 D LGWifiP2pService: P2pEnablingState
09-09 14:53:35.949  1031  1524 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 14:53:35.949  1031  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:35.949  1031  1521 D LGWifiP2pService: P2p socket connection successful
09-09 14:53:35.949  1031  1521 D LGWifiP2pService: P2pEnabledState
09-09 14:53:35.949  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:35.949  1031  1521 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 14:53:35.949  1031  1524 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 14:53:35.950  1031  1524 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 14:53:35.950  1031  1524 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 14:53:35.950  1031  1524 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 14:53:35.950  8122  8122 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 14:53:35.950  1031  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 14:53:35.950  1031  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 14:53:35.951  1031  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 14:53:35.951  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 14:53:35.951  1927  1927 D WfdsService: WifiP2pState is changed : true
09-09 14:53:35.951  1927  2345 D WfdsService: Receive the WFDS_ENABLE Method
09-09 14:53:35.951  1927  2345 D WfdsService: Set the WFDS Monitor: true
09-09 14:53:35.951  1031  1521 D WifiNative-p2p0: SET device_name G3: returned true
09-09 14:53:35.951  1927  2345 D WfdsService: Connected to the supplicant for wfds
09-09 14:53:35.951  1031  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 14:53:35.951  1927  2345 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 14:53:35.951  1031  1521 D LGWifiP2pService: before postfix = G3
09-09 14:53:35.951  8122  8122 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 14:53:35.951  1031  1521 D WifiServerServiceExt: postfix byte check : 2
09-09 14:53:35.951  1927  2345 D WfdsService: selectPreferredScanChannel [36]
09-09 14:53:35.951  1031  1521 D LGWifiP2pService: after postfix = G3
09-09 14:53:35.951  1927  2345 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 14:53:35.951  1031  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 14:53:35.952  1031  1926 I ActivityManager: Killing 7221:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-09 14:53:35.952  1031  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 14:53:35.952  1031  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 14:53:35.952  1031  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 14:53:35.952  1031  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 14:53:35.953  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 14:53:35.953  1031  1524 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 14:53:35.953  1927  1927 D WfdsService: isConnected: false
09-09 14:53:35.954  1031  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 14:53:35.954  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 14:53:35.954  1031  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 14:53:35.954  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress
09-09 14:53:35.954  1031  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 14:53:35.955  1031  1524 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 14:53:35.955  1031  1524 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 14:53:35.956  1031  1524 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 14:53:35.956  8122  8122 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 14:53:35.956  1031  1524 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 14:53:35.957  1031  1524 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 14:53:35.957  1031  1524 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 14:53:35.957  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 14:53:35.958  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:53:35.959  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:35.959  8122  8122 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:53:35.960  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.960  1927  8183 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:35.960  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.960  1927  8183 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:35.961  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:53:35.961  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:35.961  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:35.961  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:35.961  1031  8180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:35.961  1031  8180 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.961  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.961  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.961  1031  8180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:35.961  1031  8180 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.961  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.961  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:35.964  1031  1524 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 14:53:35.965  1031  1524 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:53:35.965  1031  1524 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:53:35.966  1031  1524 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 14:53:35.966  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 14:53:35.966  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 14:53:35.966  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:35.966  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 14:53:35.966  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:35.966  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:35.966  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 14:53:35.966  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 14:53:35.967  1031  1524 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 14:53:35.967  1031  1524 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 14:53:35.967  1031  1524 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 14:53:35.967  1031  1524 D WifiNative-wlan0: doBoolean: SCAN
09-09 14:53:35.968  1031  1524 D WifiNative-wlan0: SCAN: returned false
09-09 14:53:35.968  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=233209  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:53:35.969  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 14:53:35.977  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 14:53:35.978  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 14:53:35.979  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1404dd20 Bundle[{}]
09-09 14:53:35.980  6745  6823 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 14:53:35.980  6745  6823 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 14:53:35.980  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 14:53:35.981  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 14:53:35.981  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 14:53:35.982  6745  6823 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 14:53:35.987  6745  6823 I System.out: Running OutgoingSocketThread
,09-09 14:53:35.988  6745  8185 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 861)
09-09 14:53:35.989  6745  8185 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50866
09-09 14:53:35.989  6745  8185 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 14:53:35.997  1031  1999 W libprocessgroup: failed to open /acct/uid_10085/pid_7221/cgroup.procs: No such file or directory
09-09 14:53:35.997  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=233239  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 14:53:35.998  1031  1524 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:35.998  1031  1524 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:35.999  1031  1524 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:35.999  1031  1524 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:36.001  1031  1524 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 14:53:36.002  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.002  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.003  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.003  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.003  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 14:53:36.003  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.004  1031  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 14:53:36.004  1031  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 14:53:36.004  1031  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 14:53:36.004  1031  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 14:53:36.004  1031  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 14:53:36.005  1031  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 14:53:36.005  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 14:53:36.005  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 14:53:36.005  1031  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 14:53:36.005  1031  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 14:53:36.005  1927  1927 D WfdsService: Update P2p Interface State: 3
09-09 14:53:36.005  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.006  1031  1031 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 14:53:36.015  1031  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 14:53:36.015  1031  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 14:53:36.017  8161  8161 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:36.019  1031  1521 D LGWifiP2pService: InactiveState
09-09 14:53:36.019  1031  1521 D LGWifiP2pService: InactiveState{ when=-55ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.019  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-55ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.019  1031  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 14:53:36.019  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 14:53:36.020  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 14:53:36.020  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:36.021  8122  8122 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 14:53:36.021  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.021  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.022  1031  8180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:53:36.022  1031  8180 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:36.022  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:36.022  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 14:53:36.022  1031  8180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:36.022  1031  8180 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.022  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-09 14:53:36.022  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.022  1031  8180 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:36.022  1031  8180 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.022  1031  8180 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.022  1031  8180 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 14:53:36.023  1031  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.023  1927  2345 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 14:53:36.024  1031  1521 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.024  1927  8183 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 14:53:36.024  1927  8183 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:36.024  1031  1031 E WifiServerServiceExt: No p2p device connected
09-09 14:53:36.024  1927  8183 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 14:53:36.025  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:36.032  8140  8187 W FormManager: Network not available. Please check & try again.
,09-09 14:53:36.036  8140  8188 V FormManager: Network unavailable.
09-09 14:53:36.038  8140  8188 V FormManager: Network unavailable.
09-09 14:53:36.043  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:36.043  4275  4275 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 14:53:36.045  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:53:36.048  4275  4275 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 14:53:36.051  4275  8189 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 14:53:36.053  4275  8190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 14:53:36.053  4275  8190 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 14:53:36.121  1031  1926 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8191 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 14:53:36.245  8191  8191 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 14:53:36.245  8191  8191 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 14:53:36.259  8191  8191 V [BNRBootReceiver]: Boot Receiver Return
09-09 14:53:36.260  8191  8191 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-09 14:53:36.305  1031  1963 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 14:53:36.307  1031  1963 I ActivityManager: Killing 7249:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-09 14:53:36.519  1031  2036 W libprocessgroup: failed to open /acct/uid_10093/pid_7249/cgroup.procs: No such file or directory
,09-09 14:53:36.551  8122  8122 E wpa_supplicant: USIM:  scard_init function
09-09 14:53:36.551  8122  8122 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 14:53:36.559  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 14:53:36.559  1031  8180 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 14:53:36.559  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 14:53:36.559  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-09 14:53:36.559  1031  8180 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 14:53:36.559  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 14:53:36.559  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-09 14:53:36.562  1031  1524 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:53:36.569  1031  1524 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:53:36.570  1031  1524 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:53:36.570  1031  1524 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-09 14:53:36.570  1031  1524 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 14:53:36.587  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=233829  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 14:53:36.595  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.595  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.597  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.599  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.599  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.599  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-09 14:53:36.610  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.610  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.610  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:53:36.611  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=233852  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 14:53:36.612  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.612  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 14:53:36.620  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.620  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 14:53:36.627  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.650  8209  8209 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:53:36.674  8209  8209 D PluginManager: init()
,09-09 14:53:36.680  8122  8122 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 14:53:36.685  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 14:53:36.685  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 14:53:36.686  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 14:53:36.686  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 14:53:36.686  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:36.686  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:36.689  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=233930  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:53:36.689  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=233930  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 14:53:36.690  1031  1524 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233931
09-09 14:53:36.690  1031  1524 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233931
09-09 14:53:36.690  1031  1524 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233932
09-09 14:53:36.691  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233932
09-09 14:53:36.691  1031  1524 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=233932
09-09 14:53:36.692  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=233933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-09 14:53:36.699  1031  1102 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 14:53:36.701  8122  8122 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:53:36.701  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:53:36.703  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:36.703  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:36.709  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 14:53:36.709  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:53:36.710  1031  8180 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 14:53:36.710  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 14:53:36.710  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:53:36.710  1031  8180 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 14:53:36.710  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:36.711  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-09 14:53:36.724  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.724  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.728  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:36.730  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.730  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.730  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 14:53:36.737  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=233979  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-09 14:53:36.746  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.746  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 14:53:36.746  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 14:53:36.747  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.747  1031  1031 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 14:53:36.748  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.748  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.749  1031  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=233991  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:53:36.750  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=233992  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 14:53:36.751  1031  1524 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=233992
09-09 14:53:36.751  1031  1524 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=233993
09-09 14:53:36.752  1031  1524 D WifiNative-wlan0: doString: [STATUS]
09-09 14:53:36.752  1031  8180 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 14:53:36.752  1031  8180 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 14:53:36.753  1031  1524 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,09-09 14:53:36.755  1031  1524 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 14:53:36.758  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.764  1031  1524 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 14:53:36.764  1031  1524 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-09 14:53:36.774  1031  1524 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 14:53:36.774  1031  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:53:36.774  1031  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:53:36.774  1031  1531 D ConnectivityService: Got NetworkAgent Messenger
09-09 14:53:36.774  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 14:53:36.774  1031  1531 D ConnectivityService: NetworkAgent connected
09-09 14:53:36.775  1031  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:53:36.775  1031  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:53:36.777  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.777  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.778  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:53:36.778  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.778  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.779  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 14:53:36.779  1031  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 14:53:36.779  1031  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 14:53:36.779  1031  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 14:53:36.779  1031  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 14:53:36.779  1031  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 14:53:36.784  1031  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-09 14:53:36.787   310   875 D CommandListener: Setting iface cfg
09-09 14:53:36.787  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.787  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.789  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.790  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.791  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 14:53:36.791  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.792  1031  1524 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 14:53:36.792  1031  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=234033  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:36.793  1031  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=234034  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:36.793  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=234034  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:36.794  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:36.794  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:36.795  1031  1524 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:36.795  1031  1524 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:36.795  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:36.795  1031  8252 D DhcpStateMachine: StoppedState
09-09 14:53:36.796  1031  8252 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.796  1031  8252 D DhcpStateMachine: WaitBeforeStartState
09-09 14:53:36.796  1031  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 14:53:36.797  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.797  1031  1031 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 14:53:36.798  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.798  1031  1031 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 14:53:36.799  1031  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=234040  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:36.800  1031  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=234041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:36.800  1031  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=234041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 14:53:36.801  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14112] from screen [on:0 period:251834273] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:53:36.802  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:251834274] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 14:53:36.802  1031  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 14:53:36.809  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.809  1031  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-09 14:53:36.809  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.810  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.810  1031  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.810  1031  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.811  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.811  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.812  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 14:53:36.813  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.813  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 14:53:36.814  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
09-09 14:53:36.814  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
09-09 14:53:36.814  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 14:53:36.815  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 14:53:36.815  1031  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 14:53:36.815  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 14:53:36.817  1031  1524 D WifiNative-wlan0: SET ps 0: returned true
09-09 14:53:36.817  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 14:53:36.817  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 14:53:36.818  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 14:53:36.818  1031  1524 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 14:53:36.818  1031  1524 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:53:36.818  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f87ffcb target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.818  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f87ffcb target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.818  1031  1524 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:53:36.818  1031  8252 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.818  1031  8252 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-09 14:53:36.820   310   875 D CommandListener: Setting iface cfg
09-09 14:53:36.820   310   875 D CommandListener: Trying to bring up wlan0
09-09 14:53:36.821  1031  1524 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 14:53:36.822  1031  1031 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 14:53:36.822  1031  1031 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 14:53:36.823  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.823  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.824  1031  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.824  1031  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.825  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.825  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 14:53:36.826  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 14:53:36.826  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 14:53:36.827  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 14:53:36.827  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 14:53:36.827  1031  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.827  1031  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.827  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 14:53:36.827  1031  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 14:53:36.827  1031  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 14:53:36.828  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 14:53:36.828  1031  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 14:53:36.828  1031  1524 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 14:53:36.844  1031  1524 D WifiNative-wlan0: SET ps 1: returned true
09-09 14:53:36.844  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 14:53:36.845  1031  1524 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:53:36.845  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 14:53:36.845  1031  1524 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 14:53:36.846  1031  1531 D ConnectivityService: ignoring duplicate network state non-change
,09-09 14:53:36.848  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.848  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.850  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.851  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.851  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.851  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 14:53:36.855  1031  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 14:53:36.856  1031  1531 D ConnectivityService: Adding iface wlan0 to network 102
09-09 14:53:36.857  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.857  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.857  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-09 14:53:36.861  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:53:36.863  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 14:53:36.864  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.864  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.864  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:53:36.866  1031  1031 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 14:53:36.866  1031  1524 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 14:53:36.871  1031  1031 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.871  1031  1031 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 14:53:36.871  1031  1031 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 14:53:36.872  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.872  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 14:53:36.874  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:36.882  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.883  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:53:36.883  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.887  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 14:53:36.887  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 14:53:36.888  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.888  1031  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 14:53:36.888  1031  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 14:53:36.890  1031  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 14:53:36.891   310   875 E Netd    : netlink response contains error (File exists)
09-09 14:53:36.891  1031  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 14:53:36.892  1031  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 14:53:36.892  1031  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 14:53:36.892  1031  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 14:53:36.893  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 14:53:36.893  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:53:36.893  1031  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 14:53:36.894  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.894  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 14:53:36.894  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 14:53:36.895  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 14:53:36.897  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 14:53:36.897   310  8257 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 14:53:36.897  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:36.898  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:36.898  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:53:36.898  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:36.898  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 14:53:36.898  1031  1531 D ConnectivityService: currentScore = 0, newScore = 20
09-09 14:53:36.898  1031  1531 D ConnectivityService:    accepting network in place of null
09-09 14:53:36.898  1031  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:36.899  1031  1524 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:36.899  1031  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:36.899  1840  1840 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:36.900  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:53:36.900  1031  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe8,0::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 14:53:36.900  1031  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 14:53:36.900  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 14:53:36.900  1031  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 14:53:36.900  1031  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 14:53:36.902  1031  1031 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 14:53:36.902  1031  1031 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 14:53:36.902  1031  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 14:53:36.902  1031  1031 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 14:53:36.902  1031  1031 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 14:53:36.903  1031  1531 D ConnectivityService: validation of new default Network = false
09-09 14:53:36.904  1031  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 14:53:36.904  1031  1531 D DSQN    : enableDataServiceNotify 
09-09 14:53:36.904  1031  1531 D DSQN    : start dsqn bin
,09-09 14:53:36.904  8259  8259 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:36.904  8259  8259 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:36.914  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 14:53:36.914  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:36.914  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:36.914  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:36.915  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:53:36.921  1031  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-09 14:53:36.929  8259  8259 E DSQN    : DSQN ssw
,09-09 14:53:36.934  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:36.936  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.937  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:36.942   310  8257 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 14:53:36.980   310  8257 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 14:53:36.990  6745  6823 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 862)
,09-09 14:53:36.990  6745  6823 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 862)
09-09 14:53:36.998  6745  6823 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 867)
09-09 14:53:37.000  6745  6823 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 14:53:37.000  6745  6823 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
,09-09 14:53:37.007  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.008  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1a6a6f added. We now have 2 listener(s)
09-09 14:53:37.009  1031  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.009   310   874 D LGDataListener: argv[0]=dsqncommand
,09-09 14:53:37.009   310   874 D LGDataListener: argv[1]=wlan0
09-09 14:53:37.009   310   874 D LGDataListener: argv[2]=1
09-09 14:53:37.009   310   874 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 14:53:37.010  1031  1100 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 14:53:37.010  1031  1100 D DSQN    : start to monitor internet connection
09-09 14:53:37.016  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.016  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.016  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.016  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.016  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2487537c added. We now have 9 listener(s)
,09-09 14:53:37.016  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.017  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:53:37.020  1031  8252 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 14:53:37.021  1031  8252 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 14:53:37.021  1031  8252 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 14:53:37.025  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:37.024  8265  8265 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:37.024  8265  8265 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:37.033  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 14:53:37.037  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.038  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:53:37.038  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.038  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40dec5a added. We now have 3 listener(s)
09-09 14:53:37.039  1031  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.041  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.044  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 12:53:37 GMT], X-Android-Received-Millis=[1473425617044], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473425617008]}
,09-09 14:53:37.045  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-09 14:53:37.045  1031  8251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 14:53:37.045  8265  8265 I dhcpcd  : version 5.5.6 starting
09-09 14:53:37.045  1031  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 14:53:37.045  1031  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 14:53:37.045  1031  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:37.045  1031  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:37.045  1031  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 14:53:37.045  1031  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 14:53:37.045  1031  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 14:53:37.045  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:37.045  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:37.045  1031  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:37.046  1031  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:37.046  1031  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 14:53:37.046  1031  1524 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:37.046  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 14:53:37.046  1031  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 14:53:37.046  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.047  1840  1840 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 14:53:37.047  8265  8265 E dhcpcd  : get_duid: m
09-09 14:53:37.047  8265  8265 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 14:53:37.047  8265  8265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 14:53:37.047  1840  1840 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 14:53:37.051  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.052  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.052  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.052  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.052  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8d3e8b added. We now have 10 listener(s)
09-09 14:53:37.052  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.053  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:37.053  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:37.053  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:37.053  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.053  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.053  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.053  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.053  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1a6a6f removed from the list
09-09 14:53:37.053  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.054  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2487537c removed from the list
09-09 14:53:37.054  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:37.054  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.055  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.055  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.056  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.056  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.056  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.056  6745  6823 E org.thaliproject.p2p.btconnect,orlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2487537c not in the list
09-09 14:53:37.056  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.056  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.057  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.057  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.057  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.057  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8d3e8b removed from the list
09-09 14:53:37.057  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.057  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 14:53:37.057  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.057  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.057  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40dec5a removed from the list
09-09 14:53:37.058  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.058  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b42b68 added. We now have 2 listener(s)
09-09 14:53:37.058  1031  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:53:37.060  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.060  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.060  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.060  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.060  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26605b81 added. We now have 9 listener(s),
09-09 14:53:37.061  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.061  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:53:37.064  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 14:53:37.071  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 14:53:37.072  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 14:53:37.073  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:37.076  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:37.078  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.078  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:53:37.080  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.080  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@320f3867 added. We now have 3 listener(s)
09-09 14:53:37.080  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.082  1031  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.082  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.084  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.085  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.085  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.085  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.085  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a549614 added. We now have 10 listener(s)
09-09 14:53:37.085  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.085  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:37.085  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:53:37.085  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:53:37.085  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:37.085  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:53:37.088  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:53:37.089  1031  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.093  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:53:37.094  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 14:53:37.096  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:53:37.096  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.098  6745  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:53:37.098  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:37.098  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:37.101  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:37.101  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:37.101  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:37.101  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.101  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.101  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.101  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.101  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22b42b68 removed from the list
09-09 14:53:37.101  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.101  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26605b81 removed from the list
09-09 14:53:37.101  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:37.101  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.101  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.101  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.102  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.102  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.102  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.102  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26605b81 not in the list
09-09 14:53:37.102  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.103  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.103  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.104  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:37.104  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
09-09 14:53:37.104  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.104  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.104  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a549614 removed from the list
09-09 14:53:37.104  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.104  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.104  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.104  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.104  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@320f3867 removed from the list
09-09 14:53:37.105  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.105  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@accf403 added. We now have 2 listener(s)
09-09 14:53:37.106  1031  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:53:37.108  8265  8265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:53:37.108  8265  8265 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:53:37.108  8265  8265 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:53:37.108  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.108  8265  8265 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 14:53:37.108  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.108  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.109  8265  8265 D dhcpcd  : wlan0: sending REQUEST (xid 0x80a9ff2b), next in 4.62 seconds
09-09 14:53:37.109  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.109  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eeff80 added. We now have 9 listener(s)
09-09 14:53:37.109  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.109  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:53:37.112  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:37.115  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:37.117  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.117  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:53:37.119  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.120  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.120  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3295e1fe added. We now have 3 listener(s)
09-09 14:53:37.121  1031  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.121  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.123  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.124  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.124  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:53:37.124  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.124  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d20cd5f added. We now have 10 listener(s)
09-09 14:53:37.124  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.124  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:37.125  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:37.125  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:53:37.125  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:53:37.125  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:37.125  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:53:37.128  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:53:37.128  1031  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.133  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 14:53:37.133  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:53:37.135  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:53:37.135  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.137  6745  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:53:37.137  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:37.137  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:37.137  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:37.138  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.138  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.138  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.138  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.138  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@accf403 removed from the list
09-09 14:53:37.138  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.138  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eeff80 removed from the list
09-09 14:53:37.138  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:37.138  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.139  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.139  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.140  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.140  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.140  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.140  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8eeff80 not in the list
09-09 14:53:37.140  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.140  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.141  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.141  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:37.142  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:37.142  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.142  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.142  6745  ,6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d20cd5f removed from the list
09-09 14:53:37.142  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.142  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.142  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.142  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.142  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3295e1fe removed from the list
09-09 14:53:37.143  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.143  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d6a200a added. We now have 2 listener(s)
09-09 14:53:37.143  1031  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.144  8265  8265 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 14:53:37.146  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.146  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.146  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.146  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.146  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daee07b added. We now have 9 listener(s)
09-09 14:53:37.146  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.147  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:53:37.149  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:37.152  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:37.154  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.154  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 14:53:37.154  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.154  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277626f1 added. We now have 3 listener(s)
09-09 14:53:37.154  1031  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.156  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.157  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.157  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.157  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.157  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.157  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c9232d6 added. We now have 10 listener(s)
09-09 14:53:37.157  6745  6823 D ,org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.157  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:37.157  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 14:53:37.157  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 14:53:37.157  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 14:53:37.157  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 14:53:37.158  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.159  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 14:53:37.160  1031  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 14:53:37.164  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 14:53:37.165  8265  8265 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 14:53:37.165  8265  8265 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 14:53:37.165  8265  8265 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 14:53:37.165  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 14:53:37.165  8265  8265 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 14:53:37.165  8265  8265 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 14:53:37.166  8265  8265 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 14:53:37.166  8265  8265 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 14:53:37.166  8265  8265 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 14:53:37.167  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 14:53:37.167  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.169  6745  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 14:53:37.171  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:37.171  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:37.171  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:37.171  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.171  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.171  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 14:53:37.171  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.171  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d6a200a removed from the list
09-09 14:53:37.171  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.171  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daee07b removed from the list
09-09 14:53:37.171  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:37.171  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.173  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.173  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:37.173  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.174  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.174  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.174  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daee07b not in the list
09-09 14:53:37.174  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.174  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.175  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.175  6745  6823 D BluetoothLeScanner: could not find callback wrapper
09-09 14:53:37.175  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 14:53:37.175  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.175  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.175  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c9232d6 removed from the list
09-09 14:53:37.175  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.176  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.176  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.176  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.176  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277626f1 removed from the list
09-09 14:53:37.176  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.176  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35412d added. We now have 2 listener(s)
09-09 14:53:37.177  1031  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.179  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.179  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.179  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 14:53:37.179  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.179  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2856a662 added. We now have 9 listener(s)
09-09 14:53:37.180  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 14:53:37.180  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 14:53:37.182  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoot,hManager: bind: Binding a new listener
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 14:53:37.186  6745  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 14:53:37.187  6745  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 14:53:37.187  6745  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 14:53:37.189  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 14:53:37.191  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 14:53:37.191  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 14:53:37.191  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8148b0 added. We now have 3 listener(s)
,09-09 14:53:37.191  1031  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 14:53:37.194  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 14:53:37.194  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 14:53:37.194  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 14:53:37.194  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 14:53:37.194  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c51c329 added. We now have 10 listener(s)
09-09 14:53:37.194  6745  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-09 14:53:37.194  6745  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 14:53:37.194  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 14:53:37.194  6745  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 14:53:37.195  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 14:53:37.195  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.195  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-09 14:53:37.195  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.195  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35412d removed from the list
09-09 14:53:37.195  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.195  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2856a662 removed from the list
09-09 14:53:37.195  6745  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-09 14:53:37.195  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 14:53:37.196  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.196  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.197  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.197  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.197  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.197  6745  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2856a662 not in the list
,09-09 14:53:37.197  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.197  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.198  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 14:53:37.198  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 14:53:37.198  6745  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 14:53:37.198  6745  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c51c329 removed from the list
09-09 14:53:37.198  6745  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 14:53:37.198  6745  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 14:53:37.198  6745  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 14:53:37.198  6745  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 14:53:37.198  6745  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8148b0 removed from the list
09-09 14:53:37.199  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 14:53:37.199  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 14:53:37.199  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 14:53:37.199  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 14:53:37.200  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 14:53:37.200  6745  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 14:53:37.210  6745  8275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 875, name: My test thread name)
09-09 14:53:37.211  6745  8275 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 875, thread name: My test thread name)
09-09 14:53:37.211  6745  8275 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 875, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 14:53:37.213  6745  8277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 877, name: My test thread name)
09-09 14:53:37.213  6745  8277 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 877, thread name: My test thread name)
09-09 14:53:37.213  6745  8277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 877, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 14:53:37.214  6745  6823 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 14:53:37.215  6745  6823 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 14:53:37.215  6745  6823 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 14:53:37.215  6745  6823 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 14:53:37.215  6745  6823 D com.test.thalitest.ThaliTestRunner: Total duration: 23085 ms
09-09 14:53:37.216  6745  6823 I jxcore-log: *Native tests were executed*
09-09 14:53:37.216  6745  6823 I jxcore-log: 
09-09 14:53:37.216  6745  6823 I jxcore-log: Total number of executed tests:  80
09-09 14:53:37.216  6745  6823 I jxcore-log: 
09-09 14:53:37.216  6745  6823 I jxcore-log: Number of passed tests:  80
09-09 14:53:37.216  6745  6823 I jxcore-log: 
09-09 14:53:37.216  6745  6823 I jxcore-log: Number of failed tests:  0
09-09 14:53:37.216  6745  6823 I jxcore-log: 
09-09 14:53:37.216  6745  6823 I jxcore-log: Number of ignored tests:  0
09-09 14:53:37.216  6745  6823 I jxcore-log: 
09-09 14:53:37.217  6745  6823 I jxcore-log: Total duration:  23085
09-09 14:53:37.217  6745  6823 I jxcore-log: 
09-09 14:53:37.217  6745  6823 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 14:53:37.217  6745  6823 I jxcore-log: 
09-09 14:53:37.221  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.221  6745  6823 I jxcore-log: 
,09-09 14:53:37.224  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.224  6745  6823 I jxcore-log: 
09-09 14:53:37.226  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.226  6745  6823 I jxcore-log: 
09-09 14:53:37.227  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.227  6745  6823 I jxcore-log: 
09-09 14:53:37.229  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.229  6745  6823 I jxcore-log: 
09-09 14:53:37.231  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.231  6745  6823 I jxcore-log: 
09-09 14:53:37.231  6745  6745 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 14:53:37.234  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.234  6745  6823 I jxcore-log: 
09-09 14:53:37.237  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:53:37.237  6745  6823 I jxcore-log: 
,09-09 14:53:37.239  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:53:37.239  6745  6823 I jxcore-log: 
09-09 14:53:37.240  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.240  6745  6823 I jxcore-log: 
09-09 14:53:37.241  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.241  6745  6823 I jxcore-log: 
09-09 14:53:37.242  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 14:53:37.242  6745  6823 I jxcore-log: 
09-09 14:53:37.243  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:53:37.243  6745  6823 I jxcore-log: 
09-09 14:53:37.244  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 14:53:37.244  6745  6823 I jxcore-log: 
09-09 14:53:37.245  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.245  6745  6823 I jxcore-log: 
09-09 14:53:37.247  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.247  6745  6823 I jxcore-log: 
09-09 14:53:37.248  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.248  6745  6823 I jxcore-log: 
09-09 14:53:37.249  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.249  6745  6823 I jxcore-log: 
09-09 14:53:37.249  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.249  6745  6823 I jxcore-log: 
09-09 14:53:37.250  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.250  6745  6823 I jxcore-log: 
09-09 14:53:37.251  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.251  6745  6823 I jxcore-log: 
09-09 14:53:37.252  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 14:53:37.252  6745  6823 I jxcore-log: 
09-09 14:53:37.252  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:53:37.252  6745  6823 I jxcore-log: 
09-09 14:53:37.253  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 14:53:37.253  6745  6823 I jxcore-log: 
09-09 14:53:37.254  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.254  6745  6823 I jxcore-log: 
09-09 14:53:37.255  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09,-09 14:53:37.255  6745  6823 I jxcore-log: 
,09-09 14:53:37.256  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.256  6745  6823 I jxcore-log: 
09-09 14:53:37.257  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.257  6745  6823 I jxcore-log: 
09-09 14:53:37.258  6745  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 14:53:37.258  6745  6823 I jxcore-log: 
09-09 14:53:37.337  8209  8209 W ExternalStrings: load override strings
09-09 14:53:37.337  8209  8209 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:53:37.337  8209  8209 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:53:37.340  8209  8209 D StatusProvider: onCreate
,09-09 14:53:37.404  8209  8209 V Signer  : override build config not found
,09-09 14:53:37.405  8209  8209 D Signer  : value of property debug is false
09-09 14:53:37.424  1031  8252 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 14:53:37.426  1031  8252 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 14:53:37.427  1031  8252 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 14:53:37.427  1031  8252 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 14:53:37.427  1031  8252 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 14:53:37.427  1031  8252 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 14:53:37.428  1031  8252 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 14:53:37.428  1031  8252 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 14:53:37.430  1031  8252 D DhcpStateMachine: RunningState
09-09 14:53:37.449  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-09 14:53:37.449  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,09-09 14:53:37.449  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-09 14:53:37.450  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,09-09 14:53:37.450  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-09 14:53:37.451  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-09 14:53:37.452  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-09 14:53:37.452  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-09 14:53:37.452  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-09 14:53:37.452  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-09 14:53:37.453  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-09 14:53:37.453  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-09 14:53:37.453  8209  8209 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-09 14:53:37.471  8209  8209 V LGMDMManager: Create singleton instance
,09-09 14:53:37.493  8287  8287 D AndroidRuntime: 
09-09 14:53:37.493  8287  8287 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 14:53:37.495  8287  8287 D AndroidRuntime: CheckJNI is OFF
09-09 14:53:37.546  8209  8209 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-09 14:53:37.605  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 14:53:37.610  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:37.624  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:37.637  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:53:37.645  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:37.646  8287  8287 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 14:53:37.648  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:53:37.654  7743  7743 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:53:37.654  1031  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-09 14:53:37.654  1031  1098 I ActivityManager: Killing 6745:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-09 14:53:37.683  1031  1047 I WindowState: WIN DEATH: Window{3a6a7d00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 14:53:37.683  1031  1530 D WifiService: Client connection lost with reason: 4
,09-09 14:53:37.689  1031  1047 D InputDispatcher: Window went away: Window{3a6a7d00 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 14:53:37.757  8209  8307 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 14:53:37.862  1031  1098 E libprocessgroup: failed to kill 1 processes for processgroup 6745
,09-09 14:53:37.867  1031  1098 I ActivityManager:   Force finishing activity ActivityRecord{1969b315 u0 com.test.thalitest/.MainActivity t6}
,09-09 14:53:37.905   337   346 E GBMv2   : DFP En is all cleared set to be enabled
,09-09 14:53:37.910  1031  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-09 14:53:37.911  1031  1118 I ActivityManager:   Force finishing activity ActivityRecord{1969b315 u0 com.test.thalitest/.MainActivity t6 f}
,09-09 14:53:37.911  1031  1118 W ActivityManager: Duplicate finish request for ActivityRecord{1969b315 u0 com.test.thalitest/.MainActivity t6 f}
,09-09 14:53:37.914  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 14:53:37.919  6882  6882 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-09 14:53:37.933  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-09 14:53:37.940  1031  1524 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 14:53:37.941  1031  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:37.942  1031  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:37.943  1031  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:37.944  1031  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:37.945  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 14:53:37.948  1031  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 14:53:37.950  2491  2598 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 14:53:37.951  3793  3793 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-09 14:53:37.952  1031  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 14:53:37.952  1031  1531 D ConnectivityService: identical MTU - not setting
09-09 14:53:37.952  1031  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 14:53:37.952  1031  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 14:53:37.952  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 14:53:37.952  1031  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 14:53:37.954  7717  7717 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-09 14:53:37.954  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 14:53:37.959  1031  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-09 14:53:37.960  1589  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 14:53:37.989  1031  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 14:53:38.000  4551  4551 I art     : Explicit concurrent mark sweep GC freed 8193(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 635us total 77.137ms
09-09 14:53:38.009  1031  2037 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:53:38.014  1031  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
09-09 14:53:38.036  1031  1031 D administrator: Handling package changes for user 0
09-09 14:53:38.036  4440  4440 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 14:53:38.036  4440  4440 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 14:53:38.036  4440  4440 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 14:53:38.036  4440  4440 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-09 14:53:38.036  4440  4440 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,09-09 14:53:38.036  4440  4440 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:53:38.036  4440  4440 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:38.036  4440  4440 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 14:53:38.037  4440  4440 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:53:38.037  4440  4440 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 14:53:38.037  4440  4440 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 14:53:38.037  4440  4440 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 14:53:38.044  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.044  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.047  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-09 14:53:38.048  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-09 14:53:38.049  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{78ade35 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-09 14:53:38.049  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-09 14:53:38.050  1927  3948 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-09 14:53:38.050  1927  3948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17d2f2ca co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 14:53:38.059  1031  1769 W ActivityManager: Spurious death for ProcessRecord{21d56138 6745:com.test.thalitest/u0a118}, curProc for 6745: null
09-09 14:53:38.059  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-09 14:53:38.061  2019  2114 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-09 14:53:38.085  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-09 14:53:38.087  1891  1891 D ActionManagerService: notifyUserLog: 1000003
09-09 14:53:38.088  3793  4426 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-09 14:53:38.089  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 14:53:38.093  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-09 14:53:38.093  1589  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 14:53:38.093  1589  1638 D KeyguardModel: createShortcutInfo...
,09-09 14:53:38.093  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-09 14:53:38.094  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-09 14:53:38.096  1589  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 14:53:38.096  1589  1638 D KeyguardModel: createShortcutInfo...
,09-09 14:53:38.109  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.109  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-09 14:53:38.110  1857  1857 D SplitUIService: removed split : 
09-09 14:53:38.111  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-09 14:53:38.112  3793  4413 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:53:38.112  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 14:53:38.112  1891  1891 D ActionManagerService: notifyUserLog: 1000004
09-09 14:53:38.113  1589  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:53:38.113  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 14:53:38.114  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:53:38.116  3793  4426 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , display: false
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , animation: false }
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , display: false
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , animation: false }
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , create_time: 1473420113195
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , display: false
09-09 14:53:38.118  2019  2019 I GBoardWebViewUtils: , animation: false }
09-09 14:53:38.120  1589  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:53:38.121  1589  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-09 14:53:38.127  1589  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 14:53:38.127  1589  1638 D KeyguardModel: createShortcutInfo...
09-09 14:53:38.129  2019  8330 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-09 14:53:38.134  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 14:53:38.134  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 14:53:38.136  1589  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:53:38.136  1589  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 14:53:38.138  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-09 14:53:38.138  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 14:53:38.138  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.148  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 14:53:38.148  1589  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 14:53:38.148  1589  1638 D KeyguardModel: createShortcutInfo...
09-09 14:53:38.148  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-09 14:53:38.152  1589  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:53:38.152  1589  1638 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 14:53:38.152  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 14:53:38.153  1589  1638 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 14:53:38.153  1589  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:53:38.153  1589  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 14:53:38.155  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
09-09 14:53:38.155  1031  1047 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:53:38.166  1589  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 14:53:38.166  1589  1638 D KeyguardModel: createShortcutInfo...
09-09 14:53:38.172  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.172  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 14:53:38.176  1589  1589 D KeyguardModel: handleShortcutListChanged...
09-09 14:53:38.176  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 14:53:38.181  1589  1638 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 14:53:38.181  1589  1638 D KeyguardModel: createShortcutInfo...
09-09 14:53:38.182  7743  7743 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 14:53:38.187  1031  1999 V SIM_STK : Menu title from STK is T-Mobile
,09-09 14:53:38.200  1589  1638 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 14:53:38.200  1589  1638 D KeyguardModel: createShortcutInfo...
,09-09 14:53:38.202  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.204  1589  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:53:38.204  1589  1638 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 14:53:38.205  1589  1638 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 14:53:38.205  1589  1638 D KeyguardModel: createShortcutInfo...
09-09 14:53:38.206  1589  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:53:38.206  1589  1638 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 14:53:38.207  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.217  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-09 14:53:38.217  1857  1857 I SplitUIService: split app #11
,09-09 14:53:38.223  1589  1638 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 14:53:38.223  1589  1638 D KeyguardModel: createShortcutInfo...
09-09 14:53:38.231  1589  1638 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 14:53:38.231  1589  1638 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 14:53:38.232  1589  1638 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 14:53:38.232  1589  1638 D KeyguardModel: createShortcutInfo...
,09-09 14:53:38.240  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.242  1031  1046 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 14:53:38.245  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-09 14:53:38.245  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 14:53:38.245  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 14:53:38.245  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 14:53:38.245  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 14:53:38.245  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:53:38.246  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 14:53:38.246  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 14:53:38.246  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 14:53:38.246  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 14:53:38.246  7717  7717 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-09 14:53:38.248  1589  1589 D KeyguardModel: handleShortcutListChanged...
09-09 14:53:38.248  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 14:53:38.259  2019  2033 I art     : Background partial concurrent mark sweep GC freed 7071(321KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 11.168ms total 34.123ms
09-09 14:53:38.262  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:53:38.270  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.270  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.270  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:38.280  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.280  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 14:53:38.287  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.289  8209  8307 D LgDataFeature: LgDataFeature() Constructor: none
09-09 14:53:38.289  8209  8307 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 14:53:38.292  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.296  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.296  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.297  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:53:38.301  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 14:53:38.301  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 14:53:38.301  6882  6882 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 14:53:38.301  6882  6882 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 14:53:38.301  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 14:53:38.302  6882  6882 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 14:53:38.302  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 14:53:38.302  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 14:53:38.302  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 14:53:38.302  6882  6882 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 14:53:38.302  6882  6882 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 14:53:38.302  6882  6882 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 14:53:38.306  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.306  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.311  1031  1031 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 14:53:38.311  1031  1031 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 14:53:38.312  1031  1031 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 14:53:38.317  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.318  1031  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-09 14:53:38.326  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.331  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.331  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.332  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:38.336  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.336  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 14:53:38.349  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:38.364  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-09 14:53:38.367  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.368  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 14:53:38.370  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 14:53:38.371  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 14:53:38.372  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-09 14:53:38.372  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.378  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.378  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.379  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 14:53:38.381  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.382  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.387  1031  1103 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a0cf534 u0 com.lge.launcher2/.Launcher t5} time:235642
09-09 14:53:38.387  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.391  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-09 14:53:38.391  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-09 14:53:38.391  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.391  2019  2275 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 14:53:38.391  2019  2275 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 14:53:38.394  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 14:53:38.405  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.405  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.406  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:38.406  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 14:53:38.407  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 14:53:38.407  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 14:53:38.416  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.416  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.417  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-09 14:53:38.420  2622  2622 D [Concierge]Service: onStartCommand(). Type : 8
09-09 14:53:38.420  2622  2622 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-09 14:53:38.421  2622  2622 D [Concierge]Service: Update widget ID : 11
09-09 14:53:38.423  2019  2019 D [Concierge]WidgetView: change position of spinner
09-09 14:53:38.424  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1473425618424
,09-09 14:53:38.424  2622  2622 D [Concierge]Service: onStartCommand(). Type : 0
09-09 14:53:38.427  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.430  8209  8307 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-09 14:53:38.433  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.437  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 14:53:38.437  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.441  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:38.443  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.444  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.446  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-09 14:53:38.451  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:38.453  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-09 14:53:38.454  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 14:53:38.454  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 14:53:38.455  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.456  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-09 14:53:38.456  8209  8307 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-09 14:53:38.459  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.459  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 934748781
09-09 14:53:38.460  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.460  7743  7743 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 14:53:38.460  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-09 14:53:38.460  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 14:53:38.462  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
09-09 14:53:38.464  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.464  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 14:53:38.466  8209  8307 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-09 14:53:38.466  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@35ce0c22
09-09 14:53:38.466  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-09 14:53:38.467  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 14:53:38.467  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.470  8161  8161 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 14:53:38.472  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 14:53:38.472  8161  8161 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 14:53:38.473  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-09 14:53:38.473  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 14:53:38.474  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 14:53:38.474  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473425409929, New one : 1473425618424
09-09 14:53:38.474  2019  2019 D [Concierge]WidgetView: Unregister all receivers
09-09 14:53:38.474  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 14:53:38.475  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.476  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 14:53:38.477  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-09 14:53:38.477  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.478  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 14:53:38.479  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-09 14:53:38.480  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-09 14:53:38.484  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.484  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.486  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.486  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.487  7743  7743 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 14:53:38.487  7743  7743 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 14:53:38.487  7743  7743 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 14:53:38.487  1031  1118 I art     : Explicit concurrent mark sweep GC freed 83872(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.411ms total 385.723ms
09-09 14:53:38.501  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 14:53:38.501  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 14:53:38.504  8161  8161 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 14:53:38.504  8161  8161 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 14:53:38.513  6882  6882 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 14:53:38.517  6882  6882 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 14:53:38.520  7743  7743 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 14:53:38.520  7743  7743 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 14:53:38.520  7743  7743 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 14:53:38.520  7743  7743 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 14:53:38.521  7743  7743 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 14:53:38.523  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 14:53:38.524  8209  8209 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 14:53:38.524  8209  8308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 14:53:38.525  1031  1942 I ActivityManager: Killing 7282:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-09 14:53:38.531  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-09 14:53:38.540  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-09 14:53:38.540  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-09 14:53:38.541  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 14:53:38.562  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35de835e time:235817
,09-09 14:53:38.564  1031  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:53:38.569  1031  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 14:53:38.603  8287  8287 D AndroidRuntime: Shutting down VM
,09-09 14:53:38.617  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-09 14:53:38.674  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-09 14:53:38.698  1031  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8340 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-09 14:53:38.700  1031  1046 W libprocessgroup: failed to open /acct/uid_10005/pid_7282/cgroup.procs: No such file or directory
09-09 14:53:38.703  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 14:53:38.707  2199  2199 I ConfigService: onCreate
09-09 14:53:38.708  2199  2199 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-09 14:53:38.710  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-09 14:53:38.715  2199  2199 I ConfigService: onBind returning update interface
,09-09 14:53:38.716  2199  2199 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-09 14:53:38.716  2199  2199 I ConfigService: onBind returning config service
,09-09 14:53:38.738  2019  2937 I GBoardtInterface: onReloaded()
09-09 14:53:38.741  2199  2199 I ConfigService: onDestroy
09-09 14:53:38.745  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-09 14:53:38.746  1805  8358 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-09 14:53:38.751  3793  3809 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:53:38.754  3793  4413 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:53:38.768  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,09-09 14:53:38.770  3793  4426 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 14:53:38.771  3793  4426 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 14:53:38.777  1891  1891 D ActionManagerService: notifyUserLog: 1000001
09-09 14:53:38.781  3793  4413 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 14:53:38.782  5878  8367 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-09 14:53:38.786  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-09 14:53:38.786  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-09 14:53:38.786  3793  4426 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 14:53:38.787  3793  4426 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 14:53:38.787  3793  4426 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-09 14:53:38.787  3793  4426 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-09 14:53:38.790  1805  8368 I PeopleContactsSync: CP2 sync disabled
09-09 14:53:38.791  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-09 14:53:38.791  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 14:53:38.794  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-09 14:53:38.794  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 14:53:38.796  1805  4689 I Icing   : doRemovePackageData com.test.thalitest
,09-09 14:53:38.814  7077  7077 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-09 14:53:38.820  1031  1942 I ActivityManager: Killing 7798:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 14:53:38.900  1031  1901 W libprocessgroup: failed to open /acct/uid_10072/pid_7798/cgroup.procs: No such file or directory
09-09 14:53:38.900  1805  8366 W GmsApplication: Using Auth Proxy for data requests.
,09-09 14:53:38.910  2325  8372 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 14:53:38.936  1031  1942 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8373 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 14:53:38.944  1805  8366 W GmsApplication: Using Auth Proxy for data requests.
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:38.950  1805  8366 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: Runtime exception while performing operation
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:38.951  1805  8366 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnec,tionPool.java:185)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:38.952  1805  8366 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: Can't write: system_app_wtf
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:53:38.958  1031  8383 E DropBoxManagerService: 	... 5 more
09-09 14:53:38.958  2325  8372 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-09 14:53:38.959  2325  8372 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 14:53:38.959  2325  8372 E Andro,idRuntime: Process: android.process.acore, PID: 2325
09-09 14:53:38.959  2325  8372 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:38.959  2325  8372 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:53:38.964  2325  8372 I Process : Sending signal. PID: 2325 SIG: 9
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 14:53:38.964  1031  8386 E DropBoxManagerService: 	... 5 more
,09-09 14:53:38.995  1805  8360 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-09 14:53:38.996  1805  8360 E DriveAsyncService: disk I/O error (code 3850)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
09-09 14:53:38.996  1805  8360 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:53:39.010  8373  8373 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 14:53:39.010  8373  8373 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.

```
