#### Test 757892686fd65a6_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-01 09:01:00.070  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
07-01 09:01:00.080  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 09:01:00.080  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-01 09:01:00.082  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-01 09:01:00.084  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 09:01:04.843  7110  7110 D AndroidRuntime: 
07-01 09:01:04.843  7110  7110 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 09:01:04.849  7110  7110 D AndroidRuntime: CheckJNI is OFF
07-01 09:01:04.975  7110  7110 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-01 09:01:04.980  1036  1978 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 09:01:04.990  1944  2242 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-01 09:01:04.994  1036  1978 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-01 09:01:04.995  1036  1978 D ActivityManager: setTaskToReturnTo : TaskRecord{398ac8e8 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-01 09:01:04.995  1036  1978 D ActivityManager: setTaskToReturnTo : TaskRecord{398ac8e8 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-01 09:01:04.996  1036  1978 D WindowStateEx: AppWindowTokenEx init.. 
07-01 09:01:04.997   334   346 E GBMv2   : DFP En is all cleared set to be enabled
07-01 09:01:05.018  1036  1978 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7125 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 09:01:05.019  7110  7110 D AndroidRuntime: Shutting down VM
07-01 09:01:05.081  1944  2242 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-01 09:01:05.082  1944  2242 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d2aee35 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-01 09:01:05.083  1944  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-01 09:01:05.084  1944  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1d9c2ca co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-01 09:01:05.160  7125  7125 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-01 09:01:05.212  7125  7125 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-01 09:01:05.219  7125  7125 I LibraryLoader: Loading: webviewchromium
07-01 09:01:05.222  7125  7125 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4502-4506)
07-01 09:01:05.222  7125  7125 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 09:01:05.254  7125  7125 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {253cbaab}
07-01 09:01:05.256  7125  7125 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 09:01:05.256  7125  7125 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 09:01:05.269  7125  7125 I BrowserStartupController: Initializing chromium process, renderers=0
07-01 09:01:05.270  7125  7125 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 09:01:05.282  7125  7125 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-01 09:01:05.283   314  1388 V AudioPolicyService: registerClient() client 0xb558a9c0, uid 10118
07-01 09:01:05.283  7125  7125 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-01 09:01:05.283  7125  7125 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-01 09:01:05.298  7125  7125 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 09:01:05.298  7125  7125 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 09:01:05.298  7125  7125 I Adreno-EGL: Build Date: 12/12/14 금
07-01 09:01:05.298  7125  7125 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 09:01:05.298  7125  7125 I Adreno-EGL: Remote Branch: 
07-01 09:01:05.298  7125  7125 I Adreno-EGL: Local Patches: 
07-01 09:01:05.298  7125  7125 I Adreno-EGL: Reconstruct Branch: 
07-01 09:01:05.299  1036  1098 D BluetoothManagerService: Message: 20
07-01 09:01:05.300  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c35e32:true
07-01 09:01:05.420  7125  7171 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-01 09:01:05.429  7125  7125 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-01 09:01:05.461  7125  7125 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 09:01:05.471  7125  7125 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 09:01:05.477  7125  7125 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-01 09:01:05.480  7125  7125 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-01 09:01:05.480  7125  7125 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-01 09:01:05.496  7125  7125 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-01 09:01:05.504  7125  7125 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 09:01:05.504  7125  7125 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 09:01:05.537  7125  7189 D OpenGLRenderer: Render dirty regions requested: true
07-01 09:01:05.537  7125  7189 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 09:01:05.549  7125  7189 D OpenGLRenderer: Enabling debug mode 0
07-01 09:01:05.562  7125  7125 D Atlas   : Validating map...
07-01 09:01:05.567  1036  2015 D SplitWindow: check instance of lgWin Window{5ac55c u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 09:01:05.609  7125  7187 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:05.609  7125  7187 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 09:01:05.735  1036  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +655ms (total +738ms)
07-01 09:01:05.737  7125  7125 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39525d76 time:275021
07-01 09:01:05.738  1036  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14be6b01 u0 com.test.thalitest/.MainActivity t12} time:275023
07-01 09:01:05.833  7125  7125 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 09:01:05.864  7125  7125 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-01 09:01:05.864  7125  7125 I chromium: 
07-01 09:01:05.881  7125  7187 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-01 09:01:05.881  7125  7187 I chromium: 
,07-01 09:01:05.994  7125  7199 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435126144
,07-01 09:01:06.012  7125  7199 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 09:01:06.012  7125  7199 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 09:01:06.012  7125  7199 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 09:01:06.012  7125  7199 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 09:01:06.012  7125  7199 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 09:01:06.012  7125  7199 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2278c85a added. We now have 1 listener(s)
,07-01 09:01:06.016  1036  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
07-01 09:01:06.021  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-01 09:01:06.025  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-01 09:01:06.028  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 09:01:06.028  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 09:01:06.036  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7de781 added. We now have 1 listener(s)
07-01 09:01:06.037  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:06.041  1036  1547 D WifiService: New client listening to asynchronous messages
,07-01 09:01:06.044  7125  7199 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-01 09:01:06.049  7125  7199 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-01 09:01:06.049  7125  7199 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-01 09:01:06.052  7125  7199 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 09:01:06.054  1036  1579 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-01 09:01:06.056  7125  7199 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:06.064  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 09:01:06.064  7125  7199 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 09:01:06.064  7125  7199 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 09:01:06.067  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:06.067  7125  7199 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 09:01:06.069  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:06.103  7125  7125 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 09:01:06.517   334   348 E GBMv2   : DFP En is all cleared set to be enabled
07-01 09:01:06.517   334   348 E GBMv2   : Set value is all cleared set the max
07-01 09:01:06.517   334   348 I GBMv2   : DFP Enabled. Ignore VFP set
,07-01 09:01:06.932  7125  7202 W jxcore-log: Initializing JXcore engine
07-01 09:01:06.932  7125  7202 W jxcore-log: JXcore engine is ready
,07-01 09:01:06.960  7202  7202 W Thread-826: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7466]" dev="sockfs" ino=7466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-01 09:01:06.960  7202  7202 W Thread-826: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-01 09:01:06.960  7202  7202 W Thread-826: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9850]" dev="sockfs" ino=9850 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-01 09:01:06.960  7202  7202 W Thread-826: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-01 09:01:06.960  7202  7202 W Thread-826: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34999]" dev="sockfs" ino=34999 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-01 09:01:06.989  7125  7202 W jxcore-log: Starting JXcore engine
,07-01 09:01:07.063  7125  7202 W jxcore-log: Platform android
07-01 09:01:07.063  7125  7202 W jxcore-log: 
07-01 09:01:07.063  7125  7202 W jxcore-log: Process ARCH arm
07-01 09:01:07.063  7125  7202 W jxcore-log: 
,07-01 09:01:07.387  7125  7202 I jxcore-log: JXcore Cordova bridge is ready!
07-01 09:01:07.387  7125  7202 I jxcore-log: 
07-01 09:01:07.387  7125  7202 W jxcore-log: JXcore engine is started
,07-01 09:01:07.394  7125  7199 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 09:01:07.397  7125  7125 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 09:01:15.763  1036  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1ff5dd92 type 2 when 260709 android} when 260709
,07-01 09:01:15.798  2643  2643 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 09:01:17.284  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-01 09:01:17.284  7125  7202 I jxcore-log: 
,07-01 09:01:17.287  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-01 09:01:17.287  7125  7202 I jxcore-log: 
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:17.293  7125  7202 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:17.296  7125  7202 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:17.298  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-01 09:01:17.298  7125  7202 I jxcore-log: 
,07-01 09:01:17.300  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-01 09:01:17.300  7125  7202 I jxcore-log: 
,07-01 09:01:17.624  7125  7202 I jxcore-log: Unit Test app is loaded
07-01 09:01:17.624  7125  7202 I jxcore-log: 
,07-01 09:01:17.629  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 09:01:17.629  7125  7202 I jxcore-log: 
07-01 09:01:17.633  7125  7202 I jxcore-log: My device name is: LGE-LG-D855
07-01 09:01:17.633  7125  7202 I jxcore-log: 
07-01 09:01:17.635  7125  7202 I jxcore-log: WARN testUtils: myNameCallback not set!
07-01 09:01:17.635  7125  7202 I jxcore-log: 
07-01 09:01:17.653  7125  7125 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-01 09:01:17.737  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:17.737  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@223d903b added. We now have 2 listener(s)
07-01 09:01:17.737  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:17.742  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:17.742  7125  7199 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:17.742  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:17.742  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:17.743  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@223d903b removed from the list
07-01 09:01:17.744  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:17.744  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1eca9358 added. We now have 2 listener(s)
07-01 09:01:17.744  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:17.745  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:17.745  7125  7199 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:17.745  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:17.745  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:17.745  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1eca9358 removed from the list
07-01 09:01:17.746  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:17.746  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2335bcb1 added. We now have 2 listener(s)
07-01 09:01:17.746  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:17.749  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=7125, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 09:01:17.750  1036  1052 D WifiService: setWifiEnabled: false pid=7125, uid=10118
07-01 09:01:17.750  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-01 09:01:17.775  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:17.775  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:17.775  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:17.776  1036  1542 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:17.776  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:17.776  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:17.776  1036  1542 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:17.776  1036  1978 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@361e0363 mBinding = false
07-01 09:01:17.776  1036  1542 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:17.776  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:17.777  1036  1542 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-01 09:01:17.777  1036  1542 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 09:01:17.777  1036  1542 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-01 09:01:17.777  1036  1542 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-01 09:01:17.777  1036  1542 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-01 09:01:17.788  1036  1542 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-01 09:01:17.788  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-01 09:01:17.789  2681  2681 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-01 09:01:17.789  1036  1541 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.789  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.789  1036  1542 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-01 09:01:17.789  1036  1542 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 09:01:17.789  1036  1542 D WifiNative-wlan0: SET ps 1: returned true
,07-01 09:01:17.790   309   896 D CommandListener: Clearing all IP addresses on wlan0
07-01 09:01:17.796  1036  2825 D DhcpStateMachine: RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.827  1036  1542 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:17.827  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:17.827  1036  1542 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:17.828  1036  1542 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:17.828  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:17.828  1036  1542 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,07-01 09:01:17.830  1036  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-01 09:01:17.830  1036  1548 D ConnectivityService: ignoring duplicate network state non-change
07-01 09:01:17.830  1036  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-01 09:01:17.845  1036  1541 D LGWifiP2pService: InactiveState{ when=-19ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.845  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.846  1036  1541 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1bbaae0e
07-01 09:01:17.846  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 09:01:17.846  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.847  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.847  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 09:01:17.847  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 09:01:17.847  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.847  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.847  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 09:01:17.847  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 09:01:17.847  1036  1036 D RttService: SCAN_AVAILABLE : 1
,07-01 09:01:17.848  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:17.848  1036  1560 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 09:01:17.849  1036  1561 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.849  1036  1541 D LGWifiP2pService: P2pDisablingState
07-01 09:01:17.849  1036  1541 D LGWifiP2pService: P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.849  1036  1541 D LGWifiP2pService: p2p socket connection lost
07-01 09:01:17.849  1036  1541 D LGWifiP2pService: P2pDisabledState
07-01 09:01:17.850  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-01 09:01:17.852  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:17.852  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 09:01:17.854  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:17.854  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:17.854  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:17.855  1036  1098 D BluetoothManagerService: Message: 2
07-01 09:01:17.860  1036  1542 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-01 09:01:17.860  1036  1542 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,07-01 09:01:17.862  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.862  1036  1541 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.862  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-01 09:01:17.862  2681  2681 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-01 09:01:17.863  1036  1542 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-01 09:01:17.863  1036  1542 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 09:01:17.864  1036  1542 D WifiNative-wlan0: SET ps 1: returned true
07-01 09:01:17.864  1944  1944 D WfdsService: WifiP2pState is changed : false
07-01 09:01:17.865  1944  2326 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-01 09:01:17.865  1944  2326 D WfdsService: Set the WFDS Monitor: false
07-01 09:01:17.869  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:17.871  1944  2326 D WfdsMonitor: WFDS Monitor is stopped
,07-01 09:01:17.871  1944  2326 D WfdsService: STATE : WfdsDisabledState - enter
07-01 09:01:17.871  1944  2748 D CtrlSupplicant: Received on exit socket, terminate
07-01 09:01:17.871  1944  2748 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-01 09:01:17.871  1944  2748 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-01 09:01:17.871  1944  2748 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-01 09:01:17.872  1944  2327 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,07-01 09:01:17.874  1036  1098 D BluetoothManagerService: Sending off request.
07-01 09:01:17.875  1036  1979 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
07-01 09:01:17.875  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.875  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.875  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-01 09:01:17.876  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.876  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
07-01 09:01:17.878  4391  4519 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-01 09:01:17.879  4391  4462 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-01 09:01:17.879  4391  4462 D BluetoothAdapterProperties: Setting state to 13
07-01 09:01:17.879  4391  4462 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 09:01:17.880  4391  4462 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 09:01:17.880  4391  4462 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 09:01:17.882  4391  4467 D BluetoothAdapterProperties: Scan Mode:20
07-01 09:01:17.883  4391  4462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 09:01:17.883  4391  4462 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 09:01:17.885  4391  4732 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-01 09:01:17.886  4391  4731 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-01 09:01:17.886  4391  4757 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 09:01:17.887  4391  4760 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 09:01:17.887  4391  4762 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 09:01:17.889  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-01 09:01:17.889  4391  4588 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-01 09:01:17.890  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-01 09:01:17.890  4391  4588 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 09:01:17.893  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:17.893  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-01 09:01:17.893  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-01 09:01:17.897  7125  7199 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:17.899  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:17.899  1944  2326 W WfdsService: DefaultState - msg [9445378] is not handled
07-01 09:01:17.900  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:17.900  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:17.900  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:17.907  4391  4391 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:17.907  4391  4391 D BluetoothMapService: STATE_TURNING_OFF
07-01 09:01:17.907  4391  4391 V BluetoothMapService: Handler(): got msg=4
07-01 09:01:17.907  4391  4391 D BluetoothMapService: MAP Service closeService in
07-01 09:01:17.907  4391  4391 D BluetoothMapMasInstance: MAP Service shutdown
07-01 09:01:17.907  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:17.907  4391  4391 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 09:01:17.907  4391  4391 V BluetoothMapService: MAP Service closeService out
07-01 09:01:17.908  4391  4391 V BtOppService: Receiver DISABLED_ACTION 
07-01 09:01:17.908  4391  4391 I BtOppRfcommListener: stopping Accept Thread
07-01 09:01:17.908  4391  4391 V BtOppRfcommListener: close mBtServerSocket
07-01 09:01:17.908  4391  4391 V BtOppRfcommListener: waiting for thread to terminate
07-01 09:01:17.909   309   896 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:17.910  1036  1548 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-01 09:01:17.910  1036  1548 D DSQN    : disableDataServiceNotify
07-01 09:01:17.910  1036  1548 D DSQN    : stop dsqn bin
07-01 09:01:17.911  7125  7199 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:17.911  7125  7199 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 09:01:17.912   309  7235 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-01 09:01:17.912  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-01 09:01:17.912  1036  1096 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-01 09:01:17.914  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:17.915  4391  4757 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-01 09:01:17.915  4391  4391 V BtOppRfcommListener: done waiting for thread to terminate
07-01 09:01:17.915  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:17.917  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:17.918  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:17.919  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:17.920  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:17.920  1036  1548 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-01 09:01:17.921  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:17.921  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:17.921  1036  1548 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:17.921  1036  1548 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-01 09:01:17.921  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.921  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:17.921  1036  2823 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-01 09:01:17.922  1036  1548 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-01 09:01:17.922  1036  1548 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-01 09:01:17.922  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:17.922  1606  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-01 09:01:17.935  1036  1094 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7238 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-01 09:01:17.936  1036  1542 D WifiNative-p2p0: doBoolean: TERMINATE
07-01 09:01:17.936  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:17.936  1036  1542 D WifiNative-p2p0: TERMINATE: returned true
07-01 09:01:17.936  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:17.936  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:17.936  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:17.937  1036  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:17.937  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:17.937  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 09:01:17.937  4391  4391 V BtOppService: onDestroy
07-01 09:01:17.938  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.938  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.938  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 09:01:17.938  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-01 09:01:17.938  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 09:01:17.938  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 09:01:17.938  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 09:01:17.938  1036  1540 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,07-01 09:01:17.956  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:17.956  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:17.957  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 09:01:17.970  1036  1616 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7257 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-01 09:01:17.972  4391  4391 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-01 09:01:17.974  1036  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:17.974  1036  1548 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:17.974  1036  1548 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:17.974  1036  1548 D NetworkManagementService: Removing idletimer
07-01 09:01:17.975  1036  1548 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:17.975  1036  1540 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-01 09:01:17.976  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:17.976  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-01 09:01:17.976  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:17.977  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:17.977  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:17.977  1036  1542 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:17.978  1036  1542 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:17.978  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-01 09:01:17.978  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-01 09:01:17.978  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:17.978  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-01 09:01:17.978  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 09:01:17.978  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 09:01:17.978  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 09,:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:17.979  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:17.979  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:18.001  7238  7238 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 09:01:18.001  7238  7238 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-01 09:01:18.002  7238  7238 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 09:01:18.002  7238  7238 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-01 09:01:18.003  7238  7238 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 09:01:18.004  7238  7238 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-01 09:01:18.005  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-01 09:01:18.006  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:18.006  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:18.010  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:18.026  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 09:01:18.027  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 09:01:18.027  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:18.048  7257  7257 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-01 09:01:18.056  7257  7257 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 09:01:18.056  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:18.057  1036  2825 D DhcpStateMachine: StoppedState
07-01 09:01:18.057  1036  2825 D DhcpStateMachine: StoppedState{ when=-193ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.057  1036  1979 I ActivityManager: Killing 2135:com.lge.music/u0a34 (adj 15): empty #17
07-01 09:01:18.067   314  1389 V AudioFlinger: 2135 died, releasing its sessions
07-01 09:01:18.067   314  1389 V AudioFlinger:  pid 1853 @ 0
,07-01 09:01:18.067   314  1389 V AudioFlinger:  pid 3403 @ 1
07-01 09:01:18.067   314  1389 V AudioFlinger:  pid 3403 @ 2
07-01 09:01:18.069  2681  2681 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 09:01:18.069  2681  2681 I wpa_supplicant: monitor socket send errors count : 1
07-01 09:01:18.069  2681  2681 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-2\x00 that cannot receive messages
07-01 09:01:18.070  1036  2732 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-01 09:01:18.070  1036  2732 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 09:01:18.107  2681  2681 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-01 09:01:18.107  2681  2681 W wpa_supplicant: USIM:  scard_deinit function
07-01 09:01:18.108  1036  2732 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-01 09:01:18.108  1036  2732 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-01 09:01:18.108  1036  2732 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-01 09:01:18.109  1036  2732 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-01 09:01:18.109  1036  2732 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 09:01:18.109  1036  1098 D Tethering: InitialState.processMessage what=4
07-01 09:01:18.109  1036  2732 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 09:01:18.109  1036  1542 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=287381
07-01 09:01:18.109  1036  1542 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=287382
07-01 09:01:18.110  1036  1542 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=287382  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-01 09:01:18.110  1036  1542 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=287382  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-01 09:01:18.159  1036  1579 W libprocessgroup: failed to open /acct/uid_10034/pid_2135/cgroup.procs: No such file or directory
,07-01 09:01:18.170  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 09:01:18.172  1036  1542 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,07-01 09:01:18.173  1036  1542 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:18.174  1036  1542 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-01 09:01:18.175  1036  1542 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-01 09:01:18.245  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-01 09:01:18.248  4391  4391 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 09:01:18.248  4391  4391 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.248  4391  4391 V BluetoothPbapReceiver: ***********state = 13
07-01 09:01:18.250  4391  4391 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-01 09:01:18.251  4391  4391 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.251  4391  4391 V BluetoothPbapService: state: 13
07-01 09:01:18.251  4391  4391 V BluetoothPbapService: Pbap Service closeService in
07-01 09:01:18.255  4391  4391 V BluetoothPbapService: successfully stopped pbap service
07-01 09:01:18.255  4391  4391 V BluetoothPbapService: Pbap Service closeService out
07-01 09:01:18.255  4391  4391 V BluetoothPbapService: Pbap Service onDestroy
07-01 09:01:18.255  4391  4391 V BluetoothPbapService: Pbap Service closeService in
07-01 09:01:18.255  4391  4391 V BluetoothPbapService: Pbap Service closeService out
07-01 09:01:18.255  4391  4391 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 09:01:18.256  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:18.265  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:18.297  1036  1925 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7280 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-01 09:01:18.298  2681  2681 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 09:01:18.299  1036  2732 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-01 09:01:18.299  1036  2732 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-01 09:01:18.299  1036  2732 D WifiMonitor: Disconnecting from the supplicant, no more events
07-01 09:01:18.299  1036  1542 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,07-01 09:01:18.343  7238  7238 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 09:01:18.343  7238  7238 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 09:01:18.352  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:18.366  1036  1098 D BluetoothManagerService: Message: 20
07-01 09:01:18.367  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cdb8cea:true
,07-01 09:01:18.377  7280  7280 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-01 09:01:18.377  7280  7280 W LG Account v2.2: No ProfileInfo entries
07-01 09:01:18.377  7280  7280 I LG Account v2.2: isEnabled: false
07-01 09:01:18.377  7280  7280 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-01 09:01:18.377  7280  7280 I Feature : [Lifetracker]Country: EU
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Operator: OPEN
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Ranking support: false
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Comfort support: false
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Accessory: true
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Health device: true
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Extra Pedometer: false
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Blood glucose device: false
07-01 09:01:18.378  7280  7280 I Feature : [Lifetracker]Device Number: 3
07-01 09:01:18.378  1036  1098 D BluetoothManagerService: Message: 30
07-01 09:01:18.381  1036  1052 I ActivityManager: Killing 6514:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-01 09:01:18.539  1036  1924 W libprocessgroup: failed to open /acct/uid_10004/pid_6514/cgroup.procs: No such file or directory
,07-01 09:01:18.547  1944  1944 D WfdsService: Supplicant Connection state is changed : false
,07-01 09:01:18.547  1944  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-01 09:01:18.548  1944  2326 D WfdsService: Set the WFDS Monitor: false
07-01 09:01:18.548  1944  2326 D WfdsMonitor: WFDS Monitor is stopped
07-01 09:01:18.548  1036  1542 D WifiOffDelayIfNotUsed: stopMonitoring
07-01 09:01:18.549  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:18.549  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:18.549  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:18.556  1036  1098 D BluetoothManagerService: Message: 30
,07-01 09:01:18.563  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:18.566  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 09:01:18.566  2475  2475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:18.572  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:18.573  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-01 09:01:18.574  1036  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-01 09:01:18.574  1036  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-01 09:01:18.575  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:18.576  7238  7238 D LocalBluetoothProfileManager: Adding local MAP profile
07-01 09:01:18.578  7238  7238 D BluetoothMap: Create BluetoothMap proxy object
07-01 09:01:18.579  1036  1098 D BluetoothManagerService: Message: 30
,07-01 09:01:18.589  1036  1098 D BluetoothManagerService: Message: 30
07-01 09:01:18.591  7238  7238 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-01 09:01:18.593  7238  7238 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-01 09:01:18.607  7238  7238 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-01 09:01:18.612  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-01 09:01:18.630  7238  7238 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:18.643  7238  7238 D BluetoothInputDevice: Proxy object connected
,07-01 09:01:18.644  7238  7238 D HidProfile: Bluetooth service connected
07-01 09:01:18.645  7238  7238 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 09:01:18.646  7238  7238 D PanProfile: Bluetooth service connected
07-01 09:01:18.647  7238  7238 D BluetoothMap: Proxy object connected
07-01 09:01:18.648  7238  7238 D MapProfile: Bluetooth service connected
07-01 09:01:18.648  7238  7238 D BluetoothMap: getConnectedDevices()
07-01 09:01:18.648  7238  7238 D BluetoothMap: Bluetooth is Not enabled
07-01 09:01:18.648  7238  7238 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 09:01:18.650  7238  7238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 09:01:18.654  7238  7238 D BluetoothPermissionRequest: onReceive
07-01 09:01:18.656  7238  7238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-01 09:01:18.663  1036  1052 I ActivityManager: Killing 6626:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-01 09:01:18.664  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 09:01:18.759  4391  4391 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-01 09:01:18.760  4391  4391 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,07-01 09:01:18.760  4391  4391 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-01 09:01:18.761  1036  1979 W libprocessgroup: failed to open /acct/uid_10008/pid_6626/cgroup.procs: No such file or directory
07-01 09:01:18.826  1036  1052 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7316 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-01 09:01:18.838  4391  4391 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:18.838  4391  4391 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 09:01:18.840  4391  4391 V BluetoothFtpService: Ftp Service onStartCommand
07-01 09:01:18.840  4391  4391 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.840  4391  4391 V BluetoothFtpService: Ftp Service closeService
07-01 09:01:18.840  4391  4391 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,07-01 09:01:18.841  4391  4391 V BluetoothFtpService: successfully stopped ftp service
07-01 09:01:18.841  4391  4391 V BluetoothFtpService: Ftp Service onDestroy
07-01 09:01:18.841  4391  4391 V BluetoothFtpService: Ftp Service closeService
,07-01 09:01:18.843  4391  4391 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:18.843  4391  4391 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:18.843  4391  4391 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:18.843  4391  4391 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.843  4391  4391 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-01 09:01:18.843  4391  4391 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 09:01:18.844  4391  4391 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.844   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 438us total 18.814ms
07-01 09:01:18.844  4391  4391 V BluetoothSapService: state: 13
07-01 09:01:18.844  4391  4391 V BluetoothSapService: Stopping SAP server process
07-01 09:01:18.845  4391  4391 V BluetoothSapService: Sap Service closeSapService in
07-01 09:01:18.845  4391  4391 V BluetoothSapService: Close listen Socket : 
07-01 09:01:18.845  4391  4391 V BluetoothSapService: Close rfcomm Socket : 
07-01 09:01:18.845  4391  4391 V BluetoothSapService: Close sapd  Socket : 
07-01 09:01:18.863   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 352us total 17.714ms
,07-01 09:01:18.879   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 15.414ms
,07-01 09:01:18.892  4391  4467 D bt_hci_bdroid: cleanup
,07-01 09:01:18.892  4391  4591 I bt_lpm  : LPM is already off!!!
07-01 09:01:18.892  4391  4703 I bt_userial_mct: exiting userial_read_thread
07-01 09:01:18.892  4391  4703 D bt_userial_mct: Leaving userial_evt_read_thread()
07-01 09:01:18.892  4391  4467 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-01 09:01:18.892  4391  4591 I bt_vendor: hw_epilog_process
07-01 09:01:18.893  4391  4588 W bt-btif : ag scb idx 1 not allocated
07-01 09:01:18.893  4391  4588 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:18.893  4391  4588 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:18.893  4391  4588 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 09:01:18.893  4391  4467 D bt_hci_bdroid: cleanup Finalizing cleanup
07-01 09:01:18.893  4391  4467 D bt_userial_mct: userial_close
07-01 09:01:18.893  4391  4467 E bt_userial_mct: pthread_join() FAILED result:3
07-01 09:01:18.893  4391  4467 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-01 09:01:18.914  1036  1877 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7334 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-01 09:01:18.928  1036  1051 D WifiServiceImplEx: setWifiEnabled: true pid=7125, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 09:01:18.928  4391  4391 V BluetoothSapService: Sap Service closeSapService out
,07-01 09:01:18.928  4391  4391 V BluetoothSapService: Sap Service onDestroy
07-01 09:01:18.928  4391  4391 V BluetoothSapService: Sap Service closeSapService in
07-01 09:01:18.928  4391  4391 V BluetoothSapService: Close listen Socket : 
07-01 09:01:18.928  4391  4391 V BluetoothSapService: Close rfcomm Socket : 
07-01 09:01:18.928  4391  4391 V BluetoothSapService: Close sapd  Socket : 
07-01 09:01:18.928  1036  1051 D WifiService: setWifiEnabled: true pid=7125, uid=10118
07-01 09:01:18.928  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-01 09:01:18.929  4391  4391 V BluetoothSapService: Sap Service closeSapService out
07-01 09:01:18.938  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:18.938  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:18.938  1036  1542 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-01 09:01:18.938  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:18.938  1036  1542 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-01 09:01:18.939  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-01 09:01:18.939  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 09:01:18.939  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-01 09:01:18.939  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 09:01:18.939  1036  1542 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-01 09:01:18.939  1036  1542 E WifiHW  : unknown target_country: EU , set to default
07-01 09:01:18.939  1036  1542 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-01 09:01:18.939  1036  1542 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-01 09:01:18.939  1036  1542 I WifiUtil: gEnableBmps=1
07-01 09:01:18.955  7316  7316 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 09:01:18.971  7316  7316 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-01 09:01:18.971  7334  7334 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 09:01:18.986  1036  1925 I ActivityManager: Killing 6676:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-01 09:01:18.990  7316  7316 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-01 09:01:18.990  7316  7316 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-01 09:01:18.990  7316  7316 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-01 09:01:18.990  7316  7316 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-01 09:01:18.991  7316  7316 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-01 09:01:18.992  7316  7316 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-01 09:01:18.994  7316  7316 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-01 09:01:19.035  4391  4467 D bt_hci_bdroid: set_power 0
07-01 09:01:19.035  4391  4467 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-01 09:01:19.035  4391  4467 I bt_vendor: bluetooth satus is on
07-01 09:01:19.036  4391  4467 I bt_vendor: bt-vendor : resetting BT status
07-01 09:01:19.036  4391  4467 I bt_vendor: Starting hciattach daemon
07-01 09:01:19.036  4391  4467 I bt_vendor: try to set false
07-01 09:01:19.037  4391  4467 I bt_vendor: Starting hciattach daemon
07-01 09:01:19.037  4391  4467 I bt_vendor: try to set false
07-01 09:01:19.038  4391  4467 I bt_vendor: cleanup
,07-01 09:01:19.038  4391  4588 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-01 09:01:19.069  1036  1906 W libprocessgroup: failed to open /acct/uid_10011/pid_6676/cgroup.procs: No such file or directory
,07-01 09:01:19.074  4391  4467 I GKI_LINUX: GKI_exit_task 0 done
07-01 09:01:19.074  4391  4467 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-01 09:01:19.077  4391  4462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 09:01:19.080  4391  4391 D HeadsetService: Received stop request...Stopping profile...
07-01 09:01:19.081  4391  4391 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 09:01:19.081  4391  4391 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 09:01:19.081  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.082  4391  4517 D HeadsetStateMachine: Exit Disconnected: -1
,07-01 09:01:19.084  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:19.084  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 09:01:19.085  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:19.086  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:19.087  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:19.088  4391  4391 D A2dpService: Received stop request...Stopping profile...
07-01 09:01:19.088  4391  4571 D A2dpStateMachine: Exit Disconnected: -1
07-01 09:01:19.089  4391  4391 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-01 09:01:19.090  4391  4391 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-01 09:01:19.090  4391  4391 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 09:01:19.090  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.090  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:19.091  4391  4391 D HidService: Received stop request...Stopping profile...
07-01 09:01:19.091  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.091  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:19.091  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 09:01:19.091  4391  4462 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 09:01:19.092  4391  4391 D HealthService: Received stop request...Stopping profile...
07-01 09:01:19.092  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.092  7238  7238 D BluetoothInputDevice: Proxy object disconnected
07-01 09:01:19.092  4391  4391 D HeadsetStateMachine: Unbinding service...
07-01 09:01:19.092  7238  7238 D HidProfile: Bluetooth service disconnected
07-01 09:01:19.093  4391  4391 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 09:01:19.093  4391  4391 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 09:01:19.093  4391  4391 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 09:01:19.093  4391  4391 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 09:01:19.093  4391  4391 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 09:01:19.093  4391  4391 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 09:01:19.093  4391  4391 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 09:01:19.093  4391  4391 D PanService: Received stop request...Stopping profile...
07-01 09:01:19.094  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.094  4391  4391 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 09:01:19.095  4391  4391 D BtGatt.GattService: Received stop request...Stopping profile...
07-01 09:01:19.095  4391  4391 D BtGatt.GattService: stop()
07-01 09:01:19.095  4391  4391 D BtGatt.AdvertiseManager: advertise clients cleared
,07-01 09:01:19.096  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.097  4391  4391 I BluetoothA2dpServiceJni: cleanupNative
07-01 09:01:19.097  7238  7238 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 09:01:19.097  7238  7238 D PanProfile: Bluetooth service disconnected
07-01 09:01:19.097  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:19.097  4391  4572 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,07-01 09:01:19.097  4391  4391 I GKI_LINUX: GKI_exit_task 2 done
07-01 09:01:19.097  4391  4391 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 09:01:19.098  4391  4391 D BluetoothMapService: Received stop request...Stopping profile...
07-01 09:01:19.098  4391  4391 D BluetoothMapService: stop()
07-01 09:01:19.098  4391  4391 D BluetoothMapEmailAppObserver: deinitObservers()
07-01 09:01:19.098  4391  4391 D BluetoothMapEmailAppObserver: removeReceiver()
07-01 09:01:19.099  4391  4391 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26fdc508
07-01 09:01:19.100  4391  4391 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 09:01:19.100  4391  4391 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 09:01:19.100  4391  4391 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 09:01:19.100  4391  4391 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 09:01:19.100  4391  4391 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 09:01:19.100  4391  4391 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 09:01:19.100  4391  4391 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-01 09:01:19.100  7238  7238 D BluetoothMap: Proxy object disconnected
07-01 09:01:19.100  7238  7238 D MapProfile: Bluetooth service disconnected
07-01 09:01:19.101  4391  4391 V BluetoothMapService: Handler(): got msg=4
07-01 09:01:19.101  4391  4391 D BluetoothMapService: MAP Service closeService in
07-01 09:01:19.101  4391  4391 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 09:01:19.101  4391  4391 V BluetoothMapService: MAP Service closeService out
07-01 09:01:19.101  4391  4391 D BluetoothMapService: cleanup()
07-01 09:01:19.101  4391  4391 D BluetoothMapService: MAP Service closeService in
07-01 09:01:19.101  4391  4391 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 09:01:19.101  4391  4391 V BluetoothMapService: MAP Service closeService out
07-01 09:01:19.102  4391  4462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-01 09:01:19.102  4391  4462 D BluetoothAdapterProperties: Setting state to 10
07-01 09:01:19.102  4391  4462 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 09:01:19.102  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:19.102  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-01 09:01:19.102  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-01 09:01:19.102  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:19.102  4391  4462 I BluetoothAdapterState: Entering OffState
07-01 09:01:19.103  7238  7254 D BluetoothMap: onBluetoothStateChange: up=false
07-01 09:01:19.103  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:19.103  7238  7255 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 09:01:19.104  7238  7299 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-01 09:01:19.104  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 09:01:19.104  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:19.105  1853  2668 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:19.105  7238  7254 D BluetoothPan: onBluetoothStateChange on: false
07-01 09:01:19.106  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-01 09:01:19.106  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-01 09:01:19.107  1036  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-01 09:01:19.107  1036  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-01 09:01:19.107  1036  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@361e0363 mBinding = false
07-01 09:01:19.107  1036  1098 D BluetoothManagerService: Sending unbind request.
07-01 09:01:19.109  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-01 09:01:19.112  4391  4467 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-01 09:01:19.113  4391  4391 I GKI_LINUX: GKI_exit_task 1 done
07-01 09:01:19.113  4391  4391 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-01 09:01:19.113  4391  4391 I BluetoothServiceJni: cleanupNative: return from cleanup
07-01 09:01:19.114  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:19.114  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:19.114  1944  2127 D LGBluetoothAPIService: Message: 2
07-01 09:01:19.114  1944  2127 D LGBluetoothAPISer,vice: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@154dac3b mBinding = false
07-01 09:01:19.114  1944  2127 D LGBluetoothAPIService: Sending unbind request.
07-01 09:01:19.115  7238  7238 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 09:01:19.116  7238  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-01 09:01:19.116  4391  4391 I art     : --- WEIRD: removing null entry 246
07-01 09:01:19.116  7238  7238 D LGBluetoothEventManager: [BTUI] clear device connection state
07-01 09:01:19.116  4391  4391 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-01 09:01:19.116  4391  4391 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-01 09:01:19.118  4391  4391 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-01 09:01:19.119  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 09:01:19.120  4391  4391 I art     : System.exit called, status: 0
07-01 09:01:19.120  4391  4391 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-01 09:01:19.120  1606  1606 D BluetoothAdapter: 140392864: getState() :  mService = null. Returning STATE_OFF
07-01 09:01:19.120  1606  1606 D BluetoothAdapter: 140392864: getState() :  mService = null. Returning STATE_OFF
07-01 09:01:19.125  7238  7238 D DockEventReceiver: finishStartingService: stopping service
07-01 09:01:19.128  7316  7316 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 09:01:19.130  7316  7316 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-01 09:01:19.130  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:19.132  7316  7316 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-01 09:01:19.134  7257  7257 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 09:01:19.134  7257  7257 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 09:01:19.134  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:19.136  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:19.137   314  2146 V AudioFlinger: 4391 died, releasing its sessions
07-01 09:01:19.137   314  2146 V AudioFlinger:  pid 1853 @ 0
07-01 09:01:19.137   314  2146 V AudioFlinger:  pid 3403 @ 1
07-01 09:01:19.137   314  2146 V AudioFlinger:  pid 3403 @ 2
,07-01 09:01:19.158  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:19.158  7238  7238 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-01 09:01:19.196  1036  1616 I ActivityManager: Process com.android.bluetooth (pid 4391) has died
07-01 09:01:19.196  1036  1616 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-01 09:01:19.207  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:19.227  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-01 09:01:19.231  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:19.240  7316  7316 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 09:01:19.252  7238  7238 D BluetoothPermissionRequest: onReceive
,07-01 09:01:19.258  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:19.262  7238  7238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 09:01:19.263  7238  7238 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-01 09:01:19.268  7257  7257 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 09:01:19.268  7257  7257 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 09:01:19.268  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 09:01:19.271  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 09:01:19.274  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:19.280  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 09:01:19.337  1036  1943 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7357 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-01 09:01:19.346  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:19.346  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:19.350  7316  7316 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-01 09:01:19.400  1036  1979 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7374 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-01 09:01:19.419  7357  7357 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-01 09:01:19.419  7357  7357 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 09:01:19.419  7357  7357 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,07-01 09:01:19.420  7357  7357 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-01 09:01:19.435  7357  7357 D BluetoothAdapterApp: Loading JNI Library
,07-01 09:01:19.463  7357  7357 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@10961169 Instance Count = 1
,07-01 09:01:19.467  7357  7357 D BluetoothAdapterApp: onCreate
07-01 09:01:19.473  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:19.475  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:19.483  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:19.485  7357  7357 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-01 09:01:19.485  7357  7357 D ProfileConfigQcom: Adding HeadsetService
07-01 09:01:19.486  7357  7357 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-01 09:01:19.486  7357  7357 D ProfileConfigQcom: Adding A2dpService
07-01 09:01:19.486  7357  7357 D ProfileConfigQcom: [BTUI] HidService is supported
07-01 09:01:19.486  7357  7357 D ProfileConfigQcom: Adding HidService
07-01 09:01:19.487  7357  7357 D ProfileConfigQcom: [BTUI] HealthService is supported
07-01 09:01:19.487  7357  7357 D ProfileConfigQcom: Adding HealthService
07-01 09:01:19.487  7357  7357 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-01 09:01:19.489  7357  7357 D ProfileConfigQcom: [BTUI] PanService is supported
07-01 09:01:19.489  7357  7357 D ProfileConfigQcom: Adding PanService
07-01 09:01:19.489  7357  7357 D ProfileConfigQcom: [BTUI] GattService is supported
07-01 09:01:19.490  7357  7357 D ProfileConfigQcom: Adding GattService
07-01 09:01:19.490  7357  7357 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-01 09:01:19.490  7357  7357 D ProfileConfigQcom: Adding BluetoothMapService
07-01 09:01:19.490  7357  7357 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-01 09:01:19.492  7357  7357 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-01 09:01:19.496  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:19.496  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 09:01:19.496  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 09:01:19.496  7238  7238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-01 09:01:19.496  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 09:01:19.499  7357  7357 V LGMDMManagerInternal: Create singleton instance
07-01 09:01:19.500  7374  7394 W FormManager: Network not available. Please check & try again.
07-01 09:01:19.504  7238  7238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 09:01:19.504  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 09:01:19.504  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 09:01:19.504  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 09:01:19.504  7238  7238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 09:01:19.505  7238  7238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 09:01:19.506  7238  7238 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 09:01:19.507  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:19.507  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:19.509  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:19.512  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 09:01:19.518  7374  7396 V FormManager: Network unavailable.
07-01 09:01:19.520  7374  7396 V FormManager: Network unavailable.
07-01 09:01:19.525  4866  7398 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 09:01:19.526  7257  7257 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-01 09:01:19.526  7257  7257 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 09:01:19.526  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 09:01:19.528  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:19.535  4866  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:19.536  4866  7399 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:19.537  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 09:01:19.538  7374  7401 W FormManager: Network not available. Please check & try again.
07-01 09:01:19.547  7374  7402 V FormManager: Network unavailable.
07-01 09:01:19.548  7316  7316 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-01 09:01:19.548  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-01 09:01:19.548  7316  7316 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-01 09:01:19.549  7374  7402 V FormManager: Network unavailable.
07-01 09:01:19.552  1036  1978 I ActivityManager: Killing 6701:com.android.contacts/u0a19 (adj 15): empty #17
,07-01 09:01:19.570  7316  7316 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 09:01:19.571  7316  7316 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 09:01:19.575  7316  7316 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-01 09:01:19.576  7316  7316 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-01 09:01:19.576  7316  7316 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-01 09:01:19.576  7316  7316 V SoundPool: doLoad: loading sample sampleID=1
07-01 09:01:19.577  7316  7316 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-01 09:01:19.578  7316  7410 V SoundPool: Start decode
07-01 09:01:19.578  7316  7410 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-01 09:01:19.579   314  2144 V MediaPlayerService: decode(22, 10857164, 17813)
07-01 09:01:19.579   314  2144 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-01 09:01:19.579   314  2144 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-01 09:01:19.579   314  2144 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-01 09:01:19.580   314  2144 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-01 09:01:19.580   314  2144 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-01 09:01:19.580   314  2144 V MediaPlayerService: player type = 3
07-01 09:01:19.580   314  2144 V AwesomePlayer: AwesomePlayer create()
07-01 09:01:19.580   314  2144 V AwesomePlayer: reset_l() 
07-01 09:01:19.580   314  2144 V AwesomePlayer: cancelPlayerEvents
07-01 09:01:19.581   314  2144 V AwesomePlayer: setAudioSink() 
07-01 09:01:19.581   314  2144 V AwesomePlayer: reset_l() 
07-01 09:01:19.581   314  2144 V AudioCache: notify(0xb5474a40, 8, 0, 0)
07-01 09:01:19.581   314  2144 V AudioCache: ignored
07-01 09:01:19.581   314  2144 V AwesomePlayer: cancelPlayerEvents
07-01 09:01:19.581   314  2144 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
07-01 09:01:19.581   314  2144 V AwesomePlayer: setDataSource_l dataSource
07-01 09:01:19.581   314  2144 V LGParserOSAL: SniffLGParser start
07-01 09:01:19.581   314  2144 V LGParserOSAL: MainType:5, SubType=0
07-01 09:01:19.581   314  2144 V LGParserOSAL: #### check Mime : application/ogg
07-01 09:01:19.581   314  2144 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-01 09:01:19.581   314  2144 E MediaExtractor: Use LGExtractor :application/ogg 
07-01 09:01:19.606   314  2144 V LGParserOSAL: supported mime: application/ogg
07-01 09:01:19.606   314  2144 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-01 09:01:19.606   314  2144 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-01 09:01:19.606   314  2144 V AwesomePlayer: mBitrate = -1 bits/sec
07-01 09:01:19.606   314  2144 V AwesomePlayer: AudioTrack Setting
07-01 09:01:19.606   314  2144 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-01 09:01:19.606   314  2144 V AwesomePlayer: setAudioSource() 
07-01 09:01:19.606   314  2144 V MediaPlayerService: prepare
07-01 09:01:19.606   314  2144 V AwesomePlayer: prepareAsync_l() 
07-01 09:01:19.606   314  2144 V MediaPlayerService: wait for prepare
07-01 09:01:19.606   314  7412 V AwesomePlayer: onPrepareAsyncEvent() 
07-01 09:01:19.606   314  7412 V AwesomePlayer: initAudioDecoder() 
07-01 09:01:19.606   314  7412 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,07-01 09:01:19.606   314  7412 V AudioSystem: isOffloadSupported()
07-01 09:01:19.606   314  7412 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-01 09:01:19.606   314  7412 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-01 09:01:19.606   314  7412 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 09:01:19.606   314  7412 V AwesomePlayer: getUseOffload() = 0 
07-01 09:01:19.606   314  7412 V OMXCodec: OMXCodec::Create
,07-01 09:01:19.606   314  7412 V OMXCodec: findMatchingCodecs()
07-01 09:01:19.606   314  7412 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-01 09:01:19.606   314  7412 V OMXCodec: matchingCodecs.size()=1
07-01 09:01:19.607   314  7412 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
07-01 09:01:19.607   314  7412 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-01 09:01:19.607   314  7412 V LGCodecAdapter: LG Codec Adapter start
07-01 09:01:19.607   314  7412 V OMXCodec: OMXCodec Createtor
07-01 09:01:19.607   314  7412 V OMXCodec: setComponentRole
07-01 09:01:19.607   314  7412 V OMXCodec: configureCodec protected=0
07-01 09:01:19.608   314  7412 V LGCodecAdapter: called getLGCodecSpecificData
07-01 09:01:19.608   314  7412 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-01 09:01:19.608   314  7412 V LGCodecOSAL: Called LGconfigureCodecMETA
07-01 09:01:19.608   314  7412 V LGCodecOSAL: Called LGconfigureCodecMSG
07-01 09:01:19.608   314  7412 V LGCodecOSAL: Not support LGCodec
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-01 09:01:19.608   314  7412 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-01 09:01:19.608   314  7412 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-01 09:01:19.608   314  7412 I AwesomePlayer: Could not offload audio decode, try pcm offload
,07-01 09:01:19.608   314  7412 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-01 09:01:19.608   314  7412 V AudioSystem: isOffloadSupported()
07-01 09:01:19.608   314  7412 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-01 09:01:19.608   314  7412 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-01 09:01:19.608   314  7412 V OMXCodec: init()
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-01 09:01:19.608   314  7412 V OMXCodec: allocateBuffers
07-01 09:01:19.608   314  7412 V OMXCodec: allocateBuffersOnPort portIndex=0
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
07-01 09:01:19.608   314  7412 V OMXCodec: allocateBuffersOnPort portIndex=1
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
07-01 09:01:19.608   314  7412 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd240 on output port
07-01 09:01:19.608   314  7412 V OMXCodec: init() mAsyncCompletion wait!!! 
07-01 09:01:19.609   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-01 09:01:19.609   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-01 09:01:19.609   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-01 09:01:19.609   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-01 09:01:19.609   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-01 09:01:19.609   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-01 09:01:19.609   314  7412 V OMXCodec: init() mAsyncCompletion wait free! 
07-01 09:01:19.609   314  7412 V AwesomePlayer: finishAsyncPrepare_l() 
07-01 09:01:19.609   314  7412 V AudioCache: notify(0xb5474a40, 5, 0, 0)
07-01 09:01:19.609   314  7412 V AudioCache: ignored
07-01 09:01:19.609   314  7412 V AudioCache: notify(0xb5474a40, 1, 0, 0)
07-01 09:01:19.609   314  7412 V AudioCache: prepared
07-01 09:01:19.609   314  2144 V AudioCache: wait - success
07-01 09:01:19.609   314  2144 V MediaPlayerService: start
07-01 09:01:19.609   314  2144 V AwesomePlayer: play_l() 
07-01 09:01:19.609   314  2144 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-01 09:01:19.609   314  2144 V AwesomePlayer: createAudioPlayer_l
07-01 09:01:19.609   314  2144 V AwesomePlayer: seekAudioIfNecessary_l() 
07-01 09:01:19.609   314  2144 V AwesomePlayer: startAudioPlayer_l() 
07-01 09:01:19.609   314  2144 D AudioPlayer: start of Playback, useOffload 0
07-01 09:01:19.609   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-01 09:01:19.609   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] ,OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790848
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-01 09:01:19.611   314  7414 V OMXCodec: allocateBuffersOnPort portIndex=1
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd6a0 on output port
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-01 09:01:19.611   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-01 09:01:19.612   314  2144 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-01 09:01:19.612   314  2144 V AudioCache: notify(0xb5474a40, 6, 0, 0)
07-01 09:01:19.612   314  2144 V AudioCache: ignored
07-01 09:01:19.612   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.612   314  7415 V AudioCache: memcpy(0xaf104000, 0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: memcpy(0xaf105000, 0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: memcpy(0xaf106000, 0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: memcpy(0xaf107000, 0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: memcpy(0xaf108000, 0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.613   314  7415 V AudioCache: memcpy(0xaf109000, 0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: memcpy(0xaf10a000, 0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: memcpy(0xaf10b000, 0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: memcpy(0xaf10c000, 0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: memcpy(0xaf10d000, 0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.614   314  7415 V AudioCache: memcpy(0xaf10e000, 0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: memcpy(0xaf10f000, 0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: memcpy(0xaf110000, 0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: memcpy(0xaf111000, 0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.615   314  7415 V AudioCache: memcpy(0xaf112000, 0xb1472000, 4096)
07-01 09:01:19.615   314  2144 V MediaPlayerService: wait for playback complete
07-01 09:01:19.616   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.616   314  7415 V AudioCache: memcpy(0xaf113000, 0xb1472000, 4096)
07-01 09:01:19.616   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.616   314  7415 V AudioCache: memcpy(0xaf114000, 0xb1472000, 4096)
07-01 09:01:19.616   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.616   314  7415 V AudioCache: memcpy(0xaf115000, 0xb1472000, 4096)
07-01 09:01:19.617   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.617   314  7415 V AudioCache: memcpy(0xaf116000, 0xb1472000, 4096)
07-01 09:01:19.617   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.617   314  7415 V AudioCache: memcpy(0xaf117000, 0xb1472000, 4096)
07-01 09:01:19.618   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.618   314  7415 V AudioCache: memcpy(0xaf118000, 0xb1472000, 4096)
07-01 09:01:19.618   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.618   314  7415 V AudioCache: memcpy(0xaf119000, 0xb1472000, 4096)
07-01 09:01:19.619   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.619   314  7415 V AudioCache: memcpy(0xaf11a000, 0xb1472000, 4096)
07-01 09:01:19.619   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.619   314  7415 V AudioCache: memcpy(0xaf11b000, 0xb1472000, 4096)
07-01 09:01:19.620   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.620   314  7415 V AudioCache: memcpy(0xaf11c000, 0xb1472000, 4096)
07-01 09:01:19.620   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.620   314  7415 V AudioCache: memcpy(0xaf11d000, 0xb1472000, 4096)
07-01 09:01:19.621   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.621   314  7415 V AudioCache: memcpy(0xaf11e000, 0xb1472000, 4096)
07-01 09:01:19.621   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.621   314  7415 V AudioCache: memcpy(0xaf11f000, 0xb1472000, 4096)
07-01 09:01:19.621   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.621   314  7415 V AudioCache: memcpy(0xaf120000, 0xb1472000, 4096)
07-01 09:01:19.622   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.622   314  7415 V AudioCache: memcpy(0xaf121000, 0xb1472000, 4096)
07-01 09:01:19.622   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.622   314  7415 V AudioCache: memcpy(0xaf122000, 0xb1472000, 4096)
07-01 09:01:19.623   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.623   314  7415 V AudioCache: memcpy(0xaf123000, 0xb1472000, 4096)
07-01 09:01:19.623   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.623   314  7415 V AudioCache: memcpy(0xaf124000, 0xb1472000, 4096)
07-01 09:01:19.623   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.624   314  7415 V AudioCache: memcpy(0xaf125000, 0xb1472000, 4096)
07-01 09:01:19.624   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.624   314  7415 V AudioCache: memcpy(0xaf126000, 0xb1472000, 4096)
07-01 09:01:19.624   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.624   314  7415 V AudioCache: memcpy(0xaf127000, 0xb1472000, 4096)
07-01 09:01:19.625   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.625   314  7415 V AudioCache: memcpy(0xaf128000, 0xb1472000, 4096)
07-01 09:01:19.625   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.625   314  7415 V AudioCache: memcpy(0xaf129000, 0xb1472000, 4096)
07-01 09:01:19.625   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.625   314  7415 V AudioCache: memcpy(0xaf12a000, 0xb1472000, 4096)
07-01 09:01:19.626   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.626   314  7415 V AudioCache: memcpy(0xaf12b000, 0xb1472000, 4096)
07-01 09:01:19.626   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.626   314  7415 V AudioCache: memcpy(0xaf12c000, 0xb1472000, 4096)
07-01 09:01:19.627   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.627   314  7415 V AudioCache: memcpy(0xaf12d000, 0xb1472000, 4096)
07-01 09:01:19.627   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.627   314  7415 V AudioCache: memcpy(0xaf12e000, 0xb1472000, 4096)
07-01 09:01:19.628   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.628   314  7415 V AudioCache: memcpy(0xaf12f000, 0xb1472000, 4096)
07-01 09:01:19.628   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.628   314  7415 V AudioCache: memcpy(0xaf130000, 0xb1472000, 4096)
07-01 09:01:19.628   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.629   314  7415 V AudioCache: memcpy(0xaf131000, 0xb1472000, 4096)
07-01 09:01:19.629   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.629   314  7415 V AudioCache: memcpy(0xaf132000, 0xb1472000, 4096)
07-01 09:01:19.630   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.630   314  7415 V AudioCache: memcpy(0xaf133000, 0xb1472000, 4096)
07-01 09:01:19.630   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.630   314  7415 V AudioCache: memcpy(0xaf134000, 0xb1472000, 4096)
07-01 09:01:19.631   314  7415 V AudioCache: write(0xb1472000, 4096)
07-01 09:01:19.631   314  7415 V AudioCache: memcpy(0xaf135000, 0xb1472000, 4096)
07-01 09:01:19.631   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-01 09:01:19.631   314  7415 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-01 09:01:19.631   314  7415 V AwesomePlayer: postAudioEOS() 
07-01 09:01:19.631   314  7415 V AudioCache: write(0xb1472000, 280)
07-01 09:01:19.631   314  7415 V AudioCache: memcpy(0xaf136000, 0xb1472000, 280)
07-01 09:01:19.633   314  7412 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-01 09:01:19.633   314  7412 V AwesomePlayer: onStreamDone
07-01 09:01:19.633   314  7412 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-01 09:01:19.633   314  7412 V AudioCache: notify(0xb5474a40, 2, 0, 0)
07-01 09:01:19.633   314  7412 V AudioCache: playback complete
07-01 09:01:19.633   314  7412 V AwesomePlayer: pause_l() 
07-01 09:01:19.633   314  7412 V AudioCache: notify(0xb5474a40, 7, 0, 0)
07-01 09:01:19.633   314  7412 V AudioCache: ignored
07-01 09:01:19.633   314  7412 V AwesomePlayer: cancelPlayerEvents
07-01 09:01:19.633   314  2144 V AudioCache: wait - success
07-01 09:01:19.633   314  2144 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-01 09:01:19.633   314  7412 D AudioPlayer: Pause Playback at 1068125
07-01 09:01:19.634   314  2144 V AwesomePlayer: reset_l() 
07-01 09:01:19.634   314  2144 V AudioCache: notify(0xb5474a40, 8, 0, 0)
07-01 09:01:19.634   314  2144 V AudioCache: ignored
07-01 09:01:19.634   314  2144 V AwesomePlayer: cancelPlayerEvents
07-01 09:01:19.634   314  2144 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-01 09:01:19.634   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-01 09:01:19.634   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-01 09:01:19.634   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-01 09:01:19.634   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd6a0 on port 1
07-01 09:01:19.634   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-01 09:01:19.635   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-01 09:01:19.635   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-01 09:01:19.635   314  7414 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-01 09:01:19.635   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-01 09:01:19.635   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-01 09:01:19.635   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-01 09:01:19.636   314  2144 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-01 09:01:19.636   314  2144 D AudioPlayer: AudioPlayer releasing audio source
07-01 09:01:19.636   314  2144 D AudioPlayer: AudioPlayer done releasing audio source
07-01 09:01:19.636   314  2144 V AwesomePlayer: reset_l() 
07-01 09:01:19.636   314  2144 V AwesomePlayer: cancelPlayerEvents
07-01 09:01:19.636   314  2144 V AwesomePlayer: ~AwesomePlayer call
07-01 09:01:19.645   314  2144 V AwesomePlayer: reset_l() 
07-01 09:01:19.645   314  2144 V AwesomePlayer: cancelPlayerEvents
,07-01 09:01:19.645  7316  7410 V SoundPool: close(31)
07-01 09:01:19.646  7316  7410 V SoundPool: pointer = 0x9fe5e000, size = 205080, sampleRate = 48000, numChannels = 2
07-01 09:01:19.646  1036  1616 W libprocessgroup: failed to open /acct/uid_10019/pid_6701/cgroup.procs: No such file or directory
07-01 09:01:19.649  7357  7357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:19.651  7316  7316 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-01 09:01:19.652  6980  6980 D UEI.SmartControl: QS Service created
07-01 09:01:19.653  7357  7357 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:19.654  7357  7357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:19.654  7357  7357 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:19.655  7357  7357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:19.655  7357  7357 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-01 09:01:19.658  7316  7316 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 09:01:19.658  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-01 09:01:19.662  7334  7334 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-01 09:01:19.663  6980  6980 I UEI.SmartControl: Service initServices...
07-01 09:01:19.663  6980  6980 D UEI.SmartControl: QS start get config
07-01 09:01:19.664  7316  7316 V LGMDMManager: Create singleton instance
07-01 09:01:19.700  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-01 09:01:19.700  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-01 09:01:19.701  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5762
07-01 09:01:19.721  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 09:01:19.721  1036  1098 D Tethering: InitialState.processMessage what=4
07-01 09:01:19.726   309   896 D SoftapController: Softap fwReload - Ok
07-01 09:01:19.726  1036  1542 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (784ms)
07-01 09:01:19.727   309   896 D CommandListener: Setting iface cfg
07-01 09:01:19.727   309   896 D CommandListener: Trying to bring down wlan0
07-01 09:01:19.727   309   896 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:19.729  1036  1542 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-01 09:01:19.730  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:19.730  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:19.730  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:19.720  7418  7418 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:19.720  7418  7418 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:19.742  7418  7418 I wpa_supplicant: Successfully initialized wpa_supplicant
07-01 09:01:19.742  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:19.742  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 09:01:19.742  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 09:01:19.742  7238  7238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 09:01:19.743  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-01 09:01:19.747  1036  1542 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-01 09:01:19.747  1036  1542 D WifiMonitor: connecting to supplicant
07-01 09:01:19.747  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 09:01:19.748  7238  7238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 09:01:19.748  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 09:01:19.748  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 09:01:19.748  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 09:01:19.748  7238  7238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 09:01:19.748  7238  7238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 09:01:19.749  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-01 09:01:19.752  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:19.753  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-01 09:01:19.753  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:19.753  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:19.753  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 09:01:19.753  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 09:01:19.754  7238  7238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 09:01:19.754  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:19.754  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 09:01:19.754  7238  7238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 09:01:19.754  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 09:01:19.754  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 09:01:19.754  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 09:01:19.754  7238  7238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 09:01:19.754  7238  7238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 09:01:19.756  7418  7418 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-01 09:01:19.756  7418  7418 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-01 09:01:19.760  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:19.762  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:19.768  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 09:01:19.781  7374  7420 W FormManager: Network not available. Please check & try again.
07-01 09:01:19.782  7374  7421 V FormManager: Network unavailable.
07-01 09:01:19.783  7374  7421 V FormManager: Network unavailable.
07-01 09:01:19.870  7418  7418 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 09:01:19.939  1036  1943 D WifiServiceImplEx: setWifiEnabled: false pid=7125, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 09:01:19.940  1036  1943 D WifiService: setWifiEnabled: false pid=7125, uid=10118
,07-01 09:01:19.940  1036  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-01 09:01:19.947  7418  7418 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-01 09:01:19.950  7418  7418 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-01 09:01:19.950  7418  7418 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-01 09:01:19.953  1036  7422 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-01 09:01:19.953  1036  7422 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 09:01:19.953  1036  7422 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-01 09:01:19.953  1036  7422 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-01 09:01:19.953  1036  7422 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-01 09:01:19.953  1036  7422 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-01 09:01:19.954  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:19.954  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:19.954  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:19.955  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-01 09:01:19.956  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-01 09:01:19.957  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-01 09:01:19.958  1036  1542 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,07-01 09:01:19.960  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:19.961  1036  1542 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:19.962  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:19.963  1036  1542 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:19.964  1036  1542 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-01 09:01:19.964  1036  1542 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-01 09:01:19.966  1036  1542 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-01 09:01:19.966  1036  1542 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-01 09:01:19.967  1036  1542 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-01 09:01:19.968  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:19.968  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:19.968  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:19.968  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:19.968  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:19.969  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:19.969  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:19.969  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 09:01:19.972  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:19.974  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:19.974  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:19.975  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:19.975  7125  7125 D io.jxcore.node.JXcoreExtension: notifyN,etworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:19.976  1944  1944 D WfdService: Waiting for WifiP2p enabling
,07-01 09:01:19.978  1036  1542 D WifiNative-wlan0: doBoolean: SET update_config 1
,07-01 09:01:19.978  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-01 09:01:19.978  1036  1542 D WifiNative-wlan0: SET update_config 1: returned true
07-01 09:01:19.978  1036  1542 D WifiConfigStore: Loading config and enabling all networks 
07-01 09:01:19.978  1036  1542 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-01 09:01:19.978  1036  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-01 09:01:19.979  1036  1542 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-01 09:01:19.982  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:19.983  1036  1542 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-01 09:01:19.986  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:19.991  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:19.999  1036  1542 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-01 09:01:19.999  1036  1542 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 09:01:19.999  7374  7425 W FormManager: Network not available. Please check & try again.
07-01 09:01:19.999  1036  1542 D WifiStateMachine: enableVerboseLogging : level 2
07-01 09:01:19.999  1036  1542 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-01 09:01:20.000  1036  1542 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-01 09:01:20.001  1036  1542 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-01 09:01:20.001  1036  1542 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-01 09:01:20.001  1036  1542 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-01 09:01:20.002  1036  1542 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 09:01:20.002  1036  1542 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-01 09:01:20.003  1036  1542 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-01 09:01:20.003  1036  1542 D WifiNative-HAL: Setting external_sim to 1
07-01 09:01:20.003  1036  1542 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-01 09:01:20.003  1036  1542 D WifiNative-wlan0: SET external_sim 1: returned true
07-01 09:01:20.003  1036  1542 I WifiNative-HAL: startHal
07-01 09:01:20.003  1036  1542 D wifi    : setting scan oui 0xaf64e2a0
07-01 09:01:20.003  1036  1542 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 09:01:20.003  1036  1542 I WifiNative-HAL: startHal
07-01 09:01:20.003  1036  1542 D wifi    : setting scan oui 0xaf64e2a0
07-01 09:01:20.003  1036  1542 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-01 09:01:20.004  1036  1542 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-01 09:01:20.004  1944  1944 D WfdsService: Supplicant Connection state is changed : true
07-01 09:01:20.004  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-01 09:01:20.004  1944  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
,07-01 09:01:20.004  1944  2326 D WfdsService: Set the WFDS Monitor: true
07-01 09:01:20.004  1944  2326 D WfdsMonitor: WfdsMonitorThread create
07-01 09:01:20.004  1944  2326 D WfdsMonitor: WFDS Monitor is created and started
07-01 09:01:20.004  1944  2326 D WfdsService: WiFi: Supplicant connection re-established
07-01 09:01:20.004  7418  7418 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-01 09:01:20.004  1036  1542 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-01 09:01:20.004  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 09:01:20.004  7418  7418 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 09:01:20.004  1944  7427 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-01 09:01:20.004  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:20.004  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 09:01:20.004  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
,07-01 09:01:20.004  7418  7418 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-01 09:01:20.005  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-01 09:01:20.005  1944  7427 E CtrlSupplicant: Succeed to open control connection
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 09:01:20.005  7418  7418 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 09:01:20.005  1944  7427 E CtrlSupplicant: Succeed to open monitor connection
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 09:01:20.005  7418  7418 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-01 09:01:20.005  7418  7418 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-01 09:01:20.005  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 09:01:20.005  7418  7418 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 09:01:20.006  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 09:01:20.006  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:20.006  1036  1542 E WifiNative: : [289,278,448 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-01 09:01:20.006  1036  1542 D WifiNative-wlan0: doBoolean: RECONNECT
07-01 09:01:20.006  1036  1542 D WifiNative-wlan0: RECONNECT: returned true
07-01 09:01:20.006  1036  1542 D WifiNative-wlan0: doString: [STATUS]
07-01 09:01:20.007  1036  7422 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-01 09:01:20.007  1036  7422 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,07-01 09:01:20.007  1036  1542 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-01 09:01:20.007  1036  1542 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 09:01:20.007  1036  1542 D WifiNative-wlan0: SET ps 1: returned true
07-01 09:01:20.007  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.008   309   896 D CommandListener: Setting iface cfg
07-01 09:01:20.009  1036  1542 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-01 09:01:20.009   309   896 D CommandListener: Trying to bring up p2p0
07-01 09:01:20.009  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 09:01:20.009  1036  1542 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-01 09:01:20.009  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-01 09:01:20.009  1036  1560 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.009  1036  1542 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-01 09:01:20.009  1036  1560 I WifiNative-HAL: startHal
07-01 09:01:20.009  1036  1560 D wifi    : getting scan capabilities on interface[1] = 0xaf64e2a0
07-01 09:01:20.009  1036  1560 D wifi    : failed to get capabilities : -3
07-01 09:01:20.009  1036  1560 E WifiScanningService: could not get scan capabilities
,07-01 09:01:20.009  1036  1542 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-01 09:01:20.009  1036  1561 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.009  1036  1542 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:20.009  1036  1541 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 09:01:20.009  1036  1541 D LGWifiP2pService: P2pEnablingState
07-01 09:01:20.010  1036  1541 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.010  1036  1542 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:20.010  1036  1541 D LGWifiP2pService: P2p socket connection successful
07-01 09:01:20.010  1036  1541 D LGWifiP2pService: P2pEnabledState
07-01 09:01:20.010  1036  1542 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:20.010  1036  1541 D LGWifiP2pService: sending p2p connection changed broadcast
,07-01 09:01:20.010  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-01 09:01:20.010  1036  1541 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-01 09:01:20.011  1036  1541 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-01 09:01:20.011  1036  1541 D WifiNative-p2p0: doBoolean: SET device_name G3
07-01 09:01:20.012  1036  1541 D WifiNative-p2p0: SET device_name G3: returned true
07-01 09:01:20.012  1036  1541 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-01 09:01:20.012  1036  1541 D LGWifiP2pService: before postfix = G3
07-01 09:01:20.012  1036  1541 D WifiServerServiceExt: postfix byte check : 2
07-01 09:01:20.012  1036  1541 D LGWifiP2pService: after postfix = G3
07-01 09:01:20.012  1036  1541 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-01 09:01:20.012  1036  1541 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-01 09:01:20.012  1036  1541 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-01 09:01:20.013  1036  1541 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true,
07-01 09:01:20.013  1036  1541 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-01 09:01:20.013  1944  7427 D WfdsMonitor: Supplicant connection established
07-01 09:01:20.013  1036  1541 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-01 09:01:20.013  1036  1541 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-01 09:01:20.014  1036  1541 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-01 09:01:20.014  1036  1541 D WifiNative-HAL: p2pGetDeviceAddress
07-01 09:01:20.014  1036  1541 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-01 09:01:20.015  1944  2326 D WfdsService: Connected to the supplicant for wfds
,07-01 09:01:20.016  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-01 09:01:20.016  1944  1944 D WfdsService: WifiP2pState is changed : true
07-01 09:01:20.016  1944  2326 D WfdsService: Receive the WFDS_ENABLE Method
07-01 09:01:20.016  1944  2326 D WfdsService: Set the WFDS Monitor: true
,07-01 09:01:20.016  1944  2326 D WfdsService: Connected to the supplicant for wfds
07-01 09:01:20.016  1944  2326 D WfdsJNI : doCommand: WFDS_SET TRUE
07-01 09:01:20.016  7418  7418 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-01 09:01:20.017  1944  2326 D WfdsService: selectPreferredScanChannel [36]
07-01 09:01:20.017  1944  2326 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-01 09:01:20.017  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-01 09:01:20.018  1944  1944 D WfdsService: isConnected: false
07-01 09:01:20.019  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 09:01:20.019  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-01 09:01:20.019  1036  1560 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.019  1036  1561 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.020  1036  1542 E WifiStateMachine:  WaitForP2pDisableState what:132106 1 0
07-01 09:01:20.020  1036  1541 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-01 09:01:20.020  1036  1541 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-01 09:01:20.020  1036  1542 E WifiStateMachine:  SupplicantStartedState what:132106 1 0
07-01 09:01:20.020  1036  1542 E WifiStateMachine:  DefaultState what:132106 1 0
07-01 09:01:20.020  1036  1542 E WifiStateMachine: Error! unhandled message{ when=-43ms what=132106 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.021  1036  1542 E WifiStateMachine:  WaitForP2pDisableState what:132096 -100 0
07-01 09:01:20.021  1036  1542 E WifiStateMachine:  SupplicantStartedState what:132096 -100 0
07-01 09:01:20.021  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
07-01 09:01:20.021  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-01 09:01:20.021  1944  1944 D WfdsService: Update P2p Interface State: 3
07-01 09:01:20.021  1036  1542 E WifiStateMachine:  DefaultState what:132096 -100 0
07-01 09:01:20.021  1036  1542 E WifiStateMachine: Error! unhandled message{ when=-44ms what=132096 arg1=-100 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.021  1036  1541 D WifiNative-p2p0: P2P_FLUSH: returned true
07-01 09:01:20.021  1036  1541 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-01 09:01:20.022  1036  1542 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 09:01:20.022  1036  1541 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-01 09:01:20.022  1036  1542 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_FREQUENCY_BAND 0 0
07-01 09:01:20.022  1036  1541 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-01 09:01:20.022  1036  1542 E WifiStateMachine:  WaitForP2pDisableState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=289294  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 09:01:20.022  1036  1541 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-01 09:01:20.022  1036  1541 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-01 09:01:20.022  1036  1542 E WifiStateMachine:  WaitForP2pDisableState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:20.023  1036  1542 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:20.023  1036  1542 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:20.023  7374  7426 V FormManager: Network unavailable.
07-01 09:01:20.023  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:20.026  6980  6980 I UEI.SmartControl: Supports setup maps: true
,07-01 09:01:20.030  1036  1541 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-01 09:01:20.030  1036  1541 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-01 09:01:20.030  1036  1541 D LGWifiP2pService: InactiveState
07-01 09:01:20.030  1036  1541 D LGWifiP2pService: InactiveState{ when=-12ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.030  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1bbaae0e
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: P2pDisablingState
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: DefaultState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: P2pDisablingState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  7374  7426 V FormManager: Network unavailable.
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: P2pDisablingState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.031  1036  1541 D LGWifiP2pService: p2p socket connection lost
07-01 09:01:20.032  1036  1541 D LGWifiP2pService: P2pDisabledState
07-01 09:01:20.032  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.032  1036  1541 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.032  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.032  1036  1542 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-01 09:01:20.032  1036  1541 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.032   309   896 D CommandListener: Clearing all IP addresses on wlan0
07-01 09:01:20.032  1036  1036 E WifiServerServiceExt: No p2p device connected
07-01 09:01:20.033  1944  2326 W WfdsService: DefaultState - msg [9441285] is not handled
07-01 09:01:20.033  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 09:01:20.033  1944  1944 D WfdsService: WifiP2pState is changed : false
07-01 09:01:20.033  1944  2326 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-01 09:01:20.033  1944  2326 D WfdsService: Set the WFDS Monitor: false
07-01 09:01:20.034  1036  1542 D WifiNative-p2p0: doBoolean: TERMINATE
07-01 09:01:20.034  1944  2326 D WfdsMonitor: WFDS Monitor is stopped
07-01 09:01:20.034  1036  1542 D WifiNative-p2p0: TERMINATE: returned true
07-01 09:01:20.034  1944  2326 D WfdsService: STATE : WfdsDisabledState - enter
07-01 09:01:20.034  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:20.034  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:20.034  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:20.034  1944  7427 D CtrlSupplicant: Received on exit socket, terminate
07-01 09:01:20.034  1944  7427 E CtrlSupplicant: wfds_wait_for_event: buf =, CTRL-EVENT-TERMINATING  - connection closed
07-01 09:01:20.034  1944  7427 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-01 09:01:20.034  1944  7427 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-01 09:01:20.035  1944  2327 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-01 09:01:20.035  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 09:01:20.035  1944  2326 W WfdsService: DefaultState - msg [9445378] is not handled
07-01 09:01:20.037  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.037  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:20.037  6980  6980 D UEI.SmartControl: QS start statue = true Error code = 0
07-01 09:01:20.037  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:20.037  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:20.037  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 09:01:20.038  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:20.038  1036  1542 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
,07-01 09:01:20.038  1036  1542 E WifiStateMachine:  SupplicantStoppingState CMD_SET_FREQUENCY_BAND 0 0
,07-01 09:01:20.039  1036  1542 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=289311  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 09:01:20.039  1036  1542 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=289311  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 09:01:20.041  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-01 09:01:20.041  6980  6980 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-01 09:01:20.041  6980  6980 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-01 09:01:20.041  6980  6980 I UEI.SmartControl: ### init IR Blaster...
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:20.041  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:20.041  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:20.041  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:20.042  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:20.042  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:20.043  4866  7428 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-01 09:01:20.045  6980  6980 D serial_port: Configuring serial port
07-01 09:01:20.045  6950  6950 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 09:01:20.045  6980  6980 E UEI.SmartControl: UEIBLaster setting for 616
07-01 09:01:20.045  6980  6980 I UEI.SmartControl: Setting serial record hearder size = 2
07-01 09:01:20.045  6980  6980 I UEI.SmartControl: configuring settings for MAXQ616
07-01 09:01:20.045  6980  6980 I UEI.SmartControl: Get version...
07-01 09:01:20.046  6950  6950 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-01 09:01:20.047  4866  7429 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:20.047  4866  7429 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:20.051  6950  6950 V [BNRBootReceiver]: Boot Receiver Return
,07-01 09:01:20.056  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:20.060  7257  7257 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 09:01:20.060  7257  7257 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 09:01:20.060  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:20.061  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:20.062  6980  7430 D UEI.SmartControl: serial port data available: 21
07-01 09:01:20.063  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:20.067  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:20.071  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:20.072  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:20.073  7316  7316 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 09:01:20.077  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 09:01:20.079  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:20.083  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:20.088  6980  6980 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-01 09:01:20.088  6980  6980 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-01 09:01:20.088  6980  6980 I UEI.SmartControl: QS saving settings...
,07-01 09:01:20.088  6980  6980 D UEI.SmartControl: IR Blaster version: 25672567
07-01 09:01:20.094  7374  7433 W FormManager: Network not available. Please check & try again.
07-01 09:01:20.097  7374  7434 V FormManager: Network unavailable.
07-01 09:01:20.098  7374  7434 V FormManager: Network unavailable.
07-01 09:01:20.104  6980  7430 D UEI.SmartControl: serial port data available: 4
,07-01 09:01:20.131  6980  7437 I UEI.SmartControl: Device manager: loading config....
,07-01 09:01:20.135  6980  7437 D UEI.SmartControl: ----------- loading internal config...
07-01 09:01:20.135  6980  6980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
07-01 09:01:20.138  6980  6980 E UEI.SmartControl: Services init done
07-01 09:01:20.138  6980  6980 D UEI.SmartControl: QS Service init finished
07-01 09:01:20.140  6980  6980 D UEI.SmartControl: QS Service version name: 2.1.91
07-01 09:01:20.140  6980  6980 D UEI.SmartControl: QS Service version code: 201091
,07-01 09:01:20.141  6980  6980 D UEI.SmartControl: Service requested: Control
07-01 09:01:20.141  6980  7437 E UEI.SmartControl: Loading SETTINGS...
07-01 09:01:20.144  6980  6980 D UEI.SmartControl: Internal service binding...
07-01 09:01:20.144  7316  7316 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-01 09:01:20.145  6980  7437 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-01 09:01:20.146  6980  7001 I UEI.SmartControl: ------ IControl API: 11
07-01 09:01:20.146  6980  7001 D UEI.SmartControl: File observer start...
,07-01 09:01:20.147  6980  7001 E UEI.SmartControl: IR Port is disabled: false
07-01 09:01:20.147  6980  7001 D UEI.SmartControl: Starting file observer...
07-01 09:01:20.147  6980  7001 I UEI.SmartControl: Registering callback...
07-01 09:01:20.148  6980  6995 I UEI.SmartControl: ------ IControl API: 19
07-01 09:01:20.148  6980  6995 I UEI.SmartControl: Registering Services Ready callback...
07-01 09:01:20.151  6980  7436 I UEI.SmartControl: Notify AllClients services are ready: 0
07-01 09:01:20.151  6980  7436 D UEI.SmartControl: -----service ready thread exits
07-01 09:01:20.151  7316  7331 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-01 09:01:20.153  7316  7408 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-01 09:01:20.153  7316  7408 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-01 09:01:20.154  7316  7316 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-01 09:01:20.154  7316  7316 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-01 09:01:20.154  6980  7001 I UEI.SmartControl: ------ IControl API: 8
07-01 09:01:20.155  7316  7316 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-01 09:01:20.155  7316  7316 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-01 09:01:20.155  7316  7316 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-01 09:01:20.155  7316  7316 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-01 09:01:20.156  7316  7316 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-01 09:01:20.156  7316  7316 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-01 09:01:20.157  7316  7316 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-01 09:01:20.160  7316  7316 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-01 09:01:20.160  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-01 09:01:20.161  7316  7316 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 09:01:20.161  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-01 09:01:20.161  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-01 09:01:20.162  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-01 09:01:20.162  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-01 09:01:20.163  7316  7316 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1467356480163]
07-01 09:01:20.163  7316  7316 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,07-01 09:01:20.167  1036  1616 I ActivityManager: Killing 6753:com.android.gallery3d/u0a27 (adj 15): empty #17
,07-01 09:01:20.183  7316  7439 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-01 09:01:20.246  1036  1616 I ActivityManager: Killing 6729:com.lge.email/u0a23 (adj 15): empty #18
,07-01 09:01:20.347  1036  1979 W libprocessgroup: failed to open /acct/uid_10027/pid_6753/cgroup.procs: No such file or directory
,07-01 09:01:20.357  1036  1943 W libprocessgroup: failed to open /acct/uid_10023/pid_6729/cgroup.procs: No such file or directory
07-01 09:01:20.360  7316  7316 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,07-01 09:01:20.362  7316  7316 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 09:01:20.363  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-01 09:01:20.364  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-01 09:01:20.365  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,07-01 09:01:20.365  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-01 09:01:20.366  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-01 09:01:20.381  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-01 09:01:20.451  7418  7418 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-01 09:01:20.451  7418  7418 I wpa_supplicant: monitor socket send errors count : 1
07-01 09:01:20.451  7418  7418 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-4\x00 that cannot receive messages
07-01 09:01:20.454  1036  7422 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,07-01 09:01:20.454  1036  7422 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 09:01:20.454  1036  7422 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
07-01 09:01:20.454  1036  7422 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
07-01 09:01:20.460  1036  1542 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=289732  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
07-01 09:01:20.464  1036  1542 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=289736  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,07-01 09:01:20.579  7418  7418 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 09:01:20.586  1036  7422 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,07-01 09:01:20.586  1036  7422 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
07-01 09:01:20.586  1036  7422 D WifiMonitor: Disconnecting from the supplicant, no more events
,07-01 09:01:20.587  1036  1542 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
07-01 09:01:20.689  1036  1542 D WifiOffDelayIfNotUsed: stopMonitoring
07-01 09:01:20.689  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:20.689  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:20.689  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-01 09:01:20.692  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-01 09:01:20.694  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:20.695  1036  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-01 09:01:20.695  1036  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-01 09:01:20.696  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:20.696  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:20.696  1944  1944 D WfdsService: Supplicant Connection state is changed : false
07-01 09:01:20.697  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 09:01:20.697  1944  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-01 09:01:20.697  1944  2326 D WfdsService: Set the WFDS Monitor: false
07-01 09:01:20.697  1944  2326 D WfdsMonitor: WFDS Monitor is stopped
07-01 09:01:20.699  2475  2475 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:20.700  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:20.702  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:20.708  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 09:01:20.717  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:20.725  7257  7257 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-01 09:01:20.725  7257  7257 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 09:01:20.725  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 09:01:20.735  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:20.737  7374  7446 V FormManager: Network unavailable.
07-01 09:01:20.740  7374  7445 W FormManager: Network not available. Please check & try again.
07-01 09:01:20.740  4866  7443 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-01 09:01:20.746  7374  7446 V FormManager: Network unavailable.
07-01 09:01:20.750  4866  7447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:20.750  4866  7447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:20.751  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 09:01:20.891  1036  1542 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 09:01:20.891  1036  1542 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 09:01:20.891  1036  1542 E WifiStateMachine:  InitialState CMD_SET_FREQUENCY_BAND 0 0
07-01 09:01:20.892  1036  1542 E WifiStateMachine:  DefaultState CMD_SET_FREQUENCY_BAND 0 0
,07-01 09:01:20.939  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:20.944  1036  1098 D Tethering: MasterInitialState.processMessage what=3
07-01 09:01:20.946  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:20.955  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:20.956  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:20.960  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-01 09:01:20.964  6582  7247 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-01 09:01:20.966  1036  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:20.966  1036  1925 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-01 09:01:20.967  6031  6031 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-01 09:01:20.973  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.975  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:20.976  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:20.976  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:20.976  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:20.976  1036  1098 D BluetoothManagerService: Message: 1
07-01 09:01:20.976  1036  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-01 09:01:20.980  1036  1098 D Tethering: MasterInitialState.processMessage what=3
07-01 09:01:20.983  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:20.983  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:20.985  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:20.990  6031  6031 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-01 09:01:20.993  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.995  1036  1098 D BluetoothManagerService: Message: 20
07-01 09:01:20.995  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1da9767f:true
07-01 09:01:20.997  7357  7357 D BluetoothAdapterState: make
,07-01 09:01:20.999  2190  2190 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:21.003  7357  7357 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-01 09:01:21.003  7357  7357 I bluedroid-qcom: init
07-01 09:01:21.004  7357  7357 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-01 09:01:21.005  7357  7357 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-01 09:01:21.005  7357  7357 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-01 09:01:21.005  7357  7357 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-01 09:01:21.005  7357  7357 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-01 09:01:21.005  7357  7357 I bluedroid-qcom: get_profile_interface socket
07-01 09:01:21.005  7357  7457 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-01 09:01:21.005  7357  7357 I bluedroid-qcom: get_profile_interface map_client
07-01 09:01:21.006  7357  7454 I BluetoothAdapterState: Entering OffState
07-01 09:01:21.000  7458  7458 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:21.008  7357  7457 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-01 09:01:21.000  7458  7458 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:21.019  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-01 09:01:21.019  7458  7458 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-01 09:01:21.019  7458  7458 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,07-01 09:01:21.021  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-01 09:01:21.024  7458  7458 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-01 09:01:21.024  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-01 09:01:21.059  1036  1906 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7459 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-01 09:01:21.063  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,07-01 09:01:21.063  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 09:01:21.065  7357  7457 D BluetoothAdapterProperties: Name is: G3
07-01 09:01:21.066  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-01 09:01:21.066  1036  1098 D BluetoothManagerService: Message: 40
07-01 09:01:21.066  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-01 09:01:21.067  7357  7373 I bluedroid-qcom: config_hci_snoop_log
07-01 09:01:21.068  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-01 09:01:21.068  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-01 09:01:21.074  7357  7454 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-01 09:01:21.074  7357  7454 D BluetoothAdapterProperties: Setting state to 11
07-01 09:01:21.074  7357  7454 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 09:01:21.075  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:21.075  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-01 09:01:21.075  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,07-01 09:01:21.075  7357  7454 I LGBluetoothServiceJni: classInitNative: succeeds
07-01 09:01:21.078  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:21.078  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.081  7238  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-01 09:01:21.084  7357  7454 D BluetoothBondStateMachine: make
07-01 09:01:21.086  7357  7454 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.086  7357  7454 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-01 09:01:21.086  7357  7454 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.086  7357  7357 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 09:01:21.087  7357  7454 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-01 09:01:21.087  7357  7475 I BluetoothBondStateMachine: StableState(): Entering Off State
07-01 09:01:21.087  7357  7454 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-01 09:01:21.087  7357  7357 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.088  7357  7357 V BluetoothPbapReceiver: ***********state = 11
,07-01 09:01:21.205  1036  1925 I art     : Explicit concurrent mark sweep GC freed 101390(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.591ms total 116.588ms
,07-01 09:01:21.209  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:21.218  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:21.231  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
,07-01 09:01:21.235  7238  7238 D BluetoothPermissionRequest: onReceive
07-01 09:01:21.236  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:21.236  7357  7357 D HeadsetService: Received start request. Starting profile...
07-01 09:01:21.237  7357  7357 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 09:01:21.237  7357  7357 D LGBluetoothHfpAdapter: Version 1.6
07-01 09:01:21.237  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 09:01:21.241  7357  7357 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 09:01:21.241  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:21.242  7357  7357 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 09:01:21.242  7357  7357 D HeadsetStateMachine: make
,07-01 09:01:21.251  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:21.254  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:21.258  7357  7454 E BluetoothAdapterService: File transfer profiles supported!!
,07-01 09:01:21.279  7357  7357 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:21.279  7357  7357 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 09:01:21.281  7357  7454 V LGMDMManager: Create singleton instance
,07-01 09:01:21.284  7357  7357 D HeadsetStateMachine: max_hf_connections = 1
07-01 09:01:21.284  7357  7357 I bluedroid-qcom: get_profile_interface handsfree
07-01 09:01:21.286  7357  7357 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-01 09:01:21.286   314  1389 V AudioPolicyService: registerClient() client 0xb558a8a0, uid 1002
07-01 09:01:21.287   314   314 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-01 09:01:21.287   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 09:01:21.287   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 09:01:21.287  7357  7357 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-01 09:01:21.287   314  1388 V AudioFlinger: registerClient() client 0xb1788160, pid 7357
,07-01 09:01:21.287   314  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:21.287   314  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:21.288  7459  7459 I AppUp4:AppBoxCP: onCreate
07-01 09:01:21.288  1036  1906 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:21.288  1606  2102 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:21.288  1036  1906 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:21.288  1606  2102 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:21.288  1853  2668 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:21.288  1853  2668 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:21.288  3403  3422 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:21.288  3403  3422 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:21.288  7357  7372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:21.289  7459  7459 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-01 09:01:21.289   314  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:21.289   314  1383 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:21.289  1853  2665 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:21.289  1853  2665 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:21.289  1036  1943 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:21.289  1036  1943 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:21.289  1606  1627 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:21.289  1606  1627 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:21.289  3403  3423 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:21.289  3403  3423 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:21.290  7357  7372 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-01 09:01:21.290  7357  7372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:21.290  7357  7372 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-01 09:01:21.290  7357  7357 V ToneGenerator: Create Track: 0xb4928a80
07-01 09:01:21.290  7357  7357 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-01 09:01:21.290  7357  7357 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-01 09:01:21.290   314  2144 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 09:01:21.290   314  2144 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-01 09:01:21.290   314  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 09:01:21.290   314  2144 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 09:01:21.290   314  1389 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 09:01:21.290   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 09:01:21.290   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-01 09:01:21.290   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 09:01:21.290   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 09:01:21.290  7357  7357 V AudioSystem: getLatency() output 2, latency 50
07-01 09:01:21.290  7357  7357 V AudioSystem: getFrameCount() output 2, frameCount 960
07-01 09:01:21.290  7357  7357 V AudioTrack: createTrack_l() output 2 afLatency 50
07-01 09:01:21.291   314  1388 V AudioFlinger: [MABL_AudioFlinger] Playback,Thread::setMABLEnable(), enable = 0 
07-01 09:01:21.291   314  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 09:01:21.291   314  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 09:01:21.291   314  1388 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 09:01:21.291   314  1388 V AudioFlinger: createTrack() lSessionId: 22
07-01 09:01:21.291  7357  7357 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-01 09:01:21.292   314  1388 V AudioFlinger: acquiring 22 from 7357, for 7357
07-01 09:01:21.292   314  1388 V AudioFlinger:  added new entry for 22
07-01 09:01:21.292  7357  7357 V ToneGenerator: ToneGenerator INIT OK, time: 290576
07-01 09:01:21.292  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.293  7357  7478 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-01 09:01:21.293  7357  7478 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 09:01:21.293  7357  7478 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 09:01:21.293  7357  7478 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-01 09:01:21.294   314  2146 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7357
07-01 09:01:21.294  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.294   314  2146 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-01 09:01:21.294   314  2146 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-01 09:01:21.294   314  2146 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-01 09:01:21.294   314  2146 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 09:01:21.294   314  2146 V voice   : voice_set_parameters: exit with code(0)
07-01 09:01:21.294   314  2146 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-01 09:01:21.294   314  2146 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-01 09:01:21.294   314  2146 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 09:01:21.294   314  2146 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-01 09:01:21.294   314  2146 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 09:01:21.294   314  2146 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 09:01:21.294  7357  7478 V ToneGenerator: ToneGenerator destructor
07-01 09:01:21.294  7357  7478 V ToneGenerator: stopTone
07-01 09:01:21.294  7357  7478 V ToneGenerator: Delete Track: 0xb4928a80
07-01 09:01:21.295  7357  7357 D A2dpService: Received start request. Starting profile...
07-01 09:01:21.296  7357  7357 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-01 09:01:21.297  7357  7478 V AudioTrack: ~AudioTrack, releasing session id from 7357 on behalf of 7357
07-01 09:01:21.297  7357  7454 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-01 09:01:21.297   314  2144 V AudioFlinger: releasing 22 from 7357 for 7357
07-01 09:01:21.297   314  2144 V AudioFlinger:  decremented refcount to 0
07-01 09:01:21.297   314  2144 V AudioFlinger: purging stale effects
07-01 09:01:21.297   314  2144 V AudioPolicyService: AudioCommandThread() adding release output 2
07-01 09:01:21.297   314  2144 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-01 09:01:21.297   314  1111 V AudioPolicyService: AudioCommandThread() waking up
07-01 09:01:21.297   314  1111 V AudioPolicyService: AudioCommandThread() processing release output 2
07-01 09:01:21.297   314  1111 V AudioPolicyManager: releaseOutput() 2
07-01 09:01:21.297   314  1111 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 09:01:21.297   314  2144 V AudioFlinger: PlaybackThread::Track destructor
07-01 09:01:21.297   314  2144 V AudioFlinger: removeClient_l() pid 7357, calling pid 314
07-01 09:01:21.298  7357  7357 V Avrcp   : make
07-01 09:01:21.298  7357  7357 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-01 09:01:21.298  7357  7357 I bluedroid-qcom: get_profile_interface avrcp
07-01 09:01:21.298  7459  7459 I AppUp4:DB:  setFingerPrint start
07-01 09:01:21.299  7459  7459 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-01 09:01:21.299  1036  1877 W Process : Unable to open /proc/7479/status
07-01 09:01:21.307  7459  7459 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-01 09:01:21.307  7459  7459 I AppUp4:DB:  SDK version = 21
07-01 09:01:21.307  7459  7459 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-01 09:01:21.308  7459  7459 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-01 09:01:21.308  7357  7357 V AudioManager: registerRemoteController: size of Media player list: 0
07-01 09:01:21.309  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 09:01:21.309  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:21.310  7357  7357 E AudioManager: No RCC entry present to update
07-01 09:01:21.310  7357  7357 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-01 09:01:21.311  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 09:01:21.311  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-01 09:01:21.313  7357  7357 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-01 09:01:21.314  7459  7459 I AppUp4:CustModeStarterReceiver: onReceive
07-01 09:01:21.314  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-01 09:01:21.314  7357  7357 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-01 09:01:21.318  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-01 09:01:21.338  7459  7459 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:21.338  7459  7459 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:21.342  7459  7459 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@253cbaab
07-01 09:01:21.342  7459  7459 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 09:01:21.342  7459  7459 D AppUp4:CustFacade: isPhone : true
07-01 09:01:21.358  7459  7459 D AppUp4:CustModeStarterReceiver: begin check event
07-01 09:01:21.359  7459  7459 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-01 09:01:21.359  7459  7459 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-01 09:01:21.359  7459  7481 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-01 09:01:21.359  7459  7481 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-01 09:01:21.359  7459  7481 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,07-01 09:01:21.361  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:21.362  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:21.362  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:21.364  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:21.367  4866  7484 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 09:01:21.374  4866  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:21.375  4866  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:21.401  1036  1052 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7486 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-01 09:01:21.425  1036  1925 V SIM_STK : Menu title from STK is T-Mobile
,07-01 09:01:21.425  1036  1925 V SIM_STK : Menu title from STK is T-Mobile
,07-01 09:01:21.459  7486  7486 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 09:01:21.459  7486  7486 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 09:01:21.460  7486  7486 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 09:01:21.460  7486  7486 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 09:01:21.511  1036  2015 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-01 09:01:21.518  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-01 09:01:21.521  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-01 09:01:21.521  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 09:01:21.522  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-01 09:01:21.522  7357  7357 I BluetoothA2dpServiceJni: classInitNative
07-01 09:01:21.523  7357  7357 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-01 09:01:21.523  7357  7357 D A2dpStateMachine: make
07-01 09:01:21.524  7357  7357 I bluedroid-qcom: get_profile_interface a2dp
,07-01 09:01:21.524  7357  7505 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 09:01:21.526  7357  7357 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-01 09:01:21.526  7357  7357 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-01 09:01:21.526  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.528  7357  7504 D A2dpStateMachine: Enter Disconnected: -2
07-01 09:01:21.528  7357  7357 I BluetoothHidServiceJni: classInitNative: succeeds
07-01 09:01:21.529  7357  7357 D HidService: Received start request. Starting profile...
07-01 09:01:21.529  7357  7357 I bluedroid-qcom: get_profile_interface hidhost
07-01 09:01:21.529  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.530  7486  7486 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-01 09:01:21.530  7357  7357 I BluetoothHealthServiceJni: classInitNative: succeeds
07-01 09:01:21.531  7357  7357 D HealthService: Received start request. Starting profile...
07-01 09:01:21.532  7357  7357 I bluedroid-qcom: get_profile_interface health
07-01 09:01:21.533  7357  7357 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-01 09:01:21.533  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.533  7357  7357 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-01 09:01:21.535  7357  7357 D PanService: Received start request. Starting profile...
07-01 09:01:21.535  7357  7357 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 09:01:21.535  7357  7357 I bluedroid-qcom: get_profile_interface pan
,07-01 09:01:21.540  7357  7357 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-01 09:01:21.540  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.541  7357  7357 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-01 09:01:21.545  7357  7357 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 09:01:21.545  7357  7357 D BtGatt.GattService: Received start request. Starting profile...
07-01 09:01:21.545  7357  7357 D BtGatt.GattService: start()
07-01 09:01:21.545  7357  7357 I bluedroid-qcom: get_profile_interface gatt
07-01 09:01:21.546  7357  7357 D BtGatt.AdvertiseManager: advertise manager created
07-01 09:01:21.548  7486  7486 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-01 09:01:21.555  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.559  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
,07-01 09:01:21.560  7357  7357 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-01 09:01:21.563  7357  7357 V BluetoothMapService: BluetoothMapBinder()
07-01 09:01:21.564  7357  7357 D BluetoothMapService: Received start request. Starting profile...
07-01 09:01:21.564  7357  7357 D BluetoothMapService: start()
,07-01 09:01:21.570  7357  7357 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-01 09:01:21.570  7357  7357 D BluetoothMapEmailAppObserver: createReceiver()
07-01 09:01:21.572  7357  7357 D BluetoothMapEmailAppObserver: initObservers()
07-01 09:01:21.573  7357  7357 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-01 09:01:21.573  7486  7486 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-01 09:01:21.583  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:21.583  7357  7357 D HeadsetStateMachine: Proxy object connected
07-01 09:01:21.584  7357  7357 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-01 09:01:21.584  7357  7357 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-01 09:01:21.585  7357  7478 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 09:01:21.585  7357  7478 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-01 09:01:21.586  7357  7478 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-01 09:01:21.588  7357  7357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:21.591  7357  7357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-01 09:01:21.593  7357  7357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:21.594  7357  7357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.597  7357  7357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:21.599  7357  7357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:21.600  7357  7357 V PanService: [BTUI] SIM Extra State :ABSENT
07-01 09:01:21.601  7486  7486 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:21.601  7486  7486 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 09:01:21.602  7357  7357 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-01 09:01:21.602  7357  7357 V BluetoothMapService: Handler(): got msg=1
07-01 09:01:21.602  7357  7454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-01 09:01:21.602  7357  7357 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:21.603  7357  7454 I bluedroid-qcom: enable
07-01 09:01:21.603  7357  7357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:21.603  7357  7357 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:21.603  7357  7357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.603  7357  7357 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-01 09:01:21.603  7357  7454 I bt_hci_bdroid: init
07-01 09:01:21.604  7357  7454 I bt_vendor: bt-vendor : init
07-01 09:01:21.604  7357  7454 I bt_vendor: bt-vendor : get_bt_soc_type
07-01 09:01:21.604  7357  7454 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-01 09:01:21.604  7357  7454 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-01 09:01:21.604  7357  7454 D bt_userial_mct: userial_init
07-01 09:01:21.604  7357  7454 D bt_hci_bdroid: set_power 1
07-01 09:01:21.604  7357  7454 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-01 09:01:21.604  7357  7513 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-01 09:01:21.604  7357  7454 I bt_vendor: Starting hciattach daemon
07-01 09:01:21.604  7357  7513 I bt-btu  : btu_task pending for preload complete event
07-01 09:01:21.604  7357  7454 I bt_vendor: try to set true
,07-01 09:01:21.600  7516  7516 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:21.600  7516  7516 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 09:01:21.634  7519  7519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-01 09:01:21.675  7486  7486 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-01 09:01:21.679  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
07-01 09:01:21.688  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-01 09:01:21.696  3403  3403 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 09:01:21.696  3403  3403 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:21.696  3403  3403 I LgeMiscReceiver: networkInfo.isConnected() = false
07-01 09:01:21.707  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-01 09:01:21.712  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-01 09:01:21.721  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-01 09:01:21.730  7536  7536 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-01 09:01:21.733  1036  1579 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7537 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
07-01 09:01:21.739  7374  7533 V FormManager: Network unavailable.
,07-01 09:01:21.743  7546  7546 I libmdmdetect: ESOC framework not supported
07-01 09:01:21.743  7546  7546 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-01 09:01:21.743  7374  7532 W FormManager: Network not available. Please check & try again.
07-01 09:01:21.746  7374  7533 V FormManager: Network unavailable.
07-01 09:01:21.750  7546  7546 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-01 09:01:21.750  7546  7546 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-01 09:01:21.750  7546  7546 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-01 09:01:21.750  7546  7546 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-01 09:01:21.750  7546  7546 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-01 09:01:21.750  7546  7546 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-01 09:01:21.750  7546  7546 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-01 09:01:21.752  7486  7486 I HubEmail: JNI_OnLoad()
07-01 09:01:21.752  7486  7486 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 09:01:21.752  7486  7486 I HubEmail: registerNatives()
07-01 09:01:21.752  7486  7486 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 09:01:21.752  7486  7486 I HubEmail: registerNativeMethods()
07-01 09:01:21.752  7486  7486 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 09:01:21.753  7486  7486 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-01 09:01:21.755  1036  1979 I ActivityManager: Killing 6812:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,07-01 09:01:21.785  7546  7555 E QC-QMI  : qmi_client [7546] 14: failed to locate client data
,07-01 09:01:21.786   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-01 09:01:21.786   472   472 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-01 09:01:21.867  1036  1616 W libprocessgroup: failed to open /acct/uid_10061/pid_6812/cgroup.procs: No such file or directory
07-01 09:01:21.876  7486  7557 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 09:01:21.887  7558  7558 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
07-01 09:01:21.898  7559  7559 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-01 09:01:21.935  7537  7537 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 09:01:21.935  7537  7537 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:21.938  7537  7537 D PhoneMonitor: Register our PhoneStateListener
07-01 09:01:21.951  7537  7537 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 09:01:21.953  7537  7537 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-01 09:01:21.956  7357  7454 I bt_vendor: bluetooth satus is on
07-01 09:01:21.956  7357  7454 D bt_hci_bdroid: preload
07-01 09:01:21.956  7357  7515 D bt_userial_mct: userial_open(port:0)
,07-01 09:01:21.956  7357  7515 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-01 09:01:21.959  7357  7515 I bt_vendor: Done intiailizing UART
07-01 09:01:21.960  7357  7515 I bt_vendor: Done intiailizing UART
07-01 09:01:21.960  7357  7515 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-01 09:01:21.960  7357  7515 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-01 09:01:21.961  7357  7562 D bt_userial_mct: Entering userial_read_thread()
07-01 09:01:21.961  7357  7513 I bt-btu  : btu_task received preload complete event
07-01 09:01:21.961  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-01 09:01:21.961  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-01 09:01:21.963  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_HCI
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_AVDT
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_AVRC
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_A2D
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_BNEP
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_BTM
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_GAP
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_PAN
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_SDP
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_GATT
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_SMP
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-01 09:01:21.965  7357  7513 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-01 09:01:21.974  7537  7537 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-01 09:01:21.975  7537  7537 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-01 09:01:21.975  7537  7537 D TelephonyAutoProfiling: [parse] Load xml
07-01 09:01:21.978  7537  7537 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-01 09:01:21.978  7537  7537 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-01 09:01:21.978  7537  7537 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-01 09:01:21.986  7537  7537 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,07-01 09:01:22.006  1036  1906 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7564 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 09:01:22.008  7357  7513 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-01 09:01:22.008  7357  7513 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016a061 
07-01 09:01:22.008  7357  7513 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016a061 
07-01 09:01:22.009  1036  1906 I ActivityManager: Killing 6870:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-01 09:01:22.021  7357  7457 E bt-btif : Calling BTA_HhEnable
07-01 09:01:22.022  7357  7457 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-01 09:01:22.022  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-01 09:01:22.022  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-01 09:01:22.022  7357  7457 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-01 09:01:22.022  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-01 09:01:22.022  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-01 09:01:22.022  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,07-01 09:01:22.031  7357  7513 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 09:01:22.031  7357  7513 W bt-smp  : Plain text(LSB ~ MSB) = 3c ce 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 09:01:22.031  7357  7513 W bt-smp  : Encrypted text(LSB ~ MSB) = c1 4b dd c9 9b eb ec 9d a6 a2 1a 99 bd 99 51 d9 
07-01 09:01:22.031  7357  7513 W bt-btm  : Stopping oneshot timer
07-01 09:01:22.097  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-01 09:01:22.101  1036  1905 W libprocessgroup: failed to open /acct/uid_10080/pid_6870/cgroup.procs: No such file or directory
07-01 09:01:22.102  7357  7457 D BluetoothAdapterProperties: Name is: G3
07-01 09:01:22.102  1036  1978 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@338e2ff8 mBinding = false
07-01 09:01:22.115  7357  7457 D BluetoothAdapterProperties: Scan Mode:20
07-01 09:01:22.115  7357  7457 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:22.116  7357  7457 D bt_hci_bdroid: postload
07-01 09:01:22.116  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 09:01:22.117  7357  7515 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 09:01:22.117  7357  7513 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-01 09:01:22.117  7357  7457 D bte_conf: Device ID record 1 : primary
07-01 09:01:22.117  7357  7457 D bte_conf:   vendorId            = 00c4
07-01 09:01:22.117  7357  7457 D bte_conf:   vendorIdSource      = 0001
07-01 09:01:22.117  7357  7457 D bte_conf:   product             = 13a1
07-01 09:01:22.117  7357  7457 D bte_conf:   version             = 1000
07-01 09:01:22.117  7357  7457 D bte_conf:   clientExecutableURL = 
07-01 09:01:22.117  7357  7457 D bte_conf:   serviceDescription  = 
07-01 09:01:22.117  7357  7457 D bte_conf:   documentationURL    = 
07-01 09:01:22.117  7357  7457 D bte_conf: bte_load_did_conf no section named DID2.
07-01 09:01:22.118  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 09:01:22.120  7357  7457 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 09:01:22.121  7357  7454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 09:01:22.121  7357  7454 D BluetoothAdapterProperties: ScanMode =  20
07-01 09:01:22.121  7357  7454 D BluetoothAdapterProperties: State =  11
07-01 09:01:22.121  7357  7454 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-01 09:01:22.121  7357  7454 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-01 09:01:22.121  7357  7454 D BluetoothAdapterProperties: Setting state to 12
07-01 09:01:22.121  7357  7454 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-01 09:01:22.121  7357  7515 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 09:01:22.121  7357  7515 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 09:01:22.122  7357  7457 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:22.124  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:22.125  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:22.125  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-01 09:01:22.125  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-01 09:01:22.125  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:22.125  7357  7454 I BluetoothAdapterState: Entering On State
07-01 09:01:22.126  7357  7515 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 09:01:22.110  7582  7582 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:22.127  7357  7454 D LGBluetoothServiceAdapter: [BTUI] OnState
07-01 09:01:22.127  7357  7454 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-01 09:01:22.127  7357  7454 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-01 09:01:22.128  7357  7454 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-01 09:01:22.110  7582  7582 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:22.129  7238  7299 D BluetoothMap: onBluetoothStateChange: up=true
07-01 09:01:22.130  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:22.130  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:22.130  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:22.131  7357  7562 E bt_mct  : hci lib postload completed
07-01 09:01:22.133  1036  1036 D BluetoothHeadset: Proxy object connected
07-01 09:01:22.135  1853  2668 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:22.136  7238  7238 D BluetoothMap: Proxy object connected
07-01 09:01:22.136  7238  7238 D MapProfile: Bluetooth service connected
07-01 09:01:22.136  7238  7238 D BluetoothMap: getConnectedDevices()
07-01 09:01:22.136  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:22.138  1853  1853 D BluetoothHeadset: Proxy object connected
07-01 09:01:22.140  7238  7299 D BluetoothPbap: onBluetoothStateChange: up=true
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:22.142  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:22.143  7238  7255 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-01 09:01:22.145  7357  7372 V BluetoothMapService: getConnectedDevices()
07-01 09:01:22.146  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 09:01:22.147  1853  2453 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:22.148  1036  1036 D BluetoothA2dp: Proxy object connected
,07-01 09:01:22.150  7238  7238 D BluetoothInputDevice: Proxy object connected
07-01 09:01:22.150  7238  7238 D HidProfile: Bluetooth service connected
07-01 09:01:22.151  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:22.152  1853  1853 D BluetoothHeadset: Proxy object connected
07-01 09:01:22.152  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:22.155  1853  1853 D BluetoothHeadset: Proxy object connected
07-01 09:01:22.155  7238  7255 D BluetoothPan: onBluetoothStateChange on: true
07-01 09:01:22.155  7238  7255 D BluetoothPan: onBluetoothStateChange call bindService
07-01 09:01:22.157  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-01 09:01:22.158  1036  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-01 09:01:22.158  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-01 09:01:22.161  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:22.162  1944  2127 D LGBluetoothAPIService: Message: 1
07-01 09:01:22.162  1944  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-01 09:01:22.162  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:22.167  7238  7238 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 09:01:22.167  7238  7238 D PanProfile: Bluetooth service connected
07-01 09:01:22.168  1036  1098 D BluetoothManagerService: Message: 2
07-01 09:01:22.169  7357  7457 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:22.170  7357  7457 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-01 09:01:22.171  1944  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-01 09:01:22.172  7357  7357 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.172  7357  7357 D BluetoothMapService: STATE_ON
07-01 09:01:22.173  7357  7357 D LGBluetoothAPIServer: [BTUI] onCreate()
07-01 09:01:22.173  7357  7357 D LGBluetoothAPIServer: [BTUI] onBind()
07-01 09:01:22.173  1036  1098 D BluetoothManagerService: Sending off request.
07-01 09:01:22.173  7357  7357 V BluetoothMapService: Handler(): got msg=1
,07-01 09:01:22.174  7357  7357 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-01 09:01:22.175  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-01 09:01:22.175  1944  2127 D LGBluetoothAPIService: Message: 100
07-01 09:01:22.175  1944  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-01 09:01:22.176  7357  7454 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-01 09:01:22.177  7238  7238 D LocalBluetoothProfileManager: Adding local A2DP profile
07-01 09:01:22.178  7357  7583 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-01 09:01:22.178  7357  7454 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-01 09:01:22.179  7357  7454 D BluetoothAdapterProperties: Setting state to 13
07-01 09:01:22.179  7357  7454 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 09:01:22.179  7357  7454 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 09:01:22.179  7357  7454 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 09:01:22.181  7357  7457 D BluetoothAdapterProperties: Scan Mode:20
07-01 09:01:22.181  7357  7454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 09:01:22.181  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-01 09:01:22.181  7357  7513 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-01 09:01:22.181  7357  7454 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:22.183  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:22.183  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:22.185  1036  1098 D BluetoothManagerService: Message: 40
07-01 09:01:22.185  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-01 09:01:22.185  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:22.185  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-01 09:01:22.185  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-01 09:01:22.187  1036  1098 D BluetoothManagerService: Message: 30
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:22.188  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:22.188  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:22.189  7591  7591 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-01 09:01:22.189  7357  7357 V BluetoothPbapService: Pbap Service onCreate
07-01 09:01:22.189  7357  7357 V BluetoothPbapService: Starting PBAP service
07-01 09:01:22.189  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.190  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-01 09:01:22.190  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-01 09:01:22.190  7357  7513 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 09:01:22.191  7238  7238 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-01 09:01:22.191  7357  7590 D BluetoothMapMasInstance: MAS initSocket()
07-01 09:01:22.191  7357  7590 D BluetoothMapMasInstance:   masId = 00
07-01 09:01:22.191  7357  7590 D BluetoothMapMasInstance:   msgTypes = 0e
07-01 09:01:22.191  7357  7590 D BluetoothMapMasInstance:   masName = SMS/MMS
07-01 09:01:22.191  7357  7590 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-01 09:01:22.193  1036  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:22.194  1036  1098 D BluetoothManagerService: Message: 30
07-01 09:01:22.195  7357  7357 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 09:01:22.196  7357  7590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:22.195  7357  7357 V BluetoothPbapService: Pbap Service onBind
07-01 09:01:22.196  7357  7590 E BluetoothServiceJni: Socket listen failed: 2
07-01 09:01:22.196  7357  7590 E BluetoothAdapterService(407209121): Failed to create socket channel
07-01 09:01:22.197  7357  7590 E BluetoothMapMasInstance: Error create RfcommServerSocket java.io.IOException: Error: -1
07-01 09:01:22.197  723,8  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-01 09:01:22.198  7357  7357 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.198  7357  7357 V BluetoothPbapService: state: 12
07-01 09:01:22.198  7357  7357 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.199  7357  7357 D BluetoothMapService: STATE_TURNING_OFF
07-01 09:01:22.199  7357  7357 V BluetoothMapService: Handler(): got msg=4
07-01 09:01:22.199  7357  7357 D BluetoothMapService: MAP Service closeService in
07-01 09:01:22.199  7357  7357 D BluetoothMapMasInstance: MAP Service shutdown
07-01 09:01:22.199  7357  7590 W BluetoothMapMasInstance: initServerSocket failed as BT is (being) turned off
07-01 09:01:22.199  7357  7590 E BluetoothMapMasInstance: Error to create listening socket after 10 try
07-01 09:01:22.200  7357  7357 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 09:01:22.200  7357  7357 V BluetoothMapService: MAP Service closeService out
07-01 09:01:22.201  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-01 09:01:22.203  7238  7238 D BluetoothA2dp: Proxy object connected
07-01 09:01:22.204  7238  7238 D A2dpProfile: Bluetooth service connected
07-01 09:01:22.205  7238  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-01 09:01:22.205  7238  7238 D BluetoothHeadset: Proxy object connected
07-01 09:01:22.206  7357  7357 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 09:01:22.206  7357  7357 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.206  7357  7357 V BluetoothPbapReceiver: ***********state = 12
07-01 09:01:22.208  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:22.208  7238  7238 D HeadsetProfile: Bluetooth service connected
07-01 09:01:22.208  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:22.210  2190  2190 D c       : Getting all permits...
07-01 09:01:22.210  7238  7238 D BluetoothPbap: Proxy object connected
07-01 09:01:22.211  7238  7238 D PbapServerProfile: Bluetooth service connected
07-01 09:01:22.210  2190  2190 D a       : Opening database...
07-01 09:01:22.215  7238  7238 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:22.217  2190  2190 D a       : Opening database auth.proximity.permit_store...
,07-01 09:01:22.218  2190  2190 D a       : Closing database...
07-01 09:01:22.224  7238  7238 D BluetoothPermissionRequest: onReceive
07-01 09:01:22.226  7238  7238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 09:01:22.228  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-01 09:01:22.230  7357  7357 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-01 09:01:22.231  7357  7357 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-01 09:01:22.234  7357  7357 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-01 09:01:22.244  7357  7357 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 09:01:22.244  7357  7357 V BtOppService: onCreate
,07-01 09:01:22.247  7357  7357 V BluetoothOppNotification: send message
07-01 09:01:22.252  7357  7357 D BluetoothOppPreference: Dumping Names:  
07-01 09:01:22.252  7357  7357 D BluetoothOppPreference: {}
07-01 09:01:22.252  7357  7357 D BluetoothOppPreference: Dumping Channels:  
07-01 09:01:22.252  7357  7357 D BluetoothOppPreference: {}
07-01 09:01:22.252  7357  7357 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 09:01:22.252  7357  7357 V BtOppService: onStartCommand
07-01 09:01:22.253  7357  7357 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 09:01:22.254  7357  7357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.254  7357  7357 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 09:01:22.256  7357  7357 V BluetoothOppNotification: previous thread is not finished yet
07-01 09:01:22.265  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:22.265  7357  7357 V BluetoothFtpService: Ftp Service onCreate
07-01 09:01:22.265  7357  7357 I BluetoothFtpService: Ftp Service onCreate
07-01 09:01:22.265  7357  7357 V BluetoothFtpService: Ftp Service onStartCommand
,07-01 09:01:22.265  7357  7357 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.266  7357  7357 V BluetoothFtpService: Starting Listening on sockets
07-01 09:01:22.266  7357  7357 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:22.266  7357  7357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:22.266  7357  7357 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:22.266  7357  7357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.266  7357  7357 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-01 09:01:22.266  7357  7357 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 09:01:22.267  7357  7357 V BluetoothFtpService: Handler(): got msg=1
07-01 09:01:22.269  7357  7357 V BluetoothFtpService: Ftp Service closeService
07-01 09:01:22.270  7357  7596 V BtOppService: Deleted complete outbound shares, number =  0
07-01 09:01:22.271  7357  7596 V BtOppService: Deleted complete inbound failed shares, number = 0
07-01 09:01:22.271  7357  7596 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-01 09:01:22.272  7357  7357 V BluetoothFtpService: successfully stopped ftp service
07-01 09:01:22.272  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 09:01:22.272  7357  7596 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8570ff3 on behalf of 
07-01 09:01:22.275  7238  7238 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:22.281  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:22.281  7357  7357 V BluetoothSapService: Sap Service onCreate
,07-01 09:01:22.283  7357  7357 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.283  7357  7357 V BluetoothSapService: state: 12
07-01 09:01:22.283  7357  7357 V BluetoothSapService: Starting SAP server process
07-01 09:01:22.284  7357  7357 V BtOppService: ContentObserver received notification
07-01 09:01:22.284  7357  7357 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 09:01:22.284  7357  7357 V BtOppService: ContentObserver received notification
07-01 09:01:22.284  7357  7357 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 09:01:22.270  7600  7600 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:22.270  7600  7600 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 09:01:22.284  7357  7357 V BluetoothFtpService: Ftp Service onDestroy
07-01 09:01:22.284  7357  7357 V BluetoothFtpService: Ftp Service closeService
07-01 09:01:22.291  7600  7600 V BT_SAP  : Event pipe created
07-01 09:01:22.291  7600  7600 V BT_SAP  : create_server_socket qcom.sap.server
07-01 09:01:22.291  7600  7600 V BT_SAP  : created socket fd 6
07-01 09:01:22.318  1036  1051 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7601 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-01 09:01:22.318  7357  7357 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 09:01:22.318  7357  7357 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.318  7357  7357 V BluetoothPbapReceiver: ***********state = 13
07-01 09:01:22.319  7357  7357 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-01 09:01:22.319  1036  1051 I ActivityManager: Killing 6894:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-01 09:01:22.405  1036  1924 W libprocessgroup: failed to open /acct/uid_10097/pid_6894/cgroup.procs: No such file or directory
,07-01 09:01:22.408  7357  7357 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.408  7357  7357 V BluetoothPbapService: state: 13
07-01 09:01:22.408  7357  7357 V BluetoothPbapService: Pbap Service closeService in
07-01 09:01:22.411  7357  7357 V BluetoothPbapService: successfully stopped pbap service
07-01 09:01:22.411  7357  7357 V BluetoothPbapService: Pbap Service closeService out
07-01 09:01:22.411  7238  7238 D BluetoothPbap: Proxy object disconnected
07-01 09:01:22.411  7238  7238 D PbapServerProfile: Bluetooth service disconnected
07-01 09:01:22.412  7357  7357 V BluetoothPbapService: Pbap Service onDestroy
07-01 09:01:22.412  7357  7357 V BluetoothPbapService: Pbap Service closeService in
07-01 09:01:22.412  7357  7357 V BluetoothPbapService: Pbap Service closeService out
07-01 09:01:22.412  7357  7357 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 09:01:22.416  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:22.430  7238  7238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-01 09:01:22.435  7238  7238 D BluetoothPermissionRequest: onReceive
07-01 09:01:22.435  7238  7238 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 09:01:22.440  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 09:01:22.444  7357  7357 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-01 09:01:22.444  7357  7357 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-01 09:01:22.445  7357  7357 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,07-01 09:01:22.450  7357  7357 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.451  7357  7357 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 09:01:22.455  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:22.456  7357  7357 V BluetoothFtpService: Ftp Service onCreate
07-01 09:01:22.456  7357  7357 I BluetoothFtpService: Ftp Service onCreate
07-01 09:01:22.456  7357  7357 V BluetoothFtpService: Ftp Service onStartCommand
,07-01 09:01:22.456  7357  7357 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.456  7357  7357 V BluetoothFtpService: Ftp Service closeService
07-01 09:01:22.500  1036  1579 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7618 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 09:01:22.502  7357  7357 V BluetoothFtpService: successfully stopped ftp service
07-01 09:01:22.503  7357  7357 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:22.503  7357  7357 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:22.503  7357  7357 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:22.503  7357  7357 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.503  7357  7357 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-01 09:01:22.503  7357  7357 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 09:01:22.504  1036  1579 I ActivityManager: Killing 6923:com.lge.eula/1000 (adj 15): empty #17
,07-01 09:01:22.585  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-01 09:01:22.585  7125  7202 I jxcore-log: 
,07-01 09:01:22.588  7357  7357 V BluetoothFtpService: Ftp Service onDestroy
,07-01 09:01:22.589  7357  7357 V BluetoothFtpService: Ftp Service closeService
07-01 09:01:22.589  1036  1906 W libprocessgroup: failed to open /acct/uid_1000/pid_6923/cgroup.procs: No such file or directory
,07-01 09:01:22.608  7357  7357 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.608  7357  7357 V BluetoothSapService: state: 13
07-01 09:01:22.609  7357  7357 V BluetoothSapService: Stopping SAP server process
07-01 09:01:22.614  7357  7357 V BluetoothSapService: Sap Service closeSapService in
07-01 09:01:22.614  7357  7357 V BluetoothSapService: Close listen Socket : 
,07-01 09:01:22.614  7357  7357 V BluetoothSapService: Close rfcomm Socket : 
07-01 09:01:22.615  7357  7357 V BluetoothSapService: Close sapd  Socket : 
07-01 09:01:22.616  7357  7357 V BluetoothSapService: Sap Service closeSapService out
07-01 09:01:22.617  7357  7357 V BluetoothSapService: Sap Service onDestroy
07-01 09:01:22.617  7357  7357 V BluetoothSapService: Sap Service closeSapService in
07-01 09:01:22.617  7357  7357 V BluetoothSapService: Close listen Socket : 
07-01 09:01:22.617  7357  7357 V BluetoothSapService: Close rfcomm Socket : 
07-01 09:01:22.617  7357  7357 V BluetoothSapService: Close sapd  Socket : 
07-01 09:01:22.623  7357  7357 V BluetoothSapService: Sap Service closeSapService out
07-01 09:01:22.634  7618  7618 I art     : Almond Protected OAT
,07-01 09:01:22.669  7618  7618 D WeatherApplication: removeAccount
,07-01 09:01:22.671  7618  7618 D WeatherApplication: Account.length = 0
07-01 09:01:22.672  7618  7618 E WeatherApplication: OPERATOR:OPEN
07-01 09:01:22.675  7618  7618 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:1:22
07-01 09:01:22.680  7618  7618 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-01 09:01:22.680  7618  7618 D Weather.Utils: 2 : All the weather widget is gone.
07-01 09:01:22.681  7618  7618 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 09:01:22.683  7618  7618 D WeatherAncestor: connectivity changed - connection : true
07-01 09:01:22.684  7618  7618 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,07-01 09:01:22.694  7618  7618 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-01 09:01:22.694  7618  7618 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-01 09:01:22.695  7618  7618 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
07-01 09:01:22.728  7618  7618 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,07-01 09:01:22.728  7618  7618 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:1:22
07-01 09:01:22.803  1036  1905 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7636 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 09:01:22.804  1036  1905 I ActivityManager: Killing 6773:com.android.vending/u0a44 (adj 15): empty #17
,07-01 09:01:22.852  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:22.852  1036  1541 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 09:01:22.928  1036  1978 W libprocessgroup: failed to open /acct/uid_10044/pid_6773/cgroup.procs: No such file or directory
,07-01 09:01:22.939  1036  1542 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
07-01 09:01:22.940  1036  1542 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-01 09:01:23.048   278   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 09:01:23.048   278   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 09:01:23.048   278   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 09:01:23.049  7636  7654 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-01 09:01:23.051   278   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 09:01:23.051   278   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 09:01:23.051   278   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 09:01:23.052  7636  7654 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 09:01:23.061   278   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 09:01:23.061   278   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 09:01:23.061   278   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 09:01:23.061  7636  7656 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-01 09:01:23.062   278   443 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,07-01 09:01:23.062   278   443 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 09:01:23.062   278   443 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 09:01:23.062  7636  7656 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 09:01:23.095  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-01 09:01:23.095  7125  7202 I jxcore-log: 
,07-01 09:01:23.126  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-01 09:01:23.126  7125  7202 I jxcore-log: 
,07-01 09:01:23.131  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:23.131  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:23.132  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-01 09:01:23.132  7125  7202 I jxcore-log: 
07-01 09:01:23.150  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-01 09:01:23.150  7125  7202 I jxcore-log: 
,07-01 09:01:23.154  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-01 09:01:23.154  7125  7202 I jxcore-log: 
07-01 09:01:23.193  7357  7513 W bt-btif : ag scb idx 1 not allocated
,07-01 09:01:23.193  7357  7513 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:23.193  7357  7457 D bt_hci_bdroid: cleanup
07-01 09:01:23.193  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 09:01:23.194  7357  7515 I bt_lpm  : LPM is already off!!!
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 09:01:23.194  7357  7513 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:23.194  7357  7513 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 09:01:23.194  7357  7562 I bt_userial_mct: exiting userial_read_thread
07-01 09:01:23.194  7357  7562 D bt_userial_mct: Leaving userial_evt_read_thread()
07-01 09:01:23.194  7357  7457 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-01 09:01:23.195  7357  7515 I bt_vendor: hw_epilog_process
07-01 09:01:23.195  7357  7457 D bt_hci_bdroid: cleanup Finalizing cleanup
07-01 09:01:23.195  7357  7457 D bt_userial_mct: userial_close
07-01 09:01:23.195  7357  7457 E bt_userial_mct: pthread_join() FAILED result:3
07-01 09:01:23.195  7357  7457 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-01 09:01:23.257  7357  7357 V BluetoothOppNotification: previous thread is not finished yet
,07-01 09:01:23.311  7636  7636 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-01 09:01:23.332  7636  7636 I LibraryLoader: Loading: webviewchromium
,07-01 09:01:23.344  7636  7636 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 2615-2628)
07-01 09:01:23.344  7636  7636 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 09:01:23.351  7636  7636 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {338967e4}
,07-01 09:01:23.352  7636  7636 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 09:01:23.353  7636  7636 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 09:01:23.355  7357  7457 D bt_hci_bdroid: set_power 0
07-01 09:01:23.355  7357  7457 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-01 09:01:23.355  7357  7457 I bt_vendor: bluetooth satus is on
07-01 09:01:23.355  7357  7457 I bt_vendor: bt-vendor : resetting BT status
07-01 09:01:23.355  7357  7457 I bt_vendor: Starting hciattach daemon
07-01 09:01:23.355  7357  7457 I bt_vendor: try to set false
07-01 09:01:23.356  7357  7457 I bt_vendor: Starting hciattach daemon
07-01 09:01:23.356  7357  7457 I bt_vendor: try to set false
07-01 09:01:23.356  7357  7457 I bt_vendor: cleanup
07-01 09:01:23.357  7357  7513 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-01 09:01:23.357  7357  7457 I GKI_LINUX: GKI_exit_task 0 done
07-01 09:01:23.357  7357  7457 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-01 09:01:23.358  7357  7454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 09:01:23.359  7357  7357 D HeadsetService: Received stop request...Stopping profile...
07-01 09:01:23.360  7357  7357 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 09:01:23.360  7357  7357 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 09:01:23.360  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.361  7357  7478 D HeadsetStateMachine: Exit Disconnected: -1
07-01 09:01:23.362  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:23.362  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 09:01:23.362  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:23.362  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:23.363  7357  7357 D A2dpService: Received stop request...Stopping profile...
07-01 09:01:23.363  7357  7504 D A2dpStateMachine: Exit Disconnected: -1
07-01 09:01:23.364  7357  7357 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-01 09:01:23.364  7357  7454 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 09:01:23.364  1853  1853 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:23.365  7357  7357 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-01 09:01:23.365  7357  7357 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 09:01:23.365  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.366  7238  7238 D BluetoothHeadset: Proxy object disconnected
07-01 09:01:23.366  7238  7238 D HeadsetProfile: Bluetooth service disconnected
07-01 09:01:23.366  7238  7238 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:23.366  7238  7238 D A2dpProfile: Bluetooth service disconnected
07-01 09:01:23.366  7357  7357 D HidService: Received stop request...Stopping profile...
07-01 09:01:23.367  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.367  7238  7238 D BluetoothInputDevice: Proxy object disconnected
07-01 09:01:23.367  7238  7238 D HidProfile: Bluetooth service disconnected
,07-01 09:01:23.368  7357  7357 D HeadsetStateMachine: Unbinding service...
07-01 09:01:23.369  7357  7357 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 09:01:23.369  7357  7357 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 09:01:23.369  7357  7357 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,07-01 09:01:23.369  7357  7357 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 09:01:23.369  7357  7357 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 09:01:23.369  7357  7357 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 09:01:23.369  7357  7357 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 09:01:23.369  7357  7357 D HealthService: Received stop request...Stopping profile...
07-01 09:01:23.370  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.371  7357  7357 D PanService: Received stop request...Stopping profile...
07-01 09:01:23.371  7636  7636 I BrowserStartupController: Initializing chromium process, renderers=0
07-01 09:01:23.372  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.374  7636  7636 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 09:01:23.374  7357  7357 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 09:01:23.375  7357  7357 D BtGatt.GattService: Received stop request...Stopping profile...
07-01 09:01:23.375  7357  7357 D BtGatt.GattService: stop()
07-01 09:01:23.375  7357  7357 D BtGatt.AdvertiseManager: advertise clients cleared
07-01 09:01:23.376  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:23.376  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 09:01:23.376  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.377  7357  7357 D BluetoothMapService: Received stop request...Stopping profile...
07-01 09:01:23.377  7357  7357 D BluetoothMapService: stop()
07-01 09:01:23.377  7357  7357 D BluetoothMapEmailAppObserver: deinitObservers()
07-01 09:01:23.377  7357  7357 D BluetoothMapEmailAppObserver: removeReceiver()
07-01 09:01:23.378  7357  7357 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:23.378  7238  7238 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 09:01:23.378  7238  7238 D PanProfile: Bluetooth service disconnected
07-01 09:01:23.379  7357  7357 I BluetoothA2dpServiceJni: cleanupNative
07-01 09:01:23.379  7357  7505 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 09:01:23.379  7238  7238 D BluetoothMap: Proxy object disconnected
07-01 09:01:23.379  7357  7357 I GKI_LINUX: GKI_exit_task 2 done
07-01 09:01:23.379  7238  7238 D MapProfile: Bluetooth service disconnected
07-01 09:01:23.379  7357  7357 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 09:01:23.379  7357  7357 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 09:01:23.379  7357  7357 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 09:01:23.380  7357  7357 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 09:01:23.380  7357  7357 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 09:01:23.380  7357  7357 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 09:01:23.380  7357  7357 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 09:01:23.380  7357  7357 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-01 09:01:23.381  7357  7357 V BluetoothMapService: Handler(): got msg=4
07-01 09:01:23.381  7357  7357 D BluetoothMapService: MAP Service closeService in
07-01 09:01:23.381  7357  7357 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 09:01:23.381  7357  7357 V BluetoothMapService: MAP Service closeService out
07-01 09:01:23.381  7357  7357 D BluetoothMapService: cleanup()
07-01 09:01:23.381  7357  7357 D BluetoothMapService: MAP Service closeService in
07-01 09:01:23.381  7357  7357 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 09:01:23.381  7357  7357 V BluetoothMapService: MAP Service closeService out
07-01 09:01:23.381  7357  7454 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-01 09:01:23.381  7357  7454 D BluetoothAdapterProperties: Setting state to 10
07-01 09:01:23.381  7357  7454 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 09:01:23.381  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:23.381  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-01 09:01:23.381  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
07-01 09:01:23.381  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:23.382  7357  7454 I BluetoothAdapterState: Entering OffState
07-01 09:01:23.382  7238  7255 D BluetoothMap: onBluetoothStateChange: up=false
07-01 09:01:23.382  7238  7254 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:23.383  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:23.383  7238  7255 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 09:01:23.384  7238  7254 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 09:01:23.384  7238  7299 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-01 09:01:23.385  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 09:01:23.385  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 09:01:23.386  1853  2453 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-01 09:01:23.386  7238  7255 D BluetoothPan: onBluetoothStateChange on: false
07-01 09:01:23.387  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-01 09:01:23.387  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-01 09:01:23.388  1036  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-01 09:01:23.388  1036  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-01 09:01:23.388  1036  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@338e2ff8 mBinding = false
07-01 09:01:23.389  1036  1098 D BluetoothManagerService: Sending unbind request.
07-01 09:01:23.390  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-01 09:01:23.391  7636  7636 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-01 09:01:23.391  7357  7457 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-01 09:01:23.392  7357  7357 I GKI_LINUX: GKI_exit_task 1 done
07-01 09:01:23.392  7357  7357 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-01 09:01:23.392  7636  7636 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-01 09:01:23.392  7357  7357 I BluetoothServiceJni: cleanupNative: return from cleanup
07-01 09:01:23.392  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:23.392  7357  7357 I art     : --- WEIRD: removing null entry 249
07-01 09:01:23.392  7357  7357 W art     : JNI WARNING: DeleteGlobalRef(0x2003e6) failed to find entry
07-01 09:01:23.392  7357  7357 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-01 09:01:23.392  7636  7636 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-01 09:01:23.393  7357  7357 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-01 09:01:23.394  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:23.394  7238  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-01 09:01:23.394  7238  7238 D LGBluetoothEventManager: [BTUI] clear device connection state
07-01 09:01:23.394  1944  2127 D LGBluetoothAPIService: Message: 2
07-01 09:01:23.394  1944  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2d2e7f58 mBinding = false
07-01 09:01:23.394  1944  2127 D LGBluetoothAPIService: Sending unbind request.
07-01 09:01:23.396  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 09:01:23.398   314  2146 V AudioPolicyService: registerClient() client 0xb558ad00, uid 10093
07-01 09:01:23.398  1606  1606 D BluetoothAdapter: 140392864: getState() :  mService = null. Returning STATE_OFF
07-01 09:01:23.398  1606  1606 D BluetoothAdapter: 140392864: getState() :  mService = null. Returning STATE_OFF
07-01 09:01:23.399  7357  7357 I art     : System.exit called, status: 0
07-01 09:01:23.399  7357  7357 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-01 09:01:23.402  7636  7679 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-01 09:01:23.406  7238  7238 D DockEventReceiver: finishStartingService: stopping service
07-01 09:01:23.417   314  1389 V AudioFlinger: 7357 died, releasing its sessions
07-01 09:01:23.417   314  1389 V AudioFlinger:  pid 1853 @ 0
07-01 09:01:23.417   314  1389 V AudioFlinger:  pid 3403 @ 1
07-01 09:01:23.417   314  1389 V AudioFlinger:  pid 3403 @ 2
07-01 09:01:23.418  7238  7238 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,07-01 09:01:23.419  7636  7636 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 09:01:23.419  7636  7636 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 09:01:23.419  7636  7636 I Adreno-EGL: Build Date: 12/12/14 금
07-01 09:01:23.419  7636  7636 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 09:01:23.419  7636  7636 I Adreno-EGL: Remote Branch: 
07-01 09:01:23.419  7636  7636 I Adreno-EGL: Local Patches: 
07-01 09:01:23.419  7636  7636 I Adreno-EGL: Reconstruct Branch: 
07-01 09:01:23.526  1036  1925 I ActivityManager: Process com.android.bluetooth (pid 7357) has died
07-01 09:01:23.527  1036  1925 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
07-01 09:01:23.527  1036  1925 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.opp.BluetoothOppService in 14000ms
,07-01 09:01:23.538  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:23.557  7238  7238 D BluetoothPermissionRequest: onReceive
,07-01 09:01:23.558  7238  7238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 09:01:23.558  7238  7238 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-01 09:01:23.560  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 09:01:23.618  1036  1997 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7694 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-01 09:01:23.619  7636  7636 I NSApplication: Starting up...
07-01 09:01:23.643   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 25.240ms
,07-01 09:01:23.663   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 18.910ms
07-01 09:01:23.681   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 16.774ms
,07-01 09:01:23.726  1036  1943 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7711 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-01 09:01:23.726  1036  1943 I ActivityManager: Killing 7062:com.lge.clock/u0a10 (adj 15): empty #17
,07-01 09:01:23.795  1036  1616 W libprocessgroup: failed to open /acct/uid_10010/pid_7062/cgroup.procs: No such file or directory
07-01 09:01:23.816  7694  7694 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-01 09:01:23.817  7694  7694 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 09:01:23.817  7694  7694 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-01 09:01:23.818  7694  7694 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-01 09:01:23.825  7711  7711 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 09:01:23.836  7694  7694 D BluetoothAdapterApp: Loading JNI Library
,07-01 09:01:23.868  7694  7694 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@10961169 Instance Count = 1
,07-01 09:01:23.872  7694  7694 D BluetoothAdapterApp: onCreate
07-01 09:01:23.892  7694  7694 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-01 09:01:23.892  7694  7694 D ProfileConfigQcom: Adding HeadsetService
07-01 09:01:23.893  7694  7694 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-01 09:01:23.893  7694  7694 D ProfileConfigQcom: Adding A2dpService
07-01 09:01:23.893  7694  7694 D ProfileConfigQcom: [BTUI] HidService is supported
07-01 09:01:23.893  7694  7694 D ProfileConfigQcom: Adding HidService
,07-01 09:01:23.893  7694  7694 D ProfileConfigQcom: [BTUI] HealthService is supported
07-01 09:01:23.893  7694  7694 D ProfileConfigQcom: Adding HealthService
07-01 09:01:23.893  7694  7694 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-01 09:01:23.894  7694  7694 D ProfileConfigQcom: [BTUI] PanService is supported
07-01 09:01:23.894  7694  7694 D ProfileConfigQcom: Adding PanService
07-01 09:01:23.894  7694  7694 D ProfileConfigQcom: [BTUI] GattService is supported
07-01 09:01:23.894  7694  7694 D ProfileConfigQcom: Adding GattService
07-01 09:01:23.894  7694  7694 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-01 09:01:23.895  7694  7694 D ProfileConfigQcom: Adding BluetoothMapService
07-01 09:01:23.895  7694  7694 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-01 09:01:23.896  7694  7694 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-01 09:01:23.902  7694  7694 V LGMDMManagerInternal: Create singleton instance
07-01 09:01:23.909  7238  7238 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 09:01:23.953  7694  7694 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:23.956  7694  7694 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-01 09:01:23.956  7694  7694 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:23.957  7694  7694 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:23.957  7694  7694 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:23.957  7694  7694 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-01 09:01:23.959  7334  7334 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-01 09:01:23.960  1036  1052 I ActivityManager: Killing 6950:com.lge.bnr/1000 (adj 15): empty #17
07-01 09:01:24.096  1036  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_6950/cgroup.procs: No such file or directory
,07-01 09:01:24.131  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:24.131  7125  7199 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:24.132  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:24.132  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:24.132  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2335bcb1 removed from the list
07-01 09:01:24.132  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:24.132  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@226af517 added. We now have 2 listener(s)
07-01 09:01:24.132  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:24.133  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:24.133  7125  7199 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:24.133  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:24.133  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:24.133  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@226af517 removed from the list
07-01 09:01:24.133  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:24.133  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25018d04 added. We now have 2 listener(s)
07-01 09:01:24.133  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:24.136  1036  1616 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:24.136  1036  1616 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,07-01 09:01:24.139  1036  1098 D BluetoothManagerService: Message: 2
07-01 09:01:24.143  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-01 09:01:24.147  6582  7247 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-01 09:01:24.147  7125  7199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:24.149  1036  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:24.149  1036  1925 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-01 09:01:24.162  1036  1098 D BluetoothManagerService: Message: 1
07-01 09:01:24.162  1036  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-01 09:01:24.163  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-01 09:01:24.163  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-01 09:01:24.163  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 09:01:24.169  2190  2190 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:24.179  1036  1098 D BluetoothManagerService: Message: 20
07-01 09:01:24.180  1036  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@255d24ef:true
07-01 09:01:24.180  7694  7694 D BluetoothAdapterState: make
,07-01 09:01:24.183  7694  7694 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-01 09:01:24.183  7694  7694 I bluedroid-qcom: init
07-01 09:01:24.183  7694  7739 I BluetoothAdapterState: Entering OffState
07-01 09:01:24.183  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 09:01:24.183  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:24.183  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 09:01:24.183  7459  7459 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-01 09:01:24.184  7694  7694 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-01 09:01:24.184  7694  7694 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-01 09:01:24.184  7694  7694 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-01 09:01:24.184  7694  7694 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-01 09:01:24.185  7694  7694 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-01 09:01:24.185  7694  7694 I bluedroid-qcom: get_profile_interface socket
07-01 09:01:24.185  7694  7694 I bluedroid-qcom: get_profile_interface map_client
07-01 09:01:24.180  7743  7743 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:24.180  7743  7743 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:24.187  7694  7742 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-01 09:01:24.190  7743  7743 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-01 09:01:24.190  7743  7743 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-01 09:01:24.190  7743  7743 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-01 09:01:24.190  7459  7459 I AppUp4:CustModeStarterReceiver: onReceive
07-01 09:01:24.191  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-01 09:01:24.191  1036  1098 D BluetoothManagerService: Message: 40
07-01 09:01:24.191  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-01 09:01:24.192  7694  7709 I bluedroid-qcom: config_hci_snoop_log
07-01 09:01:24.192  7743  7743 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,07-01 09:01:24.195  7694  7742 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-01 09:01:24.196  1036  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-01 09:01:24.196  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
07-01 09:01:24.196  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 09:01:24.197  7743  7743 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-01 09:01:24.197  7743  7743 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-01 09:01:24.197  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 09:01:24.197  7694  7742 D BluetoothAdapterProperties: Name is: G3
07-01 09:01:24.198  7459  7459 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@253cbaab
07-01 09:01:24.198  7459  7459 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 09:01:24.198  7459  7459 D AppUp4:CustFacade: isPhone : true
07-01 09:01:24.198  7459  7459 D AppUp4:CustModeStarterReceiver: begin check event
07-01 09:01:24.199  7459  7459 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-01 09:01:24.201  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:24.201  7694  7739 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-01 09:01:24.201  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:24.201  7694  7739 D BluetoothAdapterProperties: Setting state to 11
07-01 09:01:24.201  7694  7739 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 09:01:24.202  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:24.202  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-01 09:01:24.202  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-01 09:01:24.203  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.203  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:24.203  7694  7739 I LGBluetoothServiceJni: classInitNative: succeeds
07-01 09:01:24.204  7238  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-01 09:01:24.204  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 09:01:24.209  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 09:01:24.210  7694  7694 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 09:01:24.210  7694  7694 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.210  7694  7694 V BluetoothPbapReceiver: ***********state = 11
07-01 09:01:24.211  7694  7739 D BluetoothBondStateMachine: make
07-01 09:01:24.213  7694  7739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.213  7694  7739 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-01 09:01:24.213  7694  7739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.213  7694  7739 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-01 09:01:24.214  7694  7739 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-01 09:01:24.214  7694  7746 I BluetoothBondStateMachine: StableState(): Entering Off State
07-01 09:01:24.217  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:24.324  1036  1924 I art     : Explicit concurrent mark sweep GC freed 22765(1193KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.336ms total 114.696ms
,07-01 09:01:24.328  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:24.329  4866  7749 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 09:01:24.332  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:24.332  4866  7750 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:24.332  4866  7750 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:24.336  7694  7694 D HeadsetService: Received start request. Starting profile...
07-01 09:01:24.337  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:24.337  7694  7694 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 09:01:24.338  7694  7694 D LGBluetoothHfpAdapter: Version 1.6
07-01 09:01:24.343  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:24.345  7694  7694 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 09:01:24.347  7694  7694 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 09:01:24.347  7694  7694 D HeadsetStateMachine: make
07-01 09:01:24.350  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
,07-01 09:01:24.354  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:24.359  7486  7486 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-01 09:01:24.360  7694  7739 E BluetoothAdapterService: File transfer profiles supported!!
07-01 09:01:24.362  7238  7238 D BluetoothPermissionRequest: onReceive
07-01 09:01:24.365  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-01 09:01:24.375  7694  7739 V LGMDMManager: Create singleton instance
07-01 09:01:24.376  7486  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:24.376  7694  7739 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-01 09:01:24.384  7694  7694 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 09:01:24.384  7694  7694 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 09:01:24.390  7694  7694 D HeadsetStateMachine: max_hf_connections = 1
07-01 09:01:24.390  7694  7694 I bluedroid-qcom: get_profile_interface handsfree
07-01 09:01:24.392  7694  7694 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-01 09:01:24.392   314  2144 V AudioPolicyService: registerClient() client 0xb0403d20, uid 1002
07-01 09:01:24.392   314  1389 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-01 09:01:24.392   314  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 09:01:24.393   314  1389 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 09:01:24.393  7694  7694 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-01 09:01:24.393   314  1388 V AudioFlinger: registerClient() client 0xb1433208, pid 7694
07-01 09:01:24.393   314  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:24.393   314  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:24.393  1606  3470 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:24.394  1606  3470 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:24.394  1036  1925 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:24.394  1036  1925 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:24.394  7694  7710 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:24.394   314  1383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:24.394   314  1383 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:24.394  1853  2665 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:24.394  1853  2665 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:24.394  3403  3423 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 09:01:24.394  3403  3423 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 09:01:24.394  1036  1978 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:24.394  1036  1978 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:24.394  3403  3423 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:24.394  3403  3423 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:24.394  1606  2101 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:24.394  1606  2101 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:24.394  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:24.394  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 09:01:24.394  7694  7710 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-01 09:01:24.394  7694  7710 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 09:01:24.394  7694  7710 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-01 09:01:24.394  7694  7694 V ToneGenerator: Create Track: 0xb4928a80
07-01 09:01:24.394  7694  7694 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-01 09:01:24.394  7694  7694 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-01 09:01:24.394   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 09:01:24.394   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-01 09:01:24.394   314   314 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 09:01:24.394   314   314 V AudioPolicyManagerEx: getOutput() returns output, 2
07-01 09:01:24.395   314  2144 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 09:01:24.395   314  1389 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 09:01:24.395   314  1389 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-01 09:01:24.395   314  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 09:01:24.395   314  1389 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 09:01:24.395  7694  7694 V AudioSystem: getLatency() output 2, latency 50
07-01 09:01:24.395  7694  7694 V AudioSystem: getFrameCount() output 2, frameCount 960
07-01 09:01:24.395  7694  7694 V AudioTrack: createTrack_l() output 2 afLatency 50
07-01 09:01:24.395   314  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 09:01:24.395   314  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 09:01:24.395   314  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 09:01:24.395   314  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 09:01:24.395   314  2146 V AudioFlinger: createTrack() lSessionId: 23
07-01 09:01:24.396  7694  7694 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-01 09:01:24.396   314  2146 V AudioFlinger: acquiring 23 from 7694, for 7694
07-01 09:01:24.396   314  2146 V AudioFlinger:  added new entry for 23
07-01 09:01:24.397  7694  7694 V ToneGenerator: ToneGenerator INIT OK, time: 293681
07-01 09:01:24.397  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.398  7694  7752 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-01 09:01:24.398  7694  7752 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 09:01:24.398  7694  7752 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 09:01:24.398  7694  7752 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-01 09:01:24.398   314   314 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7694
,07-01 09:01:24.398   314   314 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-01 09:01:24.398   314   314 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-01 09:01:24.398   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-01 09:01:24.398   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 09:01:24.398   314   314 V voice   : voice_set_parameters: exit with code(0)
07-01 09:01:24.398   314   314 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-01 09:01:24.398   314   314 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-01 09:01:24.399   314   314 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 09:01:24.399   314   314 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-01 09:01:24.399   314   314 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 09:01:24.399   314   314 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 09:01:24.399  7694  7752 V ToneGenerator: ToneGenerator destructor
07-01 09:01:24.399  7694  7752 V ToneGenerator: stopTone
07-01 09:01:24.399  7694  7752 V ToneGenerator: Delete Track: 0xb4928a80
07-01 09:01:24.399  7694  7752 V AudioTrack: ~AudioTrack, releasing session id from 7694 on behalf of 7694
07-01 09:01:24.399   314  1388 V AudioPolicyService: AudioCommandThread() adding release output 2
07-01 09:01:24.399   314  1388 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-01 09:01:24.399   314  1389 V AudioFlinger: releasing 23 from 7694 for 7694
07-01 09:01:24.399   314  1389 V AudioFlinger:  decremented refcount to 0
07-01 09:01:24.399   314  1389 V AudioFlinger: purging stale effects
07-01 09:01:24.399   314  1388 V AudioFlinger: PlaybackThread::Track destructor
07-01 09:01:24.399   314  1388 V AudioFlinger: removeClient_l() pid 7694, calling pid 314
07-01 09:01:24.399   314  1111 V AudioPolicyService: AudioCommandThread() waking up
07-01 09:01:24.399   314  1111 V AudioPolicyService: AudioCommandThread() processing release output 2
07-01 09:01:24.399   314  1111 V AudioPolicyManager: releaseOutput() 2
07-01 09:01:24.399   314  1111 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 09:01:24.401  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.401  3403  3403 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 09:01:24.401  3403  3403 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:24.402  3403  3403 I LgeMiscReceiver: networkInfo.isConnected() = false
07-01 09:01:24.403  7694  7694 D A2dpService: Received start request. Starting profile...
07-01 09:01:24.403  7694  7694 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-01 09:01:24.405  7694  7694 V Avrcp   : make
07-01 09:01:24.405  7537  7537 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 09:01:24.405  7537  7537 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-01 09:01:24.405  7694  7694 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-01 09:01:24.405  7694  7694 I bluedroid-qcom: get_profile_interface avrcp
07-01 09:01:24.406  1036  1997 W Process : Unable to open /proc/7756/status
07-01 09:01:24.414  7694  7694 V AudioManager: registerRemoteController: size of Media player list: 0
07-01 09:01:24.414  7374  7757 W FormManager: Network not available. Please check & try again.
,07-01 09:01:24.417  7694  7694 E AudioManager: No RCC entry present to update
07-01 09:01:24.418  7694  7694 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-01 09:01:24.420  7374  7758 V FormManager: Network unavailable.
07-01 09:01:24.422  7694  7694 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-01 09:01:24.423  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-01 09:01:24.423  7694  7694 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-01 09:01:24.424  7374  7758 V FormManager: Network unavailable.
07-01 09:01:24.426  7618  7618 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:1:24
,07-01 09:01:24.427  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-01 09:01:24.460  7618  7618 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-01 09:01:24.460  7618  7618 D Weather.Utils: 2 : All the weather widget is gone.
,07-01 09:01:24.462  7618  7618 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 09:01:24.463  7618  7618 D WeatherAncestor: connectivity changed - connection : true
07-01 09:01:24.463  7618  7618 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@184584a1
07-01 09:01:24.463  7618  7618 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-01 09:01:24.463  7618  7618 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-01 09:01:24.464  7618  7618 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-01 09:01:24.464  7618  7618 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 09:01:24.464  7618  7618 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:1:24
07-01 09:01:24.504  1036  1925 V SIM_STK : Menu title from STK is T-Mobile
07-01 09:01:24.504  1036  1925 V SIM_STK : Menu title from STK is T-Mobile
,07-01 09:01:24.555  1036  1979 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-01 09:01:24.562  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-01 09:01:24.566  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-01 09:01:24.566  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-01 09:01:24.566  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-01 09:01:24.566  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-01 09:01:24.567  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 09:01:24.567  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-01 09:01:24.567  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-01 09:01:24.567  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-01 09:01:24.567  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 09:01:24.567  7694  7694 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-01 09:01:24.567  7694  7694 I BluetoothA2dpServiceJni: classInitNative
07-01 09:01:24.567  7694  7694 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-01 09:01:24.567  7694  7694 D A2dpStateMachine: make
07-01 09:01:24.571  7694  7694 I bluedroid-qcom: get_profile_interface a2dp
07-01 09:01:24.571  7694  7762 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 09:01:24.574  7694  7694 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-01 09:01:24.574  7694  7694 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-01 09:01:24.574  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.575  7694  7694 I BluetoothHidServiceJni: classInitNative: succeeds
07-01 09:01:24.576  7694  7761 D A2dpStateMachine: Enter Disconnected: -2
,07-01 09:01:24.576  7694  7694 D HidService: Received start request. Starting profile...
,07-01 09:01:24.576  7694  7694 I bluedroid-qcom: get_profile_interface hidhost
07-01 09:01:24.577  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.577  7694  7694 I BluetoothHealthServiceJni: classInitNative: succeeds
07-01 09:01:24.578  7694  7694 D HealthService: Received start request. Starting profile...
07-01 09:01:24.581  7694  7694 I bluedroid-qcom: get_profile_interface health
07-01 09:01:24.582  7694  7694 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-01 09:01:24.582  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.582  7694  7694 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-01 09:01:24.583  7694  7694 D PanService: Received start request. Starting profile...
07-01 09:01:24.584  7694  7694 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 09:01:24.584  7694  7694 I bluedroid-qcom: get_profile_interface pan
07-01 09:01:24.588  7694  7694 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-01 09:01:24.588  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
,07-01 09:01:24.589  7694  7694 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,07-01 09:01:24.592  7694  7694 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 09:01:24.593  7694  7694 D BtGatt.GattService: Received start request. Starting profile...
07-01 09:01:24.593  7694  7694 D BtGatt.GattService: start()
07-01 09:01:24.593  7694  7694 I bluedroid-qcom: get_profile_interface gatt
07-01 09:01:24.593  7694  7694 D BtGatt.AdvertiseManager: advertise manager created
07-01 09:01:24.602  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.603  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.603  7694  7694 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-01 09:01:24.604  7694  7694 V BluetoothMapService: BluetoothMapBinder()
07-01 09:01:24.604  7694  7694 D BluetoothMapService: Received start request. Starting profile...
07-01 09:01:24.604  7694  7694 D BluetoothMapService: start()
,07-01 09:01:24.608  7694  7694 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-01 09:01:24.608  7694  7694 D BluetoothMapEmailAppObserver: createReceiver()
,07-01 09:01:24.611  7694  7694 D BluetoothMapEmailAppObserver: initObservers()
07-01 09:01:24.611  7694  7694 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-01 09:01:24.629  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:24.630  7694  7694 D HeadsetStateMachine: Proxy object connected
07-01 09:01:24.631  7694  7694 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-01 09:01:24.631  7694  7694 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-01 09:01:24.632  7694  7752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 09:01:24.633  7694  7752 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-01 09:01:24.633  7694  7752 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,07-01 09:01:24.637  7694  7694 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:24.643  7694  7694 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:24.645  7694  7694 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-01 09:01:24.647  7694  7694 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:24.648  7694  7694 V PanService: [BTUI] SIM Extra State :ABSENT
,07-01 09:01:24.649  7694  7694 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 09:01:24.652  7694  7694 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-01 09:01:24.652  7694  7694 V BluetoothMapService: Handler(): got msg=1
07-01 09:01:24.653  7694  7739 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-01 09:01:24.653  7694  7739 I bluedroid-qcom: enable
07-01 09:01:24.653  7694  7739 I bt_hci_bdroid: init
07-01 09:01:24.654  7694  7694 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.654  7694  7739 I bt_vendor: bt-vendor : init
07-01 09:01:24.654  7694  7739 I bt_vendor: bt-vendor : get_bt_soc_type
07-01 09:01:24.654  7694  7739 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-01 09:01:24.654  7694  7739 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-01 09:01:24.655  7694  7739 D bt_userial_mct: userial_init
07-01 09:01:24.655  7694  7769 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-01 09:01:24.655  7694  7769 I bt-btu  : btu_task pending for preload complete event
07-01 09:01:24.655  7694  7739 D bt_hci_bdroid: set_power 1
07-01 09:01:24.655  7694  7739 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-01 09:01:24.655  7694  7739 I bt_vendor: Starting hciattach daemon
07-01 09:01:24.655  7694  7739 I bt_vendor: try to set true
07-01 09:01:24.655  7694  7694 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:24.655  7694  7694 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:24.655  7694  7694 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:24.655  7694  7694 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.655  7694  7694 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-01 09:01:24.650  7772  7772 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:24.650  7772  7772 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 09:01:24.673  7773  7773 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-01 09:01:24.756  7779  7779 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-01 09:01:24.773  7780  7780 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-01 09:01:24.802  7782  7782 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-01 09:01:24.814  7783  7783 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-01 09:01:24.829  7784  7784 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-01 09:01:24.854  7785  7785 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-01 09:01:24.892  7790  7790 I libmdmdetect: ESOC framework not supported
07-01 09:01:24.893  7790  7790 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-01 09:01:24.902  7790  7790 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-01 09:01:24.902  7790  7790 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-01 09:01:24.903  7790  7790 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-01 09:01:24.903  7790  7790 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-01 09:01:24.903  7790  7790 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-01 09:01:24.903  7790  7790 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-01 09:01:24.903  7790  7790 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-01 09:01:24.938  7790  7791 E QC-QMI  : qmi_client [7790] 15: failed to locate client data
07-01 09:01:24.938   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-01 09:01:24.938   472   472 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-01 09:01:25.033  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:25.033  1036  1541 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 09:01:25.036  1036  1542 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-01 09:01:25.036  1036  1542 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
07-01 09:01:25.047  7792  7792 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-01 09:01:25.058  7793  7793 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-01 09:01:25.109  7694  7739 I bt_vendor: bluetooth satus is on
07-01 09:01:25.109  7694  7739 D bt_hci_bdroid: preload
,07-01 09:01:25.109  7694  7771 D bt_userial_mct: userial_open(port:0)
07-01 09:01:25.109  7694  7771 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-01 09:01:25.112  7694  7771 I bt_vendor: Done intiailizing UART
,07-01 09:01:25.115  7694  7771 I bt_vendor: Done intiailizing UART
07-01 09:01:25.115  7694  7771 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-01 09:01:25.116  7694  7771 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-01 09:01:25.117  7694  7795 D bt_userial_mct: Entering userial_read_thread()
07-01 09:01:25.117  7694  7769 I bt-btu  : btu_task received preload complete event
07-01 09:01:25.118  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-01 09:01:25.118  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-01 09:01:25.124  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_HCI
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_AVDT
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_AVRC
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_A2D
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_BNEP
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_BTM
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_GAP
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_PAN
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_SDP
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_GATT
07-01 09:01:25.129  7694  7769 I         : BTE_InitTraceLevels -- TRC_SMP
07-01 09:01:25.130  7694  7769 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-01 09:01:25.130  7694  7769 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-01 09:01:25.133  6980  7438 D UEI.SmartControl: Internal timer expired: 2
07-01 09:01:25.133  6980  7438 D UEI.SmartControl: unbind internal service
07-01 09:01:25.163  6980  7435 D serial_port: close(fd = 24)
,07-01 09:01:25.169  6980  7435 I UEI.SmartControl: Serial port is closed.
,07-01 09:01:25.210  7694  7769 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-01 09:01:25.210  7694  7769 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016a061 
,07-01 09:01:25.211  7694  7769 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016a061 
07-01 09:01:25.252  7694  7742 E bt-btif : Calling BTA_HhEnable
07-01 09:01:25.253  7694  7742 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-01 09:01:25.253  7694  7742 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-01 09:01:25.253  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-01 09:01:25.253  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-01 09:01:25.253  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-01 09:01:25.254  7694  7742 D BluetoothAdapterProperties: Name is: G3
,07-01 09:01:25.255  7694  7742 D BluetoothAdapterProperties: Scan Mode:20
07-01 09:01:25.255  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 09:01:25.255  7694  7742 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:25.255  7694  7742 D bt_hci_bdroid: postload
07-01 09:01:25.255  7694  7771 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 09:01:25.259  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 09:01:25.265  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-01 09:01:25.265  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-01 09:01:25.265  7694  7742 D bte_conf: Device ID record 1 : primary
07-01 09:01:25.265  7694  7742 D bte_conf:   vendorId            = 00c4
07-01 09:01:25.265  7694  7742 D bte_conf:   vendorIdSource      = 0001
07-01 09:01:25.265  7694  7742 D bte_conf:   product             = 13a1
07-01 09:01:25.265  7694  7742 D bte_conf:   version             = 1000
07-01 09:01:25.265  7694  7742 D bte_conf:   clientExecutableURL = 
07-01 09:01:25.265  7694  7742 D bte_conf:   serviceDescription  = 
07-01 09:01:25.265  7694  7742 D bte_conf:   documentationURL    = 
07-01 09:01:25.265  7694  7742 D bte_conf: bte_load_did_conf no section named DID2.
07-01 09:01:25.265  7694  7769 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-01 09:01:25.266  7694  7771 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 09:01:25.267  7694  7742 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 09:01:25.267  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:25.267  7694  7739 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 09:01:25.267  7694  7739 D BluetoothAdapterProperties: ScanMode =  20
07-01 09:01:25.267  7694  7739 D BluetoothAdapterProperties: State =  11
07-01 09:01:25.267  7694  7739 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-01 09:01:25.267  7694  7739 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-01 09:01:25.267  7694  7739 D BluetoothAdapterProperties: Setting state to 12
07-01 09:01:25.267  7694  7739 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-01 09:01:25.268  1036  1098 D BluetoothManagerService: Message: 60
07-01 09:01:25.268  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12,
,07-01 09:01:25.268  1036  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
07-01 09:01:25.268  1036  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:25.268  7694  7739 I BluetoothAdapterState: Entering On State
07-01 09:01:25.269  7694  7742 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 09:01:25.270  7694  7795 E bt_mct  : hci lib postload completed
,07-01 09:01:25.260  7797  7797 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:25.260  7797  7797 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:25.278  7694  7739 D LGBluetoothServiceAdapter: [BTUI] OnState
,07-01 09:01:25.278  7694  7739 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-01 09:01:25.278  7694  7739 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-01 09:01:25.279  7694  7739 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-01 09:01:25.291  1036  1036 D BluetoothHeadset: Proxy object connected
,07-01 09:01:25.295  7238  7299 D BluetoothMap: onBluetoothStateChange: up=true
07-01 09:01:25.300  7694  7742 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:25.301  7694  7742 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-01 09:01:25.301  7238  7255 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:25.301  7238  7238 D BluetoothMap: Proxy object connected
07-01 09:01:25.301  7238  7238 D MapProfile: Bluetooth service connected
07-01 09:01:25.302  7238  7238 D BluetoothMap: getConnectedDevices()
07-01 09:01:25.303  7694  7710 V BluetoothMapService: getConnectedDevices()
07-01 09:01:25.304  1853  2453 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:25.306  1853  1853 D BluetoothHeadset: Proxy object connected
07-01 09:01:25.306  7238  7254 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 09:01:25.309  7694  7769 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 09:01:25.309  7694  7769 W bt-smp  : Plain text(LSB ~ MSB) = d4 09 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 09:01:25.309  7694  7769 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 19 da 6d 30 b8 83 96 12 5f ae 97 0e 64 e3 f7 
07-01 09:01:25.309  7694  7769 W bt-btm  : Stopping oneshot timer
07-01 09:01:25.310  7238  7255 D BluetoothPbap: onBluetoothStateChange: up=true
07-01 09:01:25.313  7238  7299 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-01 09:01:25.315  7238  7238 D BluetoothHeadset: Proxy object connected
07-01 09:01:25.316  7238  7238 D HeadsetProfile: Bluetooth service connected
07-01 09:01:25.318  7694  7739 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-01 09:01:25.320  1036  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 09:01:25.321  1036  1036 D BluetoothA2dp: Proxy object connected
07-01 09:01:25.322  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:25.323  1853  1853 D BluetoothHeadset: Proxy object connected
07-01 09:01:25.323  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 09:01:25.324  1853  1853 D BluetoothHeadset: Proxy object connected
,07-01 09:01:25.325  7238  7255 D BluetoothPan: onBluetoothStateChange on: true
07-01 09:01:25.325  7238  7255 D BluetoothPan: onBluetoothStateChange call bindService
07-01 09:01:25.332  1036  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-01 09:01:25.332  1036  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-01 09:01:25.334  1606  1606 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-01 09:01:25.335  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.335  1944  2127 D LGBluetoothAPIService: Message: 1
07-01 09:01:25.337  7694  7694 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.337  7694  7694 D BluetoothMapService: STATE_ON
07-01 09:01:25.337  7694  7694 V BluetoothMapService: Handler(): got msg=1
07-01 09:01:25.337  7694  7769 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 09:01:25.338  7694  7769 W bt-smp  : Plain text(LSB ~ MSB) = cc 3c 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 09:01:25.338  7694  7769 W bt-smp  : Encrypted text(LSB ~ MSB) = 82 72 c6 9c c9 62 00 2b 39 1b 1b 53 df 32 94 9e 
07-01 09:01:25.338  7694  7769 W bt-btm  : Stopping oneshot timer
07-01 09:01:25.338  7694  7694 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-01 09:01:25.338  1944  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,07-01 09:01:25.339  7806  7806 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-01 09:01:25.340  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-01 09:01:25.343  1944  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-01 09:01:25.343  1036  1098 D BluetoothManagerService: Message: 40
07-01 09:01:25.343  1036  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-01 09:01:25.344  7238  7238 D BluetoothA2dp: Proxy object connected
07-01 09:01:25.344  7238  7238 D A2dpProfile: Bluetooth service connected
07-01 09:01:25.345  7694  7807 D BluetoothMapMasInstance: MAS initSocket()
07-01 09:01:25.346  7694  7807 D BluetoothMapMasInstance:   masId = 00
07-01 09:01:25.346  7694  7807 D BluetoothMapMasInstance:   msgTypes = 0e
07-01 09:01:25.346  7694  7807 D BluetoothMapMasInstance:   masName = SMS/MMS
07-01 09:01:25.346  7694  7807 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-01 09:01:25.346  7238  7238 D BluetoothInputDevice: Proxy object connected
07-01 09:01:25.346  7238  7238 D HidProfile: Bluetooth service connected
07-01 09:01:25.347  1036  1579 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:25.348  7238  7238 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 09:01:25.348  7238  7238 D PanProfile: Bluetooth service connected
,07-01 09:01:25.348  7694  7807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:25.349  7694  7807 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-01 09:01:25.349  7694  7769 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 09:01:25.349  7694  7769 W bt-smp  : Plain text(LSB ~ MSB) = af 1b 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 09:01:25.349  7694  7807 V BluetoothMapMasInstance: Succeed to create listening socket 
07-01 09:01:25.349  7694  7769 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 a0 27 20 8f db 5c 32 53 92 d8 ca e3 d2 13 32 
07-01 09:01:25.350  7694  7769 W bt-btm  : Stopping oneshot timer
07-01 09:01:25.350  7694  7807 D BluetoothMapMasInstance: Accepting socket connection...
07-01 09:01:25.350  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:25.350  7694  7694 V BluetoothPbapService: Pbap Service onCreate
07-01 09:01:25.350  7694  7694 V BluetoothPbapService: Starting PBAP service
07-01 09:01:25.350  7694  7742 D BluetoothAdapterProperties: Scan Mode:21
07-01 09:01:25.351  7694  7694 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 09:01:25.351  7694  7694 V BluetoothPbapService: Pbap Service onBind
07-01 09:01:25.352  7694  7742 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-01 09:01:25.352  7694  7694 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.352  7694  7694 V BluetoothPbapService: state: 12
07-01 09:01:25.353  7694  7694 D LGBluetoothAPIServer: [BTUI] onCreate()
07-01 09:01:25.353  7694  7694 D LGBluetoothAPIServer: [BTUI] onBind()
,07-01 09:01:25.355  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-01 09:01:25.357  7694  7694 V BluetoothPbapService: Handler(): got msg=1
07-01 09:01:25.357  1944  2127 D LGBluetoothAPIService: Message: 100
07-01 09:01:25.357  1944  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-01 09:01:25.357  7694  7694 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-01 09:01:25.358  7694  7811 V BluetoothPbapService: Pbap Service initSocket
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:25.359  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:25.360  7694  7769 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 09:01:25.360  7694  7769 W bt-smp  : Plain text(LSB ~ MSB) = d1 fb 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 09:01:25.360  7694  7769 W bt-smp  : Encrypted text(LSB ~ MSB) = 81 7e d7 f2 31 7a da cf d5 94 33 de 44 6b 0f c3 
07-01 09:01:25.361  7694  7769 W bt-btm  : Stopping oneshot timer
07-01 09:01:25.361  1036  1579 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:25.362  7694  7811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:25.362  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:25.363  7694  7811 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-01 09:01:25.363  7238  7238 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-01 09:01:25.363  7694  7811 V BluetoothPbapService: Succeed to create listening socket 
07-01 09:01:25.363  7694  7811 V BluetoothPbapService: Accepting socket connection...
07-01 09:01:25.364  7238  7238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 09:01:25.367  7694  7694 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 09:01:25.367  7694  7694 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.367  7694  7694 V BluetoothPbapReceiver: ***********state = 12
07-01 09:01:25.367  7238  7238 D BluetoothPbap: Proxy object connected
,07-01 09:01:25.367  7238  7238 D PbapServerProfile: Bluetooth service connected
07-01 09:01:25.369  2190  2190 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:25.370  7238  7238 D DockEventReceiver: finishStartingService: stopping service
07-01 09:01:25.370  2190  2190 D c       : Getting all permits...
07-01 09:01:25.370  2190  2190 D a       : Opening database...
07-01 09:01:25.376  2190  2190 D a       : Opening database auth.proximity.permit_store...
07-01 09:01:25.377  2190  2190 D a       : Closing database...
,07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:25.379  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:25.383  7694  7769 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 09:01:25.383  7694  7769 W bt-smp  : Plain text(LSB ~ MSB) = be 41 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 09:01:25.383  7694  7769 W bt-smp  : Encrypted text(LSB ~ MSB) = ff db e6 16 b4 20 ed 91 02 02 c1 1b 96 99 82 b9 
07-01 09:01:25.383  7694  7769 W bt-btm  : Stopping oneshot timer
07-01 09:01:25.383  7125  7199 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:25.384  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:25.384  7125  7199 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:25.384  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:25.384  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:25.384  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25018d04 removed from the list
07-01 09:01:25.384  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:25.384  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb872ed added. We now have 2 listener(s)
07-01 09:01:25.384  7125  7199 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:25.386  7238  7238 D BluetoothPermissionRequest: onReceive
07-01 09:01:25.388  1036  1978 D WifiServiceImplEx: setWifiEnabled: false pid=7125, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 09:01:25.388  7238  7238 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 09:01:25.388  1036  1978 D WifiService: setWifiEnabled: false pid=7125, uid=10118
07-01 09:01:25.388  1036  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-01 09:01:25.390  7238  7238 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 09:01:25.392  7694  7694 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-01 09:01:25.393  7694  7694 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-01 09:01:25.397  7125  7199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:25.398  7694  7694 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-01 09:01:25.399  1036  1905 D WifiServiceImplEx: setWifiEnabled: true pid=7125, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 09:01:25.399  1036  1905 D WifiService: setWifiEnabled: true pid=7125, uid=10118
07-01 09:01:25.399  1036  1905 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-01 09:01:25.412  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:01:25.412  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 09:01:25.412  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-01 09:01:25.415  1036  1542 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-01 09:01:25.415  1036  1542 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-01 09:01:25.416  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-01 09:01:25.416  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 09:01:25.416  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-01 09:01:25.416  1036  1542 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 09:01:25.416  1036  1542 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-01 09:01:25.416  1036  1542 E WifiHW  : unknown target_country: EU , set to default
07-01 09:01:25.416  1036  1542 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-01 09:01:25.416  1036  1542 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-01 09:01:25.416  1036  1542 I WifiUtil: gEnableBmps=1
07-01 09:01:25.416  7694  7694 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 09:01:25.416  7694  7694 V BtOppService: onCreate
,07-01 09:01:25.420  7694  7694 V BluetoothOppNotification: send message
07-01 09:01:25.423  7694  7694 V BtOppService: Starting RfcommListener
07-01 09:01:25.426  7694  7694 D BluetoothOppPreference: Dumping Names:  
07-01 09:01:25.426  7694  7694 D BluetoothOppPreference: {}
,07-01 09:01:25.426  7694  7694 D BluetoothOppPreference: Dumping Channels:  
07-01 09:01:25.426  7694  7694 D BluetoothOppPreference: {}
07-01 09:01:25.427  7694  7694 V BtOppService: onStartCommand
07-01 09:01:25.429  7694  7821 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-01 09:01:25.431  7694  7694 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.431  7694  7694 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 09:01:25.433  7694  7694 V BluetoothOppNotification: new notify threadi!
07-01 09:01:25.433  7694  7694 V BluetoothOppNotification: send delay message
07-01 09:01:25.434  7694  7818 V BtOppService: Deleted complete outbound shares, number =  0
07-01 09:01:25.435  7694  7818 V BtOppService: Deleted complete inbound failed shares, number = 0
07-01 09:01:25.436  7694  7694 V BtOppService: start RfcommListener
07-01 09:01:25.436  7694  7818 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-01 09:01:25.437  7694  7821 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 09:01:25.438  7694  7822 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-01 09:01:25.438  7694  7818 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23100262 on behalf of 
07-01 09:01:25.438  7694  7694 V BtOppService: RfcommListener started
07-01 09:01:25.439  7694  7823 V BtOppRfcommListener: Starting RFCOMM listener....
07-01 09:01:25.440  1036  1579 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:25.440  7694  7823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:25.442  7694  7823 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
07-01 09:01:25.442  7694  7823 V BtOppRfcommListener: Started RFCOMM listener....
,07-01 09:01:25.442  7694  7823 I BtOppRfcommListener: Accept thread started.
07-01 09:01:25.442  7694  7823 V BtOppRfcommListener: Accepting connection...
07-01 09:01:25.442  7694  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8570ff3 on behalf of 
07-01 09:01:25.444  7694  7822 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ce004b0 on behalf of 
07-01 09:01:25.446  7694  7822 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-01 09:01:25.446  7694  7821 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-01 09:01:25.446  7694  7821 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 09:01:25.447  7694  7822 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-01 09:01:25.447  7694  7821 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cefcf29 on behalf of 
07-01 09:01:25.448  7694  7821 V BluetoothOppNotification: update too frequent, put in queue
07-01 09:01:25.448  7694  7822 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5efe2ae on behalf of 
07-01 09:01:25.449  7694  7821 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-01 09:01:25.450  7694  7822 V BluetoothOppNotification: outbound: succ-0  fail-0
07-01 09:01:25.450  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
07-01 09:01:25.451  7694  7694 V BluetoothFtpService: Ftp Service onCreate
07-01 09:01:25.451  7694  7694 I BluetoothFtpService: Ftp Service onCreate
07-01 09:01:25.451  7694  7694 V BluetoothFtpService: Ftp Service onStartCommand
07-01 09:01:25.451  7694  7694 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.451  7694  7694 V BluetoothFtpService: Starting Listening on sockets
07-01 09:01:25.451  7694  7694 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 09:01:25.451  7694  7694 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 09:01:25.451  7694  7694 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 09:01:25.451  7694  7694 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.451  7694  7694 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-01 09:01:25.452  7694  7694 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 09:01:25.456  7694  7694 V BtOppService: ContentObserver received notification
,07-01 09:01:25.456  7694  7694 V BtOppService: ContentObserver received notification
07-01 09:01:25.456  7694  7694 V BluetoothFtpService: Handler(): got msg=1
07-01 09:01:25.457  7694  7694 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-01 09:01:25.457  7694  7694 V BluetoothFtpService: Ftp Service initSocket
07-01 09:01:25.458  7694  7824 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-01 09:01:25.458  7694  7824 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 09:01:25.459  7694  7822 V BluetoothOppNotification: outbound notification was removed.
07-01 09:01:25.459  7694  7822 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-01 09:01:25.460  1036  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:25.460  7694  7824 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fb8bbdc on behalf of 
07-01 09:01:25.460  7694  7822 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@330d34e5 on behalf of 
07-01 09:01:25.461  7694  7824 V BluetoothOppNotification: update too frequent, put in queue
07-01 09:01:25.461  7694  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:25.461  7694  7822 V BluetoothOppNotification: inbound: succ-0  fail-0
07-01 09:01:25.461  7694  7694 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=79
07-01 09:01:25.462  7694  7694 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-01 09:01:25.463  7694  7825 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-01 09:01:25.464  7694  7824 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-01 09:01:25.464  7694  7822 V BluetoothOppNotification: inbound notification was removed.
07-01 09:01:25.464  7694  7822 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-01 09:01:25.465  7694  7822 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10db7bba on behalf of 
07-01 09:01:25.474  7694  7694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@184584a1
,07-01 09:01:25.474  7694  7694 V BluetoothSapService: Sap Service onCreate
07-01 09:01:25.476  7694  7694 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:25.476  7694  7694 V BluetoothSapService: state: 12
07-01 09:01:25.476  7694  7694 V BluetoothSapService: Starting SAP server process
07-01 09:01:25.478  7694  7694 V BluetoothSapService: SAP Service startRfcommListenerThread
07-01 09:01:25.470  7826  7826 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:25.470  7826  7826 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:25.479  7694  7827 V BluetoothSapService: Sap Service initRfcommSocket
07-01 09:01:25.479  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 09:01:25.480  7694  7827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:25.481  7694  7827 V BluetoothSapService: Succeed to create listening socket 
07-01 09:01:25.481  7694  7827 V BluetoothSapService: Accepting socket connection...
07-01 09:01:25.486  7826  7826 V BT_SAP  : Event pipe created
07-01 09:01:25.486  7826  7826 V BT_SAP  : create_server_socket qcom.sap.server
07-01 09:01:25.486  7826  7826 V BT_SAP  : created socket fd 6
,07-01 09:01:25.714  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-01 09:01:25.714  7125  7202 I jxcore-log: 
,07-01 09:01:25.735  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-01 09:01:25.735  7125  7202 I jxcore-log: 
,07-01 09:01:25.753  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-01 09:01:25.753  7125  7202 I jxcore-log: 
,07-01 09:01:25.936  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-01 09:01:25.936  7125  7202 I jxcore-log: 
,07-01 09:01:26.019  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-01 09:01:26.019  7125  7202 I jxcore-log: 
,07-01 09:01:26.072  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-01 09:01:26.072  7125  7202 I jxcore-log: 
,07-01 09:01:26.079  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-01 09:01:26.079  7125  7202 I jxcore-log: 
07-01 09:01:26.277  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-01 09:01:26.277  7125  7202 I jxcore-log: 
,07-01 09:01:26.296  1036  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-01 09:01:26.301  1036  1098 D Tethering: InitialState.processMessage what=4
07-01 09:01:26.301  1036  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 09:01:26.304   309   896 D SoftapController: Softap fwReload - Ok
07-01 09:01:26.310  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-01 09:01:26.310  7125  7202 I jxcore-log: 
07-01 09:01:26.314  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-01 09:01:26.314  7125  7202 I jxcore-log: 
,07-01 09:01:26.321  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-01 09:01:26.321  7125  7202 I jxcore-log: 
07-01 09:01:26.333  1036  1542 E NetdConnector: NDC Command {65 softap fwreload wlan0 STA} took too long (913ms)
07-01 09:01:26.334   309   896 D CommandListener: Setting iface cfg
07-01 09:01:26.334   309   896 D CommandListener: Trying to bring down wlan0
,07-01 09:01:26.341  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-01 09:01:26.341  7125  7202 I jxcore-log: 
07-01 09:01:26.346   309   896 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:26.346  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:26.346  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 09:01:26.346  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 09:01:26.346  7238  7238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 09:01:26.349  1036  1542 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-01 09:01:26.350  7842  7842 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:26.350  7842  7842 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:26.368  7842  7842 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-01 09:01:26.383  7842  7842 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-01 09:01:26.383  7842  7842 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-01 09:01:26.386  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 09:01:26.387  7238  7238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,07-01 09:01:26.387  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-01 09:01:26.388  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 09:01:26.388  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 09:01:26.388  7238  7238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 09:01:26.388  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-01 09:01:26.389  7238  7238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 09:01:26.392  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:26.392  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 09:01:26.392  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 09:01:26.392  7238  7238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 09:01:26.393  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 09:01:26.394  7238  7238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 09:01:26.395  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 09:01:26.395  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 09:01:26.395  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 09:01:26.395  7238  7238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 09:01:26.395  7238  7238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 09:01:26.409  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-01 09:01:26.409  7125  7202 I jxcore-log: 
,07-01 09:01:26.436  7694  7694 V BluetoothOppNotification: new notify threadi!
,07-01 09:01:26.437  7694  7694 V BluetoothOppNotification: send delay message
,07-01 09:01:26.438  7694  7852 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-01 09:01:26.439  7694  7852 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29b59986 on behalf of 
07-01 09:01:26.439  7694  7852 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-01 09:01:26.440  7694  7852 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-01 09:01:26.440  7694  7852 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1abd6247 on behalf of 
07-01 09:01:26.441  7694  7852 V BluetoothOppNotification: outbound: succ-0  fail-0
07-01 09:01:26.442  7694  7852 V BluetoothOppNotification: outbound notification was removed.
07-01 09:01:26.442  7694  7852 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-01 09:01:26.443  7694  7852 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@207eaa74 on behalf of 
07-01 09:01:26.444  7694  7852 V BluetoothOppNotification: inbound: succ-0  fail-0
07-01 09:01:26.445  7694  7852 V BluetoothOppNotification: inbound notification was removed.
07-01 09:01:26.445  7694  7852 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-01 09:01:26.446  7694  7852 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37961b9d on behalf of 
07-01 09:01:26.451  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:26.451  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:26.451  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:26.452  1036  1542 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-01 09:01:26.452  1036  1542 D WifiMonitor: connecting to supplicant
07-01 09:01:26.454  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:26.454  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-01 09:01:26.455  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-01 09:01:26.455  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:26.460  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:26.462  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:26.470  7842  7842 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 09:01:26.485  7374  7855 V FormManager: Network unavailable.
07-01 09:01:26.487  7374  7855 V FormManager: Network unavailable.
07-01 09:01:26.492  7374  7854 W FormManager: Network not available. Please check & try again.
,07-01 09:01:26.497  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 09:01:26.546  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-01 09:01:26.546  7125  7202 I jxcore-log: 
07-01 09:01:26.552  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-01 09:01:26.552  7125  7202 I jxcore-log: 
,07-01 09:01:26.554  7842  7842 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-01 09:01:26.568  7842  7842 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-01 09:01:26.568  7842  7842 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,07-01 09:01:26.571  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-01 09:01:26.572  1036  7857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-01 09:01:26.572  1036  7857 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 09:01:26.572  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-01 09:01:26.572  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-01 09:01:26.572  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-01 09:01:26.572  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-01 09:01:26.573  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-01 09:01:26.573  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-01 09:01:26.574  1036  1542 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-01 09:01:26.576  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:26.578  7125  7202 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-01 09:01:26.578  7125  7202 I jxcore-log: 
07-01 09:01:26.578  1036  1542 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:26.579  1036  1542 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:26.580  1036  1542 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,07-01 09:01:26.581  1036  1542 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-01 09:01:26.581  1036  1542 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,07-01 09:01:26.584  1036  1542 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-01 09:01:26.584  1036  1542 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-01 09:01:26.584  1036  1542 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-01 09:01:26.587  7125  7202 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-01 09:01:26.587  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:26.587  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:26.587  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:26.587  1036  1542 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 09:01:26.587  1036  1542 E WifiStateMachine: useWiFiOffloading() : false
07-01 09:01:26.587  1036  1542 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 09:01:26.587  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:26.587  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 09:01:26.588  7125  7202 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-01 09:01:26.588  7125  7202 I jxcore-log: 
07-01 09:01:26.590  1036  1542 D WifiNative-wlan0: doBoolean: SET update_config 1
07-01 09:01:26.591  1036  1542 D WifiNative-wlan0: SET update_config 1: returned true
07-01 09:01:26.591  1036  1542 D WifiConfigStore: Loading config and enabling all networks 
07-01 09:01:26.591  1036  1542 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,07-01 09:01:26.593  1944  1944 D WfdService: Waiting for WifiP2p enabling
07-01 09:01:26.594  1036  1542 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-01 09:01:26.595  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:26.601  1036  1542 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:26.603  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:26.603  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-01 09:01:26.603  1036  1546 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-01 09:01:26.606  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:26.615  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 09:01:26.619  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:26.622  7374  7860 W FormManager: Network not available. Please check & try again.
07-01 09:01:26.624  1036  1542 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-01 09:01:26.625  1036  1542 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 09:01:26.625  7374  7861 V FormManager: Network unavailable.
,07-01 09:01:26.627  1036  1542 D WifiStateMachine: enableVerboseLogging : level 2
07-01 09:01:26.627  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:26.628  1036  1542 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,07-01 09:01:26.628  1036  1542 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-01 09:01:26.628  1036  1542 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:26.630  7125  7199 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:26.630  1036  1542 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-01 09:01:26.630  1036  1542 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-01 09:01:26.630  1036  1542 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-01 09:01:26.630  1036  1542 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-01 09:01:26.631  1036  1542 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-01 09:01:26.631  1036  1542 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-01 09:01:26.632  1036  1542 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-01 09:01:26.632  1036  1542 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-01 09:01:26.632  1036  1542 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-01 09:01:26.632  1036  1542 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-01 09:01:26.633  1036  1542 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-01 09:01:26.633  7125  7199 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:26.633  7125  7199 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:26.633  7125  7199 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:26.633  7125  7199 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:26.633  7125  7199 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:26.633  7125  7199 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb872ed removed from the list
07-01 09:01:26.634  1036  1542 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 09:01:26.634  1944  1944 D WfdsService: Supplicant Connection state is changed : true
07-01 09:01:26.634  1036  1542 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-01 09:01:26.635  1944  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-01 09:01:26.635  1944  2326 D WfdsService: Set the WFDS Monitor: true
07-01 09:01:26.635  1944  2326 D WfdsMonitor: WfdsMonitorThread create
07-01 09:01:26.635  1944  2326 D WfdsMonitor: WFDS Monitor is created and started
07-01 09:01:26.635  1944  2326 D WfdsService: WiFi: Supplicant connection re-established
07-01 09:01:26.635  1036  1542 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-01 09:01:26.635  1036  1542 D WifiNative-HAL: Setting external_sim to 1
07-01 09:01:26.635  1036  1542 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-01 09:01:26.636  1944  7862 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-01 09:01:26.636  1036  1542 D WifiNative-wlan0: SET external_sim 1: returned true
07-01 09:01:,26.636  1036  1542 I WifiNative-HAL: startHal
07-01 09:01:26.636  1036  1542 D wifi    : setting scan oui 0xaf64e2a0
07-01 09:01:26.636  1944  7862 E CtrlSupplicant: Succeed to open control connection
07-01 09:01:26.636  1036  1542 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 09:01:26.636  1036  1542 I WifiNative-HAL: startHal
07-01 09:01:26.636  1944  7862 E CtrlSupplicant: Succeed to open monitor connection
07-01 09:01:26.636  1036  1542 D wifi    : setting scan oui 0xaf64e2a0
07-01 09:01:26.637  1036  1542 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-01 09:01:26.637  1944  7862 D WfdsMonitor: Supplicant connection established
07-01 09:01:26.637  1036  1542 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-01 09:01:26.637  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-01 09:01:26.637  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-01 09:01:26.637  7125  7199 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-01 09:01:26.637  1944  2326 D WfdsService: Connected to the supplicant for wfds
07-01 09:01:26.638  1036  1542 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-01 09:01:26.638  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 09:01:26.638  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 09:01:26.638  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 09:01:26.638  7125  7199 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-01 09:01:26.638  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 09:01:26.638  7125  7199 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-01 09:01:26.638  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 09:01:26.638  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-01 09:01:26.638  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-01 09:01:26.638  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-01 09:01:26.638  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-01 09:01:26.639  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 09:01:26.639  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 09:01:26.639  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 09:01:26.639  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 09:01:26.639  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 09:01:26.640  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-01 09:01:26.640  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-01 09:01:26.641  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 09:01:26.641  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-01 09:01:26.641  7842  7842 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-01 09:01:26.641  7125  7199 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-01 09:01:26.641  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 09:01:26.641  7125  7199 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-01 09:01:26.642  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 09:01:26.642  7125  7199 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-01 09:01:26.642  7125  7199 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-01 09:01:26.643  7125  7199 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-01 09:01:26.643  7125  7199 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-01 09:01:26.643  7125  7199 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-01 09:01:26.643  7125  7199 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-01 09:01:26.644  7125  7199 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-01 09:01:26.644  7125  7199 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-01 09:01:26.646  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:26.646  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:26.648  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-01 09:01:26.648  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 09:01:26.648  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-01 09:01:26.648  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 09:01:26.648  1036  1542 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 09:01:26.649  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-01 09:01:26.649  1036  1542 E WifiNative: : [295,920,829 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-01 09:01:26.649  1036  1542 D WifiNative-wlan0: doBoolean: RECONNECT
07-01 09:01:26.649  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:26.649  1036  1542 D WifiNative-wlan0: RECONNECT: returned true
07-01 09:01:26.649  1036  1542 D WifiNative-wlan0: doString: [STATUS]
,07-01 09:01:26.650  1036  1542 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-01 09:01:26.650  1036  1542 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 09:01:26.650  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-01 09:01:26.650  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-01 09:01:26.651  1036  1542 D WifiNative-wlan0: SET ps 1: returned true
07-01 09:01:26.651  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:26.651  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.651  7125  7202 I jxcore-log: 
07-01 09:01:26.652  1036  1541 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.652  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.652  7125  7202 I jxcore-log: 
07-01 09:01:26.653  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.653  7125  7202 I jxcore-log: 
07-01 09:01:26.653   309   896 D CommandListener: Setting iface cfg
07-01 09:01:26.653   309   896 D CommandListener: Trying to bring up p2p0
07-01 09:01:26.654  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bec5795 Bundle[{}]
07-01 09:01:26.654  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 09:01:26.654  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-01 09:01:26.654  1036  1560 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.654  1036  1560 I WifiNative-HAL: startHal
07-01 09:01:26.654  1036  1560 D wifi    : getting scan capabilities on interface[1] = 0xaf64e2a0
07-01 09:01:26.654  1036  1560 D wifi    : failed to get capabilities : -3
07-01 09:01:26.654  7125  7199 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 09:01:26.654  1036  1560 E WifiScanningService: could not get scan capabilities
07-01 09:01:26.654  7125  7199 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-01 09:01:26.655  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.655  7125  7202 I jxcore-log: 
07-01 09:01:26.655  1036  1561 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 09:01:26.655  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-01 09:01:26.656  1036  1542 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-01 09:01:26.656  1036  1541 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 09:01:26.656  1036  1541 D LGWifiP2pService: P2pEnablingState
07-01 09:01:26.656  1036  1541 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.656  1036  1541 D LGWifiP2pService: P2p socket connection successful
07-01 09:01:26.656  1036  1541 D LGWifiP2pService: P2pEnabledState
07-01 09:01:26.656  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.656  7125  7202 I jxcore-log: 
07-01 09:01:26.656  1036  1542 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-01 09:01:26.656  1036  1541 D LGWifiP2pService: sending p2p connection changed broadcast
07-01 09:01:26.656  1036  1542 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-01 09:01:26.657  1036  1541 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-01 09:01:26.657  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.657  7125  7202 I jxcore-log: 
07-01 09:01:26.657  1036  1542 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-01 09:01:26.657  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.657  7125  7202 I jxcore-log: 
07-01 09:01:26.657  1036  1542 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-01 09:01:26.657  1036  1542 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-01 09:01:26.658  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 09:01:26.658  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.658  7125  7202 I jxcore-log: 
07-01 09:01:26.658  1036  1542 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-01 09:01:26.658  1036  1542 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-01 09:01:26.658  1036  1541 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-01 09:01:26.658  7842  7842 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-01 09:01:26.658  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 09:01:26.658  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.658  7125  7202 I jxcore-log: 
07-01 09:01:26.658  1036  1541 D WifiNative-p2p0: doBoolean: SET device_name G3
07-01 09:01:26.659  1036  1541 D WifiNative-p2p0: SET device_name G3: returned true
07-01 09:01:26.659  7125  7199 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-01 09:01:26.659  1036  1541 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-01 09:01:26.659  1036  1541 D LGWifiP2pService: before postfix = G3
07-01 09:01:26.659  1036  1541 D WifiServerServiceExt: postfix byte check : 2
07-01 09:01:26.659  1036  1541 D LGWifiP2pService: after postfix = G3
07-01 09:01:26.659  1036  1541 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-01 09:01:26.659  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.659  7125  7202 I jxcore-log: 
07-01 09:01:26.659  1036  1541 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-01 09:01:26.659  1036  1541 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-01 09:01:26.659  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChan,ged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.659  7125  7202 I jxcore-log: 
07-01 09:01:26.660  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-01 09:01:26.660  1944  1944 D WfdsService: WifiP2pState is changed : true
07-01 09:01:26.660  1944  2326 D WfdsService: Receive the WFDS_ENABLE Method
07-01 09:01:26.660  1944  2326 D WfdsService: Set the WFDS Monitor: true
07-01 09:01:26.660  1944  2326 D WfdsService: Connected to the supplicant for wfds
07-01 09:01:26.660  1944  2326 D WfdsJNI : doCommand: WFDS_SET TRUE
07-01 09:01:26.660  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.660  7125  7202 I jxcore-log: 
07-01 09:01:26.660  7842  7842 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-01 09:01:26.660  1944  2326 D WfdsService: selectPreferredScanChannel [36]
07-01 09:01:26.660  1944  2326 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-01 09:01:26.661  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-01 09:01:26.661  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.661  7125  7202 I jxcore-log: 
07-01 09:01:26.661  1944  1944 D WfdsService: isConnected: false
07-01 09:01:26.661  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.661  7125  7202 I jxcore-log: 
07-01 09:01:26.662  1036  1541 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-01 09:01:26.662  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.662  7125  7202 I jxcore-log: 
07-01 09:01:26.662  1036  1541 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-01 09:01:26.662  1036  1541 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-01 09:01:26.662  1036  1541 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-01 09:01:26.662  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.662  7125  7202 I jxcore-log: 
07-01 09:01:26.662  1036  1541 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-01 09:01:26.662  1036  1541 D WifiNative-HAL: p2pGetDeviceAddress
07-01 09:01:26.663  1036  1541 D WifiNative-HAL: p2pGetDeviceAddress returning 
07-01 09:01:26.663  1036  1542 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-01 09:01:26.664  1036  1542 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-01 09:01:26.665  1036  1542 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-01 09:01:26.665  1036  1542 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-01 09:01:26.665  7842  7842 E wpa_supplicant: disconnect_rssi_lvl: -100
07-01 09:01:26.666  4866  7863 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 09:01:26.668  1036  1542 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-01 09:01:26.669  1036  1542 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-01 09:01:26.669  1036  1542 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-01 09:01:26.669  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-01 09:01:26.670  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,07-01 09:01:26.670  7842  7842 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.670  7125  7865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 849, name: My test thread name)
07-01 09:01:26.670  7125  7865 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 849, thread name: My test thread name)
07-01 09:01:26.670  4866  7864 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 09:01:26.670  4866  7864 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:26.670  7125  7865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 849, name: My test thread name)
07-01 09:01:26.670  7842  7842 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-01 09:01:26.671  7842  7842 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  1542 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-01 09:01:26.671  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 09:01:26.671  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.671  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.671  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.671  1036  7857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.671  1036  1542 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-01 09:01:26.671  1036  7857 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  7842  7842 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  1542 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-01 09:01:26.671  1036  7857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.671  1036  7857 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  1542 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-01 09:01:26.671  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.671  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-01 09:01:26.672  1944  7862 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.672  1944  7862 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.672  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-01 09:01:26.672  7842  7842 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 09:01:26.672  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-01 09:01:26.672  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 09:01:26.672  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 09:01:26.672  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 09:01:26.673  1036  1542 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-01 09:01:26.673  1036  1542 D WifiNative-wlan0: doBoolean: BSS_FLUSH, 0
07-01 09:01:26.673  7125  7867 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 851, name: My test thread name)
07-01 09:01:26.673  7125  7867 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 851, thread name: My test thread name)
07-01 09:01:26.673  7125  7867 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 851, name: My test thread name)
07-01 09:01:26.674  1036  1542 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-01 09:01:26.674  1036  1542 D WifiNative-wlan0: doBoolean: SCAN
07-01 09:01:26.675  1036  1542 D WifiNative-wlan0: SCAN: returned false
07-01 09:01:26.675  7125  7199 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 36
07-01 09:01:26.675  1036  1542 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=295947  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 09:01:26.675  7125  7199 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 36
07-01 09:01:26.675  7125  7199 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-01 09:01:26.675  7125  7199 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-01 09:01:26.675  7125  7199 E com.test.thalitest.ThaliTestRunner: Total duration: 8943 ms
07-01 09:01:26.676  7125  7199 I System.out: Tests succeded_00
07-01 09:01:26.676  7125  7199 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 9018ms. Plugin should use CordovaInterface.getThreadPool().
07-01 09:01:26.706  1036  2015 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7868 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-01 09:01:26.708  7374  7861 V FormManager: Network unavailable.
07-01 09:01:26.708  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=295981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 09:01:26.709  1036  1542 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:26.709  1036  1542 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:26.709  1036  1542 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:26.710  1036  1542 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:26.710  1036  1542 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 09:01:26.711  1036  1541 D LGWifiP2pService: DeviceAddress: 
07-01 09:01:26.711  1036  1541 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-01 09:01:26.712  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:26.712  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:26.712  1036  1541 D WifiNative-p2p0: P2P_FLUSH: returned true
07-01 09:01:26.712  1036  1541 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-01 09:01:26.712  1036  1541 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-01 09:01:26.712  1036  1541 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-01 09:01:26.713  1036  1541 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-01 09:01:26.713  1036  1541 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-01 09:01:26.713  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:26.714  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:26.714  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:26.714  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-01 09:01:26.715  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:26.715  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-01 09:01:26.715  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
07-01 09:01:26.715  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-01 09:01:26.716  1944  1944 D WfdsService: Update P2p Interface State: 3
07-01 09:01:26.720  1036  1541 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-01 09:01:26.720  1036  1541 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-01 09:01:26.721  1036  1541 D LGWifiP2pService: InactiveState
07-01 09:01:26.721  1036  1541 D LGWifiP2pService: InactiveState{ when=-50ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.721  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-50ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.721  1036  1541 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-01 09:01:26.722  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-01 09:01:26.723  7842  7842 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.723  1036  7857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 09:01:26.723  1036  7857 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.723  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-01 09:01:26.723  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 09:01:26.723  7842  7842 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-01 09:01:26.723  7842  7842 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.723  1036  7857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.723  1036  7857 E WifiMonitor: WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.723  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.723  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.724  7842  7842 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.724  1036  7857 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.724  1036  7857 E WifiMonitor: WifiMonitor:p2p0 cnt=33 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.724  1036  7857 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.724  1036  7857 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 09:01:26.724  1944  7862 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 09:01:26.724  1944  7862 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.724  1944  7862 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 09:01:26.725  1036  1541 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.725  1036  1541 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1036  1541 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1036  1541 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1944  2326 W WfdsService: DefaultState - msg [9441285] is not handled
07-01 09:01:26.726  1036  1541 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1036  1541 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:26.726  1036  1036 E WifiServerServiceExt: No, p2p device connected
,07-01 09:01:26.830  7868  7868 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 09:01:26.830  7868  7868 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-01 09:01:26.843  7868  7868 V [BNRBootReceiver]: Boot Receiver Return
,07-01 09:01:26.844  7868  7868 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-01 09:01:26.848  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:26.858  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:26.872  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:26.882  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:26.883  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:26.886  7316  7316 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-01 09:01:27.232  7842  7842 E wpa_supplicant: USIM:  scard_init function
07-01 09:01:27.233  7842  7842 I wpa_supplicant: Trying to associate with SSID 'NG700'
,07-01 09:01:27.248  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-01 09:01:27.249  1036  7857 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-01 09:01:27.249  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-01 09:01:27.249  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: WPS-AP-AVAILABLE 
07-01 09:01:27.249  1036  7857 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-01 09:01:27.250  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-01 09:01:27.250  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-01 09:01:27.259  1036  1542 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-01 09:01:27.259  1036  1542 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-01 09:01:27.260  1036  1542 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-01 09:01:27.260  1036  1542 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-01 09:01:27.260  1036  1542 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,07-01 09:01:27.281  1036  1542 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=296553  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-01 09:01:27.290  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-01 09:01:27.293  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.293  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.293  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-01 09:01:27.294  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=296567  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-01 09:01:27.298  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.298  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-01 09:01:27.312  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.312  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.312  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-01 09:01:27.312  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:27.312  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,07-01 09:01:27.322  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.326  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.326  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:27.332  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 09:01:27.368  7842  7842 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-01 09:01:27.373  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-01 09:01:27.374  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-01 09:01:27.374  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-01 09:01:27.374  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-01 09:01:27.374  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 09:01:27.374  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 09:01:27.378  7842  7842 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 09:01:27.378  7842  7842 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,07-01 09:01:27.384  1036  1542 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=296656  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-01 09:01:27.385  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=296657  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-01 09:01:27.389  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 09:01:27.389  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 09:01:27.390  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-01 09:01:27.390  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 09:01:27.390  1036  7857 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 09:01:27.390  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-01 09:01:27.391  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-01 09:01:27.391  1036  7857 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-01 09:01:27.391  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 09:01:27.391  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 09:01:27.394  1036  1542 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=296666
,07-01 09:01:27.406  1036  1542 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=296679
07-01 09:01:27.407  1036  1542 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=296679
07-01 09:01:27.408  1036  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-01 09:01:27.414  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=296686
07-01 09:01:27.414  1036  1542 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 38 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=296686
07-01 09:01:27.415  1036  1542 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=296687  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-01 09:01:27.423  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.423  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:27.423  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.423  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.423  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-01 09:01:27.424  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=296696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-01 09:01:27.425  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.428  1036  1542 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=296697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-01 09:01:27.429  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=296701  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-01 09:01:27.430  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.430  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.430  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-01 09:01:27.431  1036  1542 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=296703
07-01 09:01:27.431  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:27.431  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,07-01 09:01:27.431  1036  1542 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=296703
,07-01 09:01:27.432  1036  1542 D WifiNative-wlan0: doString: [STATUS]
07-01 09:01:27.432  1036  7857 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 09:01:27.433  1036  7857 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 09:01:27.433  1036  1542 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-01 09:01:27.435  1036  1542 I WifiServiceExtension: setVHTCapabilityType  : false
07-01 09:01:27.437  7238  7238 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-01 09:01:27.441  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.442  1036  1542 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-01 09:01:27.442  1036  1542 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-01 09:01:27.450  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.450  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.451  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-01 09:01:27.454  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.454  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:27.456  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.458  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.458  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.458  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-01 09:01:27.460  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:27.460  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:27.462  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 09:01:27.465  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:27.466  1036  1542 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-01 09:01:27.466  1036  1542 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 09:01:27.466  1036  1542 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-01 09:01:27.467  1036  1548 D ConnectivityService: Got NetworkAgent Messenger
07-01 09:01:27.467  1036  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-01 09:01:27.467  1036  1548 D ConnectivityService: NetworkAgent connected
07-01 09:01:27.467  1036  1542 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-01 09:01:27.467  1036  1542 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-01 09:01:27.473  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.473  1036  1542 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-01 09:01:27.473  1036  1542 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 09:01:27.473  1036  1542 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,07-01 09:01:27.473  1036  1542 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-01 09:01:27.473  1036  1542 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-01 09:01:27.476  1036  1542 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-01 09:01:27.477  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.477  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:27.477   309   896 D CommandListener: Setting iface cfg
,07-01 09:01:27.479  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.479  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.479  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.480  7316  7316 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 09:01:27.483  1036  1542 E WifiStateMachine: Start Dhcp Watchdog 2
07-01 09:01:27.484  1036  7913 D DhcpStateMachine: StoppedState
,07-01 09:01:27.484  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.484  1036  7913 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.484  1036  7913 D DhcpStateMachine: WaitBeforeStartState
07-01 09:01:27.484  1036  1542 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=296756  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 09:01:27.485  1036  1542 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=296757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 09:01:27.485  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=296757  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 09:01:27.486  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:27.486  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:27.487  1036  1542 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:27.487  1036  1542 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:27.487  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:27.488  1036  1542 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 09:01:27.490  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:27.490  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:27.490  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,07-01 09:01:27.491  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:27.491  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-01 09:01:27.492  1036  1542 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=296764  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 09:01:27.493  1036  1542 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=296765  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 09:01:27.493  1036  1542 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=296765  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 09:01:27.494  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:250830] from screen [on:0 period:-1522327738] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:01:27.495  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1522327737] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:01:27.495  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:01:27.495  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.499  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.501  1036  1548 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-01 09:01:27.501  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-01 09:01:27.501  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,07-01 09:01:27.502  1036  1542 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.502  1036  1542 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.503  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.503  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.503  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.503  1036  1542 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.503  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 09:01:27.504  1036  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-01 09:01:27.504  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
07-01 09:01:27.505  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=162,0,0
07-01 09:01:27.505  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-01 09:01:27.505  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-01 09:01:27.506  1036  1542 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-01 09:01:27.506  1036  1542 D WifiNative-wlan0: doBoolean: SET ps 0
07-01 09:01:27.506  1036  1542 D WifiNative-wlan0: SET ps 0: returned true
07-01 09:01:27.506  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-01 09:01:27.506  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-01 09:01:27.506  1036  1542 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-01 09:01:27.507  1036  1541 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@289d408b target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.507  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@289d408b target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.507  1036  1542 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-01 09:01:27.507  1036  1542 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-01 09:01:27.507  1036  7913 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.507  1036  1542 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-01 09:01:27.507  1036  7913 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-01 09:01:27.508   309   896 D CommandListener: Setting iface cfg
07-01 09:01:27.508   309   896 D CommandListener: Trying to bring up wlan0
07-01 09:01:27.509  1036  1542 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-01 09:01:27.510  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:27.510  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-01 09:01:27.511  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 09:01:27.511  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-01 09:01:27.512  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:27.512  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 09:01:27.512  7238  7238 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 09:01:27.512  7238  7238 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-01 09:01:27.512  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.512  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 09:01:27.512  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.512  7238  7238 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 09:01:27.513  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-01 09:01:27.513  1036  1542 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.513  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 09:01:27.513  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 09:01:27.513  7238  7238 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 09:01:27.513  7238  7238 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-01 09:01:27.513  7238  7238 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 09:01:27.513  1036  1542 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.513  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.514  1036  1542 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 09:01:27.514  1036  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-01 09:01:27.515  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-01 09:01:27.515  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-01 09:01:27.515  1036  1541 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.515  1036  1541 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.515  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-01 09:01:27.516  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-01 09:01:27.516  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.516  1036  1542 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-01 09:01:27.516  1036  1542 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-01 09:01:27.516  7842  7842 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-01 09:01:27.516  1036  1542 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-01 09:01:27.516  1036  1542 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 09:01:27.524  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.530  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.533  1036  1542 D WifiNative-wlan0: SET ps 1: returned true
07-01 09:01:27.534  1036  1542 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-01 09:01:27.534  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-01 09:01:27.535  1036  1542 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-01 09:01:27.535  1036  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-01 09:01:27.535  1036  1548 D ConnectivityService: ignoring duplicate network state non-change
07-01 09:01:27.537  1036  1548 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-01 09:01:27.537  1036  1548 D ConnectivityService: Adding iface wlan0 to network 101
07-01 09:01:27.537  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.538  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 09:01:27.550  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.552  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.552  1606  1606 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-01 09:01:27.552  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.552  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.552  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-01 09:01:27.553  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.553  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.553  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-01 09:01:27.554  1036  1542 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-01 09:01:27.556  1036  1547 D WifiController: battery changed pluggedType: 2
07-01 09:01:27.556  1944  2103 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-01 09:01:27.556  1944  2103 D LEDHandler: Battery Level Remaining: 100%
07-01 09:01:27.556  1944  2103 D LEDHandler: Battery Temp: 279, mChargingStatus=5, mChargingStop=false
07-01 09:01:27.556  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.556  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.557  7868  7868 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-01 09:01:27.558  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.559  1036  1548 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-01 09:01:27.559  1036  1548 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-01 09:01:27.560  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-01 09:01:27.560  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.560  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.560  1036  1548 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-01 09:01:27.560  7694  7752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 09:01:27.561   309   896 E Netd    : netlink response contains error (File exists)
07-01 09:01:27.561  1036  1548 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-01 09:01:27.561  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-01 09:01:27.562  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.562  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.562  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-01 09:01:27.562  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-01 09:01:27.562  1036  1548 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-01 09:01:27.562  1036  1548 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-01 09:01:27.562  1036  1548 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-01 09:01:27.562  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 09:01:27.562  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
07-01 09:01:27.563  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.563  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:27.563  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-01 09:01:27.564  1036  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-01 09:01:27.564  1036  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.564  1036  1548 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.564  1036  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.564  1036  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.564  1036  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.565  1036  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-01 09:01:27.565  1036  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.565  1036  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-01 09:01:27.565  1036  1548 D ConnectivityService: currentScore = 0, newScore = 20
07-01 09:01:27.565  1036  1548 D ConnectivityService:    accepting network in place of null
07-01 09:01:27.565  1036  1548 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.566  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.566  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-01 09:01:27.566  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.566  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-01 09:01:27.567  1036  1542 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&N,OT_VPN] ]
07-01 09:01:27.567  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 09:01:27.567  1036  1542 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.567  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-01 09:01:27.568  1036  1548 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-01 09:01:27.568  1036  1548 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-01 09:01:27.568  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:27.569   309  7918 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-01 09:01:27.569  1036  1548 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:27.569  1036  1548 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-01 09:01:27.569  1036  1548 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-01 09:01:27.570  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 09:01:27.571  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
07-01 09:01:27.571  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-01 09:01:27.572  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-01 09:01:27.572  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 09:01:27.572  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 09:01:27.572  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 09:01:27.572  1036  1548 D ConnectivityService: validation of new default Network = false
07-01 09:01:27.572  1036  1548 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-01 09:01:27.572  1036  1548 D DSQN    : enableDataServiceNotify 
07-01 09:01:27.572  1036  1548 D DSQN    : start dsqn bin
07-01 09:01:27.576  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-01 09:01:27.577  1606  1606 I StatusBar.NetworkController: networkI,nfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.577  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-01 09:01:27.578  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.578  1036  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.578  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.578  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.579  1036  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.579  1606  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-01 09:01:27.570  7919  7919 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:27.570  7919  7919 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:27.583  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.591  7919  7919 E DSQN    : DSQN ssw
,07-01 09:01:27.591  1036  1540 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-01 09:01:27.599  1606  1606 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.599  1606  1606 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-01 09:01:27.599  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.602  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.615  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.618  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 09:01:27.618   309  7918 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-01 09:01:27.619  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.619  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.619  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.619  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.620  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 09:01:27.621  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.627  1818  7923 I CheckinService: active receiver: enabled
07-01 09:01:27.627  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.631  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.633  1818  7923 I CheckinService: Preparing to send checkin request
07-01 09:01:27.633  1818  7923 I EventLogService: Accumulating logs since 1467356235284
07-01 09:01:27.637  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.637  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.637  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 09:01:27.640  1818  7923 W EventLogAggregator: Unknown tag: snet_gcore
07-01 09:01:27.640  1818  7923 W EventLogAggregator: Unknown tag: snet_launch_service
,07-01 09:01:27.641  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.645  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:27.649  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.653  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.653  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:27.654  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 09:01:27.654   309  7918 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-01 09:01:27.659  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.666  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.670  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.674  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.674  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.678  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-01 09:01:27.682  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.683  1818  7923 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-01 09:01:27.687  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:27.688   309   895 D LGDataListener: argv[0]=dsqncommand
07-01 09:01:27.688   309   895 D LGDataListener: argv[1]=wlan0
07-01 09:01:27.688   309   895 D LGDataListener: argv[2]=1
07-01 09:01:27.688   309   895 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-01 09:01:27.688  1036  1096 D DSQN    : DSQM DsqnNotification wlan0  1
07-01 09:01:27.688  1036  1096 D DSQN    : start to monitor internet connection
,07-01 09:01:27.692  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.699  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.699  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.700  7316  7316 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 09:01:27.703  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-01 09:01:27.705  7257  7257 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-01 09:01:27.708  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:27.708  1036  7913 D DhcpStateMachine: DHCPV4 request on wlan0
07-01 09:01:27.709  1036  7913 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-01 09:01:27.709  1036  7913 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-01 09:01:27.711  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 09:01:27.700  7927  7927 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 09:01:27.700  7927  7927 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 09:01:27.717  7927  7927 I dhcpcd  : version 5.5.6 starting
,07-01 09:01:27.718  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.719  7927  7927 E dhcpcd  : get_duid: m
07-01 09:01:27.719  7927  7927 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-01 09:01:27.719  7927  7927 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-01 09:01:27.722  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Jul 2016 07:01:27 GMT], X-Android-Received-Millis=[1467356487722], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467356487688]}
07-01 09:01:27.722  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-01 09:01:27.722  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-01 09:01:27.723  1036  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.723  1036  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.723  1036  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.723  1036  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.723  1036  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-01 09:01:27.723  1036  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-01 09:01:27.723  1036  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-01 09:01:27.723  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.723  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.723  1036  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.724  1036  1548 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.724  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-01 09:01:27.724  1036  1542 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.724  1036  1542 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.725  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.725  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-01 09:01:27.726  1606  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-01 09:01:27.727  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.727  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.728  7316  7316 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-01 09:01:27.728  7316  7316 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-01 09:01:27.729  7316  7316 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are, no stored BSSIDs.
,07-01 09:01:27.734  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 09:01:27.738  7257  7257 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-01 09:01:27.740  7257  7257 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-01 09:01:27.743  7238  7238 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.750  7238  7238 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 09:01:27.756  1606  1606 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 09:01:27.757  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 09:01:27.757  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 09:01:27.763  7316  7316 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 09:01:27.763  7316  7316 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 09:01:27.764  7316  7316 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-01 09:01:27.764  7316  7316 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-01 09:01:27.764  7316  7316 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-01 09:01:27.768  7927  7927 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-01 09:01:27.768  7927  7927 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-01 09:01:27.768  7927  7927 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-01 09:01:27.768  7927  7927 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-01 09:01:27.768  7927  7927 D dhcpcd  : wlan0: sending REQUEST (xid 0x62f2d1a9), next in 3.43 seconds
07-01 09:01:27.784  7927  7927 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-01 09:01:27.806  7927  7927 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-01 09:01:27.806  7927  7927 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-01 09:01:27.806  7927  7927 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-01 09:01:27.806  7927  7927 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-01 09:01:27.806  7927  7927 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-01 09:01:27.807  7927  7927 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-01 09:01:27.807  7927  7927 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-01 09:01:27.807  7927  7927 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-01 09:01:27.808  1036  1925 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7934 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-01 09:01:27.840  7934  7934 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 09:01:27.840  7934  7934 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 09:01:27.857  7934  7934 I MultiDex: VM with version 2.1.0 has multidex support
07-01 09:01:27.857  7934  7934 I MultiDex: install
07-01 09:01:27.857  7934  7934 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 09:01:27.865  7934  7934 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-01 09:01:27.870  2190  2190 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-01 09:01:27.878  2190  2190 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-01 09:01:27.879  2190  2190 D c       : Getting all permits...
07-01 09:01:27.879  2190  2190 D a       : Opening database...
07-01 09:01:27.884  2190  2190 D a       : Opening database auth.proximity.permit_store...
07-01 09:01:27.885  2190  2190 D a       : Closing database...
,07-01 09:01:27.975  1036  1548 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-01 09:01:28.083  7636  7657 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-01 09:01:28.112  1036  7913 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-01 09:01:28.115  1036  7913 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-01 09:01:28.116  1036  7913 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-01 09:01:28.116  1036  7913 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-01 09:01:28.116  1036  7913 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-01 09:01:28.117  1036  7913 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-01 09:01:28.117  1036  7913 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-01 09:01:28.117  1036  7913 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-01 09:01:28.117  1036  7913 D DhcpStateMachine: RunningState
07-01 09:01:28.173  7934  7954 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:28.173  7934  7954 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:28.335  7980  7980 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-01 09:01:28.418  7980  7980 I dex2oat : dex2oat took 83.462ms (threads: 4)
,07-01 09:01:28.439  7934  7954 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 09:01:28.439  7934  7954 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 09:01:28.439  7934  7954 I Adreno-EGL: Build Date: 12/12/14 금
07-01 09:01:28.439  7934  7954 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 09:01:28.439  7934  7954 I Adreno-EGL: Remote Branch: 
07-01 09:01:28.439  7934  7954 I Adreno-EGL: Local Patches: 
07-01 09:01:28.439  7934  7954 I Adreno-EGL: Reconstruct Branch: 
,07-01 09:01:28.579  7934  7954 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 09:01:28.579  7934  7954 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 09:01:28.579  7934  7954 I Adreno-EGL: Build Date: 12/12/14 금
07-01 09:01:28.579  7934  7954 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 09:01:28.579  7934  7954 I Adreno-EGL: Remote Branch: 
07-01 09:01:28.579  7934  7954 I Adreno-EGL: Local Patches: 
07-01 09:01:28.579  7934  7954 I Adreno-EGL: Reconstruct Branch: 
,07-01 09:01:28.647  7934  7954 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 09:01:28.647  7934  7954 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 09:01:28.647  7934  7954 I Adreno-EGL: Build Date: 12/12/14 금
07-01 09:01:28.647  7934  7954 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 09:01:28.647  7934  7954 I Adreno-EGL: Remote Branch: 
07-01 09:01:28.647  7934  7954 I Adreno-EGL: Local Patches: 
07-01 09:01:28.647  7934  7954 I Adreno-EGL: Reconstruct Branch: 
,07-01 09:01:28.817   309  7990 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 09:01:28.820   309  7990 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-01 09:01:28.875   309  7990 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-01 09:01:29.017  1818  7923 I CheckinTask: Sending checkin request (7681 bytes)
,07-01 09:01:29.160  1036  1877 I ActivityManager: Killing 7459:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-01 09:01:29.197  1036  1905 W libprocessgroup: failed to open /acct/uid_10011/pid_7459/cgroup.procs: No such file or directory
,07-01 09:01:29.267  1818  7923 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-01 09:01:29.284  1818  7923 I CheckinService: active receiver: disabled
,07-01 09:01:29.306  2190  2190 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-01 09:01:29.318  1036  1542 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 09:01:29.318  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 09:01:29.319  1036  1542 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 09:01:29.319  1036  1542 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 09:01:29.319  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 09:01:29.319  1036  1542 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-01 09:01:29.322  1036  1548 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
07-01 09:01:29.322  1036  1548 D ConnectivityService: identical MTU - not setting
07-01 09:01:29.322  1036  1548 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-01 09:01:29.322  1036  1548 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-01 09:01:29.323  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:29.323  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:29.323  1036  1548 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:29.324  1606  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-01 09:01:29.333  2190  2190 I GCM     : GCM config loaded
07-01 09:01:29.347   309  7996 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 09:01:29.349   309  7996 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
07-01 09:01:29.355  7537  7537 V SetupWizard: Connected to Gservices successfully
07-01 09:01:29.386   309  7996 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,07-01 09:01:29.707  2190  7999 D GCM     : Connected
,07-01 09:01:29.744  2190  7999 D GCM     : Message class com.google.e.a.a.q
,07-01 09:01:30.502  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=81.0, 0.0, 0.0  rx=88.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522324730] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:30.518  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=81.0, 0.0, 0.0  rx=88.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522324727] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:30.520  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:01:30.541  1606  1606 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 09:01:30.561  1036  1543 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-01 09:01:30.569  1036  1548 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:30.574  1036  1098 D Tethering: MasterInitialState.processMessage what=3
,07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:30.585  7125  7125 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:30.587  7125  7125 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-01 09:01:30.593  7125  7202 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 09:01:30.593  7125  7202 I jxcore-log: 
07-01 09:01:30.594  1036  1093 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:30.608  6582  6582 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-01 09:01:30.612  6582  7247 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-01 09:01:30.623  6031  6031 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-01 09:01:30.643  2190  2190 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:30.715  1036  1978 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8001 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-01 09:01:30.717  1036  1052 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
07-01 09:01:30.717  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:30.718  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:30.718  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-01 09:01:30.718  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:30.718  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-01 09:01:30.750  1036  1093 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:30.757  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Jul 2016 07:01:30 GMT], X-Android-Received-Millis=[1467356490757], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467356490725]}
07-01 09:01:30.757  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-01 09:01:30.757  1036  7912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-01 09:01:30.758  1036  1548 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-01 09:01:30.758  1036  1548 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-01 09:01:30.758  1036  1548 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:30.758  1036  1548 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:30.758  1036  1548 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-01 09:01:30.758  1036  1548 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-01 09:01:30.758  1036  1548 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-01 09:01:30.758  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:30.758  1036  1548 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:30.758  1036  1548 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:30.759  1606  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-01 09:01:30.800  8001  8001 I AppUp4:AppBoxCP: onCreate
07-01 09:01:30.800  8001  8001 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-01 09:01:30.808  8001  8001 I AppUp4:DB:  setFingerPrint start
07-01 09:01:30.808  8001  8001 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-01 09:01:30.813  8001  8001 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,07-01 09:01:30.814  8001  8001 I AppUp4:DB:  SDK version = 21
07-01 09:01:30.814  8001  8001 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-01 09:01:30.815  8001  8001 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-01 09:01:30.816  8001  8001 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 09:01:30.816  8001  8001 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:30.818  8001  8001 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 09:01:30.818  8001  8001 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-01 09:01:30.823  8001  8001 I AppUp4:CustModeStarterReceiver: onReceive
07-01 09:01:30.851  8001  8001 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:30.851  8001  8001 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:30.857  8001  8001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@253cbaab
07-01 09:01:30.858  8001  8001 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 09:01:30.858  8001  8001 D AppUp4:CustFacade: isPhone : true
07-01 09:01:30.859  8001  8001 D AppUp4:CustModeStarterReceiver: begin check event
07-01 09:01:30.860  8001  8001 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-01 09:01:30.860  8001  8001 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-01 09:01:30.862  8001  8035 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-01 09:01:30.862  8001  8035 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-01 09:01:30.863  8001  8035 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-01 09:01:30.866  1036  1906 I ActivityManager: Killing 7486:com.lge.email/u0a23 (adj 15): empty #17
,07-01 09:01:30.905  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:30.906  4866  4866 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 09:01:30.906  1036  1905 W libprocessgroup: failed to open /acct/uid_10023/pid_7486/cgroup.procs: No such file or directory
,07-01 09:01:30.914  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 09:01:30.920  4866  4866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 09:01:30.930  4866  8038 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 09:01:30.930  3476  3476 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:30.935  4866  8039 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:30.936  4866  8039 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 09:01:30.937  3476  3476 V DownloadManager: DownloadService onCreate
07-01 09:01:30.941  4866  8038 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
07-01 09:01:30.946  3476  8040 I DownloadManager: in removeSpuriousFiles
07-01 09:01:30.947  3476  8040 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,07-01 09:01:30.952  3476  8040 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1dbc0fac on behalf of 3476
07-01 09:01:30.953  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
07-01 09:01:30.953  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
07-01 09:01:30.953  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
07-01 09:01:30.953  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
07-01 09:01:30.954  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
07-01 09:01:30.954  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
07-01 09:01:30.954  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
07-01 09:01:30.954  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
07-01 09:01:30.954  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
07-01 09:01:30.954  3476  8040 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
,07-01 09:01:30.957  3476  8040 I DownloadManager: in trimDatabase
07-01 09:01:30.957  3476  8040 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
07-01 09:01:30.960  3476  8040 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@e14475 on behalf of 3476
07-01 09:01:30.999  1036  1052 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8044 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-01 09:01:31.003  3476  3476 V DownloadManager: DownloadService onStartCommand
,07-01 09:01:31.006  3476  8041 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
07-01 09:01:31.006  4866  8038 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
07-01 09:01:31.010  3476  8041 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@21b07a98 on behalf of 3476
07-01 09:01:31.010  4866  4866 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
07-01 09:01:31.010  4866  4866 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
07-01 09:01:31.011  4866  4866 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
07-01 09:01:31.013  3476  8041 V DownloadManager: processing inserted download 1
07-01 09:01:31.013  4866  4866 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
07-01 09:01:31.014  3476  8041 V DownloadManager: processing inserted download 4
,07-01 09:01:31.016  3476  8041 V DownloadManager: processing inserted download 7
,07-01 09:01:31.019  3476  8041 V DownloadManager: processing inserted download 8
07-01 09:01:31.020  4866  4866 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
07-01 09:01:31.021  3476  8041 V DownloadManager: processing inserted download 9
07-01 09:01:31.024  3476  8041 V DownloadManager: processing inserted download 10
07-01 09:01:31.026  3476  8041 V DownloadManager: processing inserted download 11
07-01 09:01:31.027  3476  8041 V DownloadManager: processing inserted download 12
07-01 09:01:31.029  3476  8041 V DownloadManager: processing inserted download 13
07-01 09:01:31.030  3476  8041 V DownloadManager: processing inserted download 14
,07-01 09:01:31.033  3476  3476 V DownloadManager: DownloadService onDestroy
,07-01 09:01:31.066  8044  8044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 09:01:31.066  8044  8044 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 09:01:31.068  8044  8044 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 09:01:31.068  8044  8044 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 09:01:31.174  8044  8044 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-01 09:01:31.202  8044  8044 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-01 09:01:31.254  8044  8044 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-01 09:01:31.322  8044  8044 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 09:01:31.323  8044  8044 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:31.483  8044  8044 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-01 09:01:31.554  3403  3403 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 09:01:31.554  3403  3403 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:31.554  3403  3403 I LgeMiscReceiver: networkInfo.isConnected() = true
07-01 09:01:31.554  3403  3403 D PhoneState: setPdpRejectCasuse : false
07-01 09:01:31.585   309  8073 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-01 09:01:31.586   309  8073 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,07-01 09:01:31.642   309  8073 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,07-01 09:01:31.686  7374  8070 V FormManager: There are no updated forms. The schedule will be deleted.
,07-01 09:01:31.693  7374  8070 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
07-01 09:01:31.716  1036  1978 I art     : Explicit concurrent mark sweep GC freed 84129(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 3.274ms total 169.274ms
,07-01 09:01:31.719  7537  7537 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-01 09:01:31.719  7537  7537 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-01 09:01:31.722  8044  8044 I HubEmail: JNI_OnLoad()
,07-01 09:01:31.722  8044  8044 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 09:01:31.722  8044  8044 I HubEmail: registerNatives()
07-01 09:01:31.722  8044  8044 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 09:01:31.722  8044  8044 I HubEmail: registerNativeMethods()
07-01 09:01:31.722  8044  8044 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 09:01:31.722  8044  8044 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-01 09:01:31.727  8044  8074 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:31.738  7618  7618 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:1:31
07-01 09:01:31.739  7618  7618 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-01 09:01:31.739  7618  7618 D Weather.Utils: 2 : All the weather widget is gone.
07-01 09:01:31.740  7618  7618 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 09:01:31.740  7618  7618 D WeatherAncestor: connectivity changed - connection : true
07-01 09:01:31.740  7618  7618 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@184584a1
,07-01 09:01:31.742  7618  7618 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-01 09:01:31.742  7618  7618 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-01 09:01:31.742  7618  7618 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-01 09:01:31.742  7618  7618 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 09:01:31.742  7618  7618 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:1:31
07-01 09:01:31.757  1036  1924 I ActivityManager: Killing 7280:com.lge.lifetracker/u0a37 (adj 15): empty #17
,07-01 09:01:31.769   309  8076 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-01 09:01:31.770   309  8076 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,07-01 09:01:31.799  1036  1978 W libprocessgroup: failed to open /acct/uid_10037/pid_7280/cgroup.procs: No such file or directory
,07-01 09:01:31.805   309  8076 D libc-netbsd: res_queryN name = www.google.com succeed
07-01 09:01:31.816   309  8078 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 09:01:31.817   309  8078 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-01 09:01:31.817   309  8078 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-01 09:01:31.886  1036  1544 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,07-01 09:01:33.558  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=57.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522321675] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:33.561  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=57.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1522321671] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:33.561  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:01:33.812  1036  1906 I ActivityManager: Killing 7334:com.lge.settings.easy/1000 (adj 15): empty #17
,07-01 09:01:33.857  1036  1616 W libprocessgroup: failed to open /acct/uid_1000/pid_7334/cgroup.procs: No such file or directory
,07-01 09:01:36.582  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=37.5, 0.0, 0.0  rx=34.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522318650] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:36.585  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=37.5, 0.0, 0.0  rx=34.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522318647] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:36.585  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:01:37.724  1606  1606 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-01 09:01:37.749  1036  1444 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-01 09:01:37.821  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-01 09:01:37.840  1036  1094 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8086 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 09:01:37.850  1036  1036 D administrator: Handling package changes for user 0
07-01 09:01:37.889  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,07-01 09:01:37.891  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,07-01 09:01:37.931  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-01 09:01:37.949  8086  8086 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 09:01:37.995  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,07-01 09:01:37.995  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-01 09:01:38.042  8086  8086 D LgDataFeature: LgDataFeature() Constructor: none
07-01 09:01:38.043  8086  8086 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:38.047  1036  1093 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 09:01:38.052  1036  1093 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-01 09:01:38.058  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-01 09:01:38.059  2475  2475 V GmsNetworkLocationProvi: DISABLE
,07-01 09:01:38.079  2475  2475 E GCoreFlp: Bound FusedProviderService with LocationManager
,07-01 09:01:38.161  8086  8131 I Babel   : MmsConfig: mnc/mcc: 0/0
07-01 09:01:38.161  8086  8131 I Babel   : MmsConfig.loadMmsSettings
,07-01 09:01:38.167  8086  8131 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-01 09:01:38.167  8086  8131 I Babel   : MmsConfig.loadFromDatabase
07-01 09:01:38.173  1036  1093 D LocationProviderProxy: applying state to connected service
,07-01 09:01:38.192  8086  8131 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-01 09:01:38.193  8086  8131 I Babel   : MmsConfig.loadFromResources
07-01 09:01:38.194  8086  8131 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-01 09:01:38.195  8086  8131 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-01 09:01:38.196  8086  8086 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:38.202  8086  8130 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 09:01:38.203  8086  8130 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 09:01:38.207  8086  8130 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 09:01:38.215  1818  8133 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-01 09:01:38.217  1818  8133 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-01 09:01:38.218  8001  8001 I AppUp4:CustModeStarterReceiver: onReceive
07-01 09:01:38.220  8086  8130 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-01 09:01:38.220  8001  8001 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@253cbaab
07-01 09:01:38.220  8001  8001 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 09:01:38.220  8001  8001 D AppUp4:CustFacade: isPhone : true
07-01 09:01:38.221  8001  8001 D AppUp4:CustModeStarterReceiver: begin check event
07-01 09:01:38.221  8001  8001 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-01 09:01:38.222  8086  8130 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 09:01:38.225  1818  5212 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-01 09:01:38.226  8086  8130 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 09:01:38.236  8086  8130 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-01 09:01:38.239  8086  8130 W VideoCapabilities: Unsupported mime video/divx
07-01 09:01:38.241  8086  8130 W VideoCapabilities: Unsupported mime video/divx311
07-01 09:01:38.243  8086  8130 W VideoCapabilities: Unsupported mime video/divx4
,07-01 09:01:38.248  8086  8130 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-01 09:01:38.253  1036  1877 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8137 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-01 09:01:38.256  1036  1616 I ActivityManager: Killing 7868:com.lge.bnr/1000 (adj 15): empty #17
,07-01 09:01:38.287  8086  8130 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 09:01:38.290  8086  8130 W AudioCapabilities: Unsupported mime audio/eac3
,07-01 09:01:38.290  8086  8130 W AudioCapabilities: Unsupported mime audio/ac3
07-01 09:01:38.291  8086  8130 W AudioCapabilities: Unsupported mime audio/g726
07-01 09:01:38.292  8086  8130 W AudioCapabilities: Unsupported mime audio/wma-voice
07-01 09:01:38.292  8086  8130 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-01 09:01:38.293  8086  8130 W AudioCapabilities: Unsupported mime audio/adpcm
07-01 09:01:38.294  8086  8130 W VideoCapabilities: Unsupported mime video/theora
07-01 09:01:38.295  8086  8130 W VideoCapabilities: Unsupported mime video/mjpg
07-01 09:01:38.328  1036  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_7868/cgroup.procs: No such file or directory
,07-01 09:01:38.348  1036  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{7f9194 type 2 when 307572 com.google.android.gms} when 307572
,07-01 09:01:38.381  8137  8137 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 09:01:38.381  8137  8137 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 09:01:38.381  8137  8137 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-01 09:01:38.383  8137  8137 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-01 09:01:38.383  8137  8137 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 09:01:38.459  8137  8137 I SystemConfig: BUILD Country: EU
07-01 09:01:38.459  8137  8137 I SystemConfig: BUILD Operator: OPEN
,07-01 09:01:38.533  1036  1906 I ActivityManager: Killing 7257:com.lge.sync/1000 (adj 15): empty #17
,07-01 09:01:38.644  1036  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_7257/cgroup.procs: No such file or directory
,07-01 09:01:38.659  8137  8155 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-01 09:01:38.660  8137  8155 I SystemConfig: existFile = false
07-01 09:01:38.660  8137  8155 I SystemConfig: canReadFile = false
07-01 09:01:38.660  8137  8155 I SystemConfig: systemFeature RCS result false
07-01 09:01:38.660  8137  8155 D SystemConfig: refreshRcsSupport() :false
07-01 09:01:38.711  1036  1979 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8160 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-01 09:01:38.779  8160  8160 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 09:01:38.780  8160  8160 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 09:01:38.780  8160  8160 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-01 09:01:38.781  8160  8160 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 09:01:38.894  8160  8160 I AppConfig: Total System Memory = 2995761152
,07-01 09:01:38.905  8160  8160 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-01 09:01:38.981  1036  1906 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8179 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 09:01:38.982  1036  1906 I ActivityManager: Killing 6980:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-01 09:01:39.013  7316  7316 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,07-01 09:01:39.016  7316  7316 W System.err: android.os.DeadObjectException
07-01 09:01:39.016  7316  7316 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-01 09:01:39.016  7316  7316 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-01 09:01:39.016  7316  7316 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-01 09:01:39.016  7316  7316 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-01 09:01:39.016  7316  7316 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-01 09:01:39.016  7316  7316 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-01 09:01:39.017  7316  7316 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 09:01:39.017  7316  7316 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 09:01:39.017  7316  7316 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-01 09:01:39.017  7316  7316 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-01 09:01:39.017  7316  7316 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:39.017  7316  7316 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:39.017  7316  7316 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-01 09:01:39.017  7316  7316 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-01 09:01:39.017  7316  7316 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-01 09:01:39.017  7316  7316 W System.err: android.os.DeadObjectException
07-01 09:01:39.019  7316  7316 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-01 09:01:39.019  7316  7316 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-01 09:01:39.019  7316  7316 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-01 09:01:39.019  7316  7316 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-01 09:01:39.019  7316  7316 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:39.019  7316  7316 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:39.019  7316  7316 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-01 09:01:39.019  7316  7316 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-01 09:01:39.019  7316  7316 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-01 09:01:39.020  7316  7316 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
07-01 09:01:39.090  1036  1997 W libprocessgroup: failed to open /acct/uid_1000/pid_6980/cgroup.procs: No such file or directory
07-01 09:01:39.091  1036  1997 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-01 09:01:39.107  7316  7316 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-01 09:01:39.107  7316  7316 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-01 09:01:39.166  1036  1616 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8196 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-01 09:01:39.168  7316  7316 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,07-01 09:01:39.251  8196  8196 D UEI.SmartControl: Quickset Services start...
,07-01 09:01:39.254  8196  8196 I UEI.SmartControl: Manufacture = LGE
07-01 09:01:39.254  8196  8196 D UEI.SmartControl: Id = LGNevo
07-01 09:01:39.256  8196  8196 D UEI.SmartControl: File observer start...
07-01 09:01:39.257  8196  8196 E UEI.SmartControl: IR Port is disabled: false
07-01 09:01:39.257  8196  8196 D UEI.SmartControl: Starting file observer...
07-01 09:01:39.257  8196  8196 D UEI.SmartControl: Extracting JNI libs...
07-01 09:01:39.257  8196  8196 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-01 09:01:39.327  8179  8179 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-01 09:01:39.376  1606  1606 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 09:01:39.377  1606  1606 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-01 09:01:39.379  8196  8196 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-01 09:01:39.380  8196  8196 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-01 09:01:39.380  8196  8196 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-01 09:01:39.385  1606  1606 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
07-01 09:01:39.385  1606  1606 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-01 09:01:39.388  1944  2103 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-01 09:01:39.388  1944  2103 D LEDHandler: Battery Level Remaining: 100%
07-01 09:01:39.388  1944  2103 D LEDHandler: Battery Temp: 281, mChargingStatus=5, mChargingStop=false
07-01 09:01:39.389  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:39.389  7694  7752 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 09:01:39.389  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:39.389  1036  1547 D WifiController: battery changed pluggedType: 2
07-01 09:01:39.390  1606  1606 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-01 09:01:39.409  8179  8179 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 09:01:39.409  8179  8179 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 09:01:39.429  8196  8196 I UEI.SmartControl: --- Selecting new region: 6
,07-01 09:01:39.431  8196  8196 I UEI.SmartControl: Model = LG-D855
07-01 09:01:39.433  8196  8196 D UEI.SmartControl: QS Service created
07-01 09:01:39.446  8196  8196 I UEI.SmartControl: Service initServices...
,07-01 09:01:39.449  8196  8196 D UEI.SmartControl: QS start get config
07-01 09:01:39.450  8179  8179 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
07-01 09:01:39.467  8179  8179 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-01 09:01:39.468  8179  8179 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-01 09:01:39.482  8179  8179 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-01 09:01:39.482  8179  8179 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-01 09:01:39.497  1036  1616 I ActivityManager: Killing 7238:com.android.settings/1000 (adj 15): empty #17
,07-01 09:01:39.502  8196  8196 D UEI.SmartControl: Loading JNI Libs...
07-01 09:01:39.569  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_7238/cgroup.procs: No such file or directory
,07-01 09:01:39.585  3476  4285 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,07-01 09:01:39.591  3476  4285 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@132dced6 on behalf of 8179
07-01 09:01:39.593  5144  8234 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
07-01 09:01:39.632  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=18.8, 0.0, 0.0  rx=17.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522315600] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 09:01:39.634  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=18.8, 0.0, 0.0  rx=17.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1522315598] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:39.634  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:01:39.656  1036  1616 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8235 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:39.669   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 23.078ms
,07-01 09:01:39.690   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 19.060ms
,07-01 09:01:39.702   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 12.124ms
,07-01 09:01:39.705  8179  8179 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-01 09:01:39.727  8179  8179 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-01 09:01:39.739  8235  8235 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-01 09:01:39.751  8235  8235 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-01 09:01:39.751  8235  8235 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-01 09:01:39.751  8235  8235 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-01 09:01:39.751  8235  8235 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-01 09:01:39.751  8235  8235 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-01 09:01:39.752  8235  8235 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-01 09:01:39.763   309  8262 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-01 09:01:39.763   309  8262 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
07-01 09:01:39.763   309  8262 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,07-01 09:01:39.765  7316  7316 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-01 09:01:39.766  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5762
07-01 09:01:39.771  1036  1051 I ActivityManager: Killing 8044:com.lge.email/u0a23 (adj 15): empty #17
07-01 09:01:39.813  8196  8196 I UEI.SmartControl: Supports setup maps: true
,07-01 09:01:39.819  8196  8196 D UEI.SmartControl: QS start statue = true Error code = 0
07-01 09:01:39.819  8196  8196 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-01 09:01:39.819  8196  8196 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-01 09:01:39.819  8196  8196 I UEI.SmartControl: ### init IR Blaster...
07-01 09:01:39.824  8196  8196 D serial_port: Configuring serial port
07-01 09:01:39.834  8196  8196 E UEI.SmartControl: UEIBLaster setting for 616
,07-01 09:01:39.834  8196  8196 I UEI.SmartControl: Setting serial record hearder size = 2
07-01 09:01:39.836  8196  8196 I UEI.SmartControl: configuring settings for MAXQ616
07-01 09:01:39.836  8196  8196 I UEI.SmartControl: Get version...
07-01 09:01:39.843  1036  1979 W libprocessgroup: failed to open /acct/uid_10023/pid_8044/cgroup.procs: No such file or directory
07-01 09:01:39.858  8196  8264 D UEI.SmartControl: serial port data available: 21
,07-01 09:01:39.888  8196  8196 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-01 09:01:39.888  8196  8196 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-01 09:01:39.888  8196  8196 I UEI.SmartControl: QS saving settings...
,07-01 09:01:39.897  8196  8196 D UEI.SmartControl: IR Blaster version: 25672567
07-01 09:01:39.913  8196  8264 D UEI.SmartControl: serial port data available: 4
,07-01 09:01:39.946  8196  8268 I UEI.SmartControl: Device manager: loading config....
,07-01 09:01:39.947  8196  8268 D UEI.SmartControl: ----------- loading internal config...
07-01 09:01:39.948  8196  8196 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-01 09:01:39.953  8196  8196 E UEI.SmartControl: Services init done
07-01 09:01:39.955  8196  8196 D UEI.SmartControl: QS Service init finished
07-01 09:01:39.956  8196  8196 D UEI.SmartControl: QS Service version name: 2.1.91
07-01 09:01:39.956  8196  8196 D UEI.SmartControl: QS Service version code: 201091
07-01 09:01:39.957  8196  8196 D UEI.SmartControl: Service requested: Control
07-01 09:01:39.960  8196  8268 E UEI.SmartControl: Loading SETTINGS...
,07-01 09:01:39.962  8196  8196 D UEI.SmartControl: Request IControl service: devices are loaded...
07-01 09:01:39.965  7316  7316 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-01 09:01:39.965  1036  1943 I ActivityManager: Killing 7374:com.lge.formmanager/u0a26 (adj 15): empty #17
07-01 09:01:39.965  8196  8212 I UEI.SmartControl: ------ IControl API: 11
07-01 09:01:39.966  8196  8212 I UEI.SmartControl: Registering callback...
07-01 09:01:39.967  8196  8212 I UEI.SmartControl: ------ IControl API: 19
07-01 09:01:39.969  8196  8212 I UEI.SmartControl: Registering Services Ready callback...
07-01 09:01:39.974  8196  8268 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,07-01 09:01:39.986  8196  8267 I UEI.SmartControl: Notify AllClients services are ready: 0
07-01 09:01:39.986  7316  7331 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-01 09:01:39.987  8196  8267 D UEI.SmartControl: -----service ready thread exits
07-01 09:01:39.988  7316  7408 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-01 09:01:39.988  7316  7408 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-01 09:01:39.989  7316  7316 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,07-01 09:01:39.989  7316  7316 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-01 09:01:39.990  8196  8213 I UEI.SmartControl: ------ IControl API: 8
,07-01 09:01:39.990  7316  7316 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-01 09:01:39.991  7316  7316 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-01 09:01:39.991  7316  7316 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-01 09:01:39.992  7316  7316 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-01 09:01:39.993  7316  7316 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-01 09:01:39.993  7316  7316 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-01 09:01:40.027  1036  1616 W libprocessgroup: failed to open /acct/uid_10026/pid_7374/cgroup.procs: No such file or directory
07-01 09:01:40.028  8196  8196 D UEI.SmartControl: Internal service binding...
,07-01 09:01:40.032  7316  7316 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-01 09:01:40.034  7316  7316 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-01 09:01:40.035  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-01 09:01:40.037  7316  7316 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 09:01:40.037  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-01 09:01:40.038  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-01 09:01:40.039  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-01 09:01:40.040  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-01 09:01:40.040  7316  7316 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1467356500040]
07-01 09:01:40.041  1036  2015 V SIM_STK : Menu title from STK is T-Mobile
,07-01 09:01:40.051  2190  8266 D GCM     : Connected
,07-01 09:01:40.056  7316  8270 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-01 09:01:40.061  7316  7316 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-01 09:01:40.062  7316  7316 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 09:01:40.062  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-01 09:01:40.062  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-01 09:01:40.063  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-01 09:01:40.063  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-01 09:01:40.063  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-01 09:01:40.067  7316  7316 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
07-01 09:01:40.067  2190  8266 D GCM     : Message class com.google.e.a.a.q
,07-01 09:01:40.083  5144  8234 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 490 ms] updated apps [took 490 ms] 
,07-01 09:01:42.650  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522312583] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:42.652  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=8.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522312580] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 09:01:42.653  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:01:43.776  8160  8173 W art     : Suspending all threads took: 8.372ms
,07-01 09:01:44.939  8196  8265 D serial_port: close(fd = 25)
,07-01 09:01:44.947  8196  8269 D UEI.SmartControl: Internal timer expired: 1
,07-01 09:01:44.948  8196  8269 D UEI.SmartControl: unbind internal service
,07-01 09:01:44.952  8196  8265 I UEI.SmartControl: Serial port is closed.
,07-01 09:01:45.674  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1522309558] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:45.698  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:-1522309535] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 09:01:45.698  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:01:48.719  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522306513] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:01:48.722  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522306510] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:01:48.722  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:01:51.743  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1522303489] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:01:51.744  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1522303488] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:01:51.744  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:01:54.764  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1522300468] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:01:54.773  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1522300459] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:01:54.773  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:01:57.792  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522297440] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:01:57.806  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1522297427] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:01:57.807  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:02:00.049  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 09:02:00.049  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 09:02:00.050  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 09:02:00.050  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,07-01 09:02:00.065  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 09:02:00.066  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-01 09:02:00.068  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-01 09:02:00.070  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 09:02:00.829  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522294403] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:00.832  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522294400] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:00.832  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:03.851  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522291381] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:03.854  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522291378] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:03.855  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:04.979  1036  3548 I LocationManagerService: remove 2cb095b4
,07-01 09:02:04.988  1036  3548 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-01 09:02:04.988  1036  3548 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 09:02:04.990  1036  3548 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-01 09:02:04.992  1036  3548 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-01 09:02:04.994  1036  3548 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-01 09:02:06.880  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522288352] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:06.883  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522288349] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:06.883  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:07.487  1036  1542 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,07-01 09:02:07.488  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 09:02:07.489  1036  1542 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 09:02:07.490  1036  1542 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 09:02:07.491  1036  1542 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 09:02:07.493  1036  1542 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,07-01 09:02:09.909  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522285323] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:09.912  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522285320] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:09.912  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:12.932  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522282300] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:12.935  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522282297] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:12.943  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:15.973  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522279259] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:15.985  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1522279247] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:15.987  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:02:19.008  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522276225] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:19.011  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1522276221] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:19.011  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:22.042  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522273190] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:22.045  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522273187] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:22.045  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:22.636  1036  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=455657586, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 09:02:22.691  2643  2643 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 09:02:22.721  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=455657586 [*alarm*], flags=0x0
,07-01 09:02:25.073  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522270159] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:25.083  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1522270149] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:25.083  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:02:28.106  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522267127] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:28.109  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1522267123] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:28.109  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:31.129  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522264103] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:31.132  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522264100] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:31.132  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:34.150  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1522261082] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:34.151  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1522261081] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:34.152  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:37.171  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522258062] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-01 09:02:37.174  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522258059] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:37.174  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:40.202  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522255030] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:40.205  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522255027] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:40.205  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:43.234  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522251999] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:43.244  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1522251988] gl rssi=-44 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:43.246  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:46.267  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522248965] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:46.270  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522248962] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:46.270  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:49.298  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522245934] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:49.301  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522245931] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:49.301  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:52.324  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522242908] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:52.336  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1522242897] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:52.336  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:02:55.347  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522239885] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:55.350  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522239882] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:02:55.351  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:02:58.374  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522236858] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:58.386  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1522236846] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:02:58.386  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:03:00.055  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 09:03:00.055  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 09:03:00.055  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-01 09:03:00.065  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
07-01 09:03:00.072  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 09:03:00.072  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-01 09:03:00.074  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
07-01 09:03:00.078  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 09:03:01.406  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522233827] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:01.409  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1522233823] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:03:01.410  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:04.437  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522230797] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:04.440  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1522230792] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:03:04.440  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:07.467  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1522227765] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:07.470  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522227762] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:07.470  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:10.498  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1522224734] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:10.501  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522224731] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:03:10.501  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:13.523  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522221709] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:13.534  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1522221699] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:13.534  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:16.555  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522218678] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:16.569  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1522218663] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:16.569  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 09:03:19.589  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1522215643] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:03:19.592  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522215640] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:19.592  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:22.618  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1522212614] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:22.621  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522212611] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:03:22.621  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 09:03:25.647  1036  1542 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1522209585] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 09:03:25.650  1036  1542 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1522209582] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 09:03:25.650  1036  1542 D WifiNative-wlan0: doString: [SIGNAL_POLL]

```
