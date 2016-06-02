#### Test 7214543191b6842_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
06-02 09:37:46.154  1856  1941 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-02 09:37:46.154  1856  1941 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
06-02 09:37:46.154  1856  1941 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,06-02 09:37:46.162  1615  1701 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-02 09:37:46.163  1615  1701 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-02 09:37:46.164  1615  1615 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.99, status=Status{statusCode=unknown status code: 7503, resolution=null}
06-02 09:37:46.458  4281  4281 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-02 09:37:46.460  4281  4281 D AndroidRuntime: CheckJNI is OFF
06-02 09:37:46.549  4281  4281 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-02 09:37:46.553   763  3111 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-02 09:37:46.557   763  3111 V WindowManager: addAppToken: AppWindowToken{15c4939 token=Token{2548dd00 ActivityRecord{a15d783 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
06-02 09:37:46.583   763  3111 I ActivityManager: Start proc 4295:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
06-02 09:37:46.584  4281  4281 D AndroidRuntime: Shutting down VM
06-02 09:37:46.600   763   763 V ActivityManager: Display changed displayId=0
06-02 09:37:46.679  4295  4295 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108600)
06-02 09:37:46.688  4295  4295 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 4573-4574)
06-02 09:37:46.688  4295  4295 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-02 09:37:46.697  4295  4295 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c82516a}
06-02 09:37:46.697  4295  4295 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-02 09:37:46.697  4295  4295 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
06-02 09:37:46.708   763   865 D WifiService: New client listening to asynchronous messages
06-02 09:37:46.719  4295  4295 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-02 09:37:46.724  4295  4295 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
06-02 09:37:46.724  4295  4295 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
06-02 09:37:46.733  4295  4295 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
06-02 09:37:46.775   763   831 D BluetoothManagerService: Message: 20
06-02 09:37:46.775   763   831 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@186c78ad:true
06-02 09:37:46.792  4295  4295 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
06-02 09:37:46.792  4295  4295 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,06-02 09:37:46.826   763  3112 D ConnectivityService: listenForNetwork for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 09:37:46.826   763   866 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
06-02 09:37:46.826   763   866 D ConnectivityService: apparently satisfied.  currentScore=60
06-02 09:37:46.827  4295  4343 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-02 09:37:46.840  4295  4295 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
06-02 09:37:46.840  4295  4295 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,06-02 09:37:46.853  4295  4295 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,06-02 09:37:46.858  4295  4295 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-02 09:37:46.859  4295  4295 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,06-02 09:37:46.868  4295  4295 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-02 09:37:46.883  4295  4295 I cr_Ime  : ImeThread is not enabled.
,06-02 09:37:46.891  4295  4348 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-02 09:37:46.896  4295  4295 D Atlas   : Validating map...
,06-02 09:37:46.900   763   996 V WindowManager: Adding window Window{277c2bf u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (after Window{3f3b58eb u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,06-02 09:37:46.908   763  1192 D ConnectivityService: listenForNetwork for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 09:37:46.908   763   866 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
06-02 09:37:46.908   763   866 D ConnectivityService: apparently satisfied.  currentScore=60
,06-02 09:37:46.909  4295  4343 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-02 09:37:46.933  4295  4348 I OpenGLRenderer: Initialized EGL, version 1.4
,06-02 09:37:46.937  4295  4348 D OpenGLRenderer: Enabling debug mode 0
,06-02 09:37:46.962  4295  4354 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-02 09:37:46.977  4295  4295 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-02 09:37:46.977   763   832 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +367ms (total +420ms)
,06-02 09:37:46.992  4295  4295 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4295
06-02 09:37:46.993  4295  4295 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
06-02 09:37:46.993  4295  4295 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,06-02 09:37:47.116  4295  4295 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-02 09:37:47.117   763   866 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 09:37:47.118  4295  4343 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524296
,06-02 09:37:47.175  4295  4361 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362754176
06-02 09:37:47.178  4295  4361 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-02 09:37:47.178  4295  4361 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-02 09:37:47.178  4295  4361 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-02 09:37:47.178  4295  4361 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-02 09:37:47.178  4295  4361 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-02 09:37:47.178  4295  4361 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9459e9c added. We now have 1 listener(s)
06-02 09:37:47.178   763   997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,06-02 09:37:47.180  4295  4361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,06-02 09:37:47.181  4295  4361 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
06-02 09:37:47.181  4295  4361 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-02 09:37:47.182  4295  4361 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-02 09:37:47.184  4295  4361 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3dc2b added. We now have 1 listener(s)
06-02 09:37:47.184  4295  4361 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-02 09:37:47.186  4295  4361 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,06-02 09:37:47.187  4295  4361 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-02 09:37:47.187  4295  4361 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,06-02 09:37:47.189  4295  4361 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-02 09:37:47.189   763  3111 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,06-02 09:37:47.189  4295  4361 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-02 09:37:47.194  4295  4361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-02 09:37:47.194  4295  4361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-02 09:37:47.194  4295  4361 D io.jxcore.node.ConnectivityMonitor: start: OK
06-02 09:37:47.194  4295  4361 I io.jxcore.node.LifeCycleMonitor: start: OK
06-02 09:37:47.195  4295  4295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-02 09:37:47.196  4295  4295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-02 09:37:47.212  4295  4295 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-02 09:37:47.695  4295  4362 W jxcore-log: Initializing JXcore engine
06-02 09:37:47.695  4295  4362 W jxcore-log: JXcore engine is ready
,06-02 09:37:47.750  4362  4362 W Thread-396: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8456]" dev="sockfs" ino=8456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,06-02 09:37:47.750  4362  4362 W Thread-396: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-02 09:37:47.750  4362  4362 W Thread-396: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8602]" dev="sockfs" ino=8602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-02 09:37:47.750  4362  4362 W Thread-396: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[28512]" dev="sockfs" ino=28512 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,06-02 09:37:47.767  4295  4362 W jxcore-log: Starting JXcore engine
,06-02 09:37:47.842  4295  4362 W jxcore-log: Platform android
06-02 09:37:47.842  4295  4362 W jxcore-log: 
,06-02 09:37:47.842  4295  4362 W jxcore-log: Process ARCH arm
06-02 09:37:47.842  4295  4362 W jxcore-log: 
,06-02 09:37:48.006  4295  4362 I jxcore-log: JXcore Cordova bridge is ready!
06-02 09:37:48.006  4295  4362 I jxcore-log: 
06-02 09:37:48.006  4295  4362 W jxcore-log: JXcore engine is started
,06-02 09:37:48.012  4295  4361 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-02 09:37:48.015  4295  4295 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-02 09:37:57.581  4295  4362 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-02 09:37:57.581  4295  4362 I jxcore-log: 
,06-02 09:37:57.584  4295  4362 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-02 09:37:57.584  4295  4362 I jxcore-log: 
,06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-02 09:37:57.587  4295  4362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-02 09:37:57.589  4295  4362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-02 09:37:57.591  4295  4362 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-02 09:37:57.591  4295  4362 I jxcore-log: 
06-02 09:37:57.593  4295  4362 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-02 09:37:57.593  4295  4362 I jxcore-log: 
,06-02 09:37:57.924  4295  4362 I jxcore-log: Unit Test app is loaded
06-02 09:37:57.924  4295  4362 I jxcore-log: 
,06-02 09:37:57.930  4295  4295 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-02 09:37:57.932  4295  4362 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-02 09:37:57.932  4295  4362 I jxcore-log: 
,06-02 09:37:57.937  4295  4362 I jxcore-log: My device name is: LGE-Nexus 5
06-02 09:37:57.937  4295  4362 I jxcore-log: 
,06-02 09:38:01.802  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-02 09:38:01.802  4295  4362 I jxcore-log: 
,06-02 09:38:02.184  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-02 09:38:02.184  4295  4362 I jxcore-log: 
,06-02 09:38:02.207  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-02 09:38:02.207  4295  4362 I jxcore-log: 
06-02 09:38:02.211  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-02 09:38:02.211  4295  4362 I jxcore-log: 
,06-02 09:38:02.226  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-02 09:38:02.226  4295  4362 I jxcore-log: 
06-02 09:38:02.230  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-02 09:38:02.230  4295  4362 I jxcore-log: 
,06-02 09:38:04.158  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-02 09:38:04.158  4295  4362 I jxcore-log: 
,06-02 09:38:04.169  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-02 09:38:04.169  4295  4362 I jxcore-log: 
,06-02 09:38:04.176  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-02 09:38:04.176  4295  4362 I jxcore-log: 
,06-02 09:38:04.326  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-02 09:38:04.326  4295  4362 I jxcore-log: 
,06-02 09:38:04.408  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-02 09:38:04.408  4295  4362 I jxcore-log: 
,06-02 09:38:04.460  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-02 09:38:04.460  4295  4362 I jxcore-log: 
,06-02 09:38:04.466  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-02 09:38:04.466  4295  4362 I jxcore-log: 
,06-02 09:38:04.652  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-02 09:38:04.652  4295  4362 I jxcore-log: 
,06-02 09:38:04.672  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-02 09:38:04.672  4295  4362 I jxcore-log: 
,06-02 09:38:04.676  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-02 09:38:04.676  4295  4362 I jxcore-log: 
06-02 09:38:04.681  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-02 09:38:04.681  4295  4362 I jxcore-log: 
,06-02 09:38:04.696  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-02 09:38:04.696  4295  4362 I jxcore-log: 
,06-02 09:38:04.715  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-02 09:38:04.715  4295  4362 I jxcore-log: 
,06-02 09:38:04.798  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-02 09:38:04.798  4295  4362 I jxcore-log: 
06-02 09:38:04.802  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-02 09:38:04.802  4295  4362 I jxcore-log: 
,06-02 09:38:04.826  4295  4362 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-02 09:38:04.826  4295  4362 I jxcore-log: 
,06-02 09:38:04.834  4295  4362 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-02 09:38:04.836  4295  4362 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-02 09:38:04.836  4295  4362 I jxcore-log: 
,06-02 09:43:28.714  1544  4405 I EventLogChimeraService: Aggregate from 1464852524894 (log), 1464851452964 (data)
,06-02 09:43:28.823  1544  4408 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-02 09:43:28.841  1409  4403 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-02 09:43:28.857  1409  4403 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
06-02 09:43:28.857  1409  4403 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-02 09:43:28.863  1409  4403 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,06-02 09:43:28.863  1409  4403 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-02 09:43:28.872  1409  4403 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
06-02 09:43:28.872  1409  4403 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-02 09:43:28.995  1544  4419 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-02 09:43:29.000  1544  2242 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-02 09:43:29.366  1409  4403 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-02 09:43:29.390  1544  2556 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-02 09:43:29.410  1544  2556 E Icing   : No scoring data for corpus [23]
,06-02 09:43:29.433  1544  2556 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-02 09:43:29.451  1544  2556 E Icing   : No scoring data for corpus [13]
,06-02 09:43:29.474  1544  2556 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-02 09:43:29.499  1544  2556 E Icing   : No scoring data for corpus [11]
,06-02 09:43:29.524  1544  2242 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-02 09:43:29.539  1544  2242 E Icing   : No scoring data for corpus [24]
,06-02 09:43:29.542  1409  4403 E ContextCompilationHandl: No recognition context built for MUSIC_NAMES en-US
,06-02 09:43:39.280  1856  1955 W bt-btm  : Stopping oneshot timer
,06-02 09:48:26.027   763   826 I UsageStatsService: User[0] Flushing usage stats to disk
,06-02 09:55:11.016  1856  1941 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-02 09:55:11.049  1615  1701 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-02 09:55:11.050  1615  1701 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-02 09:55:11.050  1615  1615 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.98, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-02 09:56:47.239  1544  1544 I GCM     : Message from null null
06-02 09:56:47.239  1544  1544 E GCM     : Dropping message from null
,06-02 09:58:37.811   763   827 I ProcessStatsService: Prepared write state in 38ms
,06-02 09:58:37.821   763   827 I ProcessStatsService: Prepared write state in 6ms
,06-02 09:58:37.869  1615  1615 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-02 09:58:37.870  1615  1615 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-02 09:58:37.965  1544  2276 I art     : Explicit concurrent mark sweep GC freed 42017(2MB) AllocSpace objects, 7(112KB) LOS objects, 23% free, 25MB/33MB, paused 1.159ms total 72.155ms
,06-02 09:58:39.298  1856  1955 W bt-btm  : Stopping oneshot timer
,06-02 10:00:01.011   763   827 I ActivityManager: Killing 2886:com.google.android.gms.unstable/u0a7 (adj 15): empty for 1803s
,06-02 10:00:01.073   763   827 I ActivityManager: Killing 3631:com.android.providers.calendar/u0a1 (adj 15): empty for 1842s
,06-02 10:00:37.892  1544  3094 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 1400000ms),06-02 10:01:17.177  4494  4494 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-02 10:01:17.179  4494  4494 D AndroidRuntime: CheckJNI is OFF
06-02 10:01:17.265  4494  4494 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-02 10:01:17.269   763   827 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
06-02 10:01:17.269   763   827 I ActivityManager: Killing 4295:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
06-02 10:01:17.302   763   779 I WindowState: WIN DEATH: Window{277c2bf u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-02 10:01:17.302   763   854 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b898aee)
06-02 10:01:17.303   763   865 D WifiService: Client connection lost with reason: 4
06-02 10:01:17.303   763   866 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 10:01:17.303   763   866 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 10:01:17.310   763   838 W PackageSettings: Skipping PackageSetting{2e7603b6 com.example.hello/10116} due to missing metadata
06-02 10:01:17.344   763   827 I ActivityManager: Killing 4068:com.google.android.partnersetup/u0a11 (adj 15): empty for 1800s
06-02 10:01:17.358   763   827 I ActivityManager: Killing 4036:com.android.keychain/1000 (adj 15): empty for 1800s
06-02 10:01:17.366   763   827 I ActivityManager: Killing 3034:com.android.defcontainer/u0a4 (adj 15): empty for 1800s
06-02 10:01:17.544   763   827 I ActivityManager:   Force finishing activity 3 ActivityRecord{a15d783 u0 com.test.thalitest/.MainActivity t19}
06-02 10:01:17.548   763   996 W ActivityManager: Spurious death for ProcessRecord{33f8db8f 4295:com.test.thalitest/u0a49}, curProc for 4295: null
06-02 10:01:17.549   763   997 I ActivityManager: Killing 3414:com.quickoffice.android/u0a65 (adj 13): empty for 1800s
06-02 10:01:17.588   763   997 I ActivityManager: Killing 3353:com.google.android.apps.docs/u0a35 (adj 13): empty for 1800s
06-02 10:01:17.668   763   838 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
06-02 10:01:17.711  1227  1227 I art     : Explicit concurrent mark sweep GC freed 644(30KB) AllocSpace objects, 1(81KB) LOS objects, 38% free, 26MB/42MB, paused 1.544ms total 38.474ms
06-02 10:01:17.739   904   904 I art     : Explicit concurrent mark sweep GC freed 20625(922KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 41MB/57MB, paused 6.343ms total 43.126ms
06-02 10:01:17.761   763   883 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
06-02 10:01:17.761   763   847 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-02 10:01:17.761  1615  1662 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-02 10:01:17.799  1334  4523 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-02 10:01:17.811  1544  1544 I art     : Explicit concurrent mark sweep GC freed 343(11KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 25MB/33MB, paused 576us total 124.453ms
06-02 10:01:17.820   763   763 I art     : Explicit concurrent mark sweep GC freed 232718(5MB) AllocSpace objects, 12(315KB) LOS objects, 33% free, 28MB/42MB, paused 1.369ms total 113.878ms
06-02 10:01:17.821   763   827 I ActivityManager: Start proc 4526:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
06-02 10:01:17.823   763   838 I art     : WaitForGcToComplete blocked for 27.332ms for cause Explicit
06-02 10:01:17.828  1409  1409 I art     : Explicit concurrent mark sweep GC freed 27385(2MB) AllocSpace objects, 11(2MB) LOS objects, 24% free, 23MB/30MB, paused 3.018ms total 156.203ms
06-02 10:01:17.850  4526  4526 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
06-02 10:01:17.853  1488  1488 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(274): Wear auto uninstall disabled for package com.test.thalitest
06-02 10:01:17.864  1615  1615 E NetworkScheduler.SR: Invalid parameter app
06-02 10:01:17.864  1615  1615 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-02 10:01:17.869  1544  4549 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-02 10:01:17.869  1544  4549 D AccountUtils: Clearing selected account for com.test.thalitest
06-02 10:01:17.876   763   763 W ResourcesManager: Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
06-02 10:01:17.878  1544  4549 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
06-02 10:01:17.904  1544  4549 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-02 10:01:17.908   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-02 10:01:17.908   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-02 10:01:17.910   763  1253 I ActivityManager: Delay finish: com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
06-02 10:01:17.913   763   854 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4295 uid 10049
06-02 10:01:17.924   763   778 I ActivityManager: Resuming delayed broadcast
06-02 10:01:17.928  1544  4557 D gH_CompatibleDatabase: Open jvg@1bf3aa0f, release reference: 1
06-02 10:01:17.938  1544  4557 D gH_CompatibleDatabase: Acquire reference of jvg@1bf3aa0f: 2
06-02 10:01:17.938  1544  4557 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-02 10:01:17.938  1544  4557 D gH_CompatibleDatabase: Release reference of jvg@1bf3aa0f: 1
06-02 10:01:17.938  1544  4557 D gH_CompatibleDatabase: Open jvg@3b2a2a9c, release reference: 1
06-02 10:01:17.939  1227  1227 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-02 10:01:17.945  1544  4557 D gH_CompatibleDatabase: Acquire reference of jvg@3b2a2a9c: 2
06-02 10:01:17.945   763   778 I ActivityManager: Start proc 4558:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
06-02 10:01:17.947  1544  4557 D gH_CompatibleDatabase: Release reference of jvg@3b2a2a9c: 1
06-02 10:01:17.947  1544  4557 D gH_CompatibleDatabase: Open jvg@1a97dca5, release reference: 1
06-02 10:01:17.949  1544  4557 D gH_CompatibleDatabase: Acquire reference of jvg@1a97dca5: 2
06-02 10:01:17.950  1544  4557 D gH_CompatibleDatabase: Release reference of jvg@1a97dca5: 1
06-02 10:01:17.950  1544  4557 D gH_CompatibleDatabase: Close jvg@1bf3aa0f, release reference: 0
06-02 10:01:17.950  1544  4557 D gH_CompatibleDatabase: Close jvg@3b2a2a9c, release reference: 0
06-02 10:01:17.950  1544  4557 D gH_CompatibleDatabase: Close jvg@1a97dca5, release reference: 0
06-02 10:01:17.967  1544  2274 I Icing   : doRemovePackageData com.test.thalitest
06-02 10:01:17.970  1544  4576 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
06-02 10:01:18.001   763   838 I art     : Explicit concurrent mark sweep GC freed 19458(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 10.265ms total 176.713ms
06-02 10:01:18.033  1544  4581 W IcingInternalCorpora: getNumBytesRead when not calculated.
06-02 10:01:18.037  1227  1450 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-02 10:01:18.071  4494  4494 I art     : System.exit called, status: 0
06-02 10:01:18.071  4494  4494 I AndroidRuntime: VM exiting with result code 0.
06-02 10:01:18.103   763   838 I ActivityManager: Start proc 4583:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
06-02 10:01:18.110   199   199 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 207us total 9.400ms
06-02 10:01:18.123   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 227us total 11.039ms
06-02 10:01:18.133   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 228us total 9.868ms
06-02 10:01:18.136   763   854 I ActivityManager: Killing 4098:com.google.android.apps.magazines/u0a56 (adj 15): empty for 1800s
06-02 10:01:18.147   763  1253 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3932bc41)
06-02 10:01:18.147   763   866 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 10:01:18.148   763   866 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-02 10:01:18.233  4558  4606 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
06-02 10:01:18.233  4558  4606 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-02 10:01:18.233  4558  4606 I GAv4    :   adb logcat -s GAv4
06-02 10:01:18.242  4558  4606 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
06-02 10:01:18.249  4558  4606 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
06-02 10:01:18.249  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-02 10:01:18.249  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-02 10:01:18.252  4558  4612 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
06-02 10:01:18.252  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at hqb$a.getWritableDatabase(Unknown Source)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at hqb.m(Unknown Source)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at hqb.a(Unknown Source)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at hqb.k(Unknown Source)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at hqg.run(Unknown Source)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-02 10:01:18.258  4558  4612 E SQLiteDatabase: 	at izp$c.run(Unknown Source)
06-02 10:01:18.258  4558  4612 E GAv4    : Opening the database failed, dropping the table and recreating it
06-02 10:01:18.258  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at hqb$a.getWritableDatabase(Unknown Source)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at hqb.m(Unknown Source)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at hqb.a(Unknown Source)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at hqb.k(Unknown Source)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at hqg.run(Unknown Source)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-02 10:01:18.259  4558  4612 E SQLiteDatabase: 	at izp$c.run(Unknown Source)
06-02 10:01:18.259  4558  4612 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-02 10:01:18.259  4558  4612 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-02 10:01:18.259  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-02 10:01:18.259  4558  4612 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-02 10:01:18.260  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
06-02 10:01:18.260  4558  4611 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak

```
