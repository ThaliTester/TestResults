#### Test 80807573fdd3b64_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-18 11:58:25.114   302   912 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-18 11:58:25.114   302   912 I rmt_storage: 
08-18 11:58:25.117   302   302 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-18 11:58:25.118   901   910 E Diag_Lib: [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,08-18 11:58:57.567  6786  6786 D AndroidRuntime: 
08-18 11:58:57.567  6786  6786 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-18 11:58:57.572  6786  6786 D AndroidRuntime: CheckJNI is OFF
08-18 11:58:57.698  6786  6786 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-18 11:58:57.703  1033  2036 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-18 11:58:57.714  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-18 11:58:57.718  1033  2036 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-18 11:58:57.719  1033  2036 D ActivityManager: setTaskToReturnTo : TaskRecord{2dbf4c15 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-18 11:58:57.719  1033  2036 D ActivityManager: setTaskToReturnTo : TaskRecord{2dbf4c15 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-18 11:58:57.720  1033  2036 D WindowStateEx: AppWindowTokenEx init.. 
08-18 11:58:57.721   343   367 E GBMv2   : DFP En is all cleared set to be enabled
08-18 11:58:57.761  1033  2036 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6805 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-18 11:58:57.763  6786  6786 D AndroidRuntime: Shutting down VM
08-18 11:58:57.796  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-18 11:58:57.797  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3cec5dbe co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-18 11:58:57.798  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-18 11:58:57.798  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3427fe1f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-18 11:58:57.867  6805  6805 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-18 11:58:57.918  6805  6805 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-18 11:58:57.942  6805  6805 I LibraryLoader: Loading: webviewchromium
08-18 11:58:57.950  6805  6805 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 730-740)
08-18 11:58:57.950  6805  6805 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 11:58:57.966  6805  6805 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {288f601c}
08-18 11:58:57.967  6805  6805 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 11:58:57.968  6805  6805 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 11:58:57.992  6805  6805 I BrowserStartupController: Initializing chromium process, renderers=0
08-18 11:58:57.995  6805  6805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 11:58:58.022  6805  6805 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-18 11:58:58.025  6805  6805 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-18 11:58:58.025  6805  6805 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-18 11:58:58.027   315  1384 V AudioPolicyService: registerClient() client 0xb04104c0, uid 10118
08-18 11:58:58.037  6805  6805 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 11:58:58.037  6805  6805 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 11:58:58.037  6805  6805 I Adreno-EGL: Build Date: 12/12/14 금
08-18 11:58:58.037  6805  6805 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-18 11:58:58.037  6805  6805 I Adreno-EGL: Remote Branch: 
08-18 11:58:58.037  6805  6805 I Adreno-EGL: Local Patches: 
08-18 11:58:58.037  6805  6805 I Adreno-EGL: Reconstruct Branch: 
,08-18 11:58:58.043  1033  1109 D BluetoothManagerService: Message: 20
08-18 11:58:58.043  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35173ff7:true
08-18 11:58:58.139  6805  6842 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-18 11:58:58.141  6805  6805 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-18 11:58:58.161  6805  6805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 11:58:58.166  6805  6805 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-18 11:58:58.170  6805  6805 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-18 11:58:58.174  6805  6805 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-18 11:58:58.174  6805  6805 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-18 11:58:58.191  6805  6805 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-18 11:58:58.198  6805  6805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 11:58:58.198  6805  6805 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-18 11:58:58.225  6805  6854 D OpenGLRenderer: Render dirty regions requested: true
08-18 11:58:58.225  6805  6854 I OpenGLRenderer: Initialized EGL, version 1.4
08-18 11:58:58.236  6805  6854 D OpenGLRenderer: Enabling debug mode 0
,08-18 11:58:58.245  6805  6805 D Atlas   : Validating map...
08-18 11:58:58.249  1033  1728 D SplitWindow: check instance of lgWin Window{d23f239 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-18 11:58:58.317  6805  6852 D LgDataFeature: LgDataFeature() Constructor: none
,08-18 11:58:58.318  6805  6852 D LgDataFeature: LgDataFeature() Constructor Done, null
08-18 11:58:58.361  1033  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +569ms (total +640ms)
08-18 11:58:58.362  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30dffb2a u0 com.test.thalitest/.MainActivity t6} time:231153
,08-18 11:58:58.370  6805  6805 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@364ad59b time:231161
08-18 11:58:58.467  6805  6805 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 11:58:58.506  6805  6805 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-18 11:58:58.506  6805  6805 I chromium: 
,08-18 11:58:58.544  6805  6852 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-18 11:58:58.544  6805  6852 I chromium: 
,08-18 11:58:58.698  6805  6868 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-18 11:58:58.714  6805  6868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 11:58:58.714  6805  6868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 11:58:58.714  6805  6868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 11:58:58.714  6805  6868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 11:58:58.714  6805  6868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-18 11:58:58.714  6805  6868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bedb76f added. We now have 1 listener(s)
,08-18 11:58:58.724  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 11:58:58.728  6805  6868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-18 11:58:58.732  6805  6868 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-18 11:58:58.734  6805  6868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:58:58.735  6805  6868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-18 11:58:58.745  6805  6868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29ff5d5a added. We now have 1 listener(s)
08-18 11:58:58.746  6805  6868 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:58:58.750  1033  1541 D WifiService: New client listening to asynchronous messages
,08-18 11:58:58.754  6805  6868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:58:58.754  6805  6868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-18 11:58:58.754  6805  6868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 11:58:58.754  6805  6868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-18 11:58:58.755  6805  6868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-18 11:58:58.758  6805  6868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:58:58.759  1033  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 11:58:58.763  6805  6868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-18 11:58:58.780  6805  6868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:58:58.781  6805  6868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:58:58.781  6805  6868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-18 11:58:58.781  6805  6868 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:58:58.782  6805  6868 I io.jxcore.node.LifeCycleMonitor: start: OK
08-18 11:58:58.783  6805  6805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:58:58.785  6805  6805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:58:58.821  6805  6805 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 11:58:59.083   343   370 E GBMv2   : DFP En is all cleared set to be enabled
08-18 11:58:59.083   343   370 E GBMv2   : Set value is all cleared set the max
08-18 11:58:59.083   343   370 I GBMv2   : DFP Enabled. Ignore VFP set
,08-18 11:58:59.843  6805  6871 W jxcore-log: Initializing JXcore engine
08-18 11:58:59.843  6805  6871 W jxcore-log: JXcore engine is ready
,08-18 11:58:59.874  6871  6871 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9814]" dev="sockfs" ino=9814 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-18 11:58:59.874  6871  6871 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-18 11:58:59.874  6871  6871 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7836]" dev="sockfs" ino=7836 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-18 11:58:59.874  6871  6871 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-18 11:58:59.874  6871  6871 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32430]" dev="sockfs" ino=32430 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-18 11:58:59.892  6805  6871 W jxcore-log: Starting JXcore engine
08-18 11:58:59.970  6805  6871 W jxcore-log: Platform android
08-18 11:58:59.970  6805  6871 W jxcore-log: 
08-18 11:58:59.970  6805  6871 W jxcore-log: Process ARCH arm
08-18 11:58:59.970  6805  6871 W jxcore-log: 
,08-18 11:59:00.051  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-18 11:59:00.051  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-18 11:59:00.052  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-18 11:59:00.052  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-18 11:59:00.058  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-18 11:59:00.059  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-18 11:59:00.060  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-18 11:59:00.062  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-18 11:59:00.208  6805  6871 I jxcore-log: JXcore Cordova bridge is ready!
08-18 11:59:00.208  6805  6871 I jxcore-log: 
,08-18 11:59:00.211  6805  6871 W jxcore-log: JXcore engine is started
08-18 11:59:00.227  6805  6868 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION

```
