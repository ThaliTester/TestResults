#### Test 721454313afe4e8_thali07_LGE-LG-H815 Logs


```
--------- beginning of main
06-06 13:16:47.226   589   589 I MSM-irqbalance: Decided to move IRQ48 from CPU1 to CPU0
,06-06 13:16:47.456  9625  9625 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-06 13:16:47.456  9625  9625 D AndroidRuntime: CheckJNI is OFF
06-06 13:16:47.746  9625  9625 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-06 13:16:47.756  1277  4107 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-06 13:16:47.766  4025  4044 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
06-06 13:16:47.766  1277  4107 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0x0/ state=NATIVE]
06-06 13:16:47.766  1277  4107 D ActivityManager: setTaskToReturnTo : TaskRecord{1cdda613 #59 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-06 13:16:47.766  1277  4107 D ActivityManager: setTaskToReturnTo : TaskRecord{1cdda613 #59 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-06 13:16:47.766  1277  4107 D WindowStateEx: AppWindowTokenEx init.. 
06-06 13:16:47.766  1277  4107 V WindowManager: addAppToken: AppWindowToken{2cf7874e token=Token{3eb2a249 ActivityRecord{18abb050 u0 com.test.thalitest/.MainActivity t59}}} to stack=1 task=59 at 0
06-06 13:16:47.786  1277  4107 I ActivityManager: Start proc 9645:com.test.thalitest/u0a94 for activity com.test.thalitest/.MainActivity
06-06 13:16:47.786  1277  4107 D InputDispatcher: Focus left window: Window{e7aec65 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-06 13:16:47.786  9625  9625 D AndroidRuntime: Shutting down VM
06-06 13:16:47.786  4278  4278 I [LGHome]EVENT: [Launcher.java:5453:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
06-06 13:16:47.786  4278  4278 I [LGHome]EVENT: [Launcher.java:5479:setEnableShakeHandlers()]disableShakeHandlers
06-06 13:16:47.796  1277  1277 V ActivityManager: Display changed displayId=0
06-06 13:16:47.806  4078  4078 D DSDPConnection: Display #0 changed.
06-06 13:16:47.816  4025  4044 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
06-06 13:16:47.816  4025  4044 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3d327f8c co.....MainActivity}, taskId=59, activityType=0, bIsSplit=false
06-06 13:16:47.816  9068  9085 I EodDetector[v16]: Charging : changeTopActivity
06-06 13:16:47.816  4025  4735 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
06-06 13:16:47.816  4025  4735 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23a526d5 co.....MainActivity}, taskId=59, activityType=0, bIsSplit=false
06-06 13:16:47.816  9068  9085 I EodDetector[v16]: com.lge.launcher2 is not target app
06-06 13:16:47.816  7095  7115 D AppInfoDao: topacitivyt exist app = com.test.thalitest
06-06 13:16:47.826  7095  7115 D AppInfoDao: topacitivyt update app = com.test.thalitest time = 2016-06-06 13:16 date = 20160606
06-06 13:16:47.826  9645  9645 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-06 13:16:47.846  4173  4173 D ActionManagerService: notifyUserLog: 1000004
06-06 13:16:47.846  7068  7144 D LIA_SmartMoment_ActionManagerMessageHandler: [ActionManagerHandler] handleMessage: what(1000) actionID(0x1000004)
06-06 13:16:47.846  7068  7144 D LIA_SmartMoment_ActionManagerMessageHandler: [ActionManagerHandler] handleEvent
06-06 13:16:47.856  9645  9645 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
06-06 13:16:47.876  9645  9645 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7325-7326)
06-06 13:16:47.876  9645  9645 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-06 13:16:47.886  9645  9645 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c56acaa}
06-06 13:16:47.886  9645  9645 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-06 13:16:47.886  9645  9645 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-06 13:16:47.896  9645  9645 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-06 13:16:47.896  9645  9645 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-06 13:16:47.896  9645  9645 E SysUtils: ApplicationContext is null in ApplicationStatus
06-06 13:16:47.896  9645  9670 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-06 13:16:47.906  9645  9645 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-06 13:16:47.916  9645  9645 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-06 13:16:47.916  9645  9645 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-06 13:16:47.916  9645  9645 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:16:47.916  9645  9645 I Adreno  : Build Date                       : 07/03/15
06-06 13:16:47.916  9645  9645 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:16:47.916  9645  9645 I Adreno  : Local Branch                     : 
06-06 13:16:47.916  9645  9645 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:16:47.916  9645  9645 I Adreno  : Remote Branch                    : NONE
06-06 13:16:47.916  9645  9645 I Adreno  : Reconstruct Branch               : NOTHING
06-06 13:16:47.946   483  3210 V AudioPolicyService: registerClient() client 0xf2595740, uid 10094
06-06 13:16:47.956  1277  1358 D BluetoothManagerService: Message: 20
06-06 13:16:47.956  1277  1358 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d061e67:true
06-06 13:16:47.956  9645  9681 D BluetoothAdapter: 332106615: getState() :  mService = null. Returning STATE_OFF
06-06 13:16:47.986  9645  9645 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-06 13:16:47.986  9645  9645 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-06 13:16:47.996  9645  9645 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-06 13:16:47.996  9645  9645 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xff000000
06-06 13:16:47.996  9645  9645 I PhoneWindow: [setNavigationBarColor2] color=0x ff000000
,06-06 13:16:47.996  9645  9645 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,06-06 13:16:48.006  9645  9645 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-06 13:16:48.006  9645  9645 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-06 13:16:48.026  9645  9645 I Activity: Activity.onPostResume() called 
,06-06 13:16:48.026  9645  9693 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-06 13:16:48.026  1277  1295 D SplitWindow: check instance of lgWin Window{2ebd6f57 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,06-06 13:16:48.026  1277  1295 V WindowManager: Adding window Window{2ebd6f57 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 10 (after Window{e7aec65 u0 com.lge.launcher2/com.lge.launcher2.Launcher})
,06-06 13:16:48.036  9645  9679 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-06 13:16:48.046  9645  9693 I OpenGLRenderer: Initialized EGL, version 1.4
,06-06 13:16:48.056  1277  1357 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xff000000
06-06 13:16:48.056  1277  1357 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,06-06 13:16:48.056  3340  3340 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xff000000)
06-06 13:16:48.056  3340  3340 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> WHITE)
06-06 13:16:48.056  3340  3340 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=BLACK, LightBackground=false (NOT Transparent)
06-06 13:16:48.056  3340  3340 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
,06-06 13:16:48.056  1277  1357 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d3dbf4b,  pkg=Window{2ebd6f57 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-06 13:16:48.056  1277  1357 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-06 13:16:48.056  1277  1357 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-06 13:16:48.056  1277  1357 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-06 13:16:48.056  1277  1357 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=Window{2ebd6f57 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,06-06 13:16:48.056  1277  3374 D InputDispatcher: Focus entered window: Window{2ebd6f57 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,06-06 13:16:48.056  9645  9693 D OpenGLRenderer: Enabling debug mode 0
,06-06 13:16:48.096  9645  9645 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-06 13:16:48.096  9645  9645 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,06-06 13:16:48.096  3617  3617 E b       : Unable to connect to the editor to retrieve text... will retry later
,06-06 13:16:48.096  9645  9645 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9645
,06-06 13:16:48.106  1277  1359 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +292ms (total +2m39s233ms)
06-06 13:16:48.106  1277  1359 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18abb050 u0 com.test.thalitest/.MainActivity t59} time:197550
,06-06 13:16:48.116  9645  9645 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
06-06 13:16:48.116  9645  9645 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16467c03 time:197564
,06-06 13:16:48.146  9645  9645 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-06 13:16:48.226  9645  9694 D jxcore_app_log: JniHelper::setJavaVM(0xf4c9d200), pthread_self() = -429590400
,06-06 13:16:48.226  9645  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-06 13:16:48.226  9645  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-06 13:16:48.226  9645  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-06 13:16:48.226  9645  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-06 13:16:48.226  9645  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-06 13:16:48.226  9645  9694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4e1444 added. We now have 1 listener(s)
,06-06 13:16:48.226  1277  4172 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,06-06 13:16:48.236  9645  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:3C:51
,06-06 13:16:48.236  9645  9694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:3C:51"
06-06 13:16:48.236  9645  9694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-06 13:16:48.236  9645  9694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:3C:51
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-06 13:16:48.236  9645  9694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@264e6bf3 added. We now have 1 listener(s)
06-06 13:16:48.236  9645  9694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-06 13:16:48.236  9645  9694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-06 13:16:48.236  9645  9694 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-06 13:16:48.236  9645  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-06 13:16:48.236  9645  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-06 13:16:48.236  9645  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-06 13:16:48.236  9645  9694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-06 13:16:48.246  9645  9694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-06 13:16:48.246  1277  3645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-06 13:16:48.246  9645  9694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:3C:51
,06-06 13:16:48.246  9645  9694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-06 13:16:48.246  9645  9694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-06 13:16:48.246  9645  9694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-06 13:16:48.246  9645  9694 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-06 13:16:48.246  9645  9694 I io.jxcore.node.LifeCycleMonitor: start: OK
06-06 13:16:48.246  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-06 13:16:48.256  9645  9645 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-06 13:16:48.456  9645  9700 W jxcore-log: Initializing JXcore engine
06-06 13:16:48.456  9645  9700 W jxcore-log: JXcore engine is ready
,06-06 13:16:48.496  9645  9700 W jxcore-log: Starting JXcore engine
,06-06 13:16:48.546  9645  9700 W jxcore-log: Platform android
06-06 13:16:48.546  9645  9700 W jxcore-log: 
06-06 13:16:48.546  9645  9700 W jxcore-log: Process ARCH arm
06-06 13:16:48.546  9645  9700 W jxcore-log: 
,06-06 13:16:48.636  9645  9700 I jxcore-log: JXcore Cordova bridge is ready!
06-06 13:16:48.636  9645  9700 I jxcore-log: 
,06-06 13:16:48.636  9645  9700 W jxcore-log: JXcore engine is started
06-06 13:16:48.636  9645  9694 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-06 13:16:48.636  9645  9645 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-06 13:16:50.636  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:16:50.636  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:16:50.636  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 200081797944; DSPS: 6723741; Offset : -5110493002
,06-06 13:16:56.156  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-06 13:16:56.156  9645  9700 I jxcore-log: 
,06-06 13:16:56.166  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-06 13:16:56.166  9645  9700 I jxcore-log: 
,06-06 13:16:56.166  9645  9700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-06 13:16:56.166  9645  9700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-06 13:16:56.166  9645  9700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-06 13:16:56.166  9645  9700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-06 13:16:56.166  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-06 13:16:56.166  9645  9700 I jxcore-log: 
,06-06 13:16:56.166  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-06 13:16:56.166  9645  9700 I jxcore-log: 
,06-06 13:16:56.426  9645  9700 I jxcore-log: Unit Test app is loaded
06-06 13:16:56.426  9645  9700 I jxcore-log: 
,06-06 13:16:56.426  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-06 13:16:56.426  9645  9700 I jxcore-log: 
,06-06 13:16:56.436  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:56.436  1277  4171 D WifiServiceImplEx: setWifiEnabled: true pid=9645, uid=10094, package= com.test.thalitest, App Lable : ThaliTest
,06-06 13:16:56.446  9645  9645 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
06-06 13:16:56.446  1277  4171 D WifiServerServiceExt: ==========sendToastMessageId=================
,06-06 13:16:56.456  1277  4171 D WifiService: setWifiEnabled: true pid=9645, uid=10094
,06-06 13:16:56.476  1277  3195 D FastDownloadService: [FastDN][FDS] handleMessage: EVENT_WIFI_SETTING_CHANGED
,06-06 13:16:56.476  1277  3195 D FastDownloadService: [FastDN][FDS] wifi setting is changed to true
,06-06 13:16:56.476  1277  3188 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,06-06 13:16:56.486  1277  4149 D WifiServiceImplEx: disconnect pid=9645, uid=10094, packageName=com.test.thalitest
,06-06 13:16:56.486  1277  1295 D WifiServiceImplEx: reconnect pid=9645, uid=10094, packageName=com.test.thalitest
,06-06 13:16:56.486  1277  3188 E WifiHW  : Wifi MAC Address = a0:39:f7:6f:c9:5d
06-06 13:16:56.486  1277  3188 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:6f:c9:5d
06-06 13:16:56.486  1277  3188 E WifiHW  : ": cur_etheraddr=a0:39:f7:6f:c9:5d
,06-06 13:16:56.486  1277  4151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-06 13:16:56.486  1277  4151 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
06-06 13:16:56.486  1277  4151 D BluetoothManagerService: [CHAN] enable(): callingPackage = com.test.thalitest   callingUid = 10094
06-06 13:16:56.486  1277  9703 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-06 13:16:56.486   477  1253 D SoftapController: Softap fwReload - Ok
,06-06 13:16:56.496  1277  1277 D Atlas   : Validating map...
,06-06 13:16:56.496  1277  3188 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:16:56.496  1277  3188 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:16:56.496   477  1253 D CommandListener: Setting iface cfg
06-06 13:16:56.496   477  1253 D CommandListener: Trying to bring down wlan0
06-06 13:16:56.496  1277  1277 D SplitWindow: check instance of lgWin Window{3222dc47 u0 Toast}
,06-06 13:16:56.496  1277  1358 D BluetoothManagerService: Message: 1
06-06 13:16:56.496  1277  1358 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-06 13:16:56.496   477  1253 D CommandListener: Clearing all IP addresses on wlan0
06-06 13:16:56.496  1277  1277 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-06 13:16:56.496  1277  1277 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-06 13:16:56.496  1277  1277 D Ulp_jni : JNI:system_update. Event-4
,06-06 13:16:56.506  4464  4464 D BluetoothAdapterService(264956278): onBind()
06-06 13:16:56.506  1277  3188 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,06-06 13:16:56.506  1277  3188 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,06-06 13:16:56.506  9645  9700 I jxcore-log: My device name is: LGE-LG-H815
06-06 13:16:56.506  9645  9700 I jxcore-log: 
,06-06 13:16:56.506  9645  9700 I jxcore-log: WARN testUtils: myNameCallback not set!
06-06 13:16:56.506  9645  9700 I jxcore-log: 
,06-06 13:16:56.526  1277  9703 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:16:56.526  1277  9703 I Adreno  : Build Date                       : 07/03/15
06-06 13:16:56.526  1277  9703 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:16:56.526  1277  9703 I Adreno  : Local Branch                     : 
06-06 13:16:56.526  1277  9703 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:16:56.526  1277  9703 I Adreno  : Remote Branch                    : NONE
06-06 13:16:56.526  1277  9703 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:16:56.536  9704  9704 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-06 13:16:56.546  1277  9703 I OpenGLRenderer: Initialized EGL, version 1.4
,06-06 13:16:56.546  1277  1277 D PowerManagerServiceEx: acquireWakeLockInternal: lock=564590051, flags=0x2000000a, tag="WindowManager", ws=WorkSource{1000}, historyTag=null, uid=1000, pid=1277
,06-06 13:16:56.556  1277  9703 D OpenGLRenderer: Enabling debug mode 0
,06-06 13:16:56.556  1277  1277 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,06-06 13:16:56.556  1277  1358 D BluetoothManagerService: Message: 40
06-06 13:16:56.556  1277  1358 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,06-06 13:16:56.566  4464  4484 I bluedroid: config_hci_snoop_log
,06-06 13:16:56.566  1277  1358 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-06 13:16:56.566  1277  1358 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,06-06 13:16:56.566  9704  9704 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-06 13:16:56.566  9704  9704 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,06-06 13:16:56.576  4464  4491 V LGMDMManagerInternal: Create singleton instance
,06-06 13:16:56.596  1277  1277 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-06 13:16:56.596  1277  1277 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-06 13:16:56.596  1277  1277 D Ulp_jni : JNI:system_update. Event-4
,06-06 13:16:56.606  1277  3188 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-06 13:16:56.606  4464  4491 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:56.606  4464  4491 D BluetoothAdapterService(264956278): enable() - Enable called with quiet mode status =  false
06-06 13:16:56.606  4025  4025 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
06-06 13:16:56.606  4464  4682 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-06 13:16:56.606  4464  4682 D BluetoothAdapterProperties: Setting state to 11
06-06 13:16:56.606  4464  4682 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-06 13:16:56.606  4464  4682 D BluetoothAdapterService(264956278): updateAdapterState() - Broadcasting state to 1 receivers.
06-06 13:16:56.606  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
06-06 13:16:56.606  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-06 13:16:56.606  1277  1358 D BluetoothManagerService: Message: 60
06-06 13:16:56.606  1277  1358 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
06-06 13:16:56.606  1277  1358 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-06 13:16:56.606  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-06 13:16:56.616  4464  4682 D BluetoothAdapterService(264956278): processStart()
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,06-06 13:16:56.616  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,06-06 13:16:56.616  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,06-06 13:16:56.626  4464  4682 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService,
06-06 13:16:56.626  4464  4682 D BluetoothAdapterService(264956278): processStart() - Make Bond State Machine
06-06 13:16:56.626  4464  4682 D BluetoothBondStateMachine: make
,06-06 13:16:56.626  4464  4682 D BluetoothAdapterService: setAdapterService() - set to: null
06-06 13:16:56.626  4464  9706 I BluetoothBondStateMachine: StableState(): Entering Off State
06-06 13:16:56.626  4464  4682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:56.626  4464  4682 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,06-06 13:16:56.626  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.636  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
06-06 13:16:56.636  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-06 13:16:56.636  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-06 13:16:56.636  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,06-06 13:16:56.646  1277  1317 I ActivityManager: Start proc 9707:com.lge.ia.task.smartsetting/u0a21 for broadcast com.lge.ia.task.smartsetting/.detector.ContextDetector
,06-06 13:16:56.646  1277  1277 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,06-06 13:16:56.646  4025  4025 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,06-06 13:16:56.656  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:56.656  4025  4025 D BleQmManagerService: [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
,06-06 13:16:56.656  4464  4491 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:56.656  4464  4464 D HeadsetService: Received start request. Starting profile...
,06-06 13:16:56.656  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.656  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
06-06 13:16:56.656  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-06 13:16:56.656  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-06 13:16:56.656  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,06-06 13:16:56.666  4464  4464 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-06 13:16:56.666  4464  4464 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-06 13:16:56.676  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-06 13:16:56.676  3340  3340 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,06-06 13:16:56.676  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.676  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
06-06 13:16:56.676  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-06 13:16:56.676  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-06 13:16:56.676  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
,06-06 13:16:56.676  4464  4464 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-06 13:16:56.676  4464  4464 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-06 13:16:56.676  4464  4464 D HeadsetStateMachine: make
,06-06 13:16:56.686  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.686  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
06-06 13:16:56.686  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-06 13:16:56.686  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-06 13:16:56.686  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
,06-06 13:16:56.696  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.696  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
06-06 13:16:56.696  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-06 13:16:56.696  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
06-06 13:16:56.696  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
,06-06 13:16:56.706  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.716  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
06-06 13:16:56.716  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-06 13:16:56.716  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
06-06 13:16:56.716  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
,06-06 13:16:56.716  4464  4464 D HeadsetStateMachine: max_hf_connections = 2
06-06 13:16:56.716  4464  4464 I bluedroid: get_profile_interface handsfree
06-06 13:16:56.716  4464  4464 I bt-btif : btif_hf_get_interface
06-06 13:16:56.716  4464  4464 I bt-btif : init
06-06 13:16:56.716  4464  4464 D bt-btif : max_hf_clients = 2
06-06 13:16:56.716  4464  4464 D bt-btif : btif_max_hf_clients = 2
06-06 13:16:56.716  4464  4464 D bt-btif : btif_enable_service: current services:0xdde7e348
,06-06 13:16:56.716  4464  4464 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,06-06 13:16:56.716   483  5582 V AudioPolicyService: registerClient() client 0xf2555400, uid 1002
06-06 13:16:56.716   483  5582 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-06 13:16:56.716   483  5582 V AudioPolicyManagerEx: getOutput() returns output 2
,06-06 13:16:56.716   483   483 V AudioFlinger: registerClient() client 0xf5e15f28, pid 4464
06-06 13:16:56.716   483   483 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-06 13:16:56.716   483   483 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-06 13:16:56.716   483   483 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-06 13:16:56.716   483  3203 V AudioFlinger: thread 0xf5fab000 type 0 TID 3203 waking up
06-06 13:16:56.716   483  3204 V AudioFlinger: thread 0xf2447000 type 0 TID 3204 waking up
06-06 13:16:56.716   483  3206 V AudioFlinger: thread 0xf2491000 type 0 TID 3206 waking up
06-06 13:16:56.716  4464  4464 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-06 13:16:56.716   483  3203 V AudioFlinger: processConfigEvents_l() remaining events 1
06-06 13:16:56.716   483  3203 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xf5fab000, event 0, param 0
06-06 13:16:56.716   483  3203 V audio_hw_primary: out_get_latency: Latency 10
06-06 13:16:56.716   483  3203 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-06 13:16:56.716   483  3203 V AudioFlinger: processConfigEvents_l() DONE thread 0xf5fab000
06-06 13:16:56.716  4464  4464 V ToneGenerator: Create Track: 0xf4d1e200
06-06 13:16:56.716  4464  9713 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-06 13:16:56.716  4464  4464 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-06 13:16:56.716  1277  3751 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-06 13:16:56.726  4492  4519 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-06 13:16:56.726  4078  4103 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-06 13:16:56.726   483  3204 V AudioFlinger: processConfigEvents_l() remaining events 1
06-06 13:16:56.726   483  3204 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xf2447000, event 0, param 0
06-06 13:16:56.726   483  3204 V audio_hw_primary: out_get_latency: Latency 100
06-06 13:16:56.726   483  3204 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-06 13:16:56.726   483  3204 V AudioFlinger: processConfigEvents_l() DONE thread 0xf2447000
06-06 13:16:56.726  4464  4484 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 100
06-06 13:16:56.726  4492  7202 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-06 13:16:56.726  1277  4128 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-06 13:16:56.726  3340  3366 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-06 13:16:56.726  3340  3366 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-06 13:16:56.726  4078  4105 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-06 13:16:56.726   483  3206 V AudioFlinger: processConfigEvents_l() remaining events 1
06-06 13:16:56.726   483  3206 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xf2491000, event 0, param 0
06-06 13:16:56.726   483  3206 V audio_hw_primary: out_get_latency: Latency 64
06-06 13:16:56.726   483  3206 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-06 13:16:56.726   483  3206 V AudioFlinger: processConfigEvents_l() DONE thread 0xf2491000
06-06 13:16:56.726  4078  5366 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-06 13:16:56.726  4464  9713 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
06-06 13:16:56.726  4492  4516 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-06 13:16:56.726  1277  3374 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-06 13:16:56.726   483  5582 I AudioFlinger: isAudioPlaybackHookOn(,) false
06-06 13:16:56.726  4464  4464 D AudioTrack: createTrack_l()... isAudioHookOn = 0, mStreamType = 8
06-06 13:16:56.726  4464  4464 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
06-06 13:16:56.726  3340  5303 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-06 13:16:56.726   483  3210 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-06 13:16:56.726   483  3210 V AudioPolicyManager: getOutputForAttr() device 0x2, samplingRate 48000, format 1, channelMask 1, flags 4
06-06 13:16:56.726   483  3210 V AudioPolicyManagerEx: getOutput() returns output 2
06-06 13:16:56.726  4464  4464 V AudioSystem: getLatency() output 2, latency 50
06-06 13:16:56.726  4464  4464 V AudioSystem: getFrameCount() output 2, frameCount 960
06-06 13:16:56.726  4464  4464 V AudioTrack: createTrack_l() output 2 afLatency 50
06-06 13:16:56.726  4464  4464 V AudioTrack: Create normal PCM 0x1 Track
06-06 13:16:56.726   483  5582 V AudioFlinger: createTrack() lSessionId: 18
06-06 13:16:56.726   483  5582 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
06-06 13:16:56.726   483  5582 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
06-06 13:16:56.726  4464  4464 V AudioTrack: Flags here  0x4 
06-06 13:16:56.726  4464  4464 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-06 13:16:56.726  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.726  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
06-06 13:16:56.726  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-06 13:16:56.726  4464  4682 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
06-06 13:16:56.726   483  3210 V AudioFlinger: acquiring 18 from 4464, for 4464
06-06 13:16:56.726  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
06-06 13:16:56.726   483  3210 V AudioFlinger:  added new entry for 18
06-06 13:16:56.726  4464  4464 V ToneGenerator: ToneGenerator INIT OK, time: 206176
06-06 13:16:56.726  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:56.726  4464  9725 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-06 13:16:56.726   483  3203 V AudioFlinger: processConfigEvents_l() remaining events 1
06-06 13:16:56.726   483  3203 V AudioFlinger: processConfigEvents_l() DONE thread 0xf5fab000
06-06 13:16:56.726  4464  9725 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-06 13:16:56.736  4464  9725 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-06 13:16:56.736  4464  9725 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-06 13:16:56.736   483   483 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 4464
06-06 13:16:56.736  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:56.736   483   483 V SRS_Proc: ParamSet string: bt_samplerate=8000
06-06 13:16:56.736   483   483 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-06 13:16:56.736   483   483 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-06 13:16:56.736   483   483 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-06 13:16:56.736   483   483 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-06 13:16:56.736   483   483 V voice   : voice_set_parameters: exit with code(0)
06-06 13:16:56.736   483   483 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-06 13:16:56.736   483   483 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-06 13:16:56.736   483   483 V msm8974_platform: platform_set_parameters: exit with code(0)
06-06 13:16:56.736   483   483 V platform_param: lge_platform_factory_set_parameters: enter: bt_samplerate=8000
06-06 13:16:56.736   483   483 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-06 13:16:56.736   483   483 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-06 13:16:56.736  4464  9725 V ToneGenerator: ToneGenerator destructor
06-06 13:16:56.736  4464  9725 V ToneGenerator: stopTone
06-06 13:16:56.736  4464  9725 V ToneGenerator: Delete Track: 0xf4d1e200
06-06 13:16:56.736  4464  9725 V AudioTrack: ~AudioTrack, releasing session id from 4464 on behalf of 4464
06-06 13:16:56.736   483  3211 V AudioFlinger: remove track (4097) and delete from mixer
06-06 13:16:56.736   483  3211 V AudioPolicyService: AudioCommandThread() adding release output 2
06-06 13:16:56.736   483  3211 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-06 13:16:56.736   483  3211 V AudioFlinger: PlaybackThread::Track destructor
06-06 13:16:56.736   483  3211 V AudioFlinger: removeClient_l() pid 4464, calling pid 483
06-06 13:16:56.736   483  3076 V AudioPolicyService: AudioCommandThread() processing release output 2
06-06 13:16:56.736   483  3076 V AudioPolicyManager: releaseOutput() 2
06-06 13:16:56.736   483  3211 V AudioFlinger: releasing 18 from 4464 for 4464
06-06 13:16:56.736   483  3211 V AudioFlinger:  decremented refcount to 0
06-06 13:16:56.736   483  3211 V AudioFlinger: purging stale effects
06-06 13:16:56.736  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.736  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
06-06 13:16:56.736  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-06 13:16:56.736  4464  4682 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-06 13:16:56.736  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
06-06 13:16:56.736  4464  4464 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-06 13:16:56.736  4464  4464 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:56.736  4464  4464 V BluetoothPbapReceiver: ***********state = 11
06-06 13:16:56.746  9707  9707 V LIA_AppRecommendContentProvider: MrGContentProvider onCreate()
06-06 13:16:56.746  5117  5673 I art     : Explicit concurrent mark sweep GC freed 65415(3MB) AllocSpace objects, 14(280KB) LOS objects, 46% free, 36MB/68MB, paused 1.031ms total 95.838ms
06-06 13:16:56.746  4464  4682 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-06 13:16:56.746  4464  4682 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
06-06 13:16:56.746  4464  4682 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-06 13:16:56.746  4464  4682 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
06-06 13:16:56.746  4464  4682 D BluetoothAdapterService(264956278): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
,06-06 13:16:56.786  1277  4216 I ActivityManager: Start proc 9730:com.android.settings/1000 for broadcast com.lge.bluetoothsetting/.DockEventReceiver
06-06 13:16:56.786  1277  1277 D BluetoothA2dp: Proxy object connected
06-06 13:16:56.786  4464  4682 V LGMDMManager: Create singleton instance
06-06 13:16:56.786  4464  4464 D A2dpService: Received start request. Starting profile...
06-06 13:16:56.786  4689  4689 D BluetoothA2dp: Proxy object connected
06-06 13:16:56.796  4464  4464 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-06 13:16:56.796  4464  4464 V Avrcp   : make
06-06 13:16:56.796  4464  4682 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
06-06 13:16:56.796  4464  4464 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-06 13:16:56.796  4464  4464 I bluedroid: get_profile_interface avrcp
06-06 13:16:56.796  4464  4464 I bt-btif : btif_rc_get_interface
06-06 13:16:56.796  4464  4464 I bt-btif : ## init ##
06-06 13:16:56.796  9707  9707 I LIA_SmartSetting(4.50.6)_LogCore: LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
06-06 13:16:56.796  9707  9707 V LIA_SmartSetting(4.50.6)_ContextDetector: onReceive action android.net.wifi.WIFI_STATE_CHANGED
06-06 13:16:56.796  4464  4464 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
06-06 13:16:56.796  4464  4464 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-06 13:16:56.796  4464  4464 I LGBluetoothAvrcpServiceJni: initNative: succeeds
06-06 13:16:56.796  9707  9707 D LIA_SmartSetting(4.50.6)_WifiContextDetector: onReceive state= 2
06-06 13:16:56.796  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: recipeSlug= arrive_home_wifi
06-06 13:16:56.796  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
06-06 13:16:56.796  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: selection= recipe_slug = "arrive_home_wifi"
06-06 13:16:56.796  4464  4464 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
06-06 13:16:56.796  4464  4491 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:56.806  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: status= 0
06-06 13:16:56.806  9707  9707 D LIA_SmartSetting(4.50.6)_ContextDetector: onUpdate Wi-Fi on
,06-06 13:16:56.806  4464  4464 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
,06-06 13:16:56.816  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: onStatusChanged value= Wi-Fi on
,06-06 13:16:56.816  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: is not interactive
,06-06 13:16:56.816  9707  9707 V LIA_SmartSetting(4.50.6)_DeviceLogger: DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1465211816820, , settingStatus=Wi-Fi on, deviceTypeOrdinal=0]
06-06 13:16:56.816  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter: insert start
,06-06 13:16:56.826  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManager: insertSettingInfo ID = 7767
,06-06 13:16:56.836  9730  9730 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-06 13:16:56.836  9730  9730 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-06 13:16:56.856  1277  4171 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
06-06 13:16:56.856  1277  4171 E AudioService: No RCC entry present to update
,06-06 13:16:56.856  4464  4464 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-06 13:16:56.856  4464  4464 I BluetoothA2dpServiceJni: classInitNative
06-06 13:16:56.856  4464  4464 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-06 13:16:56.856  4464  4464 D A2dpStateMachine: make
,06-06 13:16:56.856  9730  9730 D LGBluetoothSettingApp: REFCOUNT: Constructed com.lge.bluetoothsetting.LGBluetoothSettingApp@ffff5dc Instance Count = 1
,06-06 13:16:56.856  4464  4464 I bluedroid: get_profile_interface a2dp
06-06 13:16:56.856  4464  4464 I bt-btif : btif_av_get_src_interface
,06-06 13:16:56.856  4464  4464 I bt-btif : init
06-06 13:16:56.856  4464  4464 D bt-btif : btif_enable_service: current services:0xdde7e348
06-06 13:16:56.856  4464  4464 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-06 13:16:56.856  4464  4464 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-06 13:16:56.866  4464  4464 D LGBluetoothPowerControlManager: [BTUI] getInstance
06-06 13:16:56.866  9730  9730 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 845
06-06 13:16:56.866  9730  9730 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-06 13:16:56.866  9730  9730 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-06 13:16:56.866  4464  4464 D LGBluetoothPowerControlManager: [BTUI] init
06-06 13:16:56.866  9730  9730 W ResourcesManager: Asset path '/system/framework/lgsvcitems.jar' does not exist or contains no resources.
06-06 13:16:56.866  9730  9730 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-06 13:16:56.866  9730  9730 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-06 13:16:56.876  1277  3374 I ActivityManager: Start proc 9753:com.lge.formmanager/u0a49 for broadcast com.lge.formmanager/.FormServiceReceiver
,06-06 13:16:56.876  1277  3374 I ActivityManager: Killing 9242:com.lge.eula/u0a105 (adj 15): empty #22
,06-06 13:16:57.086  4464  4464 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
,06-06 13:16:57.086  1277  1358 D BluetoothManagerService: Message: 30
,06-06 13:16:57.096  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.096  4464  4464 D LGBluetoothDeviceModeControllManager: onServiceStarted - isSink : false mWaitingForService : false
06-06 13:16:57.096  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.096  4464  4464 I BluetoothHidServiceJni: classInitNative: succeeds
,06-06 13:16:57.096  4464  9752 D A2dpStateMachine: Enter Disconnected: -2
06-06 13:16:57.096  4464  4464 D HidService: Received start request. Starting profile...
06-06 13:16:57.096  4464  4464 I bluedroid: get_profile_interface hidhost
06-06 13:16:57.096  4464  4464 I bt-btif : btif_hh_get_interface
,06-06 13:16:57.096  4464  4464 I bt-btif : init
06-06 13:16:57.096  4464  4464 D bt-btif : btif_enable_service: current services:0xdde7e348
06-06 13:16:57.096  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
,06-06 13:16:57.096  4464  4464 I BluetoothHealthServiceJni: classInitNative: succeeds
,06-06 13:16:57.096  4464  4464 D HealthService: Received start request. Starting profile...
06-06 13:16:57.106  4464  4464 I bluedroid: get_profile_interface health
06-06 13:16:57.106  4464  4464 I bt-btif : btif_hl_get_interface
06-06 13:16:57.106  4464  4464 I bt-btif : init
,06-06 13:16:57.106  4464  4464 D bt-btif : Process name (droid.bluetooth)
06-06 13:16:57.106  4464  4464 D bt-btif : btif_hl_soc_thread_init
06-06 13:16:57.106  4464  4464 D bt-btif : create_thread: entered
06-06 13:16:57.106  4464  4464 D bt-btif : create_thread: thread created successfully
06-06 13:16:57.106  4464  9774 D bt-btif : entered btif_hl_select_thread
06-06 13:16:57.106  4464  9774 D bt-btif : btif_hl_select_wakeup_init
06-06 13:16:57.106  4464  4464 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-06 13:16:57.106  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.106  4464  9774 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=58 signal_fds[1]=59
06-06 13:16:57.106  4464  9774 D bt-btif : max_s=58 
06-06 13:16:57.106  4464  9774 D bt-btif : set curr_set = org_set 
,06-06 13:16:57.106  4464  4464 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,06-06 13:16:57.106  4464  4464 D PanService: Received start request. Starting profile...
06-06 13:16:57.106  4464  4464 D BluetoothPanServiceJni: initializeNative(L110): pan
06-06 13:16:57.106  4464  4464 I bluedroid: get_profile_interface pan
06-06 13:16:57.106  4464  4464 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
,06-06 13:16:57.116  9730  9730 D LGBluetoothSettingsSearchIndexablesProvider: onCreate()
06-06 13:16:57.116  4464  4464 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-06 13:16:57.116  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.116  4464  4464 D HeadsetStateMachine: Proxy object connected
06-06 13:16:57.116  4464  4464 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,06-06 13:16:57.116  4464  4464 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,06-06 13:16:57.126  4464  4464 D BtGatt.DebugUtils: handleDebugAction() action=null
,06-06 13:16:57.126  9730  9730 I IndexDatabaseHelper: Using schema version: 115
,06-06 13:16:57.126  4464  4464 D BtGatt.GattService: Received start request. Starting profile...
06-06 13:16:57.126  4464  4464 D BtGatt.GattService: start()
06-06 13:16:57.126  4464  4464 I bluedroid: get_profile_interface gatt
,06-06 13:16:57.126  9730  9730 I IndexDatabaseHelper: Index is fine
06-06 13:16:57.126  4464  4464 D BtGatt.AdvertiseManager: advertise manager created
,06-06 13:16:57.136  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.136  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.176  1277  3751 I ActivityManager: Start proc 9781:com.lge.wifisettings/1000 for broadcast com.lge.wifisettings/.wifioffload.WiFiOffLoadBroadcast
,06-06 13:16:57.176  9730  9730 D LGBluetoothSettingApp: onCreate
,06-06 13:16:57.176  1277  3645 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.176  9753  9779 W FormManager: Network not available. Please check & try again.
06-06 13:16:57.176  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.176  4464  4464 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
06-06 13:16:57.176  4464  4464 D LGBluetoothGattAdapter: setGattService:  set to: null
06-06 13:16:57.176  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.186  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.186  4464  4464 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-06 13:16:57.186  4464  4464 V BluetoothMapService: BluetoothMapBinder()
,06-06 13:16:57.186  4464  4464 D BluetoothMapService: Received start request. Starting profile...
06-06 13:16:57.186  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.186  4464  4464 D BluetoothMapService: start()
,06-06 13:16:57.186  1277  3374 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.186  9753  9780 V FormManager: Network unavailable.
06-06 13:16:57.186  4464  4464 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-06 13:16:57.186  4464  4464 D BluetoothMapEmailAppObserver: createReceiver()
06-06 13:16:57.186  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.186  9707  9707 I LIA_SmartSetting(4.50.6)_LogCore: LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
06-06 13:16:57.186  9707  9707 V LIA_SmartSetting(4.50.6)_ContextDetector: onReceive action android.bluetooth.adapter.action.STATE_CHANGED
,06-06 13:16:57.196  9707  9707 D LIA_SmartSetting(4.50.6)_BTContextDetector: onReceive state= 11
06-06 13:16:57.196  4464  4464 D BluetoothMapEmailAppObserver: initObservers()
06-06 13:16:57.196  4464  4464 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-06 13:16:57.196  9707  9707 W LIA_SmartSetting(4.50.6)_ContextDetector: setting value is undefined.
,06-06 13:16:57.196  1277  1295 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.196  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
,06-06 13:16:57.196  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.196  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.196  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-06 13:16:57.196  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.196  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.196  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.196  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.196  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-06 13:16:57.196  9753  9780 V FormManager: Network unavailable.
,06-06 13:16:57.206  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-06 13:16:57.206  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:16:57.206  4464  9725 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
06-06 13:16:57.206  4464  9725 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-06 13:16:57.206  4464  4464 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
,06-06 13:16:57.216  4464  4464 D SapService: Received start request. Starting profile...
06-06 13:16:57.216  4464  4464 D BluetoothSAPServiceJni: initializeNative(L175): sap
06-06 13:16:57.216  4464  4464 I bluedroid: get_profile_interface sap
06-06 13:16:57.216  4464  4464 I bt-btif : btif_sc_get_interface
,06-06 13:16:57.216  4464  4464 I bt-btif : init
06-06 13:16:57.216  1277  4149 I ActivityManager: Killing 9282:com.lge.NfcSettings/1000 (adj 15): empty #22
06-06 13:16:57.216  4464  4464 D bt-btif : btif_enable_service: current services:0xdde7e348
06-06 13:16:57.216  4464  4464 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
06-06 13:16:57.216  4464  4464 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
06-06 13:16:57.216  4464  4464 D LGBluetoothSapManager: [BTUI] initSapManager
,06-06 13:16:57.216  9730  9730 D LGBluetoothProfileConnectionReceiver_LGSettingsAPK: onReceive(), ConnectedDeviceName : null , Num : 0
06-06 13:16:57.216  9730  9730 D LGBluetoothProfileConnectionReceiver_LGSettingsAPK: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information - BluetoothSettings
,06-06 13:16:57.216  9781  9781 W ResourcesManager: Asset path '/system/framework/com.quicinc.cne.jar' does not exist or contains no resources.
06-06 13:16:57.216  9781  9781 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-06 13:16:57.216  9781  9781 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-06 13:16:57.226   589   589 I MSM-irqbalance: Decided to move IRQ256 from CPU2 to CPU0
,06-06 13:16:57.326  4078  4078 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
,06-06 13:16:57.326  1277  4149 I ActivityManager: Killing 9302:com.google.android.apps.docs/u0a118 (adj 15): empty #22
,06-06 13:16:57.336  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-06 13:16:57.366  9781  9781 D WiFiOffLoadUpdatePriority: remove : truetruefalse
,06-06 13:16:57.366  9781  9781 D WiFiOffLoadUpdatePriority: remove2
,06-06 13:16:57.366  9781  9781 V WiFiOffLoadSharedPrefsUtils: save wifi state
06-06 13:16:57.366  9781  9781 V WiFiOffLoadSharedPrefsUtils: save remove
06-06 13:16:57.366  9781  9781 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-06 13:16:57.366  9781  9781 D WiFiOffLoadBroadcast: S: false, R: true
,06-06 13:16:57.446  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.446  4464  4464 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-06 13:16:57.446  1277  4149 I ActivityManager: Killing 9340:com.lge.bnr/1000 (adj 15): empty #22
06-06 13:16:57.446  4464  4464 E BluetoothOPPServiceJni: classInitNative
,06-06 13:16:57.446  4464  4464 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
,06-06 13:16:57.446  4464  4464 V OppService: Opp initBinder
,06-06 13:16:57.446  4464  4464 D **OppService: Received start request. Starting profile...
06-06 13:16:57.446  4464  4464 D OppService: Starting OppService 
,06-06 13:16:57.446  4464  4464 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,06-06 13:16:57.456  4464  4464 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
,06-06 13:16:57.456  4464  4464 V BluetoothOppNotification: send message
,06-06 13:16:57.466  4464  4464 D BluetoothOppPreference: Dumping Names:  
06-06 13:16:57.466  4464  4464 D BluetoothOppPreference: {}
06-06 13:16:57.466  4464  4464 D BluetoothOppPreference: Dumping Channels:  
06-06 13:16:57.466  4464  4464 D BluetoothOppPreference: {}
,06-06 13:16:57.466  4464  4464 D OppService: Start()
06-06 13:16:57.466  4464  4464 W BluetoothOPPServiceJni: initOppNative
06-06 13:16:57.466  4464  4464 D BluetoothOPPServiceJni: initOppNative(L383): OPP
06-06 13:16:57.466  4464  4464 I bluedroid: get_profile_interface opp
06-06 13:16:57.466  4464  4464 I bt-btif : btif_op_get_interface
06-06 13:16:57.466  4464  4464 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 1051626
06-06 13:16:57.466  4464  4464 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
,06-06 13:16:57.476  4464  4464 I bt-btif : btif_opp_init
06-06 13:16:57.476  4464  4464 D bt-btif : btif_enable_service: current services:0xdde7e348
06-06 13:16:57.476  4464  4464 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
06-06 13:16:57.476  4464  4464 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 1051626
06-06 13:16:57.476  4464  4464 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@38fe6f3f
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:57.476  4464  9810 V OppService: pendingUpdate is :  true
06-06 13:16:57.476  4464  4464 D BluetoothA2dp: Proxy object connected
06-06 13:16:57.476  4464  4464 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@13f4c00c
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-06 13:16:57.476  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.476  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-06 13:16:57.476  4464  9810 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,06-06 13:16:57.476  4464  9807 V OppService: Deleted complete outbound shares, number =  0
06-06 13:16:57.476  4464  9810 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5f4c05b on behalf of 
,06-06 13:16:57.486  4464  9810 V BluetoothOppNotification: update too frequent, put in queue
06-06 13:16:57.486  4464  9807 V OppService: Deleted complete inbound failed shares, number = 0
,06-06 13:16:57.486  4464  9807 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-06 13:16:57.486  4464  9810 V OppService: pendingUpdate is :  false
06-06 13:16:57.486  4464  9810 E OppService: UpdateThread is Completed
06-06 13:16:57.486  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
,06-06 13:16:57.486  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
,06-06 13:16:57.486  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.486  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-06 13:16:57.486  4464  9807 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d33d0f8 on behalf of 
,06-06 13:16:57.486  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService,
06-06 13:16:57.486  4464  4464 V PanService: [BTUI] SIM Extra State :ABSENT
06-06 13:16:57.486  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.486  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.486  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.486  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
,06-06 13:16:57.486  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-06 13:16:57.496  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
,06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-06 13:16:57.496  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService,
06-06 13:16:57.496  4464  4464 V BluetoothMapService: Handler(): got msg=1
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.496  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-06 13:16:57.506  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
,06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-06 13:16:57.506  4464  4464 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-06 13:16:57.506  4464  4464 V BluetoothOppNotification: new notify threadi!
,06-06 13:16:57.506  4464  4464 V BluetoothOppNotification: send delay message
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 1
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isTurningOnRadio()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isTurningOffRadio()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-06 13:16:57.506  4464  4464 D BluetoothAdapterService(264956278): onProfileServiceStateChange() - All profile services started.
06-06 13:16:57.506  4464  4464 V OppService: ContentObserver received notification
06-06 13:16:57.506  4464  4682 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-06 13:16:57.506  4464  4682 I bluedroid: enable
06-06 13:16:57.506  4464  4464 V OppService: ContentObserver received notification
06-06 13:16:57.506  4464  9811 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-06 13:16:57.506  4464  9812 V OppService: pendingUpdate is :  true
06-06 13:16:57.506  4464  9812 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-06 13:16:57.506  4464  4682 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
06-06 13:16:57.506  4464  4682 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
06-06 13:16:57.506  4464  9813 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,06-06 13:16:57.506  4464  4682 I bt_hci_bdroid: init
06-06 13:16:57.506  4464  4682 I bt_vendor: init
06-06 13:16:57.506  4464  4682 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
06-06 13:16:57.506  4464  4682 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
06-06 13:16:57.506  4464  4682 D bt_vendor: op for 5
06-06 13:16:57.506  4464  9813 I bt-btu  : btu_task pending for preload complete event
06-06 13:16:57.506  4464  4682 I bt-btif : libbt-hci init returns 0
06-06 13:16:57.506  4464  4682 D bt_vendor: op for 0
,06-06 13:16:57.506  4464  4682 D bt_vendor: op for 0
06-06 13:16:57.506  4464  9811 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@308bb9d1 on behalf of 
,06-06 13:16:57.516  4464  9812 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6c1fc36 on behalf of 
06-06 13:16:57.516  4464  9811 V BluetoothOppNotification: mUpdateCompleteNotification = true
,06-06 13:16:57.516  4464  9811 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-06 13:16:57.516  4464  9812 V OppService: pendingUpdate is :  false
06-06 13:16:57.516  4464  9812 E OppService: UpdateThread is Completed
,06-06 13:16:57.516  4464  9811 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3350737 on behalf of 
,06-06 13:16:57.516  4464  9811 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-06 13:16:57.516  4464  9811 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-06 13:16:57.516  4464  9811 V BluetoothOppNotification: outbound notification was removed.
06-06 13:16:57.516  4464  9811 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,06-06 13:16:57.516  4464  9811 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@115104a4 on behalf of 
,06-06 13:16:57.516  4464  9811 V BluetoothOppNotification: inbound: succ-0  fail-0
,06-06 13:16:57.516  4464  9811 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,06-06 13:16:57.526  4464  9811 V BluetoothOppNotification: inbound notification was removed.
06-06 13:16:57.526  4464  9811 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,06-06 13:16:57.526  4464  9811 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9c1220d on behalf of 
,06-06 13:16:57.546   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:16:57.546   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.556  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  4464  4464 V BluetoothSapReceiver: [BTUI] checkServiceStart
,06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.566  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.586   477  1246 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-06 13:16:57.586   477  1246 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-06 13:16:57.586  1277  1356 D Tethering: interfaceLinkStateChanged wlan0, true
06-06 13:16:57.586  1277  1356 D Tethering: interfaceStatusChanged wlan0, true
06-06 13:16:57.586  1277  1356 D Tethering: interfaceLinkStateChanged wlan0, true
06-06 13:16:57.586  1277  1356 D Tethering: interfaceStatusChanged wlan0, true
06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 0
06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 1
,06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 4
06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 5
06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 7
06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 9
06-06 13:16:57.586  1277  1358 D Tethering: upstreamIface add type 18
06-06 13:16:57.586  1277  1358 D Tethering: checkDunRequired: secureSetting is 2
,06-06 13:16:57.596  4464  9815 D bt_vendor: op for 3
06-06 13:16:57.596  4464  9815 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,06-06 13:16:57.596  4464  9815 I bt_userial_vendor: device fd = 73 open
06-06 13:16:57.596  4464  9815 D bt_vendor: set_bluetooth_preproto set on
,06-06 13:16:57.596  4464  9815 D bt_vendor: op for 1
06-06 13:16:57.596  4464  9816 D bt_vendor: op for 10
,06-06 13:16:57.616  1277  4172 I ActivityManager: Start proc 9817:com.lge.settings.easy/1000 for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver
,06-06 13:16:57.616  1277  1358 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-06 13:16:57.616  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.616  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.616  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.616  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.616  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.616  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.616  1277  3185 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=207064
,06-06 13:16:57.616  1277  3185 D NetworkManagementService: getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=207066
06-06 13:16:57.616  1277  3185 D NetworkManagementService:   [0] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
06-06 13:16:57.616  4464  9815 D bt_hwcfg: hw_config_cback opcode:0x0c03
06-06 13:16:57.616  4464  9815 D bt_hwcfg: hw_config_cback state=1
,06-06 13:16:57.616  9730  9730 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-06 13:16:57.616  9730  9730 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-06 13:16:57.616  9730  9730 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-06 13:16:57.616  9730  9730 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-06 13:16:57.616  1277  3185 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=207067
06-06 13:16:57.616  1277  3185 D NetworkManagementService: getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=207069
06-06 13:16:57.616  1277  3185 D NetworkManagementService:   [0] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
06-06 13:16:57.616  9730  9730 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,06-06 13:16:57.636  9730  9730 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
06-06 13:16:57.636  9730  9730 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,06-06 13:16:57.636  9730  9730 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-06 13:16:57.636  9730  9730 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,06-06 13:16:57.636  9730  9730 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
06-06 13:16:57.636  9730  9730 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
06-06 13:16:57.636  9730  9730 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,06-06 13:16:57.646  9817  9817 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-06 13:16:57.646  4464  9815 D bt_hwcfg: hw_config_cback opcode:0x0c14
06-06 13:16:57.646  4464  9815 D bt_hwcfg: hw_config_cback state=4
06-06 13:16:57.646  4464  9815 D bt_hwcfg: Chipset Name: BCM4335C0
06-06 13:16:57.646  4464  9815 D bt_hwcfg: Change chipset Name: BCM4339
06-06 13:16:57.646  4464  9815 D bt_hwcfg: Chipset BCM4339
06-06 13:16:57.646  4464  9815 D bt_hwcfg: Target name = [BCM4339]
06-06 13:16:57.646  4464  9815 I bt_hwcfg: Found patchfile: /system/bin//BCM4339_003.001.009.0108.0501_LGE_P1-EU_FM_ORC.hcd
,06-06 13:16:57.646  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-06 13:16:57.646  4464  9815 D bt_hwcfg: hw_config_cback state=2
,06-06 13:16:57.656  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-06 13:16:57.656  4464  9815 D bt_hwcfg: hw_config_cback state=3
06-06 13:16:57.656  4464  9815 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,06-06 13:16:57.666  9817  9817 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,06-06 13:16:57.676  9730  9730 D BluetoothPermissionRequest: onReceive
,06-06 13:16:57.676  9730  9730 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,06-06 13:16:57.676  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc2e
06-06 13:16:57.676  4464  9815 D bt_hwcfg: hw_config_cback state=5
,06-06 13:16:57.686  1277  1358 D BluetoothManagerService: Message: 20
06-06 13:16:57.686  1277  1358 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a644088:true
,06-06 13:16:57.696  9730  9730 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.736  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.746  1277  1294 I ActivityManager: Start proc 9842:com.google.android.apps.maps/u0a119 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  1277  1294 I ActivityManager: Killing 9397:com.lge.exchange/u0a22 (adj 15): empty #22
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.746  9704  9704 E wpa_supplicant: USIM:  scard_init function
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.746  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.756  9704  9704 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c,
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.756  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.766  9704  9704 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.766  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  1277  3188 D WifiStateMachine: MAC Addr from driver = a0:39:f7:6f:c9:5d
06-06 13:16:57.776  1277  3188 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.776  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.786  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.796  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.806  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.816  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.826  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.836  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.846  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.856  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.866  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.866  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.866  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.866  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.866  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
,06-06 13:16:57.866  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:16:57.866  4025  4025 D WfdService: Waiting for WifiP2p enabling
06-06 13:16:57.866  1277  1277 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-06 13:16:57.866  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,06-06 13:16:57.866  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.866  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.876  9707  9707 I LIA_SmartSetting(4.50.6)_LogCore: LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
06-06 13:16:57.876  9707  9707 V LIA_SmartSetting(4.50.6)_ContextDetector: onReceive action android.net.wifi.WIFI_STATE_CHANGED
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_WifiContextDetector: onReceive state= 3
06-06 13:16:57.876  1277  3192 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: recipeSlug= arrive_home_wifi
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: selection= recipe_slug = "arrive_home_wifi"
06-06 13:16:57.876  1277  1277 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 1
06-06 13:16:57.876  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.876  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.876  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.876  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: status= 0
06-06 13:16:57.876  9645  9645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_ContextDetector: onUpdate Wi-Fi on
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-06 13:16:57.876  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-06 13:16:57.876  9645  9645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-06 13:16:57.876  9645  9645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: onStatusChanged value= Wi-Fi on
06-06 13:16:57.876  1277  3188 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-06 13:16:57.876  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: is not interactive
06-06 13:16:57.876  9707  9707 V LIA_SmartSetting(4.50.6)_DeviceLogger: DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1465211817887, , settingStatus=Wi-Fi on, deviceTypeOrdinal=0]
06-06 13:16:57.876  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.876  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter: insert start
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.886  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManager: insertSettingInfo ID = 7768
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  9704  9704 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
06-06 13:16:57.896  1277  3188 D WifiStateMachine: enableVerboseLogging : level 2
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  1277  3188 D WifiStateMachine: Setting OUI to DA-A1-19
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.896  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.896  1277  3188 D WifiNative-HAL: Setting external_sim to 1
06-06 13:16:57.906  1277  3188 I WifiNative-HAL: startHal
06-06 13:16:57.906  1277  3188 D wifi    : setting scan oui 0x7f5dfc47c0
06-06 13:16:57.906  1277  3188 D WifiHAL : Sending mac address OUI
06-06 13:16:57.906  1277  3188 D WifiStateMachine: Setting OUI to DA-A1-19
06-06 13:16:57.906  1277  3188 I WifiNative-HAL: startHal
06-06 13:16:57.906  1277  3188 D wifi    : setting scan oui 0x7f5dfc47c0
06-06 13:16:57.906  1277  3188 D WifiHAL : Sending mac address OUI
06-06 13:16:57.906  4025  4025 D WfdsService: Supplicant Connection state is changed : true
06-06 13:16:57.906  4025  4631 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-06 13:16:57.906  4025  4631 D WfdsService: Set the WFDS Monitor: true
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.906  9035  9035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.906  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-06 13:16:57.906  4025  4631 D WfdsMonitor: WfdsMonitorThread create
06-06 13:16:57.906  4025  4631 D WfdsMonitor: WFDS Monitor is created and started
06-06 13:16:57.906  4025  4631 D WfdsService: WiFi: Supplicant connection re-established
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.906  1277  3188 D WifiOffDelayIfNotUsed: stopMonitoring
,06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.906  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.906  9781  9781 D WiFiOffLoadUpdatePriority: remove : truetruefalse
,06-06 13:16:57.916  1277  1277 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
06-06 13:16:57.916  1277  3192 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
06-06 13:16:57.916  4025  4025 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
06-06 13:16:57.916  1277  3192 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.916  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.916  1277  3188 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.916  1277  1277 D WifiScanningService: SCAN_AVAILABLE : 3
06-06 13:16:57.916  1277  1277 D RttService: SCAN_AVAILABLE : 3
06-06 13:16:57.916  1277  3246 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-06 13:16:57.916  1277  3246 I WifiNative-HAL: startHal
,06-06 13:16:57.916  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:16:57.916  1277  3246 D wifi    : getting scan capabilities on interface[0] = 0x7f5dfc47c0
06-06 13:16:57.916  1277  3246 D WifiHAL : Creating message to get scan capablities; iface = 5
06-06 13:16:57.916  1277  3246 D WifiHAL : In GetCapabilities::handleResponse
06-06 13:16:57.916  1277  3246 D WifiHAL : Id = 0, subcmd = 0, len = 28, expected len = 32
06-06 13:16:57.916  1277  3246 D WifiScanningService: StartedState
06-06 13:16:57.916  1277  3248 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.916  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.916  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-06 13:16:57.926  4025  4025 D WfdService: Waiting for WifiP2p enabling
06-06 13:16:57.926  1277  1277 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-06 13:16:57.926  1277  1277 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 1
06-06 13:16:57.926  1277  3192 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.926  4025  9868 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-06 13:16:57.926  4025  9868 E CtrlSupplicant: Succeed to open control connection
06-06 13:16:57.926  4025  9868 E CtrlSupplicant: Succeed to open monitor connection
06-06 13:16:57.926  4025  9868 D WfdsMonitor: Supplicant connection established
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.926  4025  4631 D WfdsService: Connected to the supplicant for wfds
06-06 13:16:57.926  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.926  1277  3188 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.926  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.926  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.926  1277  3645 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.926  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.926  1277  1294 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.936  9753  9869 W FormManager: Network not available. Please check & try again.
,06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.936  1277  1295 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.936  1277  4128 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:57.936  9753  9870 V FormManager: Network unavailable.
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.936  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.936  1277  4193 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:57.936  9753  9870 V FormManager: Network unavailable.
06-06 13:16:57.936  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,06-06 13:16:57.936  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 (has extras) }
06-06 13:16:57.936  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-06 13:16:57.936   477  1253 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.936  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.946  1277  3187 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:16:57.946  1277  3187 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:16:57.946   477  1253 D CommandListener: Setting iface cfg
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.946  1277  3187 E LGWifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '60 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 60 Failed to set address (No such device)'
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.946  1277  3187 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,06-06 13:16:57.946  1277  3188 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
06-06 13:16:57.946  1277  3187 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-06 13:16:57.946  1277  3187 D WifiServerServiceExt: postfix byte check : 4
06-06 13:16:57.946  1277  3187 D LGWifiP2pService: before postfix = G4-1
06-06 13:16:57.946  1277  3188 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-06 13:16:57.946  1277  3187 D LGWifiP2pService: after postfix = G4-1
06-06 13:16:57.946  9704  9704 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.946  1277  3188 I WifiServerServiceExt: setWifiPasspointEnabled state : 0
06-06 13:16:57.946  9704  9704 E wpa_supplicant: Passpoint is DISABLED
,06-06 13:16:57.946  1277  3187 D WifiNative-HAL: p2pGetDeviceAddress
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.946  1277  3187 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:6f:c9:5d
,06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.946  1277  3188 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-06 13:16:57.946  9704  9704 E wpa_supplicant: disconnect_rssi_lvl: -100
06-06 13:16:57.946  4025  4025 I WfdStateTracker: handleP2pThisDeviceChanged: 3
06-06 13:16:57.946  4025  4025 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-06 13:16:57.946  4025  4025 D WfdsService: Update P2p Interface State: 3
,06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.946  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.946  1277  3188 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 1
,06-06 13:16:57.956  9704  9704 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 1
,06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.956  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
,06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.956  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-06 13:16:57.956  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:57.956  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:57.956  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:57.956  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.956  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:57.956  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.956  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.966  4025  4025 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.966  4025  4025 D WfdsService: WifiP2pState is changed : true
06-06 13:16:57.966  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
06-06 13:16:57.966  4025  4025 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-06 13:16:57.966  4025  4631 D WfdsService: Receive the WFDS_ENABLE Method
06-06 13:16:57.966  4025  4631 D WfdsService: Set the WFDS Monitor: true
06-06 13:16:57.966  4025  4631 D WfdsService: Connected to the supplicant for wfds
06-06 13:16:57.966  4025  4631 D WfdsJNI : doCommand: WFDS_SET TRUE
06-06 13:16:57.966  4025  4025 D WfdsService: isConnected: false
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.966  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.976  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.986  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.986  9704  9704 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DC
,06-06 13:16:57.986  9704  9704 I wpa_supplicant: P2P: class:115 ch:36 PASSIVE
06-06 13:16:57.986  9704  9704 I wpa_supplicant: P2P: class:115 ch:40 PASSIVE
06-06 13:16:57.986  9704  9704 I wpa_supplicant: P2P: class:115 ch:44 PASSIVE
06-06 13:16:57.986  9704  9704 I wpa_supplicant: P2P: class:115 ch:48 PASSIVE
,06-06 13:16:57.986  9704  9704 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:DC
06-06 13:16:57.986  9704  9704 I wpa_supplicant: [LGE_PATCH] For Country code DC. gSupportP2P5G : P2P_5G_GC_ONLY
06-06 13:16:57.986  9704  9704 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.996  4025  4631 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:57.996  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.006  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.016  9704  9704 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,06-06 13:16:58.016  9704  9704 I wpa_supplicant: P2P: class:115 ch:36 PASSIVE
06-06 13:16:58.016  9704  9704 I wpa_supplicant: P2P: class:115 ch:40 PASSIVE
06-06 13:16:58.016  9704  9704 I wpa_supplicant: P2P: class:115 ch:44 PASSIVE
06-06 13:16:58.016  9704  9704 I wpa_supplicant: P2P: class:115 ch:48 PASSIVE
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.016  9704  9704 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
06-06 13:16:58.016  4025  4631 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
06-06 13:16:58.016  9704  9704 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
06-06 13:16:58.016  4025  4631 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
,06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.016  4025  4631 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
06-06 13:16:58.016  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.026  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.036  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.046  9704  9704 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DC
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  9704  9704 I wpa_supplicant: P2P: class:115 ch:36 PASSIVE
06-06 13:16:58.046  9704  9704 I wpa_supplicant: P2P: class:115 ch:40 PASSIVE
06-06 13:16:58.046  9704  9704 I wpa_supplicant: P2P: class:115 ch:44 PASSIVE
06-06 13:16:58.046  9704  9704 I wpa_supplicant: P2P: class:115 ch:48 PASSIVE
,06-06 13:16:58.046  9704  9704 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:DC
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  4025  4631 D WfdsService: selectPreferredScanChannel [185]
06-06 13:16:58.046  4025  4631 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:6f:c9:5d
,06-06 13:16:58.046  4025  4025 D WfdsService: GroupInfoAvailable: mGroupInfo is null
06-06 13:16:58.046  1277  1277 E WifiServerServiceExt: No p2p device connected
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  4025  4631 W WfdsService: DefaultState - msg [9441285] is not handled
,06-06 13:16:58.046  9704  9704 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  9704  9704 W wpa_supplicant: wlan0: Failed to initiate AP scan
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.046  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.046  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:58.046  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:58.046  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:58.046  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:58.046  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:16:58.056  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-06 13:16:58.056  1277  1277 D WifiHS20: hidePasspointNotification off =false
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-06 13:16:58.056  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
06-06 13:16:58.056  9704  9704 E wpa_supplicant: nWIFIDualbandAPConnection: 1
06-06 13:16:58.056  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:58.056  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,06-06 13:16:58.056  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:58.056  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: setWifiPasspointEnabled state : 0
,06-06 13:16:58.056  9704  9704 E wpa_supplicant: Passpoint is DISABLED
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
06-06 13:16:58.056  9704  9704 E wpa_supplicant: disconnect_rssi_lvl: -100
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 1
06-06 13:16:58.056  9704  9704 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 1
,06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.056  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.056  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-06 13:16:58.066  1277  3188 E WifiNative-wlan0: doBoolean: disable
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.066  9704  9704 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
06-06 13:16:58.066  9704  9704 W wpa_supplicant: wlan0: Failed to initiate AP scan
,06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.066  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:16:58.066  1277  1277 D WifiServerServiceExt: setSupplicantStateSCANNING
,06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.066  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:58.066  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:58.066  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:58.066  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:58.066  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:16:58.066  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.066  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.066  1277  1277 D WifiHS20: hidePasspointNotification off =false
06-06 13:16:58.066  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.076  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:16:58.076  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:16:58.076  1277  1277 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.076  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:58.076  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.076  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.076  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:16:58.076  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:16:58.076  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:58.076  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:16:58.076  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:16:58.076  1277  1277 D WifiHS20: hidePasspointNotification off =false
06-06 13:16:58.076  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.086  9781  9781 D WiFiOffLoadUpdatePriority: remove1
06-06 13:16:58.086  9781  9781 V WiFiOffLoadSharedPrefsUtils: save remove
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.086  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:16:58.086  1277  1277 D WifiServerServiceExt: setSupplicantStateSCANNING
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.086  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:16:58.086  1277  1277 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.086  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  9781  9781 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
06-06 13:16:58.096  9781  9781 D WiFiOffLoadBroadcast: S: false, R: false
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
,06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.exists(File.java:363)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1107)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1130)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1072)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1073)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.,gmm.map.m.q.a(PG:8693)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1073)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at andr,oid.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.k.d(PG:1187)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.k.a(PG:2107)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.v.a(PG:1161)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.y.a(PG:2188)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.e.b(PG:170)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.e.b(PG:15188)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.k.d(PG:1187)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.k.c(PG:18147)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.k.d(PG:583)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.v.a(PG:1161)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.y.a(PG:2188)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.e.b(PG:170)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.r.e.b(PG:15188)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.exists(File.java:363)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1107)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1130)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1238)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:192)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.exists(File.java:363)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.096  9842  9842 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.io.File.lastModified(File.java:571)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4700)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.access$1500(ActivityThread.java:162)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1410)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:16:58.096  9842  9842 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:16:58.106  1277  3645 D WifiServiceImplEx: addOrUpdateNetwork pid=9781, uid=1000, packageName=android.uid.system:1000
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.096  9781  9781 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
06-06 13:16:58.096  9781  9781 D WiFiOffLoadUpdatePriority: connected SSID: null
06-06 13:16:58.096  9781  9781 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.096  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.106  5117  5117 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.106  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  1277  3645 E addOrUpdateNetwork:  uid = 1000 SSID null nid=0
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  1277  3188 E WifiConfigStore:  key=nullNONE netId=0 uid=0/1000
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.116  5117  5117 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.116  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  9781  9781 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
06-06 13:16:58.126  9781  9781 D WiFiOffLoadUpdatePriority: configuration updated: 0
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc4e
06-06 13:16:58.126  4464  9815 D bt_hwcfg: hw_config_cback state=6
06-06 13:16:58.136  9781  9781 D WiFiOffLoadUpdatePriority: configuration saved: true
06-06 13:16:58.136  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
06-06 13:16:58.136  1277  3374 I ActivityManager: Killing 9420:com.lge.email/u0a56 (adj 15): empty #22
,06-06 13:16:58.146  9842  9875 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
06-06 13:16:58.156  1277  1358 D BluetoothManagerService: Message: 20
06-06 13:16:58.156  1277  1358 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2879f02a:true
,06-06 13:16:58.226  4464  9815 I bt_hwcfg: bt vendor lib: set UART baud 115200
06-06 13:16:58.226  4464  9815 D bt_hwcfg: Settlement delay -- 100 ms
06-06 13:16:58.226  4464  9815 I bt_hwcfg: Setting fw settlement delay to 100 
,06-06 13:16:58.236  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.246  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.256  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,06-06 13:16:58.256  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:16:58.256  6383  6383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2701 
,06-06 13:16:58.266  6383  6383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2701 
,06-06 13:16:58.266  9842  9907 I NotificationManager: com.google.android.apps.maps: cancel(10436) by com.google.android.apps.maps
,06-06 13:16:58.266  9707  9707 I LIA_SmartSetting(4.50.6)_LogCore: LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
06-06 13:16:58.266  9707  9707 V LIA_SmartSetting(4.50.6)_ContextDetector: onReceive action android.net.wifi.WIFI_STATE_CHANGED
06-06 13:16:58.266  9707  9707 D LIA_SmartSetting(4.50.6)_WifiContextDetector: onReceive state= 1
06-06 13:16:58.266  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: recipeSlug= arrive_home_wifi
06-06 13:16:58.266  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
06-06 13:16:58.266  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: selection= recipe_slug = "arrive_home_wifi"
,06-06 13:16:58.266  6383  9910 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-06 13:16:58.266  6383  9910 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-06 13:16:58.266  6383  9909 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [674] : iAgentState=3, isUserType=1
,06-06 13:16:58.266  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: status= 0
06-06 13:16:58.266  9707  9707 D LIA_SmartSetting(4.50.6)_ContextDetector: onUpdate Wi-Fi off
,06-06 13:16:58.276  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: onStatusChanged value= Wi-Fi off
,06-06 13:16:58.276  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: is not interactive
06-06 13:16:58.276  9707  9707 V LIA_SmartSetting(4.50.6)_DeviceLogger: DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1465211818282, , settingStatus=Wi-Fi off, deviceTypeOrdinal=0]
,06-06 13:16:58.276  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter: insert start
,06-06 13:16:58.286  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManager: insertSettingInfo ID = 7769
,06-06 13:16:58.286  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-06 13:16:58.286  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.296  9753  9912 W FormManager: Network not available. Please check & try again.
06-06 13:16:58.296  1277  1295 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.296  1277  3839 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.296  1277  3645 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  9753  9913 V FormManager: Network unavailable.
,06-06 13:16:58.296  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:58.296  1277  1294 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.296  9753  9913 V FormManager: Network unavailable.
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.296  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.306  9707  9707 I LIA_SmartSetting(4.50.6)_LogCore: LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
06-06 13:16:58.306  9707  9707 V LIA_SmartSetting(4.50.6)_ContextDetector: onReceive action android.net.wifi.WIFI_STATE_CHANGED
06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_WifiContextDetector: onReceive state= 3
06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: recipeSlug= arrive_home_wifi
06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: selection= recipe_slug = "arrive_home_wifi"
,06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: status= 0
06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_ContextDetector: onUpdate Wi-Fi on
,06-06 13:16:58.306  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: onStatusChanged value= Wi-Fi on
,06-06 13:16:58.316  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: is not interactive
06-06 13:16:58.316  9707  9707 V LIA_SmartSetting(4.50.6)_DeviceLogger: DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1465211818318, , settingStatus=Wi-Fi on, deviceTypeOrdinal=0]
,06-06 13:16:58.316  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter: insert start
,06-06 13:16:58.316  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManager: insertSettingInfo ID = 7770
,06-06 13:16:58.326  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-06 13:16:58.326  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:58.326  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.326  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.336  1277  4216 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.336  9753  9915 W FormManager: Network not available. Please check & try again.
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  4216 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  9753  9916 V FormManager: Network unavailable.
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
06-06 13:16:58.336  1277  4151 W ActivityManager: getRunningAppProcesses: caller 10049 does not hold REAL_GET_TASKS; limiting output
,06-06 13:16:58.336  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:16:58.336  9753  9916 V FormManager: Network unavailable.
06-06 13:16:58.336  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-06 13:16:58.336  4464  9815 D bt_hwcfg: hw_config_cback state=2
,06-06 13:16:58.336  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:58.346  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-06 13:16:58.346  4464  9815 D bt_hwcfg: hw_config_cback state=7
06-06 13:16:58.346  4464  9815 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-06 13:16:58.346  4464  9815 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:3C:51
,06-06 13:16:58.366  4464  9815 D bt_hwcfg: hw_config_cback opcode:0xfc01
06-06 13:16:58.366  4464  9815 D bt_hwcfg: hw_config_cback state=8
06-06 13:16:58.366  4464  9815 I bt_hwcfg: vendor lib fwcfg completed
06-06 13:16:58.366  4464  9815 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
06-06 13:16:58.366  4464  9813 I bt-btu  : btu_task received preload complete event
,06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_HCI,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_OBEX,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_AVCT,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_AVDT,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_AVRC,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_A2D,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_BNEP,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_BTM,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_GAP,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_PAN,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_SAP,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_SDP,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_GATT,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_SMP,2
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_BTIF,3
,06-06 13:16:58.376  4464  9813 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
,06-06 13:16:58.386  1277  3374 I ActivityManager: Start proc 9917:com.lge.qremote/u0a138 for broadcast com.lge.qremote/.settings.WiFiStateReceiver
,06-06 13:16:58.396   504   504 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 200us total 9.713ms
,06-06 13:16:58.406  9917  9917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-06 13:16:58.416   504   504 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 589us total 18.482ms
,06-06 13:16:58.426  9917  9917 I QRemoteSDK: [IRBlaster.java:192:createIrBlaster()] oooooo Create blaster instance.
,06-06 13:16:58.426  9917  9917 I QRemoteSDK: [UeiIrBlasterWrapper.java:236:createIrBlasterWrapper()] oooooo Create blaster instance.
,06-06 13:16:58.436   504   504 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 615us total 18.479ms
,06-06 13:16:58.436  9917  9917 I QRemoteSDK: [UeiIrBlasterInitializer.java:277:safeExec()] oooooo Bind setup service.
,06-06 13:16:58.496  1277  1277 D InputDispatcher: Window went away: Window{3222dc47 u0 Toast}
,06-06 13:16:58.506  1277  1277 D PowerManagerServiceEx: releaseWakeLockInternal: lock=564590051 [WindowManager], flags=0x0
,06-06 13:16:58.506  4464  4464 V BluetoothOppNotification: new notify threadi!
06-06 13:16:58.506  4464  4464 V BluetoothOppNotification: send delay message
,06-06 13:16:58.506  4464  9937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,06-06 13:16:58.506  4464  9937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22a9a5c2 on behalf of 
,06-06 13:16:58.516  4464  9937 V BluetoothOppNotification: mUpdateCompleteNotification = true
,06-06 13:16:58.516  4464  9937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,06-06 13:16:58.516  4464  9937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28c8dfd3 on behalf of 
,06-06 13:16:58.516  4464  9937 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-06 13:16:58.516  4464  9937 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-06 13:16:58.516  4464  9937 V BluetoothOppNotification: outbound notification was removed.
06-06 13:16:58.516  4464  9937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,06-06 13:16:58.516  4464  9937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ebc710 on behalf of 
,06-06 13:16:58.516  4464  9937 V BluetoothOppNotification: inbound: succ-0  fail-0
,06-06 13:16:58.526  4464  9937 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
,06-06 13:16:58.526  4464  9937 V BluetoothOppNotification: inbound notification was removed.
06-06 13:16:58.526  4464  9937 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,06-06 13:16:58.526  4464  9937 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e6ad209 on behalf of 
,06-06 13:16:58.626  1277  4215 I ActivityManager: Start proc 9938:com.uei.lg.quicksetsdk.irblaster/1000 for service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service
,06-06 13:16:58.626  9917  9917 I QRemoteSDK: [UeiIrBlasterInitializer.java:300:safeExec()] oooooo Bind control service.false
,06-06 13:16:58.666  9938  9938 D UEI.SmartControl: Quickset Services start...
,06-06 13:16:58.666  9938  9938 I UEI.SmartControl: Manufacture = LGE
06-06 13:16:58.666  9938  9938 D UEI.SmartControl: Id = LGNevo
,06-06 13:16:58.666  9938  9938 D UEI.SmartControl: File observer start...
06-06 13:16:58.666  9938  9938 E UEI.SmartControl: IR Port is disabled: false
06-06 13:16:58.666  9938  9938 D UEI.SmartControl: Starting file observer...
06-06 13:16:58.666  9938  9938 D UEI.SmartControl: Extracting JNI libs...
,06-06 13:16:58.666  9938  9938 D UEI.SmartControl: --- java.library.path =/vendor/factory_lib:/vendor/lib:/system/lib
,06-06 13:16:58.686  9938  9938 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
06-06 13:16:58.686  9938  9938 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-06 13:16:58.686  9938  9938 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,06-06 13:16:58.706  9938  9938 I UEI.SmartControl: --- Selecting new region: 6
,06-06 13:16:58.716  9938  9938 I UEI.SmartControl: Model = LG-H815
,06-06 13:16:58.716  9938  9938 D UEI.SmartControl: QS Service created
,06-06 13:16:58.726  9938  9938 I UEI.SmartControl: Service initServices...
,06-06 13:16:58.726  9938  9938 D UEI.SmartControl: QS start get config
,06-06 13:16:58.736  9938  9938 D UEI.SmartControl: Loading JNI Libs...
,06-06 13:16:58.736  9938  9938 D UEI.SmartControl: Loading QS Libs from folder: /data/data/com.uei.lg.quicksetsdk.irblaster/files
,06-06 13:16:58.806  4464  4722 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
,06-06 13:16:58.806  4464  4722 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,06-06 13:16:58.806  4464  9960 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,06-06 13:16:58.806  4464  4722 E bt-btif : warning : media task started media_task_refcnt 1 
,06-06 13:16:58.806  1277  4194 I art     : Explicit concurrent mark sweep GC freed 128945(6MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 57MB/86MB, paused 4.851ms total 166.508ms
,06-06 13:16:58.806  4464  9960 D BT_PROF_AUDIO: created moving average (N=100)
06-06 13:16:58.806  4464  9960 D BT_PROF_AUDIO: reset rate average
06-06 13:16:58.806  4464  4722 E bt-btif : Calling BTA_HhEnable
06-06 13:16:58.806  4464  4722 E bt-btif : btif_storage_get_adapter_property service_mask:0x1200c8
06-06 13:16:58.806  4464  4722 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-06 13:16:58.806  4464  4722 D BluetoothAdapterProperties: Address is:F8:95:C7:87:3C:51
06-06 13:16:58.806  4464  9813 W bt-smp  : Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
06-06 13:16:58.806  4464  9813 W bt-smp  : Plain text(LSB ~ MSB) = 81 5a 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-06 13:16:58.806  4464  9813 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 8f b9 89 51 76 29 2c 70 a7 cc 2e 9c a4 d3 6b 
06-06 13:16:58.806  4464  9813 W bt-btm  : Stopping oneshot timer
06-06 13:16:58.806  4464  9960 W bt-btif : overflow 0, enter 0, exit 0
,06-06 13:16:58.806  1277  1277 D BluetoothManagerService: Bluetooth Adapter name changed to G4-1
06-06 13:16:58.806  1277  1277 D BluetoothManagerService: store name and address
06-06 13:16:58.806  1277  1277 D BluetoothManagerService: Stored Bluetooth name: G4-1
06-06 13:16:58.816  4464  9813 W bt-smp  : Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
06-06 13:16:58.816  4464  9813 W bt-smp  : Plain text(LSB ~ MSB) = ea d1 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-06 13:16:58.816  4464  9813 W bt-smp  : Encrypted text(LSB ~ MSB) = 54 49 a7 11 c4 23 fe 55 ab e9 0c 3d 75 5a 3d eb 
06-06 13:16:58.816  4464  4722 D BluetoothAdapterProperties: Name is: G4-1
,06-06 13:16:58.816  4464  9813 W bt-smp  : Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
06-06 13:16:58.816  4464  9813 W bt-smp  : Plain text(LSB ~ MSB) = da c1 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-06 13:16:58.816  4464  9813 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 98 7c 21 d1 1c 0e 61 41 84 b9 0b 50 9e de 40 
06-06 13:16:58.816  4464  9813 W bt-smp  : Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
06-06 13:16:58.816  4464  9813 W bt-smp  : Plain text(LSB ~ MSB) = 4e 3f 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-06 13:16:58.816  4464  9813 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 f7 d4 8e 55 a1 16 f2 c5 1c 1d e0 4e fe 61 dd 
06-06 13:16:58.816  4464  4722 D BluetoothAdapterProperties: Scan Mode:20
06-06 13:16:58.816  4464  4722 D BluetoothAdapterProperties: Discoverable Timeout:120
,06-06 13:16:58.816  4464  9813 W bt-smp  : Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
06-06 13:16:58.816  4464  9813 W bt-smp  : Plain text(LSB ~ MSB) = f2 33 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-06 13:16:58.816  4464  9813 W bt-smp  : Encrypted text(LSB ~ MSB) = 0e 1f 58 ca 56 07 a6 42 ed 2f 6d 2f 14 87 6a a0 
06-06 13:16:58.816  4464  4722 D BluetoothAdapterProperties: Adding bonded device:10:D3:8A:FB:85:D4
06-06 13:16:58.816  4464  4722 I bt-btif : HAL bt_hal_cbacks->remote_device_properties_cb
06-06 13:16:58.816  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-06 13:16:58.826  9917  9917 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,06-06 13:16:58.826  9917  9917 V SoundPool: load: fd=30, offset=12738528, length=17813, priority=1
06-06 13:16:58.826  9917  9965 V SoundPool: Start decode
06-06 13:16:58.826  9917  9965 V MediaPlayer[Native]: decode(31, 12738528, 17813)
,06-06 13:16:58.826  9917  9917 D QRemoteSDK: [IRBlaster.java:178:createIrBlaster()] oooooo Currently blaster use: 2
06-06 13:16:58.826  9917  9917 I QRemoteSDK: [UeiIrBlasterInitializer.java:414:handleSetupDisconnected()] oooooo  handleSetupDisconnected true is bindingtrue
06-06 13:16:58.826   483  3211 V MediaPlayerService: decode(45, 12738528, 17813)
06-06 13:16:58.826   483  3211 V MediaPlayerService: player type = 4
06-06 13:16:58.826   483  3211 D VendorSourceMaster: libvendorsourcemaster v1.0.0.15.f563fd1
06-06 13:16:58.826   483  3211 E LocalMessageHandler: create LocalMessageHandler
06-06 13:16:58.826   483  9966 V NuPlayer: kWhatSetAudioSink
06-06 13:16:58.826   483  9966 V NuPlayer: kWhatSetDataSource
,06-06 13:16:58.826   483  3211 I ExtendedUtils: printFileName fd(45) -> /data/preload/com.lge.qremote-1/base.apk
06-06 13:16:58.826   483  3211 V MediaPlayerService: prepare
06-06 13:16:58.826   483  3211 V MediaPlayerService: wait for prepare
,06-06 13:16:58.826   483  9967 V LGParserOSAL: SniffLGParser start
06-06 13:16:58.826   483  9967 V LGParserOSAL: MainType:5, SubType=0
06-06 13:16:58.826   483  9967 V LGParserOSAL: #### check Mime : application/ogg
06-06 13:16:58.826   483  9967 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
06-06 13:16:58.826   483  9967 E MediaExtractor: Use LGExtractor :application/ogg 
,06-06 13:16:58.846   483  9967 V LGParserOSAL: supported mime: application/ogg
06-06 13:16:58.846   483  9967 I GenericSource: mPlayerInfo :VIDEO_TRACK_NOT_EXIST 
,06-06 13:16:58.846   483  9966 V AudioCache: notify(0xf1f030c0, 200, 1, 9120)
06-06 13:16:58.846   483  9966 V AudioCache: ignored
06-06 13:16:58.846   483  9966 V AudioCache: notify(0xf1f030c0, 1, 0, 0)
06-06 13:16:58.846   483  9966 V AudioCache: prepared
06-06 13:16:58.846   483  3211 V AudioCache: wait - success
06-06 13:16:58.846   483  3211 V MediaPlayerService: start
06-06 13:16:58.846   483  3211 D NuPlayerDriver: start(0xf1c742b0)
06-06 13:16:58.846   483  3211 V MediaPlayerService: wait for playback complete
06-06 13:16:58.846   483  9966 V NuPlayer: kWhatStart
06-06 13:16:58.846   483  9966 I GenericSource: start
,06-06 13:16:58.846   483  9966 I AudioFlinger: isAudioPlaybackHookOn() false,
06-06 13:16:58.846   483  9966 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-06 13:16:58.846   483  9966 I ExtendedUtils: No channel mask, try channel count
06-06 13:16:58.846   483  9966 W ExtendedUtils: No bitrate info
06-06 13:16:58.846   483  9966 I ExtendedUtils: decision 0 mime audio/vorbis
06-06 13:16:58.846   483  9966 I AudioFlinger: isAudioPlaybackHookOn() false
06-06 13:16:58.846   483  9966 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-06 13:16:58.846   483  9966 I NuPlayer: Could not offload audio decode, pcm offload decided :0
06-06 13:16:58.846   483  9966 V LocalMessageHandler: kWhatRegisterRendererInvoker
06-06 13:16:58.846   483  9966 V NuPlayer: scanning sources haveAudio=0, haveVideo=0
,06-06 13:16:58.846   483  9966 I AudioFlinger: isAudioPlaybackHookOn() false
06-06 13:16:58.846   483  9966 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
06-06 13:16:58.846   483  9966 V LGCodecAdapter: LG Codec Adapter start
06-06 13:16:58.846   483  9966 V LGCodecOSAL: Called LGCodeConvertMetaDataToMessage
06-06 13:16:58.846   483  9969 V LGCodecAdapter: LG Codec Adapter start,
06-06 13:16:58.846   483  9969 V ACodec  : ACodec
06-06 13:16:58.846   483  9969 V ACodec  : Now uninitialized
06-06 13:16:58.846   483  9970 V ACodec  : initiateAllocateComponent
06-06 13:16:58.846   483  9970 V ACodec  : onAllocateComponent,
06-06 13:16:58.846   483  9970 V OMXCodec: findMatchingCodecs()
06-06 13:16:58.846   483  9970 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,06-06 13:16:58.846   483  9970 D ACodec  : Successfully allocated OMX node 'OMX.google.vorbis.decoder'
06-06 13:16:58.846   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Loaded
06-06 13:16:58.846   483  9969 E MediaCodec: >>>>> MediaCodec::configure
06-06 13:16:58.846   483  9969 E MediaCodec: >>>>> MediaCodec::configure flags is 0
06-06 13:16:58.846   483  9970 V LGCodecAdapter: called getLGCodecSpecificData
06-06 13:16:58.846   483  9970 V LGCodecOSAL: Called LGgetCodecSpecificDataMSG
06-06 13:16:58.846   483  9970 V ACodec  : initiateConfigureComponent
06-06 13:16:58.846   483  9970 V ACodec  : onConfigureComponent
06-06 13:16:58.846   483  9970 V ACodec  : configureCodec
06-06 13:16:58.846   483  9970 V ACodec  : setComponentRole called
06-06 13:16:58.846   483  9970 V LGCodecOSAL: Called LGconfigureCodecMSG
06-06 13:16:58.846   483  9970 V LGCodecOSAL: Not support LGCodec
,06-06 13:16:58.846   483  9970 V ACodec  : initiateStart
06-06 13:16:58.846   483  9970 V ACodec  : onStart
06-06 13:16:58.846   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Loaded->Idle
06-06 13:16:58.846   483  9970 V ACodec  : allocateBuffersOnPort is portIndex=0
06-06 13:16:58.846   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Allocating 4 buffers of size 8192 on input port
,06-06 13:16:58.846   483  9970 V ACodec  : allocateBuffersOnPort is portIndex=1
06-06 13:16:58.846   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Allocating 4 buffers of size 32768 on output port
06-06 13:16:58.846   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Idle->Executing
,06-06 13:16:58.846   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Executing
,06-06 13:16:58.856   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now handling output port settings change
,06-06 13:16:58.856   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Output port now disabled.
06-06 13:16:58.856   483  9970 V ACodec  : allocateBuffersOnPort is portIndex=1
06-06 13:16:58.856   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Allocating 4 buffers of size 32768 on output port
,06-06 13:16:58.856   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Output port now reenabled.
06-06 13:16:58.856   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Executing
,06-06 13:16:58.856   483  9969 V LGCodecAdapter: LG Codec Adapter start
06-06 13:16:58.856   483  9969 V LGCodecOSAL: Called LGCodeConvertMetaDataToMessage
06-06 13:16:58.856   483  9968 V AudioCache: open(48000, 2, 0x0, 1, 8)
,06-06 13:16:58.856   483  9966 V NuPlayer: media rendering started
06-06 13:16:58.856   483  9966 V AudioCache: notify(0xf1f030c0, 6, 0, 0)
06-06 13:16:58.856   483  9966 V AudioCache: ignored
,06-06 13:16:58.856  1277  4171 I ActivityManager: Start proc 9973:com.lge.bnr/1000 for broadcast com.lge.bnr/.service.BNRBootReceiver
,06-06 13:16:58.856  1277  4171 I ActivityManager: Killing 9165:com.lge.appbox.client/u0a9 (adj 15): empty #22
,06-06 13:16:58.866   483  9968 I NuPlayerRenderer: boost first writing of the audio frames
,06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Signalled EOS on the input port
,06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] saw output EOS
06-06 13:16:58.876   483  9966 V NuPlayer: reached audio EOS
06-06 13:16:58.876   483  9966 V AudioCache: notify(0xf1f030c0, 2, 0, 0)
06-06 13:16:58.876   483  9966 V AudioCache: playback complete
06-06 13:16:58.876   483  3211 V AudioCache: wait - success
06-06 13:16:58.876   483  3211 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
06-06 13:16:58.876   483  3211 D NuPlayerDriver: reset(0xf1c742b0) 6 ++ 
06-06 13:16:58.876   483  3211 V AudioCache: notify(0xf1f030c0, 8, 0, 0)
06-06 13:16:58.876   483  3211 V AudioCache: ignored
06-06 13:16:58.876   483  3211 V NuPlayer: source disconnect ++ 
06-06 13:16:58.876   483  3211 V NuPlayer: source disconnect -- 
06-06 13:16:58.876   483  9966 V NuPlayer: kWhatReset
06-06 13:16:58.876   483  9966 V NuPlayer: performDecoderFlush audio=2, video=2
06-06 13:16:58.876   483  9966 V NuPlayer: [audio] flushDecoder needShutdown=1
06-06 13:16:58.876   483  9966 V NuPlayer: postponing action mFlushingAudio=2, mFlushingVideo=0
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] signalFlush
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] ExecutingState flushing now (codec owns 0/4 input, 2/4 output).
06-06 13:16:58.876   483  9966 V NuPlayer: renderer audio flush completed.
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Flushing
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] FlushingState onOMXEvent(0,1)
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] FlushingState onOMXEvent(0,1)
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Executing
06-06 13:16:58.876   483  9966 V NuPlayer: decoder audio flush completed
06-06 13:16:58.876   483  9966 V NuPlayer: initiating audio decoder shutdown
06-06 13:16:58.876   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Executing->Idle
,06-06 13:16:58.886   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Idle->Loaded
06-06 13:16:58.886   483  9970 V ACodec  : [OMX.google.vorbis.decoder] Now Loaded
06-06 13:16:58.886   483  9970 V ACodec  : Now uninitialized
,06-06 13:16:58.886   483  9969 V ACodec  : ~ACodec
06-06 13:16:58.886   483  9966 V NuPlayer: audio shutdown completed
,06-06 13:16:58.886   483  9966 V NuPlayer: both audio and video are flushed now.
06-06 13:16:58.886   483  9966 V NuPlayer: performReset
06-06 13:16:58.886   483  9966 V NuPlayer: Source stop
06-06 13:16:58.886   483  9966 V NuPlayer: Source clear ++ 
06-06 13:16:58.886   483  9966 V NuPlayer: Source clear -- 
06-06 13:16:58.886   483  9966 D NuPlayerDriver: notifyResetComplete(0xf1c742b0)
06-06 13:16:58.886   483  3211 D NuPlayerDriver: reset(0xf1c742b0) 0 -- 
06-06 13:16:58.886   483  3211 V NuPlayer: ~NuPlayer
06-06 13:16:58.886  9917  9965 V SoundPool: close(31)
06-06 13:16:58.886  9917  9965 V SoundPool: pointer = 0xdde74000, size = 205080, sampleRate = 48000, numChannels = 2
,06-06 13:16:58.966  4464  4722 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,06-06 13:16:58.976  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - Message: 40
06-06 13:16:58.976  4464  4464 D BluetoothAdapterService(264956278): handleMessage() - MESSAGE_PROFILE_INIT_PRIORITIES
06-06 13:16:58.976  4464  4722 I LGRemoteDevicePropertySetting: [BTUI] remoteDeviceSetProperties
06-06 13:16:58.976  4464  4722 I LGRemoteDevicePropertySetting: [BTUI] Get AOSP HeadsetService
,06-06 13:16:58.986  4464  4722 E BluetoothRemoteDevices: devicePropertyChangedCallback: mDeviceTrust: false
06-06 13:16:58.986  4464  4722 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
06-06 13:16:58.986  4464  9815 D bt_vendor: op for 2
06-06 13:16:58.986  4464  9815 D bt_vendor: op for 6
06-06 13:16:58.986  4464  4722 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
06-06 13:16:58.986  4464  4722 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,06-06 13:16:58.996  9938  9938 I UEI.SmartControl: Supports setup maps: true
,06-06 13:16:58.996  9938  9938 D UEI.SmartControl: QS start statue = true Error code = 0
06-06 13:16:58.996  9938  9938 I UEI.SmartControl: QS version = v2.7.11.1_RC1
06-06 13:16:58.996  9938  9938 D UEI.SmartControl: QS DB version = APAC_LG_Mobile_with_i-Two_QS_IRB_2015_Korea_database_v3.8_nevosmart
06-06 13:16:58.996  9938  9938 I UEI.SmartControl: ### init IR Blaster...
,06-06 13:16:58.996  9938  9938 D serial_port: Configuring serial port
,06-06 13:16:58.996  9938  9938 I UEI.SmartControl: Setting serial record hearder size = 2
06-06 13:16:58.996  9938  9938 I UEI.SmartControl: i-Two Get version...
,06-06 13:16:58.996  4464  4722 I bt-btif : BTA_JvEnable
06-06 13:16:58.996  4464  4722 E bt-btif : btsock_vendor_hci_init: !vhci_init
06-06 13:16:58.996  4464  4722 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-06 13:16:58.996  4464  4722 D bt-btif : init_hci_slots(L136): in
06-06 13:16:58.996  4464  4722 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,06-06 13:16:58.996  4464  4722 D IOP_DB_BT: db_open: db_open : handle 3723003960l, read 11677 bytes onto local cache
06-06 13:16:58.996  4464  4722 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
06-06 13:16:58.996  4464  4722 D IOP_DB_BT: db_query: result 1
06-06 13:16:58.996  4464  4722 I         : iop_db_open: iop_db_open status 0
06-06 13:16:58.996  4464  4722 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
06-06 13:16:58.996  4464  4722 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-06 13:16:58.996  4464  9813 I bt-btif : bta_pan_co_init
,06-06 13:16:59.006  4464  4722 D bte_conf: Device ID record 1 : primary
06-06 13:16:59.006  4464  4722 D bte_conf:   vendorId            = 00c4
06-06 13:16:59.006  4464  4722 D bte_conf:   vendorIdSource      = 0001
06-06 13:16:59.006  4464  4722 D bte_conf:   product             = 13a1
06-06 13:16:59.006  4464  4722 D bte_conf:   version             = 1000
06-06 13:16:59.006  4464  4722 D bte_conf:   clientExecutableURL = 
06-06 13:16:59.006  4464  4722 D bte_conf:   serviceDescription  = 
06-06 13:16:59.006  4464  4722 D bte_conf:   documentationURL    = 
,06-06 13:16:59.006  4464  4722 D bte_conf: bte_load_did_conf no section named DID2.
,06-06 13:16:59.006  4464  4722 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
,06-06 13:16:59.006  4464  4682 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-06 13:16:59.006  4464  4682 D BluetoothAdapterProperties: ScanMode =  20
06-06 13:16:59.006  4464  4682 D BluetoothAdapterProperties: State =  11
06-06 13:16:59.006  4464  4682 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-06 13:16:59.006  4464  4682 D BluetoothAdapterProperties: Setting state to 12
06-06 13:16:59.006  4464  4682 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): updateAdapterState() - Broadcasting state to 1 receivers.
06-06 13:16:59.006  1277  1358 D BluetoothManagerService: Message: 60
06-06 13:16:59.006  4464  4682 I BluetoothAdapterState: Entering On State
06-06 13:16:59.006  1277  1358 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-06 13:16:59.006  4464  4682 I BluetoothAdapterState: Entering On State from state = 11
06-06 13:16:59.006  1277  1358 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 8 receivers.
06-06 13:16:59.006  4464  4722 E bt-btif : btif_hf_upstreams_evt: wrong handle = 29728 
06-06 13:16:59.006  4464  4722 I bt-btif : HAL bt_op_callbacks->opc_state_cb
06-06 13:16:59.006  4464  4722 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
,06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): isQuetModeEnabled() - Enabled = false
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): autoConnect() - Initiate auto connection on BT on...
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,06-06 13:16:59.006  4464  4682 D LGBluetoothServiceAdapter: [BTUI] OnState
06-06 13:16:59.006  4464  4682 D LGBluetoothServiceAdapter: [BTUI]         global_name: G4-1
06-06 13:16:59.006  4464  4682 D LGBluetoothServiceAdapter: [BTUI]         local_name: G4-1
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): isQuetModeEnabled() - Enabled = false,
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService(264956278): autoConnect() - Initiate auto connection on BT on...
06-06 13:16:59.006  4464  4682 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-06 13:16:59.006  4689  4708 D BluetoothHeadset: onBluetoothStateChange: up=true
06-06 13:16:59.006  4464  4722 D OppService: onOpcStateChange()
06-06 13:16:59.006  4464  4722 I bt-btif : HAL bt_op_callbacks->ops_state_cb
06-06 13:16:59.006  4464  4722 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
,06-06 13:16:59.006  4464  4464 D OppService: Recieved MESSAGE_OPC_ENABLE
06-06 13:16:59.006  4464  4722 D OppService: onOpsStateChange() :0
06-06 13:16:59.006  4464  4464 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-06 13:16:59.006  4464  4464 D OppService: Recieved MESSAGE_OPS_ENABLE
06-06 13:16:59.006  4464  4722 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,06-06 13:16:59.006  4464  4722 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
,06-06 13:16:59.006  4464  4722 D BluetoothAdapterProperties: Scan Mode:21
06-06 13:16:59.006  4464  4722 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-06 13:16:59.006  4464  4722 D BluetoothAdapterProperties: Discoverable Timeout:120
06-06 13:16:59.006  4464  4722 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
06-06 13:16:59.006  4464  9815 D bt_h4   : vendor lib postload completed
,06-06 13:16:59.016  1277  1358 D BluetoothManagerService: Creating new ProfileServiceConnections object for profile: 1,
,06-06 13:16:59.016  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.016  9645  9645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
06-06 13:16:59.016  4078  5366 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-06 13:16:59.016  9973  9973 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-06 13:16:59.016  9973  9973 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,06-06 13:16:59.016  1277  1358 D BluetoothHeadset: onBluetoothStateChange: up=true
06-06 13:16:59.016  4078  5296 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-06 13:16:59.016  1277  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
06-06 13:16:59.016  4464  4491 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.016  9973  9973 V [BNRBootReceiver]: Boot Receiver Return
,06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-06 13:16:59.026  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-06 13:16:59.026  9973  9973 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-06 13:16:59.026  4689  4708 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-06 13:16:59.026  4464  4491 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.026  9645  9645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-06 13:16:59.026  4078  4103 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-06 13:16:59.026  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:16:59.026  4464  4484 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-06 13:16:59.026  1277  1358 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-06 13:16:59.026  1277  1358 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,06-06 13:16:59.026  1277  1277 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,06-06 13:16:59.026  1277  1358 D BluetoothManagerService: Message: 40
06-06 13:16:59.026  1277  1358 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-06 13:16:59.026  4025  4025 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:59.026  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.026  4025  4025 D BleQmManagerService: [BleQmManagerService]  onReceive:  android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:59.026  4025  4460 D LGBluetoothAPIService: Message: 1
06-06 13:16:59.026  4025  4460 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,06-06 13:16:59.036  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.036  4464  4464 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.036  4025  4460 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
06-06 13:16:59.036  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.036  4464  4464 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:59.036  4464  4464 D BluetoothMapService: STATE_ON
06-06 13:16:59.036  4464  4464 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-06 13:16:59.036  4464  4464 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:59.036  4464  4464 V BluetoothPbapReceiver: ***********state = 12
,06-06 13:16:59.036  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.036  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.046  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.046  4464  4464 D LGBluetoothAPIServer: [BTUI] onCreate()
,06-06 13:16:59.046  4464  4464 D LGBluetoothAPIServer: [BTUI] onBind()
,06-06 13:16:59.046  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-06 13:16:59.046  3340  3340 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
06-06 13:16:59.046  4025  4025 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-06 13:16:59.046  4025  4460 D LGBluetoothAPIService: Message: 100
06-06 13:16:59.046  4025  4460 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,06-06 13:16:59.046  9730  9730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.lge.bluetoothsetting.DockEventReceiver.beginStartingService:138 com.lge.bluetoothsetting.DockEventReceiver.onReceive:119 
06-06 13:16:59.056  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-06 13:16:59.056  9707  9707 I LIA_SmartSetting(4.50.6)_LogCore: LIA Log setTagPrefix - prefix : LIA_SmartSetting(4.50.6)_
06-06 13:16:59.056  9707  9707 V LIA_SmartSetting(4.50.6)_ContextDetector: onReceive action android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_BTContextDetector: onReceive state= 12
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: recipeSlug= arrive_home_bluetooth
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: RECIPE_URI= content://com.lge.iftttmanager.provider/recipe
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: selection= recipe_slug = "arrive_home_bluetooth"
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_LGIFTTT: status= 0
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_ContextDetector: onUpdate Bluetooth on
06-06 13:16:59.056  4464  4464 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcae976
06-06 13:16:59.056  4464  4464 V BluetoothPbapService: Pbap Service onCreate
06-06 13:16:59.056  4464  4464 V BluetoothPbapService: Starting PBAP service
06-06 13:16:59.056  4464  4464 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.056  4464  4464 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,06-06 13:16:59.056  4464  4464 V BluetoothMapService: Handler(): got msg=1
06-06 13:16:59.056  4464  4464 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
06-06 13:16:59.056  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.056  4464  4464 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-06 13:16:59.056  4464  4464 V BluetoothPbapService: state: 12
06-06 13:16:59.056  4464  4464 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
06-06 13:16:59.056  4464  4464 V BluetoothPbapService: Handler(): got msg=1
06-06 13:16:59.056  4464  4464 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,06-06 13:16:59.056  9730  9730 D LocalBluetoothProfileManager: Adding local A2DP profile
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: onStatusChanged value= Bluetooth on
,06-06 13:16:59.056  4464 10001 D BluetoothMapMasInstance: MAS initSocket()
06-06 13:16:59.056  4464 10001 D BluetoothMapMasInstance:   masId = 00
06-06 13:16:59.056  4464 10001 D BluetoothMapMasInstance:   msgTypes = 0e
06-06 13:16:59.056  4464 10001 D BluetoothMapMasInstance:   masName = SMS/MMS
06-06 13:16:59.056  4464 10001 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
06-06 13:16:59.056  9707  9707 D LIA_SmartSetting(4.50.6)_Recommender: is not interactive
06-06 13:16:59.056  9707  9707 V LIA_SmartSetting(4.50.6)_DeviceLogger: DeviceLogger.log: DeviceSettingProfile [profileId=-1, timestamp=1465211819067, , settingStatus=Bluetooth on, deviceTypeOrdinal=1]
,06-06 13:16:59.066  4464 10002 V BluetoothPbapService: Pbap Service initSocket
,06-06 13:16:59.066  9704  9704 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
06-06 13:16:59.066  9704  9704 W wpa_supplicant: wlan0: Failed to initiate AP scan
,06-06 13:16:59.066  1277  4171 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-06 13:16:59.066  1277  3751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-06 13:16:59.066  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:16:59.066  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManagerDBAdapter: insert start
06-06 13:16:59.066  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,06-06 13:16:59.066  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:59.066  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:59.066  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:59.066  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:16:59.066  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:16:59.076  1277  1277 D WifiHS20: hidePasspointNotification off =false
06-06 13:16:59.076  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:16:59.076  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:16:59.076  4464 10002 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-06 13:16:59.076  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:16:59.076  1277  1277 D WifiServerServiceExt: setSupplicantStateSCANNING
,06-06 13:16:59.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:16:59.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:16:59.076  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:16:59.076  4464 10001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
06-06 13:16:59.076  4464 10002 I bt-btif : BTA_JvCreateRecordByUser
06-06 13:16:59.076  4464  9813 I bt-btif : BTA_JvRfcommStartServer
06-06 13:16:59.076  4464 10002 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=86 mFd=0
06-06 13:16:59.076  4464 10002 V BluetoothPbapService: Succeed to create listening socket 
06-06 13:16:59.076  4464 10002 V BluetoothPbapService: Accepting socket connection...
,06-06 13:16:59.076  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:16:59.076  1277  1277 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
06-06 13:16:59.076  4464 10001 I bt-btif : BTA_JvCreateRecordByUser
06-06 13:16:59.076  4464  9813 I bt-btif : BTA_JvRfcommStartServer
06-06 13:16:59.076  4464 10001 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=88 mFd=86
06-06 13:16:59.076  4464 10001 V BluetoothMapMasInstance: Succeed to create listening socket 
06-06 13:16:59.076  4464 10001 D BluetoothMapMasInstance: Accepting socket connection...
,06-06 13:16:59.076  9938  9938 D UEI.SmartControl: ---- Waiting for ACK:
06-06 13:16:59.076  9938  9938 D UEI.SmartControl: waitForEvent: 80
06-06 13:16:59.076  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:16:59.086  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.086  1277  1358 D BluetoothManagerService: Message: 30
,06-06 13:16:59.086  9938  9995 D UEI.SmartControl: serial port data available: 3 - 1
06-06 13:16:59.086  9938  9995 D UEI.SmartControl: serial port data available: 15 - 2
,06-06 13:16:59.086  9938  9938 D UEI.SmartControl: waitForEvent: duration = 9
06-06 13:16:59.086  9938  9938 D UEI.SmartControl: ---- Got ACK: recData = 3
06-06 13:16:59.086  9938  9938 D UEI.SmartControl: waitForReply data length:  15
,06-06 13:16:59.086  9730  9730 D LocalBluetoothProfileManager: Adding local HEADSET profile
,06-06 13:16:59.096  1277  1358 D BluetoothManagerService: Message: 30
,06-06 13:16:59.096  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:16:59.096  9938  9938 D UEI.SmartControl: ------ i-Two Version: 170004170001
06-06 13:16:59.096  9938  9938 D UEI.SmartControl: X4 firmware supports checksum!
06-06 13:16:59.096  9938  9938 I UEI.SmartControl: IR Blaster version: 170004170001
06-06 13:16:59.096  9938  9938 D UEI.SmartControl: X4 firmware supports checksum!
06-06 13:16:59.096  9938  9938 I UEI.SmartControl: QS saving settings...
,06-06 13:16:59.096  9707  9707 D LIA_SmartSetting(4.50.6)_LocationDBManager: insertSettingInfo ID = 7771
,06-06 13:16:59.096  1277  1358 D BluetoothManagerService: Message: 30
,06-06 13:16:59.096  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.096  9938  9938 D UEI.SmartControl: IR Blaster version: 170004170001
06-06 13:16:59.106  9730  9730 I LGBluetoothContextForResources: [BTUI] create LGBluetoothContextForResources new Instance
06-06 13:16:59.106  9730  9730 D LGBluetoothContextForResources: context.getPackageName : com.lge.bluetoothsetting
06-06 13:16:59.106  9730  9730 D LGBluetoothContextForResources: mBluetoothContext.getPackageName : com.lge.bluetoothsetting
06-06 13:16:59.106  9730  9730 D PanProfile: mainContext : com.lge.bluetoothsetting
06-06 13:16:59.106  9938  9938 E UEI.SmartControl: Services init done
06-06 13:16:59.106  1277  1358 D BluetoothManagerService: Message: 30
06-06 13:16:59.106  9938  9938 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1870 android.content.ContextWrapper.bindService:539 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,06-06 13:16:59.106  9938 10005 D UEI.SmartControl: DeviceManager.load starts...
,06-06 13:16:59.106  9938 10005 I UEI.SmartControl: Device manager: loading config....
,06-06 13:16:59.106  9938 10005 D UEI.SmartControl: ----------- loading internal config...
06-06 13:16:59.106  9938 10005 D UEI.SmartControl: ----------- reading config...
06-06 13:16:59.106  9938 10005 D UEI.SmartControl: --- decode config data: 146
06-06 13:16:59.106  9730  9730 D LocalBluetoothProfileManager: Adding local MAP profile
06-06 13:16:59.106  9938 10005 D UEI.SmartControl: --- Decoded buffer length = 194
06-06 13:16:59.106  9938 10005 D UEI.SmartControl: --- decoding is done
06-06 13:16:59.106  9938  9938 D UEI.SmartControl: QS Service init finished
06-06 13:16:59.106  9938  9938 D UEI.SmartControl: QS Service version name: 3.0.019
06-06 13:16:59.106  9938  9938 D UEI.SmartControl: QS Service version code: 300019
06-06 13:16:59.106  9730  9730 D BluetoothMap: Create BluetoothMap proxy object
06-06 13:16:59.106  9938  9938 D UEI.SmartControl: Service requested: Setup
06-06 13:16:59.106  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.106  1277  1358 D BluetoothManagerService: Message: 30
,06-06 13:16:59.116  9938  9938 D UEI.SmartControl: Service requested: Control
,06-06 13:16:59.116  1277  1358 D BluetoothManagerService: Message: 400
06-06 13:16:59.116  9938  9938 D UEI.SmartControl: Internal service binding...
06-06 13:16:59.116  4689  4708 D BluetoothHeadset: Proxy object connected
06-06 13:16:59.116  4464 10000 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.116  9917  9917 D QRemoteSDK: [UeiIrBlasterInitializer.java:196:onServiceConnected()] oooooo Setup connected.
06-06 13:16:59.116  4464  4491 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.116  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:16:59.116  9730  9730 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-06 13:16:59.116  1277  1358 D BluetoothManagerService: Message: 30
06-06 13:16:59.116  9938  9956 I UEI.SmartControl: ------ ISetup API: 4
06-06 13:16:59.116  1277  1358 D BluetoothManagerService: Message: 400
06-06 13:16:59.116  4464  4464 V BluetoothPbapService: Pbap Service onBind
06-06 13:16:59.116  9938  9956 I UEI.SmartControl: Last result code = 9(Quickset Services are not ready)
06-06 13:16:59.116  4078  4103 D BluetoothHeadset: Proxy object connected
,06-06 13:16:59.116  9938 10005 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,06-06 13:16:59.116  9730  9730 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-06 13:16:59.126  1277  1358 D BluetoothManagerService: Message: 400
06-06 13:16:59.126  9938 10005 D UEI.SmartControl: DeviceManager.load finished.
06-06 13:16:59.126  1277  1358 D BluetoothHeadset: Proxy object connected
,06-06 13:16:59.126  1277  1358 D BluetoothManagerService: Message: 400
06-06 13:16:59.126  4078  4105 D BluetoothHeadset: Proxy object connected
,06-06 13:16:59.126  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.126  9917  9917 D QRemoteSDK: [UeiBackupRestore.java:61:getBackupFile()] oooooo QRemote Device backup path : /data/data/com.lge.qremote/Device.bin
06-06 13:16:59.126  9730  9730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1870 android.content.ContextWrapper.bindService:539 com.lge.bluetoothsetting.LGBluetoothUserBindClient.initUserBindClient:98 com.lge.bluetoothsetting.LGBluetoothUserBindClient.<init>:57 com.lge.bluetoothsetting.LGBluetoothUserBindClient.getInstance:47 
,06-06 13:16:59.126  9938  9957 I UEI.SmartControl: ------ ISetup API: 26
,06-06 13:16:59.126  1277  1358 D BluetoothManagerService: Message: 400
06-06 13:16:59.126  9938  9957 I UEI.SmartControl: Registering Services Ready callback...
06-06 13:16:59.126  4078  5296 D BluetoothHeadset: Proxy object connected
06-06 13:16:59.126  9938  9957 I UEI.SmartControl: Notify client services are ready...
06-06 13:16:59.126  9917  9935 D QRemoteSDK: [UeiIrBlasterInitializer.java:146:QSSetupIsReady()] oooooo Blaster ready: statusCode = 9
06-06 13:16:59.126  9917  9935 D QRemoteSDK: [UeiIrBlasterInitializer.java:150:QSSetupIsReady()] oooooo Blaster ready Error: Quickset Services are not ready
06-06 13:16:59.126  9917  9917 D QRemoteSDK: [UeiIrBlasterInitializer.java:239:onServiceConnected()] oooooo Control connected.
06-06 13:16:59.126  9917  9935 W QRemoteSDK: [IrBlasterProListenerArray.java:95:execCycle()] oooooo There are no callbacks in the list to call.
,06-06 13:16:59.126  9917  9917 I QRemoteSDK: [UeiIrBlasterInitializer.java:414:handleSetupDisconnected()] oooooo  handleSetupDisconnected true is bindingfalse
,06-06 13:16:59.136  9730  9730 D DockEventReceiver: finishStartingService: stopping service
06-06 13:16:59.136  9938 10004 D UEI.SmartControl:  --- Service is ready...
06-06 13:16:59.136  9938 10004 I UEI.SmartControl: Notify AllClients services are ready: 0
06-06 13:16:59.136  9730  9730 D BluetoothA2dp: Proxy object connected
06-06 13:16:59.136  9917  9934 D QRemoteSDK: [UeiIrBlasterInitializer.java:146:QSSetupIsReady()] oooooo Blaster ready: statusCode = 0
06-06 13:16:59.136  9730  9730 D A2dpProfile: Bluetooth service connected
06-06 13:16:59.136  9938  9956 I UEI.SmartControl: ------ IControl API: 11
,06-06 13:16:59.136  9938  9956 I UEI.SmartControl: Registering callback...
06-06 13:16:59.136  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.136  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.136  9730  9730 D LGBluetoothProfileConnectionReceiver_LGSettingsAPK: onReceive(), ConnectedDeviceName : null , Num : 0
06-06 13:16:59.136  9730  9730 D BluetoothInputDevice: Proxy object connected
06-06 13:16:59.136  9938  9957 I UEI.SmartControl: ------ ISetup API: 1
06-06 13:16:59.136  9730  9730 D HidProfile: Bluetooth service connected
06-06 13:16:59.136  9938  9957 I UEI.SmartControl: Activating Quickset services....
06-06 13:16:59.136  9938  9957 I UEI.SmartControl: QS saving settings...
06-06 13:16:59.136  9917 10011 D QRemoteSDK: [UeiIrBlasterInitializer.java:359:run()] oooooo Setup service activated.
06-06 13:16:59.136  9917 10011 D QRemoteSDK: [UeiIrBlasterInitializer.java:369:run()] oooooo Setup initialized.
06-06 13:16:59.136  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.136  4464  4464 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
06-06 13:16:59.136  9938  9957 I UEI.SmartControl: ------ ISetup API: 24
06-06 13:16:59.136  9938  9956 I UEI.SmartControl: ------ ISetup API: 3
,06-06 13:16:59.146  9730  9730 D BluetoothPan: BluetoothPAN Proxy object connected
06-06 13:16:59.146  9938  9957 I UEI.SmartControl: ------ ISetup API: 24
06-06 13:16:59.146  9730  9730 D PanProfile: Bluetooth service connected
,06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ------ ISetup API: 28
06-06 13:16:59.146  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ---- get Device Categories ----
,06-06 13:16:59.146  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:16:59.146  9730  9730 D BluetoothMap: Proxy object connected
,06-06 13:16:59.146  9730  9730 D MapProfile: Bluetooth service connected
06-06 13:16:59.146  9730  9730 D BluetoothMap: getConnectedDevices()
,06-06 13:16:59.146  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:16:59.146  4464  4491 V BluetoothMapService: getConnectedDevices()
06-06 13:16:59.146  9938  9956 D UEI.SmartControl: Retrieving Device Types: TV
06-06 13:16:59.146  9938  9956 D UEI.SmartControl: Retrieving Device Types: STB
06-06 13:16:59.146  9938  9956 D UEI.SmartControl: Retrieving Device Types: Audio
06-06 13:16:59.146  9938  9956 D UEI.SmartControl: Retrieving Device Types: Video Projector
06-06 13:16:59.146  9938  9956 D UEI.SmartControl: Retrieving Device Types: AirCon
06-06 13:16:59.146  9938  9956 D UEI.SmartControl: Retrieving Device Types: AirCon_Complex
,06-06 13:16:59.146  9730  9730 D BluetoothPbap: Proxy object connected
06-06 13:16:59.146  9730  9730 D PbapServerProfile: Bluetooth service connected
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: Device Type: TV
06-06 13:16:59.146  9730  9730 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ===> 0: TV - T
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: Device Type: STB
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ===> 1: STB - C,N,S
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: Device Type: Audio
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ===> 2: Audio - A,D,M,R
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: Device Type: Video Projector
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ===> 3: Video Projector - T
,06-06 13:16:59.146  9938  9956 I UEI.SmartControl: Device Type: AirCon
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ===> 4: AirCon - H
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: Device Type: AirCon_Complex
06-06 13:16:59.146  9938  9956 I UEI.SmartControl: ===> 5: AirCon_Complex - Z
06-06 13:16:59.146  4464  4464 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
06-06 13:16:59.146  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.156  1277  3645 I ActivityManager: Killing 9191:com.android.contacts/u0a18 (adj 15): empty #22
,06-06 13:16:59.156  9938  9956 D UEI.SmartControl: Retrieving Device Types: TV
06-06 13:16:59.156  9938  9956 D UEI.SmartControl: Retrieving Device Types: STB
06-06 13:16:59.156  9938  9956 D UEI.SmartControl: Retrieving Device Types: Audio
06-06 13:16:59.156  9938  9956 D UEI.SmartControl: Retrieving Device Types: Video Projector
06-06 13:16:59.156  9938  9956 D UEI.SmartControl: Retrieving Device Types: AirCon
06-06 13:16:59.156  9938  9956 D UEI.SmartControl: Retrieving Device Types: AirCon_Complex
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device Type: TV
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ===> 0: TV - T
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device Type: STB
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ===> 1: STB - C,N,S
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device Type: Audio
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ===> 2: Audio - A,D,M,R
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device Type: Video Projector
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ===> 3: Video Projector - T
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device Type: AirCon
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ===> 4: AirCon - H
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device Type: AirCon_Complex
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ===> 5: AirCon_Complex - Z
06-06 13:16:59.156  9938  9956 I UEI.SmartControl:  #### Device type: TV
06-06 13:16:59.156  9938  9956 I UEI.SmartControl:  #### Device type: STB
06-06 13:16:59.156  9938  9956 I UEI.SmartControl:  #### Device type: Audio
06-06 13:16:59.156  9938  9956 I UEI.SmartControl:  #### Device type: Video Projector
06-06 13:16:59.156  9938  9956 I UEI.SmartControl:  #### Device type: AirCon
06-06 13:16:59.156  9938  9956 I UEI.SmartControl:  #### Device type: AirCon_Complex
06-06 13:16:59.156  9938  9956 I UEI.SmartControl: Device types count: 6
06-06 13:16:59.156  9917 10011 D QRemoteSDK: [UeiIrBlasterInitializer.java:398:setupOperation()] oooooo Amount of device types: 6
,06-06 13:16:59.156  9938  9957 I UEI.SmartControl: ------ ISetup API: 22
06-06 13:16:59.156  9917 10011 D QRemoteSDK: [UeiIrBlasterUtils.java:91:printLastResultCode()] oooooo retrieve device type:  Last result code = 0 - Success
,06-06 13:16:59.156  9917 10011 I QRemoteSDK: [UeiIrBlasterWrapper.java:579:notifyInitialized()] oooooo Notify setup initialized in Blaster.
06-06 13:16:59.156  9917 10011 W QRemoteSDK: [IrBlasterProListenerArray.java:95:execCycle()] oooooo There are no callbacks in the list to call.
06-06 13:16:59.156  9917 10011 I QRemoteSDK: [UeiIrBlasterWrapper.java:585:notifyInitialized()] oooooo Notify control initialized in Blaster.
,06-06 13:16:59.156  9917  9917 D QRemoteSDK: [IRBlaster.java:178:createIrBlaster()] oooooo Currently blaster use: 3
06-06 13:16:59.156  9938 10014 I UEI.SmartControl: ------ ISetup API: 24
,06-06 13:16:59.156  9938  9956 I UEI.SmartControl: ------ ISetup API: 46
,06-06 13:16:59.166  9938  9956 I UEI.SmartControl: register IRLearningStatusCallback
,06-06 13:16:59.166  9938  9957 I UEI.SmartControl: ------ ISetup API: 24
,06-06 13:16:59.166  9938 10014 I UEI.SmartControl: ------ ISetup API: 8
,06-06 13:16:59.166  9917  9917 V LGMDMManager: Create singleton instance
,06-06 13:16:59.166  9917 10016 D QRemoteSDK: [UeiBrandsRetriever.java:81:retrieveBrandTranslationXML()] oooooo Start getting brand XML from setup service...
,06-06 13:16:59.176  9917 10011 D QRemoteSDK: [UeiIrBlasterUtils.java:53:compareDeviceList()] oooooo All size are same. return NEED_BACKUP
,06-06 13:16:59.176  9917 10011 D QRemoteSDK: [UeiBackupRestore.java:226:runDbRestore()] oooooo 140707:isNeedRestore : 1
06-06 13:16:59.176  9917 10011 D QRemoteSDK: [UeiBackupRestore.java:144:backupDevice()] oooooo 140707:Device Backup running.
06-06 13:16:59.176  9938  9956 I UEI.SmartControl: ------ ISetup API: 8
,06-06 13:16:59.176  9917 10011 D QRemoteSDK: [UeiBackupRestore.java:151:backupDevice()] oooooo 140707:devices:[Lcom.uei.control.Device;@792726f
,06-06 13:16:59.176  9917 10011 D QRemoteSDK: [UeiBackupRestore.java:202:backupDevice()] oooooo 140707:devices is null or length is 0. Backup canceled
,06-06 13:16:59.176  9938  9957 I UEI.SmartControl: ------ ISetup API: 24
,06-06 13:16:59.176  9938 10014 I UEI.SmartControl: ------ ISetup API: 31
06-06 13:16:59.176  9938 10014 D UEI.SmartControl:  --- read brands list....
,06-06 13:16:59.196  1277  1358 D BluetoothManagerService: Message: 400
,06-06 13:16:59.196  9730 10007 D BluetoothHeadset: Proxy object connected
,06-06 13:16:59.196  9730  9730 D HeadsetProfile: Bluetooth service connected
,06-06 13:16:59.196  4464  9999 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:16:59.266  4464  4464 V BluetoothSapReceiver: [BTUI] checkServiceStart
,06-06 13:16:59.276  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:16:59.276  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.286  9730  9730 D BluetoothPermissionRequest: onReceive
,06-06 13:16:59.286  9730  9730 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,06-06 13:16:59.286  9730  9730 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,06-06 13:16:59.296  9730  9730 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,06-06 13:16:59.296  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:16:59.306  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.306  5117  5117 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,06-06 13:16:59.316  5117 10017 D EasyUnlockInitService: Handling intent for initializer IntentService.
,06-06 13:16:59.316  5117  5117 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,06-06 13:16:59.326  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:16:59.336  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:16:59.336  5117 10017 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,06-06 13:16:59.476  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-06 13:16:59.476  9645  9700 I jxcore-log: 
,06-06 13:16:59.716   483  3203 V AudioFlinger: thread 0xf5fab000 type 0 TID 3203 going to sleep
,06-06 13:16:59.736   483  3204 V AudioFlinger: thread 0xf2447000 type 0 TID 3204 going to sleep
06-06 13:16:59.736   483  3206 V AudioFlinger: thread 0xf2491000 type 0 TID 3206 going to sleep
,06-06 13:16:59.766  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-06 13:16:59.766  9645  9700 I jxcore-log: 
,06-06 13:16:59.776  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-06 13:16:59.776  9645  9700 I jxcore-log: 
,06-06 13:16:59.786  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-06 13:16:59.786  9645  9700 I jxcore-log: 
,06-06 13:16:59.796  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-06 13:16:59.796  9645  9700 I jxcore-log: 
,06-06 13:16:59.796  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-06 13:16:59.796  9645  9700 I jxcore-log: 
,06-06 13:17:00.026  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59996
06-06 13:17:00.026  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:17:00.026  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
06-06 13:17:00.036  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:17:00.036  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
06-06 13:17:00.036  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
06-06 13:17:00.036  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:17:00.066  9704  9704 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
06-06 13:17:00.066  9704  9704 W wpa_supplicant: wlan0: Failed to initiate AP scan
,06-06 13:17:00.066  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:17:00.076  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-06 13:17:00.076  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
,06-06 13:17:00.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:00.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:00.076  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:00.076  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:00.086  1277  1277 D WifiHS20: hidePasspointNotification off =false,
06-06 13:17:00.086  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:00.086  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
,06-06 13:17:00.086  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,06-06 13:17:00.086  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:17:00.086  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:00.086  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:00.086  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:00.086  1277  1277 D WifiServerServiceExt: setSupplicantStateSCANNING
06-06 13:17:00.086  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:00.086  1277  1277 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,06-06 13:17:00.096  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:00.106  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:00.116  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.066  9704  9704 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
06-06 13:17:01.066  9704  9704 W wpa_supplicant: wlan0: Failed to initiate AP scan
,06-06 13:17:01.076  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:01.076  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.076  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
06-06 13:17:01.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.076  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.076  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:01.086  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:01.086  1277  1277 D WifiHS20: hidePasspointNotification off =false
06-06 13:17:01.086  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:17:01.086  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.086  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-06 13:17:01.086  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.086  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.086  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:01.086  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,06-06 13:17:01.086  1277  1277 D WifiServerServiceExt: setSupplicantStateSCANNING
06-06 13:17:01.086  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:01.086  1277  1277 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,06-06 13:17:01.096  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.116  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:01.116  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.316  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-06 13:17:01.316  9645  9700 I jxcore-log: 
,06-06 13:17:01.326  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-06 13:17:01.326  9645  9700 I jxcore-log: 
,06-06 13:17:01.336  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-06 13:17:01.336  9645  9700 I jxcore-log: 
,06-06 13:17:01.406  9704  9704 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
06-06 13:17:01.406  9704  9704 I wpa_supplicant: P2P: class:115 ch:40 PASSIVE
06-06 13:17:01.406  9704  9704 I wpa_supplicant: P2P: class:115 ch:44 PASSIVE
06-06 13:17:01.406  9704  9704 I wpa_supplicant: P2P: class:115 ch:48 PASSIVE
06-06 13:17:01.406  4025  9868 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,06-06 13:17:01.406  1277  3188 E WifiNative-wlan0: doBoolean: enable
,06-06 13:17:01.436  1277  3188 E WifiAutoJoinController : noInternetAccess :true SSID : "NG700"
06-06 13:17:01.436  1277  3188 E WifiAutoJoinController : isLastSelected  :false
,06-06 13:17:01.436  1277  3188 E WifiStateMachine: WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
06-06 13:17:01.436  1277  3188 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,06-06 13:17:01.446  1277  3188 E WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
06-06 13:17:01.446  1277  3188 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-06 13:17:01.446  1277  1277 D LocSvc_java: onReceive
06-06 13:17:01.446  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,06-06 13:17:01.446  9781  9781 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,06-06 13:17:01.446  1277  3188 E WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
06-06 13:17:01.456  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-06 13:17:01.456  9645  9700 I jxcore-log: 
,06-06 13:17:01.506  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-06 13:17:01.506  9645  9700 I jxcore-log: 
,06-06 13:17:01.536  1277  3188 E WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,06-06 13:17:01.546  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-06 13:17:01.546  9645  9700 I jxcore-log: 
,06-06 13:17:01.556  9704  9704 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
06-06 13:17:01.556  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-06 13:17:01.556  9645  9700 I jxcore-log: 
,06-06 13:17:01.576  1277  3188 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
,06-06 13:17:01.576  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:01.576  1277  1277 D WifiServerServiceExt: setSupplicantStateASSOCIATING
06-06 13:17:01.576  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:01.576  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.576  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-06 13:17:01.586  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.586  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.586  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:01.586  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:01.586  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.696  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-06 13:17:01.696  9645  9700 I jxcore-log: 
,06-06 13:17:01.706  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-06 13:17:01.706  9645  9700 I jxcore-log: 
,06-06 13:17:01.716  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-06 13:17:01.716  9645  9700 I jxcore-log: 
,06-06 13:17:01.716  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-06 13:17:01.716  9645  9700 I jxcore-log: 
,06-06 13:17:01.726  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-06 13:17:01.726  9645  9700 I jxcore-log: 
,06-06 13:17:01.746  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-06 13:17:01.746  9645  9700 I jxcore-log: 
,06-06 13:17:01.746  9704  9704 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,06-06 13:17:01.756  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:01.756  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.756  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,06-06 13:17:01.756  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.756  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.756  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:17:01.756  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.756  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.756  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.756  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:17:01.756  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-06 13:17:01.756  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:01.756  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:01.756  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:01.756  1277  1277 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,06-06 13:17:01.766  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.776  9704  9704 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,06-06 13:17:01.776  9704  9704 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
06-06 13:17:01.776   477  1246 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,06-06 13:17:01.776  1277  1356 D Tethering: interfaceLinkStateChanged wlan0, true
06-06 13:17:01.776  1277  1356 D Tethering: interfaceStatusChanged wlan0, true
,06-06 13:17:01.776  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:01.776  1277  1277 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,06-06 13:17:01.786  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:01.786  1277  3188 I WifiServiceExtension: setVHTCapabilityType  : false
,06-06 13:17:01.786  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.786  1277  3188 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
06-06 13:17:01.786  1277  3188 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
06-06 13:17:01.786  1277  3188 I WifiServiceExtension: setSecurityType  : 2
,06-06 13:17:01.796  1277  3188 E WifiNative-wlan0: doBoolean: disable
06-06 13:17:01.796  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:17:01.796  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.796  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
06-06 13:17:01.796  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.796  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.796  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:01.796  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:01.796  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-06 13:17:01.796  9645  9700 I jxcore-log: 
06-06 13:17:01.796  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:17:01.806  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.806  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
06-06 13:17:01.806  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.806  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.806  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:01.806  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-06 13:17:01.806  9645  9700 I jxcore-log: 
,06-06 13:17:01.806  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.816  1277  3188 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
06-06 13:17:01.816  1277  3194 D ConnectivityService: Got NetworkAgent Messenger
,06-06 13:17:01.816  1277  3188 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@fa3303e
06-06 13:17:01.816  1277 10020 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@35f098f9
,06-06 13:17:01.816  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:01.816  1277  3194 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
06-06 13:17:01.816  1277  3194 D ConnectivityService: NetworkAgent connected
,06-06 13:17:01.816  9645  9700 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-06 13:17:01.816  9645  9700 I jxcore-log: 
,06-06 13:17:01.826  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.826  4078  5366 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-06 13:17:01.826  4078  5366 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
06-06 13:17:01.826  4025  4042 D WifiServiceExtension: isInternetCheckAvailable return false
06-06 13:17:01.826  1277  3188 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-06 13:17:01.826  4464  4484 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
,06-06 13:17:01.826  9645  9700 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
06-06 13:17:01.826  9645  9700 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
06-06 13:17:01.826  9645  9700 I jxcore-log: 
,06-06 13:17:01.836  1277  3188 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-06 13:17:01.836  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:01.836  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:01.836  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,06-06 13:17:01.836  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:01.836  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:01.836  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:17:01.836  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-06 13:17:01.836  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:01.846   477  1246 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
06-06 13:17:01.846  1277  3188 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:01.846  1277  3188 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:01.846   477  1253 D CommandListener: Setting iface cfg
,06-06 13:17:01.846  1277  1356 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:01.846  1277  1356 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:01.856  1277 10021 D DhcpStateMachine: StoppedState
06-06 13:17:01.856  1277  3188 E WifiStateMachine: Start Dhcp Watchdog 1
06-06 13:17:01.856  1277 10021 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,06-06 13:17:01.856  1277 10021 D DhcpStateMachine: WaitBeforeStartState
,06-06 13:17:01.856  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 (has extras) }
,06-06 13:17:01.856  1277  3194 D ConnectivityService: ignoring duplicate network state non-change
,06-06 13:17:01.866  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-06 13:17:01.866  9645  9700 I jxcore-log: 
06-06 13:17:01.866  1277  3194 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-06 13:17:01.866  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-06 13:17:01.866  9645  9700 I jxcore-log: 
,06-06 13:17:01.946  1277  3188 E WifiStateMachine: scanCount==0 - aborting
,06-06 13:17:01.946  1277  3188 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,06-06 13:17:01.946  1277  3188 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-06 13:17:01.946  1277 10021 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
06-06 13:17:01.946  1277 10021 D DhcpStateMachine: DHCP Start wake lock is acquired.
06-06 13:17:01.946  1277  3188 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-06 13:17:01.946  1277  3188 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
,06-06 13:17:01.956  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:01.956  1277  1277 D WifiServerServiceExt: setSupplicantStateCOMPLETED
06-06 13:17:01.956  1277  1277 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-06 13:17:01.956  1277  1277 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,06-06 13:17:02.156  1277 10021 D DhcpStateMachine: DHCPV4 request on wlan0
,06-06 13:17:02.156  1277 10021 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
06-06 13:17:02.156  1277 10021 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,06-06 13:17:02.176 10022 10022 I dhcpcd  : version 5.5.6 starting
,06-06 13:17:02.176 10022 10022 E dhcpcd  : get_duid: Read-only file system
,06-06 13:17:02.226   589   589 I MSM-irqbalance: Discovered a new IRQ: 146
,06-06 13:17:02.226   589   589 I MSM-irqbalance: Decided to move IRQ240 from CPU1 to CPU0
,06-06 13:17:02.246 10022 10022 I dhcpcd  : wlan0: broadcasting for a lease
,06-06 13:17:02.856   477  1246 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,06-06 13:17:02.856  1277  1356 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:02.856  1277  1356 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:02.876  1277  3194 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,06-06 13:17:03.186 10022 10022 I dhcpcd  : wlan0: offered 192.168.1.101 from 192.168.1.1
,06-06 13:17:03.196 10022 10022 I dhcpcd  : wlan0: acknowledged 192.168.1.101 from 192.168.1.1
,06-06 13:17:03.286 10022 10022 I dhcpcd  : wlan0: leased 192.168.1.101 for 172800 seconds
,06-06 13:17:03.286   477  1246 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,06-06 13:17:03.286  1277  1356 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.296  1277  3194 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
06-06 13:17:03.286  1277  1356 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.566  1277 10021 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.566  1277 10021 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,06-06 13:17:03.576  1277 10021 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 5
06-06 13:17:03.576  1277 10021 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
06-06 13:17:03.576  1277 10021 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.576  1277 10021 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.576  1277 10021 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.101
06-06 13:17:03.576  1277 10021 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
06-06 13:17:03.576  1277 10021 V DhcpStateMachine: Current State is mWaitBeforeStartState.
06-06 13:17:03.576  1277 10021 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
,06-06 13:17:03.576  1277 10021 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,06-06 13:17:03.586  1277 10021 D DhcpStateMachine: RunningState
,06-06 13:17:03.616  1277  3194 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,06-06 13:17:03.616  1277  3194 D ConnectivityService: internetCapabilityChanged : false
,06-06 13:17:03.616  1277  3194 D ConnectivityService: ignoring duplicate network state non-change,
,06-06 13:17:03.626  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:03.626  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
,06-06 13:17:03.636  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,06-06 13:17:03.636  4078  5366 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-06 13:17:03.636  4078  5366 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
06-06 13:17:03.636  4025  4735 D WifiServiceExtension: isInternetCheckAvailable return false
,06-06 13:17:03.646  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:03.646  1277  3194 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,06-06 13:17:03.646  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:17:03.646  1277  3194 D ConnectivityService: Adding iface wlan0 to network 100
,06-06 13:17:03.656  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,06-06 13:17:03.656  4078  4103 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
06-06 13:17:03.656  4078  4103 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
,06-06 13:17:03.656  4025  4042 D WifiServiceExtension: isInternetCheckAvailable return false
06-06 13:17:03.656  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-06 13:17:03.656  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-06 13:17:03.656  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:03.656  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:17:03.656  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
06-06 13:17:03.656  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,06-06 13:17:03.656  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:03.656  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:17:03.666  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
,06-06 13:17:03.666  1277  3188 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,06-06 13:17:03.666  4025  4025 V WfdStateTracker: handleWifiStateChangedEvent: 1
06-06 13:17:03.666  1277  1277 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-06 13:17:03.666  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
06-06 13:17:03.666  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
06-06 13:17:03.666  1277  1277 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
06-06 13:17:03.666  1277  1277 D LgWifiTrafficPoller: ENABLE_TRAFFIC_STATS_POLL, mTriggeringTput = 100Mbits
,06-06 13:17:03.676  1277  1277 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,06-06 13:17:03.676  3340  3340 I [SystemUI]NetworkController: mWifiConnected = true, mWifiLevel = 3
,06-06 13:17:03.676  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,06-06 13:17:03.676  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:03.676  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
06-06 13:17:03.676  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 (has extras) }
,06-06 13:17:03.676  3340  3340 I [SystemUI]NetworkController: mWifiConnected = true, mWifiLevel = 3
06-06 13:17:03.686  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
,06-06 13:17:03.686  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-06 13:17:03.686  3340  3340 I [SystemUI]QuickSettingsHandler: Remote
,06-06 13:17:03.686   477  1253 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-06 13:17:03.686  1277  3194 E ConnectivityService: Unexpected mtu value: 0, wlan0
06-06 13:17:03.686   477  1253 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.686  1277  3194 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
06-06 13:17:03.686   477  1253 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-06 13:17:03.686   477  1253 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.686  1277  3194 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,06-06 13:17:03.686   477  1253 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-06 13:17:03.686   477  1253 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.696  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:03.696   477  1253 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-06 13:17:03.696   477  1253 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.696  1277  3194 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
06-06 13:17:03.696   477  1253 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
06-06 13:17:03.696   477  1253 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.696  1277  3194 D ConnectivityService: addLocalRoutetoDefaultNetwork
06-06 13:17:03.696  1277  3194 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
,06-06 13:17:03.696  1277  3194 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
06-06 13:17:03.696  1277  3194 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.696  1277  3194 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.706  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-06 13:17:03.706   477  1253 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
06-06 13:17:03.706   477  1253 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.706  1277  3194 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,06-06 13:17:03.706  1277  3194 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=213157
,06-06 13:17:03.706  1277  3194 D NetworkManagementService: getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=213158
06-06 13:17:03.706  1277  3194 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=1152 rxPackets=2 txBytes=196 txPackets=3 operations=0
06-06 13:17:03.706  1277  3194 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
,06-06 13:17:03.716  1277  3194 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=213159
06-06 13:17:03.716  1277  3194 D NetworkManagementService: getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=213161
06-06 13:17:03.716  1277  3194 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=1452 rxPackets=5 txBytes=1198 txPackets=7 operations=0
06-06 13:17:03.716  1277  3194 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
06-06 13:17:03.716  1277  3194 V NetworkStats: [LG_RESTRICTED] capa :[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-06 13:17:03.716  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:03.716  1277  3194 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,06-06 13:17:03.716  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-06 13:17:03.716  1277  3194 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=213166
,06-06 13:17:03.716  1277  3194 D NetworkManagementService: getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=213168
06-06 13:17:03.716  1277  3194 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=1152 rxPackets=2 txBytes=196 txPackets=3 operations=0
06-06 13:17:03.716  1277  3194 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
,06-06 13:17:03.716  1277  3194 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=213168
,06-06 13:17:03.726  1277  3194 D NetworkManagementService: getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=213169
06-06 13:17:03.726  1277  3194 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=1452 rxPackets=5 txBytes=1198 txPackets=7 operations=0
06-06 13:17:03.726  1277  3194 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
06-06 13:17:03.726  1277  3194 V NetworkStats: [LG_RESTRICTED] capa :[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:03.726  1277  3194 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
06-06 13:17:03.726  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-06 13:17:03.726  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
06-06 13:17:03.726  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-06 13:17:03.726  1277  3194 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-06 13:17:03.726  1277  3194 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:03.726  1277  3194 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-06 13:17:03.726  1277  3194 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-06 13:17:03.726  1277  3194 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.726  1277  3194 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
06-06 13:17:03.726  1277  3194 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.726  1277  3194 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
06-06 13:17:03.726  1277  3194 D ConnectivityService: currentScore = 0, newScore = 20
06-06 13:17:03.726  1277  3194 D ConnectivityService:    accepting network in place of null
06-06 13:17:03.726  1277  3194 D ConnectivityService: Canceling linger of NetworkAgentInfo [WIFI () - 100]
,06-06 13:17:03.726  1277  3188 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.726  1277  3194 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.726  1277  3188 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:03.726  1277  3188 D WIFI_UT : evalRequest
06-06 13:17:03.726  1277  3188 D WIFI_UT :   done
06-06 13:17:03.726  1277  3188 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.726  1277  3188 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:03.726  1277  3188 D WIFI    : evalRequest
06-06 13:17:03.726  1277  3194 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe6f:c95d/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} } for legacy network type 1
06-06 13:17:03.726  1277  3188 D WIFI    :   done
06-06 13:17:03.726  1277  3194 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
06-06 13:17:03.726  1277  3194 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-06 13:17:03.726  1277  3194 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
06-06 13:17:03.726  1277  1277 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,06-06 13:17:03.726  4045  4045 W QCNEJ   : |CORE| No family connected
06-06 13:17:03.726  1277  1277 D FastDownloadService: [FastDN][FDS] received CONNECTIVITY_ACTION_IMMEDIATE for WIFI detailedState: CONNECTED
06-06 13:17:03.726  1277  1358 D Tethering: MasterInitialState.processMessage what=3
06-06 13:17:03.726  1277  1277 D FastDownloadService: [FastDN][FDS] WIFI is connected
06-06 13:17:03.726  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,06-06 13:17:03.726  4078  4078 D [LGE_DATA][PayPopUp_ko] : intent received :android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-06 13:17:03.726  1277  3194 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
06-06 13:17:03.726  1277  1277 D LocSvc_java: onReceive
06-06 13:17:03.726  1277  1277 D FastDownloadService: [FastDN][FDS] [getLocalAddress] Interface: wlan0, ipv4_addr: /192.168.1.101
06-06 13:17:03.726  1277  1277 D LocSvc_java: got connectivity action
06-06 13:17:03.726  1277  3194 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe6f:c95d/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
06-06 13:17:03.726  1277  1277 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
06-06 13:17:03.726  1277  1277 D FastDownloadService: [FastDN][FDS] received CONNECTIVITY_ACTION for WIFI detailedState: CONNECTED
06-06 13:17:03.726  1277  1277 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
06-06 13:17:03.736  1277  1314 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,06-06 13:17:03.736  1277  3194 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
06-06 13:17:03.736  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] Start DNSResolver start to wait
,06-06 13:17:03.736  1277 10054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] wait 500ms before dns check
,06-06 13:17:03.736  1277  3194 D ConnectivityService: validation of new default Network = false
06-06 13:17:03.736  1277  3194 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
06-06 13:17:03.736  4464  9713 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:17:03.736  1277  3194 D DSQN    : enableDataServiceNotify 
06-06 13:17:03.736  1277  3194 D DSQN    : start dsqn bin
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-06 13:17:03.736  9645  9645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-06 13:17:03.736  1277  1277 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-06 13:17:03.746  1277  1277 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-06 13:17:03.746  1277  1277 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-06 13:17:03.746  1277  1277 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
,06-06 13:17:03.746  1277  4024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.746  1277  4024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.746  1277  4024 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.746  1277  4024 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:03.746   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:03.746   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-06 13:17:03.746  1277  3186 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.746  1277  3186 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:03.746  1277  3186 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.746  1277  3186 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:03.746   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:03.746   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-06 13:17:03.746   477 10057 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:03.746   477 10057 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:03.746   477 10057 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:03.746  4464  9999 D BluetoothAdapterService(264956278): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1001cc05
06-06 13:17:03.746  1277 10055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.746  1277 10055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.746   477 10057 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:03.746  1277 10055 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.746   477 10056 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:03.746   477 10056 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:03.746  1277 10055 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:03.746  9645  9645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-06 13:17:03.746   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:03.746   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:03.746   477 10056 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:03.746  9645  9700 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-06 13:17:03.746  9645  9700 I jxcore-log: 
,06-06 13:17:03.746   477 10056 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:03.756  1277  3194 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-06 13:17:03.756  1277  3194 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.756  1277  3194 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,06-06 13:17:03.756  9781  9781 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-06 13:17:03.756  1277  3194 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-06 13:17:03.756  3340  3771 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-06 13:17:03.756  1277  3194 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.756  7556  9590 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-06 13:17:03.756  1277  3194 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:03.756  1277  3194 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe6f:c95d/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} } for legacy network type 1
,06-06 13:17:03.756  1277  3194 E ConnectivityService: Attempting to register duplicate agent for type 1: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe6f:c95d/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,06-06 13:17:03.756   477 10058 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:03.756   477 10058 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:03.756   477 10058 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:03.756   477 10058 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:03.756 10059 10059 I DSQN    : DSQN samuel.seo ver 141203
06-06 13:17:03.756 10059 10059 E DSQN    : DSQN sock connect success to lgdatalistenerd
06-06 13:17:03.756 10059 10059 I DSQN    : created command queue thread
06-06 13:17:03.756 10059 10059 I DSQN    : Interface wlan0 address 192.168.1.101 0xc0a80165
06-06 13:17:03.756 10059 10059 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80165
,06-06 13:17:03.766  9512  9512 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-06 13:17:03.766  3340  3340 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,06-06 13:17:03.776  9781  9781 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,06-06 13:17:03.796  9512  9512 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-06 13:17:03.826  1277  1314 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-06 13:17:03.876  1277  4193 I ActivityManager: Start proc 10071:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor
,06-06 13:17:03.876   477 10056 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:03.876   477 10057 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:03.876  1277  3186 I System.out: propertyValue:false
06-06 13:17:03.876   477 10058 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:03.876  1277  4024 I System.out: propertyValue:false
06-06 13:17:03.876  1277 10055 I System.out: propertyValue:false
,06-06 13:17:03.876  1277  1314 E GpsLocationProvider: No APN found to select.
,06-06 13:17:03.886  1277 10087 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
,06-06 13:17:03.886  1277 10087 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.886  1277 10087 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.896  1277 10089 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.896  1277 10089 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:03.896  1277 10089 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:03.896  1277 10089 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:03.896   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:03.896   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-06 13:17:03.896   477 10095 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:03.896   477 10095 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:03.896   477 10095 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:03.896   477 10095 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:03.926  1277  1314 I NotificationManager: android: cancelAsUser(-1597574061) by android
,06-06 13:17:03.926  7556 10097 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,06-06 13:17:03.936  1277  1314 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 27613, reason: UserStart, SyncResult: databaseError: true stats []
,06-06 13:17:03.936  1277  1314 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 244175, reason: UserStart
06-06 13:17:03.936  1277  1314 I NotificationManager: android: cancelAsUser(716319171) by android
,06-06 13:17:03.946 10071 10071 I AppUp4:AppBoxCP: onCreate
,06-06 13:17:03.946 10071 10071 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-06 13:17:03.946 10071 10071 I AppUp4:DB:  setFingerPrint start
,06-06 13:17:03.946 10071 10071 I AppUp4:DB:  newfinger = lge/p1_global_com/p1:5.1/LMY47D/1520217361856:user/release-keys SDK version = 22
,06-06 13:17:03.956 10071 10071 I AppUp4:DB:  beforefinger = lge/p1_global_com/p1:5.1/LMY47D/1520217361856:user/release-keys
06-06 13:17:03.956 10071 10071 I AppUp4:DB:  SDK version = 22
06-06 13:17:03.956 10071 10071 I AppUp4:DB:  beforefinger == newfinger no write in DB
,06-06 13:17:03.956 10071 10071 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,06-06 13:17:03.956 10071 10071 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-06 13:17:03.956 10071 10071 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,06-06 13:17:03.956 10071 10071 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-06 13:17:03.956 10071 10071 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,06-06 13:17:03.966 10071 10071 I AppUp4:CustModeStarterReceiver: onReceive
06-06 13:17:03.966 10071 10071 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,06-06 13:17:03.966 10071 10071 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2eff809b
06-06 13:17:03.966 10071 10071 D AppUp4:CustFacade: isCustomizationCompleted : false
,06-06 13:17:03.966  1277  4024 D AlarmManagerService: Setting time of day to sec=1465211824
06-06 13:17:04.283  1277  4024 W AlarmManagerService: Unable to set rtc to 1465211824: Invalid argument
,06-06 13:17:04.283 10071 10071 D AppUp4:CustFacade: isSimDevice : true
,06-06 13:17:04.283 10071 10071 V AppUp4:DpFacade:  isStartDpPreload : false
06-06 13:17:04.283 10071 10071 D AppUp4:CustModeStarterReceiver: begin check event
06-06 13:17:04.283 10071 10071 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-06 13:17:04.283 10071 10071 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,06-06 13:17:04.283 10071 10102 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-06 13:17:04.283 10071 10102 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-06 13:17:04.283 10071 10102 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-06 13:17:04.283  1277  1294 I ActivityManager: Killing 9090:com.google.android.googlequicksearchbox:search/u0a63 (adj 15): empty #22
,06-06 13:17:04.283  1277  3186 V NetworkPolicy: [LG_RESTRICTED] capa :[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-06 13:17:04.292  5117  5117 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:04.292  5117  5117 D WearableService: callingUid 10006, callindPid: 5117
,06-06 13:17:04.302  7556 10083 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,06-06 13:17:04.332  1277 10055 D LocSvc_java: NTP server : europe.pool.ntp.org
06-06 13:17:04.332  1277 10087 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
,06-06 13:17:04.332  1277 10055 D LocSvc_java: NTP server returned: 1465211824344 (Mon Jun 06 13:17:04 CEST 2016) reference: 213475 certainty: 76 system time offset: 2
06-06 13:17:04.332  1277 10087 D LgeGpsLocationProvider: NTP server returned: 1465211824339 (Mon Jun 06 13:17:04 CEST 2016) reference: 213475 certainty: 71 system time offset: -3
,06-06 13:17:04.332  1277 10055 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,06-06 13:17:04.342   477 10095 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:04.352  1277 10089 I System.out: propertyValue:false
,06-06 13:17:04.352  1277 10089 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.352  1277 10089 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:04.412  9938 10006 D UEI.SmartControl: Internal timer expired: 1
,06-06 13:17:04.422 10059 10060 I DSQN    : first global connection report this to start monitoring at DSQM.
06-06 13:17:04.422 10059 10060 I DSQN    : restart monitoring
06-06 13:17:04.422   477  1252 D LGDataListener: argv[0]=dsqncommand
06-06 13:17:04.422   477  1252 D LGDataListener: argv[1]=wlan0
06-06 13:17:04.422   477  1252 D LGDataListener: argv[2]=1
06-06 13:17:04.422   477  1252 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
06-06 13:17:04.422 10059 10108 I DSQN    : dsqn report finish
,06-06 13:17:04.422  1277  1356 D DSQN    : DSQM DsqnNotification wlan0  1
06-06 13:17:04.422  1277  1356 D DSQN    : start to monitor internet connection
,06-06 13:17:04.452  9938 10003 D serial_port: close(fd = 29)
,06-06 13:17:04.452  9938 10003 I UEI.SmartControl: Serial port is closed.
,06-06 13:17:04.492  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,06-06 13:17:04.492  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:17:04.512  1277  1314 I NotificationManager: android: cancelAsUser(-591465577) by android
,06-06 13:17:04.512  6383  6383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2701 
,06-06 13:17:04.512  6383  6383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2701 
,06-06 13:17:04.532  1277 10089 D GpsLocationProvider: calling native_inject_xtra_data
,06-06 13:17:04.532  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
06-06 13:17:04.532  7068  7068 D LIA_SmartMoment_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
06-06 13:17:04.532  3340  3340 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
06-06 13:17:04.532  7068  7068 I LIA_SmartMoment_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-06-06 13:17:04...... Request
,06-06 13:17:04.532  7068  7068 I LIA_SmartMoment_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 13, total count : 276, new day : false...... Request
06-06 13:17:04.532  7068  7068 D LIA_SmartMoment_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 276
06-06 13:17:04.532  7068  7068 D LIA_SmartMoment_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 13
06-06 13:17:04.532  7068  7068 D LIA_SmartMoment_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-06-06 13:17:04
06-06 13:17:04.532  7689  7689 I CalendarProvider2: onReceive() android.intent.action.TIME_SET
06-06 13:17:04.532  7689  7689 D CalendarProvider2: Scheduling check of next Alarm
,06-06 13:17:04.542  6383 10110 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [674] : iAgentState=3, isUserType=1
,06-06 13:17:04.542  1277 10054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] DNSResolver start dns
06-06 13:17:04.542  6383 10110 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
06-06 13:17:04.542  1277 10054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.542  1277 10054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:04.542  1277 10054 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
06-06 13:17:04.542  1277 10054 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:04.542   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:04.542   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:04.542   477 10112 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
06-06 13:17:04.542   477 10112 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:04.542   477 10112 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:04.542   477 10112 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:04.542  6383 10111 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-06 13:17:04.542  6383 10111 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-06 13:17:04.582  1277  1317 I ActivityManager: Start proc 10115:com.lge.cic.eden.service/u0a7 for broadcast com.lge.cic.eden.service/com.lge.cic.eden.receiver.EdenBroadcastReceiver
,06-06 13:17:04.582  4278  4278 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:82:updateCalendarShortcut()]date=6 currentDate=-1 dayofweek=2 currentDayOfWeek=-1
06-06 13:17:04.582  6383 10110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1804 android.content.ContextWrapper.startService:516 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,06-06 13:17:04.592  3340  3340 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,06-06 13:17:04.592  4278  4278 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:222:makeCalendarBitmap()]Locale = en_GB dayofweek= Mon date= 6
,06-06 13:17:04.592  5390  5390 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,06-06 13:17:04.602  6383  6383 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,06-06 13:17:04.602  5390  5390 V DownloadManager: DownloadService onCreate
,06-06 13:17:04.602  6404  6404 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-06 13:17:04.602  6404  6404 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,06-06 13:17:04.602  6404  6404 I LgeMiscReceiver: networkInfo.isConnected() = true
06-06 13:17:04.602  6404  6404 D PhoneState: setPdpRejectCasuse : false
,06-06 13:17:04.602  5390  5390 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
,06-06 13:17:04.602   477 10112 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:04.612  1277 10054 I System.out: propertyValue:false
06-06 13:17:04.612  1277 10054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] addr = connectivitycheck.android.com/172.217.21.110
06-06 13:17:04.612  1277 10054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] Connectivity Check server is global. IPv4 domain save this server  for general purpose
06-06 13:17:04.612  1277 10054 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] DNSResolver end dns
,06-06 13:17:04.612  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,06-06 13:17:04.612  5390  5390 V DownloadManager: DownloadService onStartCommand
06-06 13:17:04.612  6383  6383 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
06-06 13:17:04.612  6383  6383 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,06-06 13:17:04.612  5390 10134 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
06-06 13:17:04.612  1277 10020 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.612  1277 10020 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:04.622  5390 10134 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@9f4b227 on behalf of 5390
,06-06 13:17:04.622 10115 10115 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-06 13:17:04.622  4278  4278 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:222:makeCalendarBitmap()]Locale = en_GB dayofweek= Mon date= 6
06-06 13:17:04.622  4278  4278 I [LGHome]Launcher: [Launcher.java:5771:waitUntilResume()]Deferring update until onResume
,06-06 13:17:04.632  5390  5390 V DownloadManager: DownloadService onDestroy
,06-06 13:17:04.652 10115 10115 I EdenDbOpenHelper: sqlite writable database created!
06-06 13:17:04.652 10115 10115 D EdenContentProvider: onCreate()
,06-06 13:17:04.662  5117 10142 I CheckinUtil: Classify the device as Phone.
,06-06 13:17:04.682  9753 10141 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:04.682  9753 10141 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:04.682  9753 10141 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.682  9753 10141 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:04.682   477  1248 E BandwidthController: [LG DATA] No such appUid: 10049
06-06 13:17:04.682   477  1248 D DnsProxyListener: App 10049 tries DNS query. Accept family:0 protocol:0
06-06 13:17:04.682   477 10153 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:04.682   477 10153 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:04.682   477 10153 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:04.682   477 10153 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:04.682  1277  1294 I ActivityManager: Start proc 10145:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver
,06-06 13:17:04.682 10115 10115 I EdenBroadcastReceiver: onReceive()
,06-06 13:17:04.682 10115 10115 D EdenBroadcastReceiver:   action: android.intent.action.TIME_SET, received at: Mon Jun 06 13:17:04 CEST 2016
,06-06 13:17:04.692  1277  1314 I NotificationManager: android: cancelAsUser(353845882) by android
06-06 13:17:04.692 10115 10115 V EdenBroadcastReceiver:     register date. prev = 20160606, current = 20160606
06-06 13:17:04.692 10115 10115 D EdenBroadcastReceiver:   aleady register alarm
,06-06 13:17:04.692 10115 10115 V EdenEventClusteringAlarmHelper:     register date: 20160606
,06-06 13:17:04.692  5117 10106 I PhenotypeConfigurator: Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,06-06 13:17:04.692  5199  5199 D [Concierge][ConciergeService]: onStartCommand(). Type : 11
,06-06 13:17:04.692  5117 10142 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.692  5117 10142 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:04.692  5117 10142 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.692  5117 10142 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:04.702 10115 10115 I EdenEventClusteringAlarmHelper: stopAnalysisIfSatisfiedCondition()
06-06 13:17:04.702 10115 10115 I ServiceTriggeringHelper: stopAnalysisService()
,06-06 13:17:04.702  9753 10140 V FormManager: App version changed.
,06-06 13:17:04.702 10115 10115 I EdenService: onCreate()
06-06 13:17:04.702   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:04.702   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:04.702 10115 10115 I EdenService: Eden Service Engine v0.8.31, code = 3403
06-06 13:17:04.702   477 10168 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:04.702   477 10168 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:04.702   477 10168 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:04.702   477 10168 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:04.712  4278  4278 E [IFTTT]LGIFTTTCategoryLayout: [LGIFTTTCategoryLayout.java:131:getActionLogMap()]getActionLogMap acitonLog List from DB count = 0
,06-06 13:17:04.722 10115 10115 I EdenService: onStartCommand - Intent { cmp=com.lge.cic.eden.service/.EdenService (has extras) }, flags=0, startId=1
06-06 13:17:04.722 10115 10115 V EdenService: onStartCommand - receivedIntentCount : 1
06-06 13:17:04.722 10115 10169 I EdenCommandDispatcher: onCommand(): Intent { cmp=com.lge.cic.eden.service/.EdenService (has extras) }
06-06 13:17:04.722 10115 10169 I EdenCommandDispatcher: command for starting service : STOP_ANALYSIS
,06-06 13:17:04.722 10115 10169 I TaskScheduler: TaskScheduler has been already stopped!! 
,06-06 13:17:04.742  1277  3374 I ActivityManager: Start proc 10171:com.lge.clock/u0a16 for broadcast com.lge.clock/.alarmclock.AlarmInitReceiver
,06-06 13:17:04.742 10115 10169 D TaskScheduler: TaskScheduler (isDone?) : true
,06-06 13:17:04.742 10115 10169 I TaskScheduler: TaskScheduler is started!! 
06-06 13:17:04.742 10115 10169 V EdenService: onHandleIntent - receivedIntentCount : 0
,06-06 13:17:04.742 10115 10169 V EdenController: requestStopService : stopSelf
,06-06 13:17:04.742 10115 10182 I TaskScheduler: A worker of the TaskScheduler is started
,06-06 13:17:04.752 10115 10115 I EdenService: onDestroy()
06-06 13:17:04.752 10115 10115 D TaskScheduler: TaskScheduler (isShutDown and isTerminated) : false , false
06-06 13:17:04.752 10115 10115 D TaskScheduler: TaskScheduler will be stopped!! true,false
,06-06 13:17:04.762 10115 10182 I TaskScheduler: A worker of the TaskScheduler has no task : java.lang.IllegalStateException: There is no task
,06-06 13:17:04.762 10115 10182 I TaskScheduler: A worker of the TaskScheduler is finished
06-06 13:17:04.762 10115 10115 I TaskScheduler: TaskScheduler is stopped!! 
,06-06 13:17:04.762 10115 10115 V EdenService:   destroy time = 14ms
06-06 13:17:04.762 10115 10115 I EdenService: onCreate()
06-06 13:17:04.762 10115 10115 I EdenService: Eden Service Engine v0.8.31, code = 3403
06-06 13:17:04.762 10115 10115 I EdenService: onStartCommand - Intent { cmp=com.lge.cic.eden.service/.EdenService (has extras) }, flags=0, startId=1
06-06 13:17:04.762 10115 10115 V EdenService: onStartCommand - receivedIntentCount : 1
06-06 13:17:04.762 10115 10192 I EdenCommandDispatcher: onCommand(): Intent { cmp=com.lge.cic.eden.service/.EdenService (has extras) }
06-06 13:17:04.762 10115 10192 I EdenCommandDispatcher: command for starting service : REQUEST_STOP_MANAGING_SERVICE
,06-06 13:17:04.762 10115 10192 V EdenController: isMonitoring: falsereceivedIntentCount: 1
06-06 13:17:04.762 10115 10192 V EdenService: onHandleIntent - receivedIntentCount : 0
,06-06 13:17:04.772 10115 10192 V EdenController: requestStopService : stopSelf
,06-06 13:17:04.772 10115 10115 I EdenService: onDestroy()
06-06 13:17:04.772 10115 10115 D TaskScheduler: TaskScheduler (isShutDown and isTerminated) : true , true
06-06 13:17:04.772 10115 10115 I TaskScheduler: TaskScheduler has been already stopped!! 
06-06 13:17:04.772 10115 10115 V EdenService:   destroy time = 0ms
,06-06 13:17:04.792   477 10168 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:04.792  5117 10142 I System.out: propertyValue:false
,06-06 13:17:04.802   477 10153 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:04.802  9753 10141 I System.out: propertyValue:false
,06-06 13:17:04.832 10171 10198 D AlarmClock: setNextAlert
,06-06 13:17:04.832 10171 10198 D AlarmClock: updateTimeForEnabledAlarms
,06-06 13:17:04.842 10171 10198 D AlarmClock: getEarliestAlarmTime
,06-06 13:17:04.852 10171 10198 D AlarmClock: Earliest Alarm Time is Thu 1:00 am[id : 0]
,06-06 13:17:04.872  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 06 Jun 2016 11:17:04 GMT], X-Android-Received-Millis=[1465211824876], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1465211824751]}
06-06 13:17:04.872  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Don't send network conditions - lacking user consent.
,06-06 13:17:04.872  4078  5366 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,06-06 13:17:04.872  4078  5366 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=false
06-06 13:17:04.872  4025  4735 D WifiServiceExtension: isInternetCheckAvailable return false
06-06 13:17:04.872  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] wifi && isInternetCheckAvailable is false
06-06 13:17:04.872  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: [LWD] save succeded connectivityCheck server IP address : connectivitycheck.android.com/172.217.21.110
06-06 13:17:04.872  1277 10020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
06-06 13:17:04.872  1277  3194 I NotificationManager: android: cancel(100) by android
06-06 13:17:04.872  1277  3194 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
06-06 13:17:04.872  5117 10142 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:04.872  1277  3194 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
06-06 13:17:04.872  5117 10142 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:04.872  1277  3194 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
06-06 13:17:04.872  3340  3771 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
06-06 13:17:04.872  1277  3194 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:04.872  1277  3188 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  1277  3194 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
06-06 13:17:04.872  1277  3188 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:04.872  1277  3194 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
06-06 13:17:04.872  1277  3188 D WIFI_UT : evalRequest
06-06 13:17:04.872  1277  3194 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  1277  3188 D WIFI_UT :   done
06-06 13:17:04.872  1277  3194 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
06-06 13:17:04.872  1277  3188 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  1277  3194 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
06-06 13:17:04.872  1277  3188 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-06 13:17:04.872  1277  3194 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
06-06 13:17:04.872  1277  3188 D WIFI    : evalRequest
06-06 13:17:04.872  1277  3194 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  1277  3188 D WIFI    :   done
06-06 13:17:04.872  1277  3194 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-06 13:17:04.872  1277  3194 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
06-06 13:17:04.872  1277  3194 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  ,1277  3194 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  1277  3194 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-06 13:17:04.872  1277  3751 I ActivityManager: Start proc 10199:com.lge.myplace/u0a30 for broadcast com.lge.myplace/.Receiver
06-06 13:17:04.872  1277  3194 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
06-06 13:17:04.882  7556  9590 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-06 13:17:04.882  1277  1277 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
06-06 13:17:04.882  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
06-06 13:17:04.882 10171 10198 I CommonUtil: BUILD Operator: OPEN
06-06 13:17:04.882  1277  3188 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
,06-06 13:17:04.882  1277  1314 I NotificationManager: android: cancelAsUser(-591465577) by android
,06-06 13:17:04.882 10171 10198 V AlarmClock: AlarmInitReceiver finished
,06-06 13:17:04.892 10171 10171 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
,06-06 13:17:04.892 10171 10171 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@fcae976
,06-06 13:17:04.902  1277  4193 I ActivityManager: Killing 9363:com.google.android.apps.plus/u0a122 (adj 15): empty #22
,06-06 13:17:04.902 10171 10171 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@fcae976
,06-06 13:17:04.962  9753 10141 V FormManager: There are no updated forms. The schedule will be deleted.
,06-06 13:17:04.962  9753 10141 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,06-06 13:17:05.122 10171 10171 D QuickCoverProvider: onReceiver
,06-06 13:17:05.162 10199 10199 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-06 13:17:05.172 10199 10199 I [IFTTT] : logServiceEnable 0 is log disable => logServiceEnable value : false
,06-06 13:17:05.172 10199 10199 I [IFTTT]TriggerProvider: [TriggerManager.java:38:registerTriggerProvider()]trigger Provider for /ifttt/v1/triggers/arrive_at_home is registered
,06-06 13:17:05.172 10199 10199 I [IFTTT]TriggerProvider: [TriggerManager.java:38:registerTriggerProvider()]trigger Provider for /ifttt/v1/triggers/leave_from_home is registered
,06-06 13:17:05.182 10199 10199 E MYPLACE_Receiver: onReceive android.net.conn.CONNECTIVITY_CHANGE
06-06 13:17:05.182 10199 10199 E Pref    : get_inner_onoff: false
06-06 13:17:05.182 10199 10199 I MYPLACE_EngineInterface: Stop
,06-06 13:17:05.182  1277  1314 I ActivityManager: Start proc 10222:com.google.android.apps.docs.editors.docs/u0a120 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,06-06 13:17:05.192  1277  1314 I NotificationManager: android: cancelAsUser(-1548111331) by android
,06-06 13:17:05.202  3340  3340 I [SystemUI]NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 (has extras) }
06-06 13:17:05.202  3340  3340 I [SystemUI]NetworkController: mWifiConnected = true, mWifiLevel = 3
,06-06 13:17:05.312  1277  4151 I art     : Explicit concurrent mark sweep GC freed 81709(3MB) AllocSpace objects, 6(352KB) LOS objects, 33% free, 57MB/86MB, paused 2.243ms total 192.259ms
,06-06 13:17:05.322 10171 10171 D QuickCoverProvider: onReceiver
,06-06 13:17:05.322 10199 10199 I MYPLACE_EngineInterface: non Stop 0
06-06 13:17:05.322 10199 10199 E MYPLACE_Utils: activityFinish
,06-06 13:17:05.332  5117 10106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:05.332  5117 10106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:05.332  5117 10106 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:05.332  5117 10106 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:05.332   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:05.332   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:05.332   477 10242 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:05.332   477 10242 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:05.332   477 10242 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:05.332   477 10242 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:05.342  1277  4107 I ActivityManager: Killing 8102:com.lge.task/u0a20 (adj 15): empty #22
,06-06 13:17:05.342 10145 10196 I SetupWizard.FrpHelper: FRP status: supported: true, challengeRequired: false
,06-06 13:17:05.372  7556 10098 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
,06-06 13:17:05.372  7556 10098 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,06-06 13:17:05.412   477 10242 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:05.412  5117 10106 I System.out: propertyValue:false
,06-06 13:17:05.462 10171 10171 D QuickCoverProvider: onReceiver
,06-06 13:17:05.472  1277  3645 W ActivityManager: getRunningAppProcesses: caller 10120 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:05.502  1277  4107 I ActivityManager: Start proc 10244:com.lge.drmservice/u0a68 for broadcast com.lge.drmservice/.DrmBroadcastReceiver
,06-06 13:17:05.512  1277  4216 I ActivityManager: Killing 9460:com.google.android.gm/u0a113 (adj 15): empty #22
,06-06 13:17:05.512  1277  1314 I NotificationManager: android: cancelAsUser(353845882) by android
,06-06 13:17:05.522  1277  3839 W ActivityManager: getRunningAppProcesses: caller 10120 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:05.632 10171 10171 D QuickCoverProvider: onReceiver
,06-06 13:17:05.632  5725  5725 D CalendarAppWidgetProvider: [AppWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,06-06 13:17:05.632  5725  5725 E AgendaWidgetManager: [updateWidgets] 
,06-06 13:17:05.642  5725  5725 D MonthWidgetProvider: [onReceive]
06-06 13:17:05.642  5725  5725 D CalendarWidgetProvider: [onReceive]
06-06 13:17:05.642  5725  5725 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
06-06 13:17:05.642  5725  5725 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,06-06 13:17:05.642  5725  5725 D WeekWidgetProvider: [onReceive]
06-06 13:17:05.642  1277  3374 I ActivityManager: Killing 7689:com.android.providers.calendar/u0a19 (adj 15): empty #22
06-06 13:17:05.642  5725  5725 D CalendarWidgetProvider: [onReceive]
06-06 13:17:05.642  5725  5725 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
06-06 13:17:05.642  5725  5725 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,06-06 13:17:05.652 10244 10244 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,06-06 13:17:05.652 10244 10244 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,06-06 13:17:05.752  1277  3657 D GpsLocationProvider: SV count: 18 ephemerisMask: 0 almanacMask: 16000
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 18.0 azimuth: 37.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 2.0 azimuth: 298.0    
06-06 13:17:05.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:05.752  5725  5725 D TasksWidgetProvider: [onReceive] intent = Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.tasks.widget.TasksWidgetProvider }
,06-06 13:17:05.812  1277  1314 I ActivityManager: Start proc 10266:com.google.android.apps.docs.editors.sheets/u0a125 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,06-06 13:17:05.812  5725  5725 D MyScheduleWidgetProvider: [onReceive] intent = Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.myschedule.MyScheduleWidgetProvider }
,06-06 13:17:05.812 10244 10244 V DrmService: Service onCreate
06-06 13:17:05.812 10244 10244 D DrmService: Received new request = 2
,06-06 13:17:05.822 10244 10277 I DrmSntpClient: Start Sync process
06-06 13:17:05.822 10244 10277 D DrmSntpClient: Server : 0
,06-06 13:17:05.822 10244 10277 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:05.822 10244 10277 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:05.822 10244 10277 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:05.822 10244 10277 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:05.822   477  1248 E BandwidthController: [LG DATA] No such appUid: 10068
06-06 13:17:05.822   477  1248 D DnsProxyListener: App 10068 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:05.822   477 10285 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:05.822   477 10285 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:05.822   477 10285 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:05.822   477 10285 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:05.862  1277  4171 I ActivityManager: Start proc 10288:com.lge.sizechangable.weather.platform/u0a96 for broadcast com.lge.sizechangable.weather.platform/.receiver.WeatherPlatformCommonReceiver
,06-06 13:17:05.872  5725  5725 D MyScheduleWidgetProvider: [onReceive] sPocketCardStatus = 0
06-06 13:17:05.872  5725  5725 D MyScheduleWidgetService: [onCreate]
,06-06 13:17:05.872  5725  5725 D MyScheduleWidgetService: [onStartCommand]
06-06 13:17:05.872  5725  5725 D MyScheduleFactory: [MyScheduleFactory]
06-06 13:17:05.872  5725  5725 D MyScheduleFactory: [onReceive] intent = Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.myschedule.MyScheduleWidgetService$MyScheduleFactory }
,06-06 13:17:05.882  5725  5725 D MyScheduleFactory: [initLoader]
06-06 13:17:05.882  5725  5725 D WidgetUtils: [getVisibleCalendarSelection] selection = visible=1
,06-06 13:17:05.882  5725  5725 D WidgetUtils: [getVisibleTasksSelection] selection = tdeleted=0 AND DATE(tduedate,'localtime') > DATE('2457545','localtime') AND DATE(tduedate,'localtime') < DATE('2457548','localtime') AND fvisible = 0
,06-06 13:17:05.882  5725  5725 D PocketCardFactory: [PocketCardFactory]
06-06 13:17:05.882  5725  5725 D PocketCardFactory: [onReceive] intent = Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.myschedule.MyPocketCardService$PocketCardFactory }
,06-06 13:17:05.882  5725  5725 D PocketCardFactory: [onReceive] pocket card no display 
,06-06 13:17:05.902   477 10285 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:05.902 10244 10277 I System.out: propertyValue:false
,06-06 13:17:05.922  1277  3374 I ActivityManager: Start proc 10310:com.lge.task/u0a20 for content provider com.lge.task/.database.TasksProvider
,06-06 13:17:05.942 10288 10288 I art     : Almond Protected OAT
,06-06 13:17:05.972 10244 10277 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
,06-06 13:17:05.972  1277  4216 W ActivityManager: getRunningAppProcesses: caller 10125 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:05.972   488   488 V ILGDrmService: eDRM_SetDRMTime +++
,06-06 13:17:05.972   488   488 I LGDRM   : [DRM] SET TIME : YR=2016, MON=6, DAY=6
06-06 13:17:05.972   488   488 I LGDRM   : [DRM] SET TIME : HR=11, MIN=17, SEC=4
,06-06 13:17:05.972   488   488 V ILGDrmService: eDRM_SetDRMTime ---
,06-06 13:17:05.972 10244 10277 I DrmSntpClient: Synched
,06-06 13:17:05.982 10244 10244 D DrmService: Completed !! request = 2
06-06 13:17:05.982 10244 10244 D DrmService: Request count = 0
,06-06 13:17:05.982  1277  4149 I ActivityManager: Start proc 10331:com.android.providers.calendar/u0a19 for content provider com.android.providers.calendar/.CalendarProvider2
,06-06 13:17:05.982  1277  1295 W ActivityManager: getRunningAppProcesses: caller 10120 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:05.992 10244 10244 V DrmService: Service onDestroy
,06-06 13:17:05.992 10288 10288 D WeatherPlatformReceiver: start action : android.net.conn.CONNECTIVITY_CHANGE
,06-06 13:17:06.002 10288 10288 D WeatherPlatformReceiver: end action : android.net.conn.CONNECTIVITY_CHANGE : 17ms
,06-06 13:17:06.012 10288 10288 D WeatherPlatformReceiver: start action : android.intent.action.TIME_SET
06-06 13:17:06.012  1277  4128 W ActivityManager: getRunningAppProcesses: caller 10125 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:06.012 10310 10310 D TasksProvider: [onCreate]
,06-06 13:17:06.052  1277  4194 I ActivityManager: Start proc 10357:com.android.chrome/u0a101 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,06-06 13:17:06.062 10288 10288 D WeatherPlatformReceiver: end action : android.intent.action.TIME_SET : 52ms
,06-06 13:17:06.062 10288 10288 D WeatherUpdateService: start update service by com.lge.sizechangable.weather.platform.UpdateService.action.update.all)
06-06 13:17:06.062 10288 10288 D WeatherUpdateService: Make update type - checker : 11111111, action : 10
,06-06 13:17:06.062 10288 10288 D WeatherUpdateService: start update service by com.lge.sizechangable.weather.platform.UpdateService.action.update.all)
06-06 13:17:06.062 10288 10288 D WeatherUpdateService: Make update type - checker : 11111111, action : 10
06-06 13:17:06.062 10288 10288 D WeatherUpdateService: check update on : 11111111 & 1 = 1
06-06 13:17:06.062 10288 10288 D WeatherUpdateService: check remained time : 11111111 & 10 = 10
,06-06 13:17:06.062 10288 10288 D WeatherPlatform_Alarm: CurrentTime = 6/6 13:17:6
,06-06 13:17:06.072 10288 10288 D WeatherPlatform_Alarm: lastUpdatedTime = 1/1 1:0:0
06-06 13:17:06.072 10288 10288 D WeatherPlatform_Alarm: RemainedTime = -407000:-17:-6
,06-06 13:17:06.072 10288 10288 D WeatherUpdateService: set isOnUpdating : true
06-06 13:17:06.072 10331 10331 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-06 13:17:06.072 10288 10288 D WeatherUpdateService: check update on : 11111111 & 1 = 1
06-06 13:17:06.072 10288 10288 D WeatherUpdateService: check remained time : 11111111 & 10 = 10
,06-06 13:17:06.072 10288 10288 D WeatherPlatform_Alarm: CurrentTime = 6/6 13:17:6
06-06 13:17:06.072 10288 10288 D WeatherPlatform_Alarm: lastUpdatedTime = 1/1 1:0:0
06-06 13:17:06.072 10288 10288 D WeatherPlatform_Alarm: RemainedTime = -407000:-17:-6
06-06 13:17:06.072 10288 10288 D WeatherUpdateService: set isOnUpdating : true
,06-06 13:17:06.072   503   503 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 221us total 21.386ms
,06-06 13:17:06.092 10288 10376 D WeatherUpdateService: check screen on : 11111111 & 100 = 100
06-06 13:17:06.092 10288 10378 D WeatherUpdateService: check screen on : 11111111 & 100 = 100
06-06 13:17:06.092 10288 10378 D WeatherUpdateWorker: do not update. update is already on processing.
06-06 13:17:06.092 10288 10378 D WeatherUpdateService: onResult
,06-06 13:17:06.092 10331 10331 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1084e49e
,06-06 13:17:06.102   503   503 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 188us total 19.823ms
,06-06 13:17:06.112 10222 10222 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-06 13:17:06.112 10222 10222 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-06 13:17:06.112 10222 10222 I GAv4    :   adb logcat -s GAv4
,06-06 13:17:06.112   503   503 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 149us total 17.178ms
,06-06 13:17:06.152  1277  4216 I ActivityManager: Start proc 10383:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,06-06 13:17:06.162 10331 10331 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,06-06 13:17:06.162 10222 10222 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
06-06 13:17:06.162  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10120 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.162 10331 10331 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2eff809b(com.android.providers.calendar.CalendarProvider2@1084e49e)
,06-06 13:17:06.172 10222 10222 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.172  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.182  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.182  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.182 10222 10222 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.46
06-06 13:17:06.182  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:06.182  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:06.182 10222 10402 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:06.182 10288 10376 D WeatherUpdateWorker: do not update. screen off.
06-06 13:17:06.182 10288 10376 D WeatherUpdateService: onResult
06-06 13:17:06.182 10288 10376 D WeatherUpdateService: action start screen on service : 10 & 10 = 10
06-06 13:17:06.182 10288 10376 D WeatherUpdateService: set isOnUpdating : false
,06-06 13:17:06.192  4278  4278 D [Concierge][WeatherPanel]: refreshIconClicked spinning Status : false
06-06 13:17:06.202 10288 10288 D WeatherUpdateService: stop this service at update result handler.
06-06 13:17:06.202 10288 10288 D WeatherUpdateService: isOnProcessing - onAdding : false, onUpdating : false
06-06 13:17:06.202 10288 10288 D WeatherUpdateService: stop update service
,06-06 13:17:06.202 10288 10288 D WeatherScreenOnChecker: start receiving SCREEN_ON
,06-06 13:17:06.212  1277  4151 I ActivityManager: Killing 4492:com.lge.music/u0a58 (adj 15): empty #22
,06-06 13:17:06.212 10383 10383 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1465211826226
06-06 13:17:06.222 10383 10383 D         : TimeServiceNative: User Time to be set is 1465211826226
06-06 13:17:06.222 10383 10383 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
06-06 13:17:06.222 10383 10383 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
06-06 13:17:06.222 10383 10383 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1465211826226
06-06 13:17:06.222 10383 10383 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,06-06 13:17:06.222   512  1261 D QC-time-services: Daemon: Connection accepted:time_genoff
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1465211826226
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1465211826226, operation = 0
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS9/17/115 17:57:12
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:Value read from RTC seconds = 1445108232000
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:new time 1465211826226 
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon: delta 20103594226 genoff 20103594226 
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 20103594226 to memory
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:Opening File: /data/time/ats_2
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-06 13:17:06.222   512 10406 D QC-time-services: Updating the TOD offset
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 20103594226 to memory
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-06 13:17:06.222   512 10406 E QC-time-services: Daemon:Update to modem bit set
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-06 13:17:06.222   512 10406 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 18446743777848345842
,06-06 13:17:06.222 10383 10383 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,06-06 13:17:06.232   512  1261 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,06-06 13:17:06.292   483  3211 V AudioFlinger: 4492 died, releasing its sessions
06-06 13:17:06.292   483  3211 V AudioFlinger:  pid 4078 @ 0
,06-06 13:17:06.322  9973  9973 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,06-06 13:17:06.332  9973  9973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1439 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,06-06 13:17:06.332  3340  3340 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-06 13:17:06.332  3340  3340 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-06 13:17:06.332  3340  3340 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
06-06 13:17:06.332  5137  5137 I LGCover : AppNotifierManager.java:38 onReceive(): Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.bnr.launcher.BNRLauncherActivity, com.lge.updatecenter.UpdateCenterPrfActivity]
,06-06 13:17:06.332  9973  9973 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
,06-06 13:17:06.332  9973  9973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1439 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,06-06 13:17:06.332  9973  9973 V [BNRBootReceiver]: Boot Receiver Return
,06-06 13:17:06.342  1277  1294 W ActivityManager: getRunningAppProcesses: caller 10120 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:06.362  1277  1294 I ActivityManager: Killing 9035:com.google.android.talk/u0a121 (adj 15): empty #22
,06-06 13:17:06.392 10222 10421 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:06.392 10222 10421 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:06.392 10222 10421 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:06.392 10222 10421 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:06.392   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:06.392   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:06.392   477 10424 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:06.392   477 10424 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:06.402   477 10424 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:06.402   477 10424 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:06.412 10222 10222 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:06.412 10222 10415 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:06.412 10222 10415 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-06 13:17:06.412 10222 10222 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:06.472  1277  4128 I ActivityManager: Killing 9707:com.lge.ia.task.smartsetting/u0a21 (adj 15): empty #22
,06-06 13:17:06.532   477 10424 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:06.532 10222 10421 I System.out: propertyValue:false
,06-06 13:17:06.602  1277  3839 W ActivityManager: getRunningAppProcesses: caller 10125 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:06.622 10222 10222 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
,06-06 13:17:06.632 10222 10222 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:17:06.632 10222 10222 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
,06-06 13:17:06.632 10222 10222 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:06.652  1277  1294 I ActivityManager: Start proc 10425:com.google.android.apps.plus/u0a122 for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver
,06-06 13:17:06.662  1277  4193 I ActivityManager: Killing 9817:com.lge.settings.easy/1000 (adj 15): empty #22
,06-06 13:17:06.672 10222 10222 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:17:06.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 26.0 azimuth: 126.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:06.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:06.802  1277  4128 D WifiServiceImplEx: acquireWifiLock pid=10222, uid=10120, packageName=com.google.android.apps.docs.editors.docs, tag=BaseSyncManager
,06-06 13:17:06.802 10425 10425 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-06 13:17:06.812 10222 10222 I NotificationManager: com.google.android.apps.docs.editors.docs: cancel(10436) by com.google.android.apps.docs.editors.docs
,06-06 13:17:06.822 10222 10448 I NotificationManager: com.google.android.apps.docs.editors.docs: cancel(1) by com.google.android.apps.docs.editors.docs
,06-06 13:17:06.852  5117 10106 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,06-06 13:17:06.912 10222 10448 W Flag    : Duration spec must be at least 2 characters long
,06-06 13:17:06.932 10222 10448 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:06.932 10222 10448 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:06.932 10222 10448 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:06.932 10222 10448 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:06.932   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:06.932   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
06-06 13:17:06.932   477 10462 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:06.932   477 10462 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:06.932   477 10462 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:06.932   477 10462 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:06.952 10222 10421 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:06.952 10222 10421 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:06.972 10266 10371 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
06-06 13:17:06.972 10266 10371 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-06 13:17:06.972 10266 10371 I GAv4    :   adb logcat -s GAv4
,06-06 13:17:06.972  1277  3189 V WifiInternetCheck: Single check msg out of sync, ignoring.
,06-06 13:17:07.002 10266 10371 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:07.002  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10125 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:07.012 10266 10371 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:07.022 10266 10470 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:07.032   477 10462 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:07.032 10222 10448 I System.out: propertyValue:false
,06-06 13:17:07.032 10266 10371 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.46
,06-06 13:17:07.042  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:07.082  1277  4172 I ActivityManager: Start proc 10474:com.google.android.talk/u0a121 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,06-06 13:17:07.082  1277  4172 I ActivityManager: Killing 9730:com.android.settings/1000 (adj 15): empty #22
,06-06 13:17:07.102   504   504 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 590us total 19.082ms
,06-06 13:17:07.122 10222 10448 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.122 10222 10448 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:07.122   504   504 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 605us total 19.045ms
,06-06 13:17:07.142   504   504 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 387us total 16.455ms
,06-06 13:17:07.162 10310 10310 I TasksProvider: Sending task notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ }
,06-06 13:17:07.162 10310 10310 W ContentResolver: Failed to get type for: content://com.lge.task/ (Unknown URI content://com.lge.task/)
,06-06 13:17:07.212 10474 10474 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-06 13:17:07.242 10266 10499 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:07.242 10266 10499 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:07.242 10266 10499 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.242 10266 10499 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:07.252   477  1248 E BandwidthController: [LG DATA] No such appUid: 10125
06-06 13:17:07.252   477  1248 D DnsProxyListener: App 10125 tries DNS query. Accept family:0 protocol:0
06-06 13:17:07.252   477 10504 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:07.252   477 10504 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:07.252   477 10504 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:07.252   477 10504 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:07.252   477 10504 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:07.262 10266 10499 I System.out: propertyValue:false
,06-06 13:17:07.272  1277  4171 I ActivityManager: Start proc 10505:com.lge.email/u0a56 for broadcast com.lge.email/.receiver.UpdateScheduleReceiver
,06-06 13:17:07.322  1277  3374 D WifiServiceImplEx: acquireWifiLock pid=10266, uid=10125, packageName=com.google.android.apps.docs.editors.sheets, tag=BaseSyncManager
,06-06 13:17:07.332 10505 10505 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-06 13:17:07.332 10266 10518 I NotificationManager: com.google.android.apps.docs.editors.sheets: cancel(10436) by com.google.android.apps.docs.editors.sheets
06-06 13:17:07.332 10505 10505 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-06 13:17:07.332 10505 10505 W ResourcesManager: Asset path '/system/framework/lgsvcitems.jar' does not exist or contains no resources.
,06-06 13:17:07.332 10505 10505 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-06 13:17:07.332 10505 10505 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,06-06 13:17:07.352 10266 10526 I NotificationManager: com.google.android.apps.docs.editors.sheets: cancel(1) by com.google.android.apps.docs.editors.sheets
,06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: Attempt to close HttpIssuer when no request is executing.
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: java.io.IOException
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at fur.b(PG:162)
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at fup.b(PG:6072)
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.a(PG:1080)
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.c(PG:26263)
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:611)
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at gtm.run(PG:2507)
06-06 13:17:07.372 10222 10448 E DefaultHttpIssuer: 	at gtk.run(PG:3031)
,06-06 13:17:07.372 10505 10505 D EmailContent: init for com.lge.email.provider (at EmailContent.java init 198)[v:null]
,06-06 13:17:07.372 10222 10448 E BaseSyncManager: ClientFlagSyncException
06-06 13:17:07.372 10222 10448 E BaseSyncManager: com.google.android.apps.docs.flags.ClientFlagSynchronizer$ClientFlagSyncException: IO Exception opening: https://ssl.gstatic.com/docs/android/editors/docs/client_flags Socket is closed
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.b(PG:4108)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.a(PG:1060)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.c(PG:26263)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:611)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at gtm.run(PG:2507)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at gtk.run(PG:3031)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: Caused by: java.net.SocketException: Socket is closed
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.checkOpen(SourceFile:251)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.access$000(SourceFile:58)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at smm.write(SourceFile:765)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at kcm.a_(PG:78)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at kby.a_(PG:155)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at kcp.flush(PG:221)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at kab$d.b(PG:381)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at kan.a(PG:279)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at jzu.a(PG:10245)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at jzj$a.a(PG:890)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at jxv.a(PG:50089)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at jxv$a.a(PG:230)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at jxv.a(PG:3201)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fxi.a(PG:127)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fun.a(PG:47)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fum.a(PG:22)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fuo.a(PG:68)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fur.b(PG:92)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fur.a(PG:80)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fup.b(PG:6140)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fup.a(PG:2096)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at fup.a(PG:1062)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.b(PG:4106)
06-06 13:17:07.372 10222 10448 E BaseSyncManager: 	... 5 more
,06-06 13:17:07.382 10474 10542 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,06-06 13:17:07.382 10474 10542 I Babel_SMS: MmsConfig.loadMmsSettings
,06-06 13:17:07.402 10474 10542 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-H815 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/YSdHbanpHC5h2R_E/H815-M3-D1.xml
06-06 13:17:07.402 10474 10542 I Babel_SMS: MmsConfig.loadFromDatabase
,06-06 13:17:07.402  7556 10531 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
,06-06 13:17:07.402  7556 10531 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,06-06 13:17:07.402 10266 10526 W Flag    : Duration spec must be at least 2 characters long
06-06 13:17:07.402 10505 10505 D LGEmail : [Secret] anonymous class instance (dummy) (at SecretFilterFactory.java newInstance 18)[v:null]
,06-06 13:17:07.412 10505 10505 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 156)[v:null]
,06-06 13:17:07.412 10266 10526 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:07.412 10266 10526 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:07.412 10266 10496 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:07.412 10266 10496 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:07.422 10474 10542 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-06 13:17:07.422 10474 10542 I Babel_SMS: MmsConfig.loadFromResources
,06-06 13:17:07.422 10474 10542 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,06-06 13:17:07.422 10474 10542 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-H815 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/YSdHbanpHC5h2R_E/H815-M3-D1.xml
,06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Accelerometer, handle=0
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Magnetometer, handle=10
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Magnetometer Uncalibrated, handle=11
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Gyroscope, handle=2
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Gyroscope Uncalibrated, handle=8
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Proximity, handle=48
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Knock-on Proximity Sensor, handle=74
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Virtual Proximity Sensor, handle=75
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Light, handle=1
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Pressure, handle=3
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Accelerometer -Wakeup Secondary, handle=17
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Magnetometer -Wakeup Secondary, handle=26
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Magnetometer Uncalibrated -Wakeup Secondary, handle=27
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Gyroscope -Wakeup Secondary, handle=19
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Gyroscope Uncalibrated -Wakeup Secondary, handle=24
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Proximity -Non Wakeup Secondary, handle=67
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Light -Wakeup Secondary, handle=18
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Pressure -Wakeup Secondary, handle=20
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Game Rotation Vector Sensor, handle=50
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-06 13:17:07.432 10266 10526 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Gravity -Wakeup Secondary, handle=60
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Linear Acceleration -Wakeup Secondary, handle=61
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Rotation Vector -Wakeup Secondary, handle=62
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Step Detector -Wakeup Secondary, handle=65
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Step Counter -Wakeup Secondary, handle=66
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Game Rotation Vector -Wakeup Secondary, handle=63
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: GeoMagnetic Rotation Vector -Wakeup Secondary, handle=64
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: Orientation -Wakeup Secondary, handle=59
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-06 13:17:07.432 10474 10474 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-06 13:17:07.43,2 10474 10474 D SensorManager: found sensor: Motion Accel, handle=46
,06-06 13:17:07.442 10266 10526 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:17:07.442 10266 10526 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
,06-06 13:17:07.442 10266 10526 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:07.472 10266 10526 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:17:07.482 10266 10526 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.482 10266 10526 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:07.482 10266 10526 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.482 10266 10526 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:07.482   477  1248 E BandwidthController: [LG DATA] No such appUid: 10125
06-06 13:17:07.482   477  1248 D DnsProxyListener: App 10125 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:07.482   477 10550 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:07.482   477 10550 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:07.492   477 10550 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:07.492   477 10550 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:07.492   477 10550 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:07.492 10266 10499 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.492 10266 10526 I System.out: propertyValue:false
06-06 13:17:07.492 10266 10499 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:07.532   589   589 I MSM-irqbalance: Decided to move IRQ216 from CPU0 to CPU3
,06-06 13:17:07.572  1277  4171 I art     : Explicit concurrent mark sweep GC freed 28348(1442KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 57MB/86MB, paused 1.613ms total 128.709ms
,06-06 13:17:07.572 10474 10474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-06 13:17:07.572 10474 10474 I Babel_Crash: startup - clean
,06-06 13:17:07.582 10474 10551 I Babel   : deleted: false for 0
,06-06 13:17:07.592  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:07.592  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:07.602 10266 10526 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.602 10266 10526 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:07.612 10474 10474 I Babel_telephony: TeleModule.launchCompleted
,06-06 13:17:07.622 10474 10474 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,06-06 13:17:07.622 10474 10474 W Babel   : BAM#gBA: invalid account id: -1
06-06 13:17:07.622 10474 10474 W Babel   : BAM#gBA: invalid account id: -1
06-06 13:17:07.622 10474 10474 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,06-06 13:17:07.622  7556 10556 V CheckinChimeraService: No Subscriptions found on the device
06-06 13:17:07.622  7556 10556 I CheckinChimeraService: Checking schedule, now: 1465211827632 next: 1464940037998
06-06 13:17:07.622  7556 10556 I CheckinChimeraService: active receiver: enabled
,06-06 13:17:07.632  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:07.632  7556 10556 I CheckinChimeraService: Preparing to send checkin request
,06-06 13:17:07.632  7556 10556 I EventLogChimeraService: Accumulating logs since 1465210888168
,06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/adpcm
06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/g726
06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/eac3
06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/ac3
06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/wma-voice
06-06 13:17:07.642 10474 10474 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-06 13:17:07.642 10474 10474 W VideoCapabilities: Unsupported mime video/theora
,06-06 13:17:07.642 10474 10474 W VideoCapabilities: Unsupported mime video/mjpg
,06-06 13:17:07.672 10474 10474 W AudioCapabilities: Unsupported mime audio/evrc
,06-06 13:17:07.672 10474 10474 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-06 13:17:07.682 10474 10474 W AudioCapabilities: Unsupported mime audio/evrc
,06-06 13:17:07.692 10474 10474 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-06 13:17:07.692 10474 10474 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-06 13:17:07.692 10474 10474 W VideoCapabilities: Unsupported mime video/divx
,06-06 13:17:07.692 10474 10474 W VideoCapabilities: Unsupported mime video/divx4
,06-06 13:17:07.702 10474 10474 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-06 13:17:07.712 10474 10474 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-06 13:17:07.722 10474 10474 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-06 13:17:07.722 10474 10474 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-06 13:17:07.722 10474 10474 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-06 13:17:07.732  1277  3839 I ActivityManager: Start proc 10560:com.google.android.youtube/u0a124 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,06-06 13:17:07.732 10474 10474 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-06 13:17:07.742 10474 10474 I vclib   : onServiceConnected
06-06 13:17:07.742 10474 10474 W Babel   : Attempted to change video mute state without an active call.
,06-06 13:17:07.752 10474 10474 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-06 13:17:07.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 26.0 azimuth: 126.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
,06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:07.752  1277  4215 I ActivityManager: Killing 9842:com.google.android.apps.maps/u0a119 (adj 15): empty #22
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:07.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:07.752 10474 10572 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.752 10474 10572 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:07.752 10474 10572 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.752 10474 10572 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:07.752   477  1248 E BandwidthController: [LG DATA] No such appUid: 10121
06-06 13:17:07.752   477  1248 D DnsProxyListener: App 10121 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:07.762   477 10581 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:07.762   477 10581 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:07.762   477 10581 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:07.762   477 10581 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:07.862   477 10581 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:07.862 10474 10572 I System.out: propertyValue:false
,06-06 13:17:07.922  1277  4171 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:07.942  5117 10590 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.942  5117 10590 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:07.942  5117 10590 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:07.942  5117 10590 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:07.942   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:07.942   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:07.942   477 10591 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:07.942   477 10591 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:07.942   477 10591 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:07.942   477 10591 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:07.942 10560 10586 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:07.952 10560 10586 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:07.952  7556 10593 I iu.SyncManager: SYNC; picasa accounts
,06-06 13:17:07.962  7556  7556 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,06-06 13:17:07.962  7556  7556 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-06 13:17:07.982  7556 10593 I iu.UploadsManager: num queued entries: 0
,06-06 13:17:07.982  7556 10593 I iu.UploadsManager: num updated entries: 0
,06-06 13:17:07.992  7556 10593 I iu.SyncManager: NEXT; no task
,06-06 13:17:08.002 10560 10586 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
,06-06 13:17:08.012 10560 10586 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:17:08.012 10560 10586 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
06-06 13:17:08.012 10560 10586 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:08.012 10474 10572 I Babel   : connection state changed from UNKNOWN to CONNECTED
,06-06 13:17:08.022   477 10591 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:08.022  5117 10590 I System.out: propertyValue:false
,06-06 13:17:08.062 10560 10586 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:17:08.082  1277  3839 I ActivityManager: Start proc 10596:com.google.android.apps.magazines/u0a115 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,06-06 13:17:08.092  5117 10590 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.092  5117 10590 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.142 10560 10619 D ChimeraCfgMgr: Reading stored module config
,06-06 13:17:08.172 10560 10619 D ChimeraFileApk: Primary ABI of requesting process is arm64-v8a
,06-06 13:17:08.172 10560 10619 D ChimeraFileApk: Classloading successful. Optimized code found.
,06-06 13:17:08.182  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:08.182  1277  3189 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.182  1277  3189 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.182  1277  3189 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.182  1277  3189 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:08.182 10560 10619 D DynamitePackage: Instantiated singleton DynamitePackage.
06-06 13:17:08.182 10560 10619 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
06-06 13:17:08.182   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:08.182   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-06 13:17:08.182   477 10622 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:08.182   477 10622 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.182   477 10622 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:08.182   477 10622 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:08.192  5117  5672 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.192  5117  5672 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.192  5117  5672 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.192  5117  5672 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:08.192   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:08.192   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:08.192   477 10625 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:08.192   477 10625 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:08.192   477 10625 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:08.192   477 10625 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:08.212 10560 10560 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,06-06 13:17:08.222  7556 10556 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-06 13:17:08.222 10560 10560 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.222 10560 10560 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.232  7556 10556 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-06 13:17:08.242 10596 10596 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-06 13:17:08.242 10596 10596 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-06 13:17:08.242 10596 10596 I GAv4    :   adb logcat -s GAv4
,06-06 13:17:08.262 10596 10596 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:08.262  1277  3645 W ActivityManager: getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:08.272 10596 10596 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:08.272   477 10622 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:08.272  1277  3189 I System.out: propertyValue:false
06-06 13:17:08.272   477 10625 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:08.272  1277  4151 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.282  5117  5672 I System.out: propertyValue:false
06-06 13:17:08.282 10596 10656 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,06-06 13:17:08.282  1277  3190 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.282  1277  3190 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.282  1277  3190 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.282  1277  3190 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.282   477  1248 E BandwidthController: [LG DATA] No such appUid: 1000
06-06 13:17:08.282   477  1248 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
06-06 13:17:08.282   477 10661 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,06-06 13:17:08.282   477 10661 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:08.282   477 10661 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:08.282   477 10661 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:08.282   477 10661 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:08.282  1277  3190 I System.out: propertyValue:false
,06-06 13:17:08.342 10560 10560 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,06-06 13:17:08.352  1277  4215 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:08.362 10560 10560 W InstanceID/Rpc: Found 10006
,06-06 13:17:08.372  7556 10556 V CheckinRequestBuilder: No Subscriptions found on the device
,06-06 13:17:08.442  4618  4733 I art     : Explicit concurrent mark sweep GC freed 1740(64KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.161ms total 29.996ms
06-06 13:17:08.442  5117  5672 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.442  5117  5672 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.452  5117 10590 I GCM     : GCM config loaded
,06-06 13:17:08.452 10596 10596 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309050)
,06-06 13:17:08.462 10596 10596 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7602-7603)
06-06 13:17:08.462 10596 10596 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-06 13:17:08.462 10596 10596 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0cde9c}
,06-06 13:17:08.462 10596 10596 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-06 13:17:08.462 10596 10596 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,06-06 13:17:08.472  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:08.472 10560 10711 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:08.472 10596 10596 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-06 13:17:08.472 10560 10711 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.472 10596 10596 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-06 13:17:08.472 10560 10711 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.472 10560 10711 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:08.472 10596 10596 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-06 13:17:08.472   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:17:08.472   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:08.472   477 10724 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:08.472   477 10724 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.472   477 10724 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:08.472   477 10724 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:08.472  5117  5140 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.472  5117  5140 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.482 10560 10655 I NotificationManager: com.google.android.youtube: cancel(10436) by com.google.android.youtube
,06-06 13:17:08.482 10596 10596 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-06 13:17:08.492 10596 10596 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-06 13:17:08.492 10596 10596 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-06 13:17:08.492 10596 10596 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:08.492 10596 10596 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:08.492 10596 10596 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:08.492 10596 10596 I Adreno  : Local Branch                     : 
06-06 13:17:08.492 10596 10596 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:08.492 10596 10596 I Adreno  : Remote Branch                    : NONE
06-06 13:17:08.492 10596 10596 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:08.512 10560 10697 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.512 10560 10697 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.512 10560 10697 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.512 10560 10697 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.512   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:17:08.512   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
06-06 13:17:08.512   477 10730 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:08.512   477 10730 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.512   477 10730 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:08.512   477 10730 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:08.512   477 10730 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:08.512 10560 10697 I System.out: propertyValue:false
,06-06 13:17:08.512 10560 10697 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.512 10560 10697 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.532   483  3211 V AudioPolicyService: registerClient() client 0xf2555360, uid 10115
,06-06 13:17:08.532 10596 10596 I NSApplication: Starting up...
,06-06 13:17:08.532  1277  3190 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,06-06 13:17:08.542  1277  1295 W ActivityManager: getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.542 10596 10738 W AudioManagerAndroid: Requires BLUETOOTH permission
,06-06 13:17:08.542  1277  4151 W ActivityManager: getRunningAppProcesses: caller 10115 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:08.562   477 10724 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:08.562  5117  5140 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.562  5117  5140 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.562 10560 10711 I System.out: propertyValue:false
06-06 13:17:08.562 10560 10711 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.562 10560 10711 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.572 10560 10697 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.572 10560 10697 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:08.572  1277  4151 I ActivityManager: Start proc 10744:com.lge.exchange/u0a22 for broadcast com.lge.exchange/.receiver.NetworkStatusReceiver
,06-06 13:17:08.572  1277  4151 I ActivityManager: Killing 9262:com.lge.lockscreensettings/1000 (adj 15): empty #22
,06-06 13:17:08.682  1277  4151 I ActivityManager: Killing 9781:com.lge.wifisettings/1000 (adj 15): empty #23
,06-06 13:17:08.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 26.0 azimuth: 126.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:08.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:08.802 10744 10744 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-06 13:17:08.812 10744 10744 D EXCHG_DEBUGS: onCreate!! (at ExchangeProvider.java onCreate 169)[vnull]
,06-06 13:17:08.812 10744 10744 D EmailContent: init for com.lge.email.provider (at EmailContent.java init 198)[v:null]
,06-06 13:17:08.832 10744 10744 D EXCHG_DEBUGS: onCreate!! (at ExchangeProvisionProvider.java onCreate 39)[vnull]
,06-06 13:17:08.832 10744 10744 D EXCHG_DEBUGS: Create (at UpsyncProvider.java onCreate 176)[vnull]
,06-06 13:17:08.832  1277  3374 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:08.842 10744 10744 D EXCHG_DEBUGS: onCreate (at ExchangeCalendarProvider.java onCreate 40)[vnull]
,06-06 13:17:08.842 10744 10744 D EXCHG_DEBUGS: onCreate!! (at Exchange.java onCreate 33)[vnull]
06-06 13:17:08.842 10744 10765 W EXCHG_DEBUGS: Exchange account is not existed! (at EasHostAuth.java getExchangeHostAuthIds 106)[vnull]
,06-06 13:17:08.842 10744 10744 D EXCHG_DEBUGS: Device is in user mode (at LogPreference.java <clinit> 20)[v1.0.45]
06-06 13:17:08.842 10744 10765 W EXCHG_DEBUGS: hostAuthIds is null! (at EasAccount.java getAccountIds 176)[v1.0.45]
06-06 13:17:08.842 10744 10765 E EXCHG_DEBUGS: There is no EAS account (at EasAccount.java isExisted 238)[v1.0.45]
,06-06 13:17:08.852  5117  5672 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:08.862 10744 10744 I EAS_DEBUG: Library log has been toggled
,06-06 13:17:08.862 10744 10767 I HubEmail: jarg2 is null.
06-06 13:17:08.862 10744 10767 I HubEmail: -- called from 2449 jni/../ExternalLib/WbxmlParser/../EmailInterface/jni/EmailCoreLinkApi/eas_wrap.cpp
06-06 13:17:08.862 10744 10767 I HubEmail: jarg2 is null.
06-06 13:17:08.862 10744 10767 I HubEmail: -- called from 2473 jni/../ExternalLib/WbxmlParser/../EmailInterface/jni/EmailCoreLinkApi/eas_wrap.cpp
,06-06 13:17:08.862  1277  4194 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:08.862  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.862  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.862  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.862  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.862  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.862  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:08.872  1277  4194 W ActivityManager: getRunningAppProcesses: caller 10094 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:08.892 10744 10767 I HubEmail: requestEASService() Start - EnevtType = 1
06-06 13:17:08.892 10744 10767 I HubEmail: -- called from 5197 jni/../ExternalLib/WbxmlParser/../EmailInterface/jni/EmailCoreLinkApi/eas_wrap.cpp
,06-06 13:17:08.892  1277  4194 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:08.902 10222 10448 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.902 10222 10448 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:08.902  1277  3751 I ActivityManager: Killing 9938:com.uei.lg.quicksetsdk.irblaster/1000 (adj 15): empty #22
06-06 13:17:08.902 10222 10448 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:08.902 10222 10448 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.902   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:08.902   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
06-06 13:17:08.902   477 10770 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:08.902   477 10770 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:08.902   477 10770 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:08.902   477 10770 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:08.922  9917  9917 D QRemoteSDK: [UeiIrBlasterInitializer.java:174:onServiceDisconnected()] oooooo Setup disconnected 
,06-06 13:17:08.922  9917  9917 W System.err: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.uei.control.ISetup.unregisterSetupReadyCallback(ISetup.java:1216)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer$2.onServiceDisconnected(UeiIrBlasterInitializer.java:181)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1395)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1409)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:17:08.922  9917  9917 E UEI.SmartControl: ISetup.unregisterSetupReadyCallback error: android.os.DeadObjectException
,06-06 13:17:08.922  9917  9917 W QRemoteSDK: [IrBlasterProListenerArray.java:95:execCycle()] oooooo There are no callbacks in the list to call.
06-06 13:17:08.922  9917  9917 W System.err: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.uei.control.ISetup.validateSession(ISetup.java:1119)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer.hasValidSetupSession(UeiIrBlasterInitializer.java:556)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer.execSetupOperations(UeiIrBlasterInitializer.java:469)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrLearnCallback.removeIrLearnedListener(UeiIrLearnCallback.java:152)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterWrapper$1.onSetupDisconnected(UeiIrBlasterWrapper.java:110)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer$2.onServiceDisconnected(UeiIrBlasterInitializer.java:188)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1395)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1409)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:17:08.922  9917  9917 E UEI.SmartControl: ISetup.validateSession error: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 W System.err: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.uei.control.ISetup.getLastResultcode(ISetup.java:1055)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterUtils.printLastResultCode(UeiIrBlasterUtils.java:87)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer.hasValidSetupSession(UeiIrBlasterInitializer.java:559)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer.execSetupOperations(UeiIrBlasterInitializer.java:469)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrLearnCallback.removeIrLearnedListener(UeiIrLearnCallback.java:152)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterWrapper$1.onSetupDisconnected(UeiIrBlasterWrapper.java:110)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer$2.onServiceDisconnected(UeiIrBlasterInitializer.java:188)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1395)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1409)
06-06 1,3:17:08.922  9917  9917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:17:08.922  9917  9917 E UEI.SmartControl: ISetup.getLastResultcode error: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 D QRemoteSDK: [UeiIrBlasterUtils.java:91:printLastResultCode()] oooooo Invalid session result:  Last result code = 1 - Error
06-06 13:17:08.922  9917  9917 E QRemoteSDK: [UeiIrBlasterInitializer.java:485:execSetupOperations()] oooooo Problem to obtain a valid session for setup.
06-06 13:17:08.922  9917  9917 I QRemoteSDK: [UeiIrBlasterInitializer.java:223:onServiceDisconnected()] oooooo Control disconnected.
06-06 13:17:08.922  9917  9917 W System.err: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:512)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.lge.hardware.IRBlaster.Uei.UeiIrBlasterInitializer$3.onServiceDisconnected(UeiIrBlasterInitializer.java:228)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1395)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1409)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-06 13:17:08.922  9917  9917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-06 13:17:08.922  5117  5140 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
06-06 13:17:08.922  9917  9917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5430)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-06 13:17:08.922  9917  9917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:913)
06-06 13:17:08.922  9917  9917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:706)
06-06 13:17:08.922  9917  9917 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
06-06 13:17:08.922  9917  9917 E QRemoteSDK: [UeiIrBlasterInitializer.java:643:run()] oooooo Setup service has encountered unexpected error and will need to close.
,06-06 13:17:08.982   477 10770 D libc-netbsd: res_queryN name = xxxxx succeed,
,06-06 13:17:08.982 10222 10448 I System.out: propertyValue:false
,06-06 13:17:09.082 10222 10448 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.082 10222 10448 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:09.122  1277  4172 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.irblaster/com.uei.control.Service in 1000ms
,06-06 13:17:09.132  1277  4172 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:09.132  1277  4193 I ActivityManager: Killing 9917:com.lge.qremote/u0a138 (adj 15): empty #22
,06-06 13:17:09.152  5117  5672 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:09.162  1277  4149 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:09.242  7556 10764 V AccountUtils: 0 accounts found with uca feature
06-06 13:17:09.242  7556 10764 I GamesSyncAdapter: Starting sync for 3a3529a
,06-06 13:17:09.262 10266 10526 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.262 10266 10526 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:09.262 10266 10526 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.262 10266 10526 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.262   477  1248 E BandwidthController: [LG DATA] No such appUid: 10125
06-06 13:17:09.262   477  1248 D DnsProxyListener: App 10125 tries DNS query. Accept family:0 protocol:0
06-06 13:17:09.262   477 10773 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:09.262   477 10773 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.262   477 10773 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:09.262   477 10773 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:09.262   477 10773 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:09.262 10266 10526 I System.out: propertyValue:false
,06-06 13:17:09.322  1277  4216 I art     : Explicit concurrent mark sweep GC freed 23433(1201KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 57MB/86MB, paused 2.207ms total 189.125ms
,06-06 13:17:09.332  4278  4278 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,06-06 13:17:09.332  4278  5986 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
06-06 13:17:09.332 10266 10526 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.332 10266 10526 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:09.332  4278  5986 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,06-06 13:17:09.332  4278  5986 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
06-06 13:17:09.342  4278  5986 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,06-06 13:17:09.342  9973  9973 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
,06-06 13:17:09.342  9973  9973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1439 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
,06-06 13:17:09.342  3340  3340 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
06-06 13:17:09.342  3340  3340 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
06-06 13:17:09.342  3340  3340 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
06-06 13:17:09.342  5137  5137 I LGCover : AppNotifierManager.java:38 onReceive(): Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.bnr.launcher.BNRLauncherActivity, com.lge.updatecenter.UpdateCenterPrfActivity]
,06-06 13:17:09.352 10744 10767 I HubEmail: jarg2 is null.
06-06 13:17:09.352 10744 10767 I HubEmail: -- called from 2449 jni/../ExternalLib/WbxmlParser/../EmailInterface/jni/EmailCoreLinkApi/eas_wrap.cpp
06-06 13:17:09.352 10744 10767 I HubEmail: jarg2 is null.
06-06 13:17:09.352 10744 10767 I HubEmail: -- called from 2473 jni/../ExternalLib/WbxmlParser/../EmailInterface/jni/EmailCoreLinkApi/eas_wrap.cpp
,06-06 13:17:09.352 10744 10767 I HubEmail: requestEASService() Start - EnevtType = 5
06-06 13:17:09.352 10744 10767 I HubEmail: -- called from 5197 jni/../ExternalLib/WbxmlParser/../EmailInterface/jni/EmailCoreLinkApi/eas_wrap.cpp
,06-06 13:17:09.352  9973  9973 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
06-06 13:17:09.352  9973  9973 V [BNRBootReceiver]: Boot Receiver Return
,06-06 13:17:09.392  1277  4149 I ActivityManager: Start proc 10777:com.google.android.gms.unstable/u0a6 for service com.google.android.gms/.droidguard.DroidGuardService
,06-06 13:17:09.402  5725  5725 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,06-06 13:17:09.412  5725 10793 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
06-06 13:17:09.412  5725  5725 D CalendarAppWidgetProvider: [AppWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,06-06 13:17:09.412  5725  5725 E AgendaWidgetManager: [updateWidgets] 
06-06 13:17:09.422  5725  5725 D MonthWidgetProvider: [onReceive]
06-06 13:17:09.422  5725  5725 D CalendarWidgetProvider: [onReceive]
06-06 13:17:09.422  5725  5725 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,06-06 13:17:09.422  5725  5725 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
,06-06 13:17:09.422  5725  5725 D WeekWidgetProvider: [onReceive]
06-06 13:17:09.422  5725  5725 D CalendarWidgetProvider: [onReceive]
06-06 13:17:09.422  5725  5725 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,06-06 13:17:09.422  5725  5725 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
,06-06 13:17:09.432  5725  5725 D TasksWidgetProvider: [onReceive] intent = Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ flg=0x10 cmp=com.android.calendar/.tasks.widget.TasksWidgetProvider }
,06-06 13:17:09.432  5725  5725 D MyScheduleFactory: [MyScheduleFactory]
06-06 13:17:09.432  5725  5725 D MyScheduleFactory: [onReceive] intent = Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.lge.task/ flg=0x10 cmp=com.android.calendar/.widget.myschedule.MyScheduleWidgetService$MyScheduleFactory }
,06-06 13:17:09.432  5725  5725 D MyScheduleFactory: [initLoader]
06-06 13:17:09.432  5725  5725 D WidgetUtils: [getVisibleCalendarSelection] selection = visible=1
06-06 13:17:09.432  5725  5725 D WidgetUtils: [getVisibleTasksSelection] selection = tdeleted=0 AND DATE(tduedate,'localtime') > DATE('2457545','localtime') AND DATE(tduedate,'localtime') < DATE('2457548','localtime') AND fvisible = 0
,06-06 13:17:09.462 10777 10777 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:09.462 10777 10777 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:09.482 10777 10777 D GmsApplication: Forcing legacy multidex for PROD_LMP build.
,06-06 13:17:09.482 10777 10777 I MultiDex: VM with version 2.1.0 has multidex support
06-06 13:17:09.482 10777 10777 I MultiDex: install
,06-06 13:17:09.482 10777 10777 I MultiDex: MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
,06-06 13:17:09.492 10777 10777 I MultiDex: loading existing secondary dex files
,06-06 13:17:09.492 10777 10777 I MultiDex: load found 3 secondary dex files
,06-06 13:17:09.502 10777 10777 I MultiDex: install done
,06-06 13:17:09.542 10777 10777 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
,06-06 13:17:09.542 10777 10777 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:17:09.542 10777 10777 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
,06-06 13:17:09.542 10777 10777 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:09.562  4278  4278 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,06-06 13:17:09.562  4278  6499 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
06-06 13:17:09.562  4278  6499 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,06-06 13:17:09.562  4278  6499 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,06-06 13:17:09.562  4278  6499 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,06-06 13:17:09.582 10777 10777 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:17:09.582 10777 10777 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,06-06 13:17:09.582 10777 10777 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
,06-06 13:17:09.592 10777 10777 D ChimeraCfgMgr: Reading stored module config
,06-06 13:17:09.592  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:09.602  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{32a0c0b2 type 2 when 218737 com.android.providers.calendar} when 218737
,06-06 13:17:09.642  7556  7904 I art     : Explicit concurrent mark sweep GC freed 19752(1536KB) AllocSpace objects, 35(700KB) LOS objects, 28% free, 39MB/55MB, paused 1.139ms total 117.699ms
,06-06 13:17:09.642  7556 10801 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-06 13:17:09.652  1277  3839 I ActivityManager: Start proc 10809:com.google.android.play.games.ui/u0a114 for service com.google.android.play.games/com.google.android.gms.games.service.PlayGamesBridgeService
,06-06 13:17:09.662 10331 10331 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,06-06 13:17:09.662 10331 10331 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
,06-06 13:17:09.672  7556  7569 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ff7ec1f)
06-06 13:17:09.672  5199  5199 D [Concierge][ConciergeService]: onStartCommand(). Type : 11
,06-06 13:17:09.672  1277  4194 I NotificationManager: android: cancelAsUser(2) by android
06-06 13:17:09.672  7556  7569 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@57b2b6c)
,06-06 13:17:09.672 10331 10331 D CalendarProvider2: CalendarProviderIntentService.onCreate()
06-06 13:17:09.672 10331 10827 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
06-06 13:17:09.682 10331 10827 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
,06-06 13:17:09.722 10331 10827 D CalendarProvider2: [IntentService] Release Lock
,06-06 13:17:09.722 10331 10331 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
,06-06 13:17:09.722 10777 10806 D NativeLibraryUtils: Install completed successfully. count=18 extracted=0
,06-06 13:17:09.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 26.0 azimuth: 126.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:09.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:09.752 10777 10777 I art     : Rejecting re-init on previously-failed class java.lang.Class<jry>
06-06 13:17:09.752 10777 10777 I art     : Rejecting re-init on previously-failed class java.lang.Class<jry>
,06-06 13:17:09.792  7556  8082 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.792  7556  8082 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:09.792  7556  8082 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.792  7556  8082 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:09.792   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:09.792   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:09.792   477 10835 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:09.792   477 10835 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:09.792   477 10835 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:09.792   477 10835 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:09.792   477 10835 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:09.792  7556  8082 I System.out: propertyValue:false
,06-06 13:17:09.842  7556 10764 I GamesSyncAdapter: Sync duration for 3a3529a: 597
,06-06 13:17:09.852   483  5582 D WVCdm   : Instantiating CDM.
,06-06 13:17:09.852   483  3211 I WVCdm   : CdmEngine::OpenSession
06-06 13:17:09.852   483  3211 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,06-06 13:17:09.892 10222 10841 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.892 10222 10841 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:09.892 10222 10841 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.892 10222 10841 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.892   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:09.892   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
06-06 13:17:09.892   477 10843 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:09.892   477 10843 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:09.892   477 10843 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:09.892   477 10843 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:09.912   483  3211 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-06 13:17:09.912 10777 10796 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.912 10777 10796 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:09.922 10777 10796 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.922 10777 10796 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.922   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:09.922   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:09.922 10809 10832 I NotificationManager: com.google.android.play.games: cancel(10436) by com.google.android.play.games
,06-06 13:17:09.922   483  3211 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
06-06 13:17:09.922   483  3211 D DrmWidevineDash: Service_Initialize: starts!
06-06 13:17:09.922   483  3211 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-06 13:17:09.922   483  3211 D QSEECOMAPI: : App is not loaded in QSEE
06-06 13:17:09.922   477 10847 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:09.922   477 10847 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:09.922   477 10847 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:09.922   477 10847 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:09.922   477 10847 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:09.922 10777 10796 I System.out: propertyValue:false
,06-06 13:17:09.922  1277  4172 D WifiServiceImplEx: releaseWifiLock pid=10222, uid=10120, packageName=com.google.android.apps.docs.editors.docs
,06-06 13:17:09.952 10222 10849 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:09.952 10222 10849 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:09.952 10222 10849 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.952 10222 10849 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.952   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:09.952   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
06-06 13:17:09.952   477 10850 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:09.952   477 10850 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.962   477 10850 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:09.962   477 10850 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:09.962   477 10850 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:09.962   483  3211 D QSEECOMAPI: : Loaded image: APP id = 5
,06-06 13:17:09.962  1277  1314 I NotificationManager: android: cancelAsUser(1322057929) by android
06-06 13:17:09.962 10222 10849 I System.out: propertyValue:false
06-06 13:17:09.962  1277  4194 I ActivityManager: Killing 9512:com.google.android.music:main/u0a123 (adj 15): empty #22
,06-06 13:17:09.962   483  3211 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-06 13:17:09.962   483  3211 D DrmWidevineDash: Service_Initialize: function time: 46ms (0s 46082395ns)
,06-06 13:17:09.972   483  3211 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
06-06 13:17:09.972   483  3211 D QSAPPSVER: qsapps_get_capabilities: returns 0
06-06 13:17:09.972   483  3211 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf13e1000
06-06 13:17:09.972   483  3211 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf13e1000
,06-06 13:17:09.972   462   468 D DrmLibTime: got the req here! ret=0
06-06 13:17:09.972   462   468 D DrmLibTime: command id, time_cmd_id = 770
06-06 13:17:09.972   462   468 D DrmLibTime: time_getutcsec starts!
06-06 13:17:09.972   462   468 D DrmLibTime: QSEE Time Listener: time_getutcsec
06-06 13:17:09.972   462   468 D DrmLibTime: QSEE Time Listener: get_utc_seconds
06-06 13:17:09.972   462   468 D DrmLibTime: QSEE Time Listener: time_get_modem_time
06-06 13:17:09.972   462   468 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
06-06 13:17:09.972   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
06-06 13:17:09.972   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
06-06 13:17:09.972   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
06-06 13:17:09.972   462   468 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-06 13:17:09.972   512  1261 D QC-time-services: Daemon: Connection accepted:time_genoff
06-06 13:17:09.972   512 10852 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
06-06 13:17:09.972   512 10852 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
06-06 13:17:09.972   512 10852 D QC-time-services: offset is: 0 for base: 13
06-06 13:17:09.972   462   468 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
06-06 13:17:09.972   462   468 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
06-06 13:17:09.972   462   468 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1465211829
06-06 13:17:09.972   462   468 D DrmLibTime: time_getutcsec returns 0, sec = 1465211829; nsec = 0
06-06 13:17:09.972   462   468 D DrmLibTime: time_getutcsec finished! 
06-06 13:17:09.972   462   468 D DrmLibTime: iotcl_continue_command finished! and return 0 
06-06 13:17:09.972   462   468 D DrmLibTime: before calling ioctl to read the next time_cmd
06-06 13:17:09.972   512  1261 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,06-06 13:17:09.972   483  3211 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 4ms (0s 4576614ns)
06-06 13:17:09.972   483  3211 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-06 13:17:09.972   483  3211 D DrmWidevineDash: _oecc01: function time: 55ms (0s 55587031ns)
06-06 13:17:09.972   483  3211 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-06 13:17:09.972   483  3211 D DrmWidevineDash: hlos api version =  9
06-06 13:17:09.972   483  3211 D DrmWidevineDash: tz api version =  9
06-06 13:17:09.972   483  3211 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-06 13:17:09.972   483  3211 D DrmWidevineDash: _oecc22: function time: 0ms (0s 559896ns)
06-06 13:17:09.972   483  3211 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-06 13:17:09.982  7556 10764 E PopupManager: No content view usable to display popups. Popups will not be displayed in response to this client's calls. Use setViewForPopups() to set your content view.
,06-06 13:17:09.992 10266 10854 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.992 10266 10854 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:09.992 10266 10854 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:09.992 10266 10854 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.992   477  1248 E BandwidthController: [LG DATA] No such appUid: 10125
06-06 13:17:09.992   477  1248 D DnsProxyListener: App 10125 tries DNS query. Accept family:0 protocol:0
06-06 13:17:09.992   477 10856 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:09.992   477 10856 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:09.992   477 10856 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:09.992   477 10856 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:10.002   477 10843 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:10.002   477 10856 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-06 13:17:10.002   483  3211 D DrmWidevineDash: _oecc05: function time: 25ms (0s 25677500ns)
06-06 13:17:10.002   483  3211 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf17ef920
06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
06-06 13:17:10.002 10777 10796 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.002 10777 10796 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-06 13:17:10.002   483  3211 D DrmWidevineDash: _oecc09: function time: 0ms (0s 665781ns)
06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf081f3b8, dataLength=8
,06-06 13:17:10.002   483  3211 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
06-06 13:17:10.002 10222 10841 I System.out: propertyValue:false
06-06 13:17:10.002   483  3211 D DrmWidevineDash: _oecc06: function time: 1ms (0s 1149740ns)
,06-06 13:17:10.002 10266 10854 I System.out: propertyValue:false
,06-06 13:17:10.012   483  3211 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xf1fbf000, wrapped_rsa_key_length=1280
,06-06 13:17:10.012   483  3211 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-06 13:17:10.012   483  3211 D DrmWidevineDash: _oecc19: function time: 3ms (0s 3593854ns)
06-06 13:17:10.012   483  3211 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-06 13:17:10.012   483   483 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-06 13:17:10.012   483   483 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-06 13:17:10.012   483   483 I WVCdm   : CdmEngine::GenerateKeyRequest
06-06 13:17:10.012   483   483 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xf0823340, idLength=0xff9986e0
,06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-06 13:17:10.032   483   483 D DrmWidevineDash: _oecc07: function time: 16ms (0s 16768907ns)
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
06-06 13:17:10.032   483   483 D DrmWidevineDash: _oecc29: function time: 0ms (0s 470937ns)
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xff9986f6, maximum = 0xff9986f7
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
06-06 13:17:10.032   483   483 D DrmWidevineDash: _oecc28: function time: 0ms (0s 396979ns)
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-06 13:17:10.032   483   483 D DrmWidevineDash: hlos api version =  9
06-06 13:17:10.032   483   483 D DrmWidevineDash: tz api version =  9
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-06 13:17:10.032   483   483 D DrmWidevineDash: _oecc22: function time: 0ms (0s 439531ns)
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff998764
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-06 13:17:10.032   483   483 D DrmWidevineDash: _oecc14: function time: 0ms (0s 516458ns)
06-06 13:17:10.032   483   483 D WVCdm   : PrepareKeyRequest: nonce=46332912
06-06 13:17:10.032   483   483 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xf5f9b400
06-06 13:17:10.032   483   483 D DrmWidevineDash: message_length=1604, signature=0xf1ce7680, signature_length=0xff9986c4
,06-06 13:17:10.072  1277  3374 I ActivityManager: Killing 8814:com.android.gallery3d/u0a55 (adj 15): empty #22
,06-06 13:17:10.092 10266 10854 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.092 10222 10841 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.092 10222 10841 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:10.092 10266 10854 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:10.142   483   483 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
06-06 13:17:10.142   483   483 D DrmWidevineDash: _oecc36: function time: 112ms (0s 112137292ns)
,06-06 13:17:10.152   483  5582 I WVCdm   : CdmEngine::CloseSession
06-06 13:17:10.152   483  5582 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,06-06 13:17:10.152   483  5582 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-06 13:17:10.152   483  5582 D DrmWidevineDash: _oecc10: function time: 0ms (0s 684375ns)
06-06 13:17:10.152   483  5582 I WVCdm   : L3 Terminate.
06-06 13:17:10.152   483  5582 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,06-06 13:17:10.152   483  5582 D DrmWidevineDash: Service_Uninitialize: starts!
06-06 13:17:10.152   483  5582 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-06 13:17:10.152   483  5582 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 5
06-06 13:17:10.152   483  5582 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
06-06 13:17:10.152   483  5582 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 569219ns)
,06-06 13:17:10.152   483  5582 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 253073ns)
06-06 13:17:10.152   483  5582 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
06-06 13:17:10.152   483  5582 D DrmWidevineDash: _oecc02: function time: 1ms (0s 1342917ns)
,06-06 13:17:10.212 10222 10849 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.212 10222 10849 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:10.342  7556 10860 W GamesServiceBroker: Client connected with SDK 8487000, Services 9083240, and Games 37230040
,06-06 13:17:10.362  1277  4107 D WifiServiceImplEx: releaseWifiLock pid=10266, uid=10125, packageName=com.google.android.apps.docs.editors.sheets
,06-06 13:17:10.362  7556  7556 D PlayCommon: [1] DfeRequest.deliverResponse: Not delivering second response for request=[[ ] https://android.clients.google.com/fdfe/api/experiments 0xe8d195d1 NORMAL 1]
,06-06 13:17:10.372 10266 10862 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.372 10266 10862 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:10.372 10266 10862 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.372 10266 10862 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:10.372   477  1248 E BandwidthController: [LG DATA] No such appUid: 10125
06-06 13:17:10.372   477  1248 D DnsProxyListener: App 10125 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:10.372   477 10864 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:10.372   477 10864 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:10.372   477 10864 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:10.372   477 10864 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:10.372   477 10864 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:10.372 10266 10862 I System.out: propertyValue:false
,06-06 13:17:10.392  1277  1314 I NotificationManager: android: cancelAsUser(895932782) by android
,06-06 13:17:10.452  1277  1314 I ActivityManager: Start proc 10865:com.android.gallery3d/u0a55 for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService
,06-06 13:17:10.452  7556 10853 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,06-06 13:17:10.492 10865 10865 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-06 13:17:10.492 10865 10865 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-06 13:17:10.492 10865 10865 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,06-06 13:17:10.492 10865 10865 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,06-06 13:17:10.552 10865 10865 I AppTier : App Tier : HIGH
,06-06 13:17:10.552 10865 10865 I AppConfig: Total System Memory = 2968948736
,06-06 13:17:10.562 10865 10865 I GalleryUtils: Application Heap = 512 MB
,06-06 13:17:10.562 10865 10865 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,06-06 13:17:10.592  1277  1314 I NotificationManager: android: cancelAsUser(-1597574061) by android
,06-06 13:17:10.592  1277  3374 I ActivityManager: Killing 10071:com.lge.appbox.client/u0a9 (adj 15): empty #22
,06-06 13:17:10.622 10266 10862 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:10.622 10266 10862 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:10.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 26.0 azimuth: 126.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:10.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:10.852  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:10.862  5117 10897 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:10.872  7556 10898 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:10.882 10899 10899 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=45 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-06 13:17:10.922 10899 10899 I dex2oat : dex2oat took 40.418ms (threads: 6) arena alloc=183KB java alloc=18KB native alloc=1509KB free=6MB
,06-06 13:17:10.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:17:10.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:17:10.942  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 220082634967; DSPS: 7379129; Offset : -5110508023
,06-06 13:17:10.952 10777 10796 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:10.952 10777 10796 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:10.952 10777 10796 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:10.952 10777 10796 I Adreno  : Local Branch                     : 
06-06 13:17:10.952 10777 10796 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:10.952 10777 10796 I Adreno  : Remote Branch                    : NONE
06-06 13:17:10.952 10777 10796 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:10.972  5117 10715 I art     : Explicit concurrent mark sweep GC freed 126533(7MB) AllocSpace objects, 46(940KB) LOS objects, 45% free, 37MB/69MB, paused 1.718ms total 121.796ms
,06-06 13:17:10.982  5117  5132 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@cfa9ea8)
,06-06 13:17:10.982  1277  3839 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:10.992  5117  5132 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20683966)
,06-06 13:17:11.002  1277  4193 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:11.012  1277  1295 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:11.012  7556 10898 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:11.012  7556 10898 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:11.042  5117 10897 D GoogleSignatureVerifier: Package manager can't find package null, defaulting to false
,06-06 13:17:11.042  5117 10897 I GLSUser : Method not found getActionBar
,06-06 13:17:11.062  5117 10897 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:11.062  5117 10897 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:11.062  5117 10897 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:11.062  5117 10897 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:11.062   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:11.062   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:11.062   477 10912 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:11.062   477 10912 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:11.062   477 10912 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:11.062   477 10912 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:11.062   477 10912 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:11.062  5117 10897 I System.out: propertyValue:false
,06-06 13:17:11.082 10777 10796 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:11.082 10777 10796 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:11.082 10777 10796 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:11.082 10777 10796 I Adreno  : Local Branch                     : 
06-06 13:17:11.082 10777 10796 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:11.082 10777 10796 I Adreno  : Remote Branch                    : NONE
06-06 13:17:11.082 10777 10796 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:11.092  1277  3839 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:11.112  5117  5140 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:11.152 10425 10883 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-06 13:17:11.182 10425 10916 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:11.182 10425 10916 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,06-06 13:17:11.182   477  1248 E BandwidthController: [LG DATA] No such appUid: 10122
06-06 13:17:11.182   477  1248 D DnsProxyListener: App 10122 tries DNS query. Accept family:2 protocol:0
06-06 13:17:11.182   477 10920 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:11.182   477 10920 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-06 13:17:11.182   477 10920 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:11.182   477 10920 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:11.192  1277  4172 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:11.202  5117 10716 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:11.612  7556 10890 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:11.612  7556 10890 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:11.612  7556 10890 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:11.612  7556 10890 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:11.612   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:11.612   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:11.622   477 10946 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:11.622   477 10946 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:11.622   477 10946 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:11.622   477 10946 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:11.622   477 10946 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:11.622  7556 10890 I System.out: propertyValue:false
,06-06 13:17:11.682  1277  1314 I NotificationManager: android: cancelAsUser(2126026182) by android
,06-06 13:17:11.692  5117 10947 I VacuumService: Vacuum at: now=1465211831700 tag=VacuumService
,06-06 13:17:11.732  7556 10890 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:11.732  7556 10890 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:11.742 10222 10458 D NDK_Model: setting up template
,06-06 13:17:11.742 10266 10544 D NDK_Model: setting up template
,06-06 13:17:11.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:11.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:11.762  7556 10949 I PeopleSync: onPerformSync() [5005f081]
,06-06 13:17:11.772  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:11.842   483  3211 I WVCdm   : CdmEngine::OpenSession
06-06 13:17:11.842   483  3211 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,06-06 13:17:11.842   483  3211 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-06 13:17:11.842   483  3211 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
06-06 13:17:11.842   483  3211 D DrmWidevineDash: Service_Initialize: starts!
06-06 13:17:11.842   483  3211 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-06 13:17:11.842   483  3211 D QSEECOMAPI: : App is not loaded in QSEE
,06-06 13:17:11.872   483  3211 D QSEECOMAPI: : Loaded image: APP id = 6
,06-06 13:17:11.872   483  3211 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-06 13:17:11.872   483  3211 D DrmWidevineDash: Service_Initialize: function time: 26ms (0s 26804635ns)
06-06 13:17:11.872   483  3211 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
06-06 13:17:11.872   483  3211 D QSAPPSVER: qsapps_get_capabilities: returns 0
06-06 13:17:11.872   483  3211 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf13e1000
06-06 13:17:11.872   483  3211 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf13e1000
,06-06 13:17:11.882   462   468 D DrmLibTime: got the req here! ret=0
06-06 13:17:11.882   462   468 D DrmLibTime: command id, time_cmd_id = 770
06-06 13:17:11.882   462   468 D DrmLibTime: time_getutcsec starts!
06-06 13:17:11.882   462   468 D DrmLibTime: QSEE Time Listener: time_getutcsec
06-06 13:17:11.882   462   468 D DrmLibTime: QSEE Time Listener: get_utc_seconds
06-06 13:17:11.882   462   468 D DrmLibTime: QSEE Time Listener: time_get_modem_time
06-06 13:17:11.882   462   468 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
06-06 13:17:11.882   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
06-06 13:17:11.882   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
06-06 13:17:11.882   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
06-06 13:17:11.882   462   468 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-06 13:17:11.882   512  1261 D QC-time-services: Daemon: Connection accepted:time_genoff
,06-06 13:17:11.882   512 10953 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
06-06 13:17:11.882   512 10953 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
06-06 13:17:11.882   512 10953 D QC-time-services: offset is: 0 for base: 13
06-06 13:17:11.882   462   468 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
06-06 13:17:11.882   462   468 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
06-06 13:17:11.882   462   468 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1465211831
06-06 13:17:11.882   462   468 D DrmLibTime: time_getutcsec returns 0, sec = 1465211831; nsec = 0
06-06 13:17:11.882   462   468 D DrmLibTime: time_getutcsec finished! 
06-06 13:17:11.882   462   468 D DrmLibTime: iotcl_continue_command finished! and return 0 
06-06 13:17:11.882   462   468 D DrmLibTime: before calling ioctl to read the next time_cmd
06-06 13:17:11.882   512  1261 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,06-06 13:17:11.882   483  3211 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 5ms (0s 5132448ns)
06-06 13:17:11.882   483  3211 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-06 13:17:11.882   483  3211 D DrmWidevineDash: _oecc01: function time: 40ms (0s 40802344ns)
06-06 13:17:11.882   483  3211 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
06-06 13:17:11.892   483  3211 D DrmWidevineDash: hlos api version =  9
06-06 13:17:11.892   483  3211 D DrmWidevineDash: tz api version =  9
06-06 13:17:11.892   483  3211 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-06 13:17:11.892   483  3211 D DrmWidevineDash: _oecc22: function time: 0ms (0s 662604ns)
06-06 13:17:11.892   483  3211 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-06 13:17:11.962   483  3211 D DrmWidevineDash: _oecc05: function time: 73ms (0s 73069427ns)
06-06 13:17:11.962   483  3211 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf17ef920
06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
,06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-06 13:17:11.962   483  3211 D DrmWidevineDash: _oecc09: function time: 1ms (0s 1068542ns)
06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf257b498, dataLength=8
06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
06-06 13:17:11.962   483  3211 D DrmWidevineDash: _oecc06: function time: 1ms (0s 1137344ns)
06-06 13:17:11.962   483  3211 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xf1fbea00, wrapped_rsa_key_length=1280
,06-06 13:17:11.972   483  3211 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-06 13:17:11.972   483  3211 D DrmWidevineDash: _oecc19: function time: 5ms (0s 5045625ns)
06-06 13:17:11.972   483  3211 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-06 13:17:11.982   483  3210 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-06 13:17:11.982   483  3210 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-06 13:17:11.982   483  3210 I WVCdm   : CdmEngine::GenerateKeyRequest
06-06 13:17:11.982   483  3210 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xf0823380, idLength=0xf18ef6f0
,06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-06 13:17:12.012   483  3210 D DrmWidevineDash: _oecc07: function time: 26ms (0s 26049584ns)
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
06-06 13:17:12.012   483  3210 D DrmWidevineDash: _oecc29: function time: 0ms (0s 575105ns)
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf18ef706, maximum = 0xf18ef707
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
06-06 13:17:12.012   483  3210 D DrmWidevineDash: _oecc28: function time: 0ms (0s 547500ns)
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-06 13:17:12.012   483  3210 D DrmWidevineDash: hlos api version =  9
06-06 13:17:12.012   483  3210 D DrmWidevineDash: tz api version =  9
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-06 13:17:12.012   483  3210 D DrmWidevineDash: _oecc22: function time: 0ms (0s 542969ns)
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf18ef774
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-06 13:17:12.012   483  3210 D DrmWidevineDash: _oecc14: function time: 0ms (0s 684584ns)
06-06 13:17:12.012   483  3210 D WVCdm   : PrepareKeyRequest: nonce=1937787387
06-06 13:17:12.012   483  3210 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xf5f9de00
06-06 13:17:12.012   483  3210 D DrmWidevineDash: message_length=1636, signature=0xf5d09580, signature_length=0xf18ef6d4
,06-06 13:17:12.062  7556 10949 I PeopleSync: Setting subscription: result=true [5005f081]
,06-06 13:17:12.082  7556 10949 I PeopleSync: Starting sync, feed=null [5005f081]
,06-06 13:17:12.092 10222 10458 D NDK_Model: Compile Source0
,06-06 13:17:12.102 10266 10544 D NDK_Model: Compile Source0
,06-06 13:17:12.142   483  3210 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
06-06 13:17:12.142   483  3210 D DrmWidevineDash: _oecc36: function time: 130ms (0s 130463021ns)
,06-06 13:17:12.142   483  3211 I WVCdm   : CdmEngine::CloseSession
06-06 13:17:12.142   483  3211 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
06-06 13:17:12.142   483  3211 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-06 13:17:12.142   483  3211 D DrmWidevineDash: _oecc10: function time: 0ms (0s 556354ns)
06-06 13:17:12.142   483  3211 I WVCdm   : L3 Terminate.
06-06 13:17:12.142   483  3211 D DrmWidevineDash: OEMCrypto_Terminate: starts!
06-06 13:17:12.142   483  3211 D DrmWidevineDash: Service_Uninitialize: starts!
06-06 13:17:12.142   483  3211 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-06 13:17:12.142   483  3211 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 6
06-06 13:17:12.142   483  3211 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
06-06 13:17:12.142   483  3211 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 946979ns)
06-06 13:17:12.142   483  3211 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 217553ns)
06-06 13:17:12.142   483  3211 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
06-06 13:17:12.142   483  3211 D DrmWidevineDash: _oecc02: function time: 1ms (0s 1731615ns)
,06-06 13:17:12.182 10222 10458 W JSVM    : Starting JSVM with App Version: explorer_2016-21-Thu_RC1
,06-06 13:17:12.202 10266 10544 W JSVM    : Starting JSVM with App Version: explorer_2016-21-Thu_RC1
,06-06 13:17:12.212  4618  6266 I art     : Explicit concurrent mark sweep GC freed 2796(110KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 528us total 38.578ms
,06-06 13:17:12.222 10777 10796 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:12.222 10777 10796 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:12.222 10777 10796 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:12.222 10777 10796 I Adreno  : Local Branch                     : 
06-06 13:17:12.222 10777 10796 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:12.222 10777 10796 I Adreno  : Remote Branch                    : NONE
06-06 13:17:12.222 10777 10796 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:12.262  1277  4172 I art     : Explicit concurrent mark sweep GC freed 36912(1673KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 57MB/86MB, paused 1.649ms total 155.603ms
,06-06 13:17:12.282  1277  4193 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:12.322  5117 10715 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:12.362  5117  5117 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,06-06 13:17:12.362  7556 10556 I CheckinUtil: Classify the device as Phone.
,06-06 13:17:12.422  7556 10949 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,06-06 13:17:12.492  5117 10969 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,06-06 13:17:12.512 10425 10425 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,06-06 13:17:12.532   589   589 I MSM-irqbalance: Decided to move IRQ65 from CPU0 to CPU3
,06-06 13:17:12.542  7556 10556 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:12.542  7556 10556 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:12.542  7556 10556 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:12.542  7556 10556 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:12.542   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:12.542   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:12.542   477 10970 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:12.542   477 10970 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:12.542   477 10970 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:12.542   477 10970 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:12.542   477 10970 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:12.542  7556 10556 I System.out: propertyValue:false
,06-06 13:17:12.582  1277  4215 I ActivityManager: Killing 9753:com.lge.formmanager/u0a49 (adj 15): empty #22
,06-06 13:17:12.592  1277  1314 I NotificationManager: android: cancelAsUser(2145784878) by android
,06-06 13:17:12.622  7556 10556 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:12.622  7556 10556 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:12.692  1277  3751 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:12.732  5117 10715 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:12.742  1277  1314 I ActivityManager: Start proc 10971:com.google.android.syncadapters.calendar/u0a109 for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService
,06-06 13:17:12.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:12.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:12.802  7556  8083 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:12.802  7556  8083 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:12.822 10971 10971 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,06-06 13:17:12.862  7556 10556 I CheckinTask: Sending checkin request (12335 bytes)
,06-06 13:17:13.152  1277  1294 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:13.182  5117  5136 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:13.222 10971 10992 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.222 10971 10992 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:13.222 10971 10992 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.222 10971 10992 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:13.222   477  1248 E BandwidthController: [LG DATA] No such appUid: 10109
06-06 13:17:13.222   477  1248 D DnsProxyListener: App 10109 tries DNS query. Accept family:0 protocol:0
06-06 13:17:13.222   477 10995 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:13.222   477 10995 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:13.222   477 10995 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:13.222   477 10995 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:13.222   477 10995 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:13.222 10971 10992 I System.out: propertyValue:false
,06-06 13:17:13.282  7556 10556 I CheckinResponseProcessor: From server: 4 gservices updates and 0 deletes
,06-06 13:17:13.322 10971 10992 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.322 10971 10992 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:13.352 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.352 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:13.352 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.352 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:13.352   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:13.352   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
06-06 13:17:13.352   477 10999 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:13.352   477 10999 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:13.352 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.352 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:13.352   477 10999 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:13.352 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.352 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:13.352   477 10999 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:13.352   477  1248 E BandwidthController: [LG DATA] No such appUid: 10120
06-06 13:17:13.352   477  1248 D DnsProxyListener: App 10120 tries DNS query. Accept family:0 protocol:0
06-06 13:17:13.352   477 11000 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:13.352   477 11000 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:13.362   477 11000 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:13.362   477 11000 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:13.392  1277 11001 I CertBlacklister: Certificate blacklist changed, updating...
,06-06 13:17:13.402  1277 11001 I CertBlacklister: Certificate blacklist updated
,06-06 13:17:13.412  1277  1277 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-06 13:17:13.412  1277  1277 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-06 13:17:13.412  1277  1277 D Ulp_jni : JNI:system_update. Event-4
,06-06 13:17:13.422  1277  1277 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-06 13:17:13.422  1277  1277 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-06 13:17:13.422  1277  1277 D Ulp_jni : JNI:system_update. Event-4
,06-06 13:17:13.432  4618  4739 I GservicesProvider: main difference update completed
,06-06 13:17:13.482  1277  1317 I ActivityManager: Start proc 11005:com.google.android.partnersetup/u0a5 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,06-06 13:17:13.482  7556 10556 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,06-06 13:17:13.492  7556 10556 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-06 13:17:13.512 10474 10474 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
06-06 13:17:13.512 10474 10474 W Babel   : BAM#gBA: invalid account id: -1
06-06 13:17:13.512 10474 10474 W Babel   : BAM#gBA: invalid account id: -1
06-06 13:17:13.512 10474 10474 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,06-06 13:17:13.612  1277  1294 I ActivityManager: Start proc 11034:com.google.android.configupdater/u0a64 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,06-06 13:17:13.672  7556 10556 V CheckinRequestBuilder: No Subscriptions found on the device
,06-06 13:17:13.682 11034 11034 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-06 13:17:13.692 11034 11034 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-06 13:17:13.692 11034 11034 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-06 13:17:13.702 11034 11034 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-06 13:17:13.742  1277  4171 I ActivityManager: Start proc 11066:com.google.android.googlequicksearchbox:search/u0a63 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,06-06 13:17:13.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:13.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:13.782  1277  4215 I ActivityManager: Killing 10145:com.google.android.setupwizard/u0a54 (adj 15): empty #22
,06-06 13:17:13.792  7556 10556 I CheckinUtil: Classify the device as Phone.
,06-06 13:17:13.802   477 11000 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:13.802   477 10999 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:13.802 10222 10998 I System.out: propertyValue:false
06-06 13:17:13.802 10222 10997 I System.out: propertyValue:false
,06-06 13:17:13.902 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.902 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:13.902 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:13.902 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.002  1277  4193 D LocationManagerService: getProviders()=[passive, gps]
,06-06 13:17:14.022  7556 10556 I art     : Explicit concurrent mark sweep GC freed 51375(3MB) AllocSpace objects, 32(960KB) LOS objects, 28% free, 40MB/56MB, paused 1.300ms total 114.402ms
,06-06 13:17:14.062  4618  4739 I art     : Explicit concurrent mark sweep GC freed 11129(560KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 592us total 31.296ms
,06-06 13:17:14.082  7556 10556 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-06 13:17:14.082  7556 11098 D GmsModuleFndr: Beginning GMS chimera module scan
,06-06 13:17:14.082  7556 11098 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
06-06 13:17:14.082  7556 10556 V CheckinChimeraService: No Subscriptions found on the device
06-06 13:17:14.082  7556 11098 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
,06-06 13:17:14.082  7556 11098 D ChimeraCfgMgr: Beginning module configuration check
,06-06 13:17:14.092  7556 11098 D ChimeraCfgMgr: Module APKs unchanged, check complete
,06-06 13:17:14.092  7556 10556 I CheckinChimeraService: Checking schedule, now: 1465211834106 next: 1465779930086
06-06 13:17:14.092  7556 10556 I CheckinChimeraService: active receiver: disabled
,06-06 13:17:14.122 11066 11105 I GservicesUpdateTask: Updating Gservices keys
,06-06 13:17:14.122  7556  7556 D CheckinChimeraService: Recording last checkin time for package unspecified as 1465211834132
,06-06 13:17:14.132  7556  7556 D GoogleSignatureVerifier: Package manager can't find package com.google.android.apps.work.core, defaulting to false
,06-06 13:17:14.162  7556  7556 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,06-06 13:17:14.282 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.282 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.282 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.282 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.282  1277  3839 I art     : Explicit concurrent mark sweep GC freed 23454(1138KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 57MB/86MB, paused 1.889ms total 145.274ms
,06-06 13:17:14.282  4618  4637 I art     : Explicit concurrent mark sweep GC freed 3279(131KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 780us total 29.926ms
,06-06 13:17:14.322 10971 10992 D CalendarSyncAdapter: Found 0 events marked dirty & lastSynced
,06-06 13:17:14.352  1277  4171 I ActivityManager: Killing 10115:com.lge.cic.eden.service/u0a7 (adj 15): empty #22
,06-06 13:17:14.412  5725 10793 D AlertService: Beginning updateAlertNotification
,06-06 13:17:14.432 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.432 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.432 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:14.432 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.572  1277  1314 I NotificationManager: android: cancelAsUser(1107085079) by android
,06-06 13:17:14.582  5725 10793 D AlertService: No fired or scheduled alerts
,06-06 13:17:14.582  5725 10793 I NotificationManager: com.android.calendar: cancel(0) by com.android.calendar
,06-06 13:17:14.582  5725 10793 I NotificationManager: com.android.calendar: cancel(1) by com.android.calendar
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(2) by com.android.calendar
,06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(3) by com.android.calendar
,06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(4) by com.android.calendar
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(5) by com.android.calendar
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(6) by com.android.calendar
,06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(7) by com.android.calendar
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(8) by com.android.calendar
,06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(9) by com.android.calendar
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(10) by com.android.calendar
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(11) by com.android.calendar
,06-06 13:17:14.592  5117 11120 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
06-06 13:17:14.592  5725 10793 I NotificationManager: com.android.calendar: cancel(12) by com.android.calendar
,06-06 13:17:14.602  5725 10793 I NotificationManager: com.android.calendar: cancel(13) by com.android.calendar
06-06 13:17:14.602  5725 10793 I NotificationManager: com.android.calendar: cancel(14) by com.android.calendar
,06-06 13:17:14.602  5725 10793 I NotificationManager: com.android.calendar: cancel(15) by com.android.calendar
,06-06 13:17:14.602  5725 10793 I NotificationManager: com.android.calendar: cancel(16) by com.android.calendar
,06-06 13:17:14.602  5725 10793 I NotificationManager: com.android.calendar: cancel(17) by com.android.calendar
,06-06 13:17:14.602  5725 10793 I NotificationManager: com.android.calendar: cancel(18) by com.android.calendar
,06-06 13:17:14.612  5725 10793 I NotificationManager: com.android.calendar: cancel(19) by com.android.calendar
06-06 13:17:14.612  5725 10793 I NotificationManager: com.android.calendar: cancel(20) by com.android.calendar
,06-06 13:17:14.612  5725 10793 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,06-06 13:17:14.642  5725 10793 D AlarmScheduler: No events found starting within 1 week.
,06-06 13:17:14.642 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.642 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.642 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.642 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.652  4618  4637 I art     : Explicit concurrent mark sweep GC freed 2743(109KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 683us total 27.755ms
,06-06 13:17:14.652  1277  3839 I ActivityManager: Killing 10199:com.lge.myplace/u0a30 (adj 15): empty #22
,06-06 13:17:14.692  5117  5635 I art     : Explicit concurrent mark sweep GC freed 56960(3MB) AllocSpace objects, 7(140KB) LOS objects, 45% free, 37MB/69MB, paused 1.361ms total 94.513ms
,06-06 13:17:14.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:14.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:14.832  5117 11122 I GCoreUlr: Uploading GCM registration ID for account#2#
,06-06 13:17:14.852 10222 10997 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.852 10222 10998 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.852 10222 10998 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:14.852 10222 10997 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.862  5117 11122 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:14.872  5117 11122 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,06-06 13:17:14.872  5117 11122 V BaseAppContext: GmsRequestQueue started.
,06-06 13:17:14.922  5117 11122 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.922  5117 11122 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:14.922  5117 11122 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:14.922  5117 11122 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:14.922   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:14.922   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:14.922   477 11131 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:14.922   477 11131 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:14.922   477 11131 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:14.922   477 11131 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:14.922   477 11131 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:14.922  5117 11122 I System.out: propertyValue:false
06-06 13:17:14.922  7556  7556 I art     : Explicit concurrent mark sweep GC freed 12812(774KB) AllocSpace objects, 7(140KB) LOS objects, 28% free, 40MB/56MB, paused 1.569ms total 100.196ms
,06-06 13:17:14.932  7556  7569 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,06-06 13:17:14.992  7556  7968 E Icing   : dlopen failed: "/data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so" is 32-bit instead of 64-bit
06-06 13:17:14.992  7556  7968 E Icing   : Loading extension /data/data/com.google.android.gms/files/libAppDataSearchExt_arm64_v8a.so failed
,06-06 13:17:14.992  1277  4149 I ActivityManager: Killing 10171:com.lge.clock/u0a16 (adj 15): empty #22
,06-06 13:17:15.032  5117 11122 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:15.032  5117 11122 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:15.182  4618  6266 I art     : Explicit concurrent mark sweep GC freed 2691(105KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 606us total 40.282ms
,06-06 13:17:15.192  1277  1314 I NotificationManager: android: cancelAsUser(148851818) by android
,06-06 13:17:15.212  7556 10949 I PeopleSync: Sync finished, successful=false, took 2782ms
,06-06 13:17:15.212  7556 11138 V CheckinChimeraService: No Subscriptions found on the device
,06-06 13:17:15.212  7556 11138 I CheckinChimeraService: Checking schedule, now: 1465211835222 next: 1465779930086
06-06 13:17:15.212  7556 11138 I CheckinChimeraService: active receiver: disabled
,06-06 13:17:15.302  7556 10949 I PeopleSync: ***Sync canceled***, duration: 3535 [5005f081]
,06-06 13:17:15.312  1277  1314 I NotificationManager: android: cancelAsUser(-591465577) by android
,06-06 13:17:15.322  1277  1314 D SyncManager: handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 220824, mTimeoutStartTime 220824, mHistoryRowId 12, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 37570, reason: Periodic
,06-06 13:17:15.342  7556 11141 I PeopleSync: onPerformSync() [5005f081]
,06-06 13:17:15.362  1277  1294 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:15.382  5117 11122 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:15.662  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:15.672  7556  7556 I DynamiteModule: Considering local module com.google.android.gms.flags:0 and remote module com.google.android.gms.flags:1
06-06 13:17:15.672  7556  7556 I DynamiteModule: Selected remote version of com.google.android.gms.flags, version >= 1
,06-06 13:17:15.702  5117 11127 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:15.702  5117 11127 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:15.702  5117 11127 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:15.702  5117 11127 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:15.702  5117  5117 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=705f5327-65dd-42f3-b528-402e75b02ac4
06-06 13:17:15.702   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:15.702   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,06-06 13:17:15.702   477 11145 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:15.702   477 11145 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:15.702   477 11145 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:15.702   477 11145 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:15.702   477 11145 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:15.702  5117 11127 I System.out: propertyValue:false
,06-06 13:17:15.742  7556 11141 I PeopleSync: Setting subscription: result=true [5005f081]
,06-06 13:17:15.752  7556 11141 I PeopleSync: Starting sync, feed=null [5005f081]
,06-06 13:17:15.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:15.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:15.762  7556 11141 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,06-06 13:17:15.782  4618  4638 I art     : Explicit concurrent mark sweep GC freed 3301(130KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 552us total 34.245ms
,06-06 13:17:15.782  5117  5639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-06 13:17:15.792  5117  5117 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,06-06 13:17:15.802  5117  5635 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-06 13:17:15.802  1277  4128 W ActivityManager: Unable to start service Intent { act=com.google.android.gms.measurement.REFRESH_ENABLED_STATE pkg=com.google.android.gms } U=0: not found
,06-06 13:17:15.832  5117  5696 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,06-06 13:17:15.832  7556  7556 D OcrModelBroadcastRcvr: com.google.gservices.intent.action.GSERVICES_CHANGED
06-06 13:17:15.832  7556  7556 D OcrModelBroadcastRcvr: Updating OCR activity and model state
,06-06 13:17:15.842  7556  7556 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
06-06 13:17:15.842  7556  7556 I CmaSystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateServiceReceiver }
,06-06 13:17:15.852  5117  5635 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-06 13:17:15.852  5117  5117 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.8, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-06 13:17:15.852  7556 11146 V PrereqChecker: Build version: 22
06-06 13:17:15.852  7556 11146 V PrereqChecker: Model: LG-H815
06-06 13:17:15.852  7556 11146 V PrereqChecker: CPU_ABI: arm64-v8a
06-06 13:17:15.852  7556 11146 V PrereqChecker: CPU_ABI2: 
06-06 13:17:15.852  7556  7556 D CmaSystemUpdateService: onCreate
06-06 13:17:15.862  7556  7556 D CmaSystemUpdateService: mProcessPackageEnabled: false, mAutomaticUpdateEnabled: false
,06-06 13:17:15.862  7556  7556 D CmaSystemUpdateService: onStartCommand: intent: Intent { act=com.google.android.gms.update.START_SERVICE pkg=com.google.android.gms (has extras) }
,06-06 13:17:15.872  7556 11146 V PrereqChecker: Camera #0 is a rear-facing camera.
,06-06 13:17:15.872  7556 11147 I SystemUpdateTask: cancelUpdate (empty URL)
06-06 13:17:15.872  7556 11147 I CmaSystemUpdateService: active receiver: disabled
,06-06 13:17:15.872  7556 11146 D CreditCardPrerequisiteChecker: All prerequisites OK.
06-06 13:17:15.872  7556 11146 I OcrModelUpdtStIntSvc: Updating ocr activity enabled=false (gservicesFlag=false, lowRamDevice=false, prereqCheck=true)
,06-06 13:17:15.872  7556 11147 I NotificationManager: com.google.android.gms: cancel(2130838238) by com.google.android.gms
,06-06 13:17:15.872  7556 11147 I NotificationManager: com.google.android.gms: cancel(2130838239) by com.google.android.gms
,06-06 13:17:15.932  5117  5696 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,06-06 13:17:15.942  5117  5696 I GCoreUlr: Unbound from all location providers
,06-06 13:17:15.972  7556  7556 I art     : Explicit concurrent mark sweep GC freed 18723(1130KB) AllocSpace objects, 7(140KB) LOS objects, 28% free, 40MB/56MB, paused 1.686ms total 105.085ms
,06-06 13:17:15.992  7556  7556 D CmaSystemUpdateService: onDestroy
,06-06 13:17:16.062  1277  3374 I ActivityManager: Start proc 11152:com.google.android.setupwizard/u0a54 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
,06-06 13:17:16.062  5117  5117 I art     : Explicit concurrent mark sweep GC freed 28942(1729KB) AllocSpace objects, 6(120KB) LOS objects, 45% free, 38MB/70MB, paused 1.476ms total 98.403ms
06-06 13:17:16.062  5117  5134 I art     : WaitForGcToComplete blocked for 89.993ms for cause HeapTrim
,06-06 13:17:16.132 11152 11152 I SetupWizard: Connected to Gservices successfully
,06-06 13:17:16.192  5117  5117 I GCoreUlr: DispatchingService.onDestroy()
06-06 13:17:16.192  5117  5117 I GCoreUlr: Stopping handler for UlrDispSvcFast
,06-06 13:17:16.192  5117  5117 I GCoreUlr: Unbound from all location providers
,06-06 13:17:16.212  1277  4172 I ActivityManager: Killing 10244:com.lge.drmservice/u0a68 (adj 15): empty #22
,06-06 13:17:16.322  5117  5639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-06 13:17:16.332  5117  5639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-06 13:17:16.362  5117 11176 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-06 13:17:16.382 11152 11172 I SetupWizard.FrpHelper: FRP status: supported: true, challengeRequired: false
,06-06 13:17:16.472  5117 11122 I GCoreUlr: GCM ID uploaded for account#2#
,06-06 13:17:16.492  5117 11178 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-06 13:17:16.502  5117 11122 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,06-06 13:17:16.522  1277  1314 I NotificationManager: android: cancelAsUser(1222422273) by android
,06-06 13:17:16.522  7556 11177 D UdcContextInitService: registered all accounts: true
,06-06 13:17:16.572  1277  1314 I ActivityManager: Start proc 11179:com.google.android.gm/u0a113 for service com.google.android.gm/.provider.MailSyncAdapterService
,06-06 13:17:16.592   503   503 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 241us total 23.323ms
,06-06 13:17:16.622   503   503 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 254us total 21.434ms
,06-06 13:17:16.642   503   503 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 53% free, 28MB/60MB, paused 207us total 20.942ms
,06-06 13:17:16.642  5117  5696 I GCoreUlr: DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,06-06 13:17:16.652  5117  5696 I GCoreUlr: Unbound from all location providers
,06-06 13:17:16.652 11179 11201 I Gmail   : getAccountsCursor
,06-06 13:17:16.652 11179 11202 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,06-06 13:17:16.662  7556 11141 I PeopleSync: Sync finished, successful=true, took 894ms
,06-06 13:17:16.682  1277  4193 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,06-06 13:17:16.702  1277  4216 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,06-06 13:17:16.702  5117  5117 I GCoreUlr: DispatchingService.onDestroy()
06-06 13:17:16.702  5117  5117 I GCoreUlr: Stopping handler for UlrDispSvcFast
,06-06 13:17:16.712  5117  5117 I GCoreUlr: Unbound from all location providers
,06-06 13:17:16.722  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:16.732 11179 11179 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-06 13:17:16.732  1277  4171 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,06-06 13:17:16.742 11179 11208 I Gmail   : Observing account changes for notifications
,06-06 13:17:16.752  1277  4194 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,06-06 13:17:16.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:16.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:16.762  1277  4172 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,06-06 13:17:16.762 11179 11212 W Gmail   : Sync started for account: account:61035162
,06-06 13:17:16.772 11179 11214 I Gmail   : getAccountsCursor
,06-06 13:17:16.782 11179 11213 E Gmail   : Error finding the version of the Email provider.....
06-06 13:17:16.782 11179 11213 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
06-06 13:17:16.782 11179 11213 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-06 13:17:16.782 11179 11213 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
06-06 13:17:16.782 11179 11213 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
06-06 13:17:16.782 11179 11213 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-06 13:17:16.782 11179 11213 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-06 13:17:16.782 11179 11213 E Gmail   : 	at android.os.Looper.loop(Looper.java:135)
06-06 13:17:16.782 11179 11213 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-06 13:17:16.782 11179 11213 W EmailMigration: We do not support migrating this version of the Email provider.
,06-06 13:17:16.842  1277  3839 I art     : Explicit concurrent mark sweep GC freed 39831(1829KB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 57MB/86MB, paused 1.513ms total 169.149ms
,06-06 13:17:16.852 11179 11217 I Gmail   : notifyAccountChanged
,06-06 13:17:16.852 11179 11217 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,06-06 13:17:16.852 11179 11221 I Gmail   : getAccountsCursor
,06-06 13:17:16.862  7556 11141 I PeopleContactsSync: CP2 sync start [5005f081]
,06-06 13:17:16.862 11179 11217 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,06-06 13:17:16.862  7556 11141 I PeopleContactsSync: CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,06-06 13:17:16.872  7556 11218 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
06-06 13:17:16.872  7556 11218 D SchedPeriodicTask: Scheduled AdAttestation task.
,06-06 13:17:16.872  7556 11141 I PeopleContactsSync: Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,06-06 13:17:16.872 11179 11217 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,06-06 13:17:16.872 11179 11217 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,06-06 13:17:16.882  4618  4638 I art     : Explicit concurrent mark sweep GC freed 2747(111KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 541us total 26.545ms
,06-06 13:17:16.892 11179 11212 I Gmail   : notifyAccountChanged
,06-06 13:17:16.902  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:16.972  7556 11141 I PeopleContactsSync: CP2 cleanup done, kept= duration=99 ms
,06-06 13:17:16.972  7556 11141 I PeopleContactsSync: ===CP2 sync finished, success=true, time=110,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,06-06 13:17:16.982 11179 11228 I Gmail   : getAccountsCursor
,06-06 13:17:16.982  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:16.992 11179 11212 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 23000, normalSync: true
,06-06 13:17:16.992  7556 11141 I PeopleSync: ***Sync finished***, duration: 1653 [5005f081]
,06-06 13:17:17.012   483  5582 D WVCdm   : Instantiating CDM.
,06-06 13:17:17.012   483  3211 I WVCdm   : CdmEngine::OpenSession
06-06 13:17:17.012   483  3211 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,06-06 13:17:17.022  1277  1314 I NotificationManager: android: cancelAsUser(148851818) by android
,06-06 13:17:17.032   483  3211 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
06-06 13:17:17.032   483  3211 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
06-06 13:17:17.032   483  3211 D DrmWidevineDash: Service_Initialize: starts!
06-06 13:17:17.032   483  3211 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-06 13:17:17.032   483  3211 D QSEECOMAPI: : App is not loaded in QSEE
,06-06 13:17:17.062   483  3211 D QSEECOMAPI: : Loaded image: APP id = 7
,06-06 13:17:17.062   483  3211 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-06 13:17:17.062   483  3211 D DrmWidevineDash: Service_Initialize: function time: 32ms (0s 32672292ns)
,06-06 13:17:17.062   483  3211 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
06-06 13:17:17.062   483  3211 D QSAPPSVER: qsapps_get_capabilities: returns 0
06-06 13:17:17.062   483  3211 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf13df000
06-06 13:17:17.062   483  3211 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf13df000
,06-06 13:17:17.072   462   468 D DrmLibTime: got the req here! ret=0
06-06 13:17:17.072   462   468 D DrmLibTime: command id, time_cmd_id = 770
06-06 13:17:17.072   462   468 D DrmLibTime: time_getutcsec starts!
06-06 13:17:17.072   462   468 D DrmLibTime: QSEE Time Listener: time_getutcsec
06-06 13:17:17.072   462   468 D DrmLibTime: QSEE Time Listener: get_utc_seconds
06-06 13:17:17.072   462   468 D DrmLibTime: QSEE Time Listener: time_get_modem_time
06-06 13:17:17.072   462   468 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
06-06 13:17:17.072   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
06-06 13:17:17.072   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
06-06 13:17:17.072   462   468 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
06-06 13:17:17.072   462   468 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
06-06 13:17:17.072   512  1261 D QC-time-services: Daemon: Connection accepted:time_genoff
06-06 13:17:17.072   512 11231 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
06-06 13:17:17.072   512 11231 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
06-06 13:17:17.072   512 11231 D QC-time-services: offset is: 0 for base: 13
06-06 13:17:17.072   512  1261 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
06-06 13:17:17.072   462   468 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
06-06 13:17:17.072   462   468 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
06-06 13:17:17.072   462   468 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1465211837
06-06 13:17:17.072   462   468 D DrmLibTime: time_getutcsec returns 0, sec = 1465211837; nsec = 0
06-06 13:17:17.072   462   468 D DrmLibTime: time_getutcsec finished! 
06-06 13:17:17.072   462   468 D DrmLibTime: iotcl_continue_command finished! and return 0 
06-06 13:17:17.072   462   468 D DrmLibTime: before calling ioctl to read the next time_cmd
,06-06 13:17:17.072   483  3211 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 2ms (0s 2941979ns)
06-06 13:17:17.072   483  3211 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-06 13:17:17.072   483  3211 D DrmWidevineDash: _oecc01: function time: 41ms (0s 41274323ns)
06-06 13:17:17.072   483  3211 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-06 13:17:17.072   483  3211 D DrmWidevineDash: hlos api version =  9
06-06 13:17:17.072   483  3211 D DrmWidevineDash: tz api version =  9
06-06 13:17:17.072   483  3211 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-06 13:17:17.072   483  3211 D DrmWidevineDash: _oecc22: function time: 0ms (0s 532343ns)
06-06 13:17:17.072   483  3211 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-06 13:17:17.082 11179 11212 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:17.082 11179 11212 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-06 13:17:17.092   483  3211 D DrmWidevineDash: _oecc05: function time: 18ms (0s 18405260ns)
06-06 13:17:17.092   483  3211 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf17ef920
06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
,06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-06 13:17:17.092   483  3211 D DrmWidevineDash: _oecc09: function time: 0ms (0s 518646ns)
06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xf257b498, dataLength=8
,06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
06-06 13:17:17.092   483  3211 D DrmWidevineDash: _oecc06: function time: 0ms (0s 919635ns)
06-06 13:17:17.092   483  3211 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xf1fbe400, wrapped_rsa_key_length=1280
,06-06 13:17:17.102   483  3211 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-06 13:17:17.102   483  3211 D DrmWidevineDash: _oecc19: function time: 3ms (0s 3745312ns)
06-06 13:17:17.102   483  3211 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-06 13:17:17.102   483   483 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-06 13:17:17.102   483   483 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-06 13:17:17.102   483   483 I WVCdm   : CdmEngine::GenerateKeyRequest
06-06 13:17:17.102   483   483 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xf0823360, idLength=0xff9986e0
,06-06 13:17:17.102 11179 11212 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
,06-06 13:17:17.102 11179 11212 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:17:17.102 11179 11212 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
06-06 13:17:17.102 11179 11212 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:17.112   483   483 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-06 13:17:17.112   483   483 D DrmWidevineDash: _oecc07: function time: 18ms (0s 18358177ns)
06-06 13:17:17.112   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
06-06 13:17:17.122   483   483 D DrmWidevineDash: _oecc29: function time: 0ms (0s 778750ns)
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xff9986f6, maximum = 0xff9986f7
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
06-06 13:17:17.122   483   483 D DrmWidevineDash: _oecc28: function time: 0ms (0s 481823ns)
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-06 13:17:17.122   483   483 D DrmWidevineDash: hlos api version =  9
06-06 13:17:17.122   483   483 D DrmWidevineDash: tz api version =  9
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-06 13:17:17.122   483   483 D DrmWidevineDash: _oecc22: function time: 0ms (0s 500469ns)
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xff998764
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-06 13:17:17.122   483   483 D DrmWidevineDash: _oecc14: function time: 0ms (0s 581250ns)
06-06 13:17:17.122   483   483 D WVCdm   : PrepareKeyRequest: nonce=1216181381
06-06 13:17:17.122   483   483 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xf5f9b400
06-06 13:17:17.122   483   483 D DrmWidevineDash: message_length=1605, signature=0xf1ce7680, signature_length=0xff9986c4
,06-06 13:17:17.142 11179 11212 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:17:17.152  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:17.162  1277  4193 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:17.172  1277  1314 I NotificationManager: android: cancelAsUser(-1548111331) by android
,06-06 13:17:17.202  4618 11234 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,06-06 13:17:17.212 11179 11212 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.212 11179 11212 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:17.212 11179 11212 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.212 11179 11212 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:17.212   477  1248 E BandwidthController: [LG DATA] No such appUid: 10113
06-06 13:17:17.212   477  1248 D DnsProxyListener: App 10113 tries DNS query. Accept family:0 protocol:0
06-06 13:17:17.212   477 11235 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:17.212   477 11235 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:17.212   477 11235 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:17.212   477 11235 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:17.232   483   483 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
06-06 13:17:17.232   483   483 D DrmWidevineDash: _oecc36: function time: 112ms (0s 112289167ns)
,06-06 13:17:17.232   483  5582 I WVCdm   : CdmEngine::CloseSession
06-06 13:17:17.232   483  5582 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
06-06 13:17:17.232   483  5582 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-06 13:17:17.232   483  5582 D DrmWidevineDash: _oecc10: function time: 0ms (0s 488073ns)
06-06 13:17:17.232   483  5582 I WVCdm   : L3 Terminate.
06-06 13:17:17.232   483  5582 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,06-06 13:17:17.232   483  5582 D DrmWidevineDash: Service_Uninitialize: starts!
06-06 13:17:17.232   483  5582 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-06 13:17:17.232   483  5582 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 7
06-06 13:17:17.232   483  5582 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
06-06 13:17:17.232   483  5582 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 414792ns)
06-06 13:17:17.232   483  5582 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 185469ns)
06-06 13:17:17.232   483  5582 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
06-06 13:17:17.232   483  5582 D DrmWidevineDash: _oecc02: function time: 1ms (0s 1072760ns)
,06-06 13:17:17.262  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:17.282  1277  4216 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:17.292   477 11235 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:17.292 11179 11212 I System.out: propertyValue:false
,06-06 13:17:17.292 11179 11212 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.292 11179 11212 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:17.302  4618 11238 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.302  4618 11238 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:17.302  4618 11238 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.302  4618 11238 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:17.302   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:17.302   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:17.302   477 11240 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:17.302   477 11240 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:17.302   477 11240 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:17.302   477 11240 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:17.302   477 11240 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:17.302  4618 11238 I System.out: propertyValue:false
06-06 13:17:17.302  4618 11238 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.302  4618 11238 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:17.382 10777 10796 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:17.382 10777 10796 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:17.382 10777 10796 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:17.382 10777 10796 I Adreno  : Local Branch                     : 
06-06 13:17:17.382 10777 10796 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:17.382 10777 10796 I Adreno  : Remote Branch                    : NONE
06-06 13:17:17.382 10777 10796 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:17.492 10777 10796 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:17.492 10777 10796 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:17.492 10777 10796 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:17.492 10777 10796 I Adreno  : Local Branch                     : 
06-06 13:17:17.492 10777 10796 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:17.492 10777 10796 I Adreno  : Remote Branch                    : NONE
06-06 13:17:17.492 10777 10796 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:17.532   589   589 I MSM-irqbalance: Decided to move IRQ215 from CPU0 to CPU3
,06-06 13:17:17.552 10777 10796 I Adreno  : QUALCOMM build                   : 7fcf94b, Ib2e715f795
06-06 13:17:17.552 10777 10796 I Adreno  : Build Date                       : 07/03/15
06-06 13:17:17.552 10777 10796 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.09
06-06 13:17:17.552 10777 10796 I Adreno  : Local Branch                     : 
06-06 13:17:17.552 10777 10796 I Adreno  : Remote Branch                    : refs/tags/AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.01.081.049
06-06 13:17:17.552 10777 10796 I Adreno  : Remote Branch                    : NONE
06-06 13:17:17.552 10777 10796 I Adreno  : Reconstruct Branch               : NOTHING
,06-06 13:17:17.662  5117 11223 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.662  5117 11223 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:17.662  5117 11223 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.662  5117 11223 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:17.662   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:17.662   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:17.662   477 11242 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:17.662   477 11242 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:17.662   477 11242 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:17.662   477 11242 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:17.662   477 11242 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:17.672  5117 11223 I System.out: propertyValue:false
,06-06 13:17:17.672  4618 11238 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.672  4618 11238 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:17.672  3340  3340 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
06-06 13:17:17.672  5137  5137 I LGCover : PackageIntentReceiver: PackageIntentReceiver Received Broadcast : android.intent.action.PACKAGE_CHANGED
,06-06 13:17:17.682  1277  3177 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-06 13:17:17.682  4350  4350 I MirrorLink_UPnP: pkgReceiver : ACTION_PACKAGE_CHANGED:com.google.android.gms [TmAppListManager.java:390:onReceive()]
06-06 13:17:17.682  4350  4350 D MirrorLink_UPnP: removeApp : com.google.android.gms [TmAppListManager.java:1503:removeApp()]
,06-06 13:17:17.682  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass()
,06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.camera.app.QuickWindowCameraActivity
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.android.mms.quickcover.QuickCoverActivity
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.android.contacts.activities.QuickCircleActivity
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.music.MusicQuickCircle
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.lifetracker.QuickCover
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.smartcover.quickcircle.apps.AppMarketCoverCloseActivity
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsProvider: QuickCover getClass() cursor.getString()com.lge.smartcover.quickcircle.apps.SettingCoverCloseActivity
,06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsUtil.java:215 isSupportsQuickCircle(): cover_type : 3
06-06 13:17:17.692  5137  5137 D LGCover : QuickCoverSettingsUtil.java:226 isSupportsYGCover(): cover_type : 3
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.android.mms.quickcover.QuickCoverActivity  true
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.android.contacts.activities.QuickCircleActivity  true
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.lge.music.MusicQuickCircle  true
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.lge.lifetracker.QuickCover  true
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.lge.smartcover.quickcircle.apps.AppMarketCoverCloseActivity  true
06-06 13:17:17.702  5137  5137 D LGCover : PackageIntentReceiver: Quick cover app present in DB = com.lge.smartcover.quickcircle.apps.SettingCoverCloseActivity  true
06-06 13:17:17.712  3340  3340 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.QSlideContacts in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
06-06 13:17:17.722  3340  3340 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
06-06 13:17:17.722  3340  3340 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,06-06 13:17:17.742  1277  1314 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 334.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:17.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
06-06 13:17:17.752  4350  4350 V MirrorLink_UPnP: package name:com.google.android.gms [TmAppListManager.java:853:addInstalledPackageInfo()]
06-06 13:17:17.762  1277  1277 D administrator: Handling package changes for user 0
,06-06 13:17:17.762  4350  4350 V MirrorLink_UPnP: activity name:Google Settings class:com.google.android.gms.app.settings.GoogleSettingsActivity [TmAppListManager.java:855:addInstalledPackageInfo()]
,06-06 13:17:17.812  1277  4215 I ActivityManager: Start proc 11245:com.lge.appbox.client/u0a9 for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper
,06-06 13:17:17.812  1277  1277 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
06-06 13:17:17.812  1277  1277 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-06 13:17:17.812  1277  1277 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-06 13:17:17.832 10474 11243 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,06-06 13:17:17.832  1277  1277 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
06-06 13:17:17.832  1277  1277 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1ffaa36c
,06-06 13:17:17.832 10474 10474 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:17:17.832 10474 10474 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:17.842  4278  4278 I [LGHome]EVENT: [LauncherModel.java:199:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,06-06 13:17:17.852  4278  4278 I [LGHome]Launcher.Model: onPackageChanged=com.google.android.gms for UserHandle{0}
,06-06 13:17:17.852 11245 11245 I AppUp4:AppBoxCP: onCreate
,06-06 13:17:17.852 11245 11245 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,06-06 13:17:17.862 11245 11245 I AppUp4:DB:  setFingerPrint start
06-06 13:17:17.862 11245 11245 I AppUp4:DB:  newfinger = lge/p1_global_com/p1:5.1/LMY47D/1520217361856:user/release-keys SDK version = 22
,06-06 13:17:17.862 10474 10474 W linker  : libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
06-06 13:17:17.862 11245 11245 I AppUp4:DB:  beforefinger = lge/p1_global_com/p1:5.1/LMY47D/1520217361856:user/release-keys
06-06 13:17:17.862 11245 11245 I AppUp4:DB:  SDK version = 22
06-06 13:17:17.862 11245 11245 I AppUp4:DB:  beforefinger == newfinger no write in DB
,06-06 13:17:17.862 11245 11245 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,06-06 13:17:17.862 10474 10474 W linker  : libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
06-06 13:17:17.862 10474 10474 W linker  : libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
06-06 13:17:17.862 10474 10474 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:17.872  4278  4278 I [LGHome]Launcher: [Launcher.java:5771:waitUntilResume()]Deferring update until onResume
,06-06 13:17:17.872 11245 11245 I AppUp4:CustModeStarterReceiver: onReceive
06-06 13:17:17.872 11245 11245 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,06-06 13:17:17.872 11245 11245 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@33e0e74c
06-06 13:17:17.872 11245 11245 D AppUp4:CustFacade: isCustomizationCompleted : false
,06-06 13:17:17.872 11245 11245 D AppUp4:CustFacade: isSimDevice : true
,06-06 13:17:17.882 11245 11245 V AppUp4:DpFacade:  isStartDpPreload : false
06-06 13:17:17.882 11245 11245 D AppUp4:CustModeStarterReceiver: begin check event
06-06 13:17:17.882 11245 11245 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,06-06 13:17:17.882 10474 10474 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:17:17.932  1277  4194 I ActivityManager: Start proc 11269:com.android.contacts/u0a18 for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver
,06-06 13:17:17.952 10474 10474 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-06 13:17:17.952  5117 11223 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:17.952  5117 11223 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/com.lge.opera.jar' does not exist or contains no resources.
06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-06 13:17:17.962 11269 11269 W asset   : Asset path /system/framework/com.lge.telephony.sms.jar is neither a directory nor file (type=1).
06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/lgsvcitems.jar' does not exist or contains no resources.
,06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
06-06 13:17:17.962 11269 11269 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,06-06 13:17:17.992 11269 11269 I SystemConfig: BUILD Country: EU,
06-06 13:17:17.992 11269 11269 I SystemConfig: BUILD Operator: OPEN
,06-06 13:17:18.002 11269 11269 I NameIDHelper: NameIDHelper static init called
,06-06 13:17:18.002 11269 11269 D NameIDHelper: error trying to detect package -- we are probably not installed
,06-06 13:17:18.012 11269 11290 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
06-06 13:17:18.012 11269 11290 I SystemConfig: existFile = false
06-06 13:17:18.012 11269 11290 I SystemConfig: canReadFile = false
06-06 13:17:18.012 11269 11290 I SystemConfig: systemFeature RCS result false
06-06 13:17:18.012 11269 11290 D SystemConfig: refreshRcsSupport() :false
,06-06 13:17:18.022  4173  4192 D AbsDBObserver: onChange: false,content://com.android.contacts
06-06 13:17:18.022  3816  3816 D PackageUpdateReceiver: Action : android.intent.action.PACKAGE_CHANGED
06-06 13:17:18.022  3816  3816 D PackageUpdateReceiver: packageName : com.google.android.gms
,06-06 13:17:18.022  4173  5785 D AbsDBObserver: onChangeInternal: false,content://com.android.contacts
06-06 13:17:18.022  3816  3816 D PackageUpdateReceiver: packageName getApplicationEnabledSetting result : 0
06-06 13:17:18.022  3816  3816 D PackageUpdateReceiver: packageName appStatus : enable_app
,06-06 13:17:18.022  6404  6404 I LOG_TAG : sendMessageToComposeMessageActivy + null
,06-06 13:17:18.072  1277  4149 I ActivityManager: Start proc 11295:com.lge.lockscreensettings/1000 for broadcast com.lge.lockscreensettings/.PackageIntentReceiver
,06-06 13:17:18.072  5117 10715 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:18.072  5117 10715 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:18.102 11295 11295 W ResourcesManager: Asset path '/system/framework/com.lge.locksettings.jar' does not exist or contains no resources.
06-06 13:17:18.102 11295 11295 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-06 13:17:18.122  1277  4216 I ActivityManager: Killing 10357:com.android.chrome/u0a101 (adj 15): empty #22
,06-06 13:17:18.192  5117 10715 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:18.192  5117 10715 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:18.292  4173  4190 D AbsDBObserver: onChange: false,content://com.android.contacts
06-06 13:17:18.302  6404  6404 I LOG_TAG : sendMessageToComposeMessageActivy + null
06-06 13:17:18.302  4173  5785 D AbsDBObserver: onChangeInternal: false,content://com.android.contacts
06-06 13:17:18.352 11066 11316 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
06-06 13:17:18.422 10560 10692 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:18.422 10560 10692 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:18.422 10560 10692 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:18.422 10560 10692 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:18.422   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:17:18.422   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
06-06 13:17:18.422   477 11320 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:18.422   477 11320 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:18.422   477 11320 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:18.422   477 11320 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:18.472  7556 11107 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
06-06 13:17:18.472  7556 11107 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoring.
06-06 13:17:18.472 11066 11316 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
06-06 13:17:18.482  7556 11107 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
06-06 13:17:18.502  7556 11323 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
06-06 13:17:18.502  7556  7968 I Icing   : updateResources: need to parse pru{com.google.android.gms}
06-06 13:17:18.502   477 11320 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:17:18.502 10560 10692 I System.out: propertyValue:false
06-06 13:17:18.502 10560 10692 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:18.502 10560 10692 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:18.502  1277  4215 I NotificationManager: android: cancelAsUser(2) by android
06-06 13:17:18.522  5117 10715 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
06-06 13:17:18.602 10474 11288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-06 13:17:18.612 10560 10692 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:18.612 10560 10692 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:18.672  1277  4194 I art     : Explicit concurrent mark sweep GC freed 28301(1372KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 57MB/86MB, paused 1.766ms total 164.273ms
06-06 13:17:18.712  1277  4149 I ActivityManager: Killing 10383:com.qualcomm.timeservice/1000 (adj 15): empty #22
06-06 13:17:18.712  1277  1314 I NotificationManager: android: cancelAsUser(1756586498) by android
,06-06 13:17:18.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:18.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:18.852 10474 11330 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:18.852 10474 11330 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
06-06 13:17:18.852   477  1248 E BandwidthController: [LG DATA] No such appUid: 10121
06-06 13:17:18.852   477  1248 D DnsProxyListener: App 10121 tries DNS query. Accept family:2 protocol:0
06-06 13:17:18.852   477 11338 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:18.852   477 11338 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,06-06 13:17:18.852   477 11338 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:18.852   477 11338 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:18.862  7556 11326 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-06 13:17:18.882 11179 11179 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,06-06 13:17:18.902  1277  1314 I NotificationManager: android: cancelAsUser(2145784878) by android
,06-06 13:17:18.952  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:18.972  5117 11342 E CommitToConfigurationOperation: Malformed snapshot token: 
,06-06 13:17:18.972  5117 11321 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-06 13:17:18.982  4618  4638 I art     : Explicit concurrent mark sweep GC freed 14368(762KB) AllocSpace objects, 3(80KB) LOS objects, 52% free, 29MB/61MB, paused 875us total 44.084ms
,06-06 13:17:19.012  5117 11341 E CommitToConfigurationOperation: Malformed snapshot token: 
06-06 13:17:19.012  5117 11321 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-06 13:17:19.032  5117 11341 E CommitToConfigurationOperation: Malformed snapshot token: 
06-06 13:17:19.032  5117 11321 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-06 13:17:19.032  5117 11321 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,06-06 13:17:19.042  5117  5696 W Herrevad: Invalid mccmnc 
06-06 13:17:19.042  5117  5696 W Herrevad: Invalid mccmnc 
,06-06 13:17:19.042  5117 11321 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:19.062  4078  4105 E PhoneInterfaceManager: [teleUICC] getCellinfo Called for subId --> 2147483643
,06-06 13:17:19.102  1277  4194 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:19.132  5117 11343 I art     : Explicit concurrent mark sweep GC freed 103527(5MB) AllocSpace objects, 30(708KB) LOS objects, 44% free, 39MB/71MB, paused 8.669ms total 150.821ms
,06-06 13:17:19.142  5117 11321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:19.142  5117 11321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:17:19.142  5117 11321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:19.142  5117 11321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:19.142   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:19.142   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:19.142   477 11349 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:19.142   477 11349 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:19.142   477 11349 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:19.142   477 11349 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:19.212  5117  5696 V NQFileLogger: [182] LightweightReportNetworkQualityChimeraOperation.a: about to write to file
,06-06 13:17:19.232   477 11349 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:19.232  5117 11321 I System.out: propertyValue:false
,06-06 13:17:19.242  1277  1314 I NotificationManager: android: cancelAsUser(898701380) by android
,06-06 13:17:19.252  5117  5696 V ProcessReports: [182] LightweightReportNetworkQualityChimeraOperation.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,06-06 13:17:19.272  1277  1314 I NotificationManager: android: cancelAsUser(1500439826) by android
,06-06 13:17:19.312 11179 11212 I art     : Explicit concurrent mark sweep GC freed 164128(6MB) AllocSpace objects, 15(320KB) LOS objects, 34% free, 30MB/46MB, paused 667us total 65.507ms
,06-06 13:17:19.322 11179 11212 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 23183, normalSync: true
,06-06 13:17:19.322 11179 11212 I Gmail   : lowestBackward conversation id 0
,06-06 13:17:19.352 11179 11179 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,06-06 13:17:19.362 11179 11179 I NotificationManager: com.google.android.gm: cancel(10436) by com.google.android.gm
,06-06 13:17:19.402 11179 11212 I Gmail   : notifyAccountChanged
,06-06 13:17:19.412 11179 11357 I Gmail   : getAccountsCursor
,06-06 13:17:19.412  1277  1314 I NotificationManager: android: cancelAsUser(-1874035846) by android
,06-06 13:17:19.412  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:19.412 11179 11212 I Gmail   : notifyAccountChanged
06-06 13:17:19.422 11179 11212 W Gmail   : Sync complete for account: account:61035162
,06-06 13:17:19.432 11179 11201 I Gmail   : getAccountsCursor
,06-06 13:17:19.442  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-06 13:17:19.442  1277  1314 I NotificationManager: android: cancelAsUser(1479798955) by android
,06-06 13:17:19.462 10596 11358 I SyncAdapterService: Ignoring sync request for non-current account
,06-06 13:17:19.542  1277  1314 I NotificationManager: android: cancelAsUser(-701419433) by android
,06-06 13:17:19.592  1277  1314 I ActivityManager: Start proc 11361:com.google.android.music:main/u0a123 for service com.google.android.music/.sync.SyncAdapterService
,06-06 13:17:19.662 10474 11288 I art     : Note: end time exceeds epoch: 
,06-06 13:17:19.662 11361 11361 I MusicStore: Database version: 120
,06-06 13:17:19.672  1277  3751 I ActivityManager: Killing 10744:com.lge.exchange/u0a22 (adj 15): empty #22
,06-06 13:17:19.672 10474 11383 I Babel   : Account registration complete:1-Redacted-21
,06-06 13:17:19.682 10474 11383 I Babel   : ProcessRegisterDeviceResponse
06-06 13:17:19.682 10474 11383 I Babel   : Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,06-06 13:17:19.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:19.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:19.812  1277  4107 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:19.842  5117 11321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:19.842  5117 11321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:19.842  5117 11321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:19.842  5117 11321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:19.842   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:17:19.842   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:17:19.842   477 11398 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:19.842   477 11398 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:17:19.842   477 11398 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:17:19.842   477 11398 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:17:19.842   477 11398 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:19.842  5117 11321 I System.out: propertyValue:false
06-06 13:17:19.842  1277  1314 I NotificationManager: android: cancelAsUser(-379682945) by android
,06-06 13:17:19.872  1277  1314 I NotificationManager: android: cancelAsUser(-1816247584) by android
,06-06 13:17:19.882  1277  4107 W ActivityManager: getRunningAppProcesses: caller 10123 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:19.892  7556  7968 I Icing   : Indexing D03D1C6FF4E2944E5873460C70D2CF7EDFA0293F from com.google.android.gms
,06-06 13:17:19.902 11361 11361 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-06 13:17:19.902 11361 11361 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:17:19.902  5117 11321 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:19.902  5117 11321 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:19.922 11361 11361 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
,06-06 13:17:19.922  7556 11401 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,06-06 13:17:19.922 11361 11361 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:17:19.922 11361 11361 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
,06-06 13:17:19.922 11361 11361 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:17:19.932  1277  1314 I NotificationManager: android: cancelAsUser(-591465577) by android
,06-06 13:17:19.942  7556  7968 I Icing   : Indexing done D03D1C6FF4E2944E5873460C70D2CF7EDFA0293F
,06-06 13:17:19.962 11361 11361 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-06 13:17:19.962 11361 11361 D AndroidMusic: GMSCore installation verified
,06-06 13:17:19.972 11361 11361 I ConfigStore: Config Database version: 1
,06-06 13:17:20.012  4618  4638 I art     : Explicit concurrent mark sweep GC freed 4508(182KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 615us total 27.306ms
,06-06 13:17:20.262  1277  4194 I art     : Explicit concurrent mark sweep GC freed 35219(1449KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 57MB/86MB, paused 2.826ms total 195.924ms
,06-06 13:17:20.262 11361 11361 V MediaRouter: selectRouteStatic types 8388615
,06-06 13:17:20.282 11361 11361 I art     : Thread[1,tid=11361,WaitingForJniOnLoad,Thread*=0x7f80c95000,peer=0x758a4fa8,"main"] recursive attempt to load library "/system/lib64/libhook_jni.so"
,06-06 13:17:20.282 11361 11361 E MediaProfilesEx-JNI: register_com_lge_media_MediaProfilesEx
,06-06 13:17:20.282 11361 11361 E MediaRecorderEx-JNI: register_com_lge_media_MediaRecorderEx
06-06 13:17:20.282 11361 11361 D AudioSystemEx: register_com_lge_media_LGAudioSystem
,06-06 13:17:20.282 11361 11361 E SurfaceControlEx: register_com_lge_view_SurfaceControlEx
,06-06 13:17:20.292 11361 11361 I art     : Thread[1,tid=11361,WaitingForJniOnLoad,Thread*=0x7f80c95000,peer=0x758a4fa8,"main"] recursive attempt to load library "/system/lib64/libhook_jni.so"
06-06 13:17:20.292 11361 11361 D LGMtpDatabaseJNI: register_android_mtp_LGMtpDatabase
,06-06 13:17:20.292 11361 11361 I art     : Thread[1,tid=11361,WaitingForJniOnLoad,Thread*=0x7f80c95000,peer=0x758a4fa8,"main"] recursive attempt to load library "/system/lib64/libhook_jni.so"
,06-06 13:17:20.292 11361 11361 D LGMtpServerJNI: register_android_mtp_LGMtpServer
,06-06 13:17:20.292 11361 11361 I art     : Thread[1,tid=11361,WaitingForJniOnLoad,Thread*=0x7f80c95000,peer=0x758a4fa8,"main"] recursive attempt to load library "/system/lib64/libhook_jni.so"
06-06 13:17:20.292 11361 11361 E MediaPlayerEx-jni: register_com_lge_view_MediaPlayerEx
,06-06 13:17:20.292 11361 11361 I art     : Thread[1,tid=11361,WaitingForJniOnLoad,Thread*=0x7f80c95000,peer=0x758a4fa8,"main"] recursive attempt to load library "/system/lib64/libhook_jni.so"
06-06 13:17:20.292 11361 11361 D         : register_com_lge_emoji_EmojiUtil
,06-06 13:17:20.292   483  3210 V AudioPolicyManagerEx: [twin_headset] getTwinHeadsetOn() 0
06-06 13:17:20.292   483  3210 D AllegroService: AllegroService getParameters GET_TWIN_HEADSET_ON = OFF
06-06 13:17:20.292 11361 11361 V AudioManager: [twin_headset] getTwinHeadsetOn() on false
,06-06 13:17:20.302 11361 11361 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-06 13:17:20.302 10971 11403 V CalendarSyncAdapter: Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-06-23T00:00:00.000Z, updatedMin=2016-05-14T14:11:57.773Z}
,06-06 13:17:20.312  1277  1295 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:20.322  4173  4190 D AbsDBObserver: onChange: false,content://com.android.calendar
06-06 13:17:20.322  4173  4192 D AbsDBObserver: onChange: false,content://com.android.calendar
,06-06 13:17:20.322  4173  5785 D AbsDBObserver: onChangeInternal: false,content://com.android.calendar
,06-06 13:17:20.332 10971 11402 D CalendarSyncAdapter: Found 0 events marked dirty & lastSynced
,06-06 13:17:20.352  4173  5785 D AbsDBObserver: onChangeInternal: false,content://com.android.calendar
,06-06 13:17:20.352  5117 11321 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:17:20.352  1277  1314 I NotificationManager: android: cancelAsUser(1107085079) by android
,06-06 13:17:20.372 11361 11361 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-06 13:17:20.372 11361 11361 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:20.382  7556  7968 I Icing   : Indexing 2136551A50F2EBE4C3306AC1CFB7354C1CA47211 from com.google.android.gm
,06-06 13:17:20.382 11361 11361 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-06 13:17:20.382 11361 11408 I MusicLifecycle: Sync started
,06-06 13:17:20.402 11179 11328 I Gmail   : Backfilling search sequence table
,06-06 13:17:20.412 11361 11361 V MediaRouter: selectRouteStatic types 8388611
,06-06 13:17:20.412   483   483 V AudioPolicyManagerEx: [twin_headset] getTwinHeadsetOn() 0
06-06 13:17:20.412   483   483 D AllegroService: AllegroService getParameters GET_TWIN_HEADSET_ON = OFF
06-06 13:17:20.412 11361 11361 V AudioManager: [twin_headset] getTwinHeadsetOn() on false
06-06 13:17:20.412 11361 11361 W MediaRouter: selectRouteStatic oldRoute and route same case return;
,06-06 13:17:20.422 11361 11361 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-06 13:17:20.432 11361 11361 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-06 13:17:20.432 11361 11361 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-06 13:17:20.452  7556  7968 I Icing   : Indexing done 2136551A50F2EBE4C3306AC1CFB7354C1CA47211
,06-06 13:17:20.462 11361 11387 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,06-06 13:17:20.492  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:17:20.512  1277  4151 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:17:20.512 11361 11408 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:20.512 11361 11408 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:20.512 11361 11408 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:17:20.512 11361 11408 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:20.512   477  1248 E BandwidthController: [LG DATA] No such appUid: 10123
06-06 13:17:20.512   477  1248 D DnsProxyListener: App 10123 tries DNS query. Accept family:0 protocol:0
06-06 13:17:20.512   477 11416 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:17:20.512   477 11416 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:17:20.512   477 11416 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:17:20.512   477 11416 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:17:20.612   477 11416 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:17:20.612 11361 11408 I System.out: propertyValue:false
,06-06 13:17:20.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 126.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:20.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:20.762 11361 11408 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:17:20.762 11361 11408 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:17:21.192  1277  1317 I ActivityManager: Waited long enough for: ServiceRecord{33c567d4 u0 com.lge.sizechangable.weather.platform/.receiver.ScreenOnCheckerService}
,06-06 13:17:21.202 11361 11408 I MusicSyncAdapter: Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
06-06 13:17:21.202 11361 11408 I MusicSyncAdapter: Periodic update
,06-06 13:17:21.232 11361 11411 W MusicApiClient: Activity events list is null or empty. Skip reporting.
,06-06 13:17:21.242 11361 11408 I MusicLifecycle: Sync ended
,06-06 13:17:21.242  1277  1314 I NotificationManager: android: cancelAsUser(-1123058983) by android
,06-06 13:17:21.272 11361 11420 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-06 13:17:21.272 11361 11420 I MusicLeanback: Stop autocaching.
,06-06 13:17:21.312  5117  5117 D WearableService: callingUid 10006, callindPid: 5117
,06-06 13:17:21.332 11361 11361 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
06-06 13:17:21.332 11361 11426 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-06 13:17:21.332  1277  3839 I ActivityManager: Killing 10505:com.lge.email/u0a56 (adj 15): empty #22
,06-06 13:17:21.552  1277  1294 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:21.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:21.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
06-06 13:17:21.752 11179 11207 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-06 13:17:21.762  1277  3839 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,06-06 13:17:21.892  1277  4149 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:21.932  5117 11148 D PlaceInferenceEngine: Stop called when not running
,06-06 13:17:21.942  5117  5639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-06 13:17:22.322  1277  4216 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:22.492  1277  4216 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:22.532   589   589 I MSM-irqbalance: Decided to move IRQ57 from CPU0 to CPU3
,06-06 13:17:22.612  1277  3839 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:22.662  1277  4128 I ActivityManager: Killing 9973:com.lge.bnr/1000 (adj 15): empty #22
,06-06 13:17:22.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:22.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:22.882  1277  3645 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.022  1277  3645 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.192  1277  4128 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.222  1277  3185 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=232362
,06-06 13:17:23.222  1277  3185 D NetworkManagementService: getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=232364
06-06 13:17:23.222  1277  3185 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=1887239 rxPackets=1962 txBytes=215127 txPackets=1483 operations=0
06-06 13:17:23.222  1277  3185 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
,06-06 13:17:23.222  1277  3185 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=232366
06-06 13:17:23.222  1277  3185 D NetworkManagementService: getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=232367
06-06 13:17:23.222  1277  3185 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=1887567 rxPackets=1966 txBytes=233921 txPackets=1443 operations=0
06-06 13:17:23.222  1277  3185 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
,06-06 13:17:23.362  1277  1294 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.492  1277  3374 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.642  1277  1364 W PackageSettings: Skipping PackageSetting{11437863 com.example.hello/10361} due to missing metadata
,06-06 13:17:23.672  1277  4215 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:23.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:23.812  1277  4172 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:23.962  1277  3374 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:24.162  1277  3374 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:24.332  1277  4172 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:24.502  1277  1294 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:24.652  1277  3374 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:24.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:24.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:24.782  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3cb4d529 type 2 when 228826 com.google.android.talk} when 228826
,06-06 13:17:24.832  1277  3751 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:24.972  1277  4107 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:25.122 11361 11434 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
06-06 13:17:25.122 11361 11434 I MusicLeanback: Stop autocaching.
,06-06 13:17:25.132  1277  4107 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:25.152 10474 11433 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
06-06 13:17:25.152 10474 11433 E Babel   : Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,06-06 13:17:25.162 11361 11361 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-06 13:17:25.162 11361 11437 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-06 13:17:25.292  1277  3645 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:25.422 10474 11288 I art     : Note: end time exceeds epoch: 
,06-06 13:17:25.502  1277  4216 I ActivityManager: Killing 10310:com.lge.task/u0a20 (adj 15): empty #22
,06-06 13:17:25.502  1277  3374 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:25.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:25.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:25.762  1277  4107 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:17:26.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
,06-06 13:17:26.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:27.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:27.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:28.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 6.0 azimuth: 43.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:28.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:29.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
,06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:29.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:30.462  1277  4216 I ActivityManager: Killing 10560:com.google.android.youtube/u0a124 (adj 15): empty #22
,06-06 13:17:30.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:30.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:30.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:17:30.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:17:30.942  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 240083937303; DSPS: 8034531; Offset : -5110489406
,06-06 13:17:31.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:31.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:32.532   589   589 I MSM-irqbalance: Decided to move IRQ222 from CPU0 to CPU3
,06-06 13:17:32.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:32.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found,
06-06 13:17:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:17:32.932  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:17:32.932  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:17:32.932  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:17:32.932  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:17:32.932  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:17:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 285,
06-06 13:17:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:17:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:17:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 288
,06-06 13:17:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
,06-06 13:17:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:17:32.952  4025  4383 D LEDHandler: Battery Temp: 285, mChargingStatus=2, mChargingStop=false
06-06 13:17:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:17:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:17:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:17:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:17:33.152  1277  3185 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=242297,
,06-06 13:17:33.162  1277  3185 D NetworkManagementService: getNetworkStatsSummaryXt:NetworkStats: elapsedRealtime=242299
06-06 13:17:33.162  1277  3185 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=3892172 rxPackets=3668 txBytes=325259 txPackets=2393 operations=0
06-06 13:17:33.162  1277  3185 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
,06-06 13:17:33.162  1277  3185 D NetworkManagementService: hardware tether stats:NetworkStats: elapsedRealtime=242303
,06-06 13:17:33.172  1277  3185 D NetworkManagementService: getNetworkStatsSummaryDev:NetworkStats: elapsedRealtime=242307,
06-06 13:17:33.172  1277  3185 D NetworkManagementService:   [0] iface=wlan0 uid=-1 set=ALL tag=0x0 rxBytes=3904500 rxPackets=3680 txBytes=352107 txPackets=2282 operations=0
06-06 13:17:33.172  1277  3185 D NetworkManagementService:   [1] iface=lo uid=-1 set=ALL tag=0x0 rxBytes=0 rxPackets=0 txBytes=0 txPackets=0 operations=0
,06-06 13:17:33.302  1277  4172 W ActivityManager: Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
,06-06 13:17:33.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:33.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:34.132  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{fa83e36 type 2 when 243268 android} when 243268
,06-06 13:17:34.142 10288 10288 D WeatherPlatformReceiver: start action : com.lge.sizechangable.weather.action.autoupdate
06-06 13:17:34.142 10288 10288 D WeatherPlatformReceiver: start update by AutoUpdate
,06-06 13:17:34.142 10288 10288 D WeatherPlatformReceiver: end action : com.lge.sizechangable.weather.action.autoupdate : 9ms
06-06 13:17:34.152 10288 10288 D WeatherUpdateService: start update service by com.lge.sizechangable.weather.platform.UpdateService.action.update.all)
06-06 13:17:34.152 10288 10288 D WeatherUpdateService: Make update type - checker : 100, action : 11
06-06 13:17:34.152 10288 10288 D WeatherUpdateService: check update on : 100 & 1 = 0
06-06 13:17:34.152 10288 10288 D WeatherUpdateService: check remained time : 100 & 10 = 0
06-06 13:17:34.152 10288 10288 D WeatherUpdateService: set isOnUpdating : true
,06-06 13:17:34.152 10288 11443 D WeatherUpdateService: check screen on : 100 & 100 = 100
,06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.162  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.172  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.172  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.172  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.172  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
06-06 13:17:34.172  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:34.172  1277  4172 W ActivityManager: getRunningAppProcesses: caller 10096 does not hold REAL_GET_TASKS; limiting output
,06-06 13:17:34.172 10288 11443 D WeatherUpdateWorker: do not update. screen off.
06-06 13:17:34.172 10288 11443 D WeatherUpdateService: onResult
06-06 13:17:34.172 10288 11443 D WeatherUpdateService: action start screen on service : 11 & 10 = 10
06-06 13:17:34.172 10288 11443 D WeatherUpdateService: set isOnUpdating : false
,06-06 13:17:34.172 10288 10288 D WeatherUpdateService: stop this service at update result handler.
,06-06 13:17:34.182 10288 10288 D WeatherUpdateService: isOnProcessing - onAdding : false, onUpdating : false
06-06 13:17:34.182 10288 10288 D WeatherUpdateService: stop update service
,06-06 13:17:34.182  4278  4278 D [Concierge][WeatherPanel]: refreshIconClicked spinning Status : false
,06-06 13:17:34.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:34.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:35.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:35.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:36.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826,
,06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A,
,06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A,
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
,06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
,06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:36.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:37.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
,06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:37.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:38.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 336.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:38.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:39.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:39.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:40.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:40.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:41.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:41.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:42.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:42.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
,06-06 13:17:43.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:44.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:44.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:45.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
,06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
,06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:45.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:46.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:46.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:47.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:47.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:48.072  7556 11445 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-06 13:17:48.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:48.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:49.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:49.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:50.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
,06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
,06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:50.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:50.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2,
06-06 13:17:50.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,06-06 13:17:50.942  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 260086295316; DSPS: 8689968; Offset : -5110481011
,06-06 13:17:51.462 11361 11361 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-06 13:17:51.502  7556 11447 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-06 13:17:51.512 11361 11361 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-06 13:17:51.532 11361 11361 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-06 13:17:51.552 11361 11361 I NotificationManager: com.google.android.music: cancel(10436) by com.google.android.music
,06-06 13:17:51.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:51.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:52.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
,06-06 13:17:52.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:52.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:52.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:52.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:52.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:52.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
,06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
,06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
,06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:52.762  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:53.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
,06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
,06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
,06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:53.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
,06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
,06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
,06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
,06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
,06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
,06-06 13:17:53.762  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:54.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:54.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:55.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:55.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:56.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:56.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:57.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:57.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:58.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
,06-06 13:17:58.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
,06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
,06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
,06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
,06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
,06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
,06-06 13:17:58.762  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:17:59.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 337.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:17:59.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:00.342  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59685
06-06 13:18:00.342  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:18:00.342  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:18:00.342  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:18:00.342  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:18:00.342  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:18:00.352  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:18:00.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
,06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:00.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:01.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:01.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:02.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826,
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A,
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A,
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:02.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:03.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
,06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 302.0   A
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
,06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
,06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:03.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:04.152  1277  3175 D PowerManagerServiceEx: acquireWakeLockInternal: lock=409116303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1277,
,06-06 13:18:04.152  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8daa0e6 type 2 when 273296 android} when 273296
,06-06 13:18:04.192  5199  5199 D [Concierge][ConciergeService]: onStartCommand(). Type : 11
,06-06 13:18:04.192  1277  1277 D PowerManagerServiceEx: releaseWakeLockInternal: lock=409116303 [*alarm*], flags=0x0,
,06-06 13:18:04.242  7556 11450 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,06-06 13:18:04.242  1277  1314 I NotificationManager: android: cancelAsUser(1322057929) by android
,06-06 13:18:04.252  1277  1314 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 244175, reason: UserStart, SyncResult: databaseError: true stats []
06-06 13:18:04.252  1277  1314 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 334980, reason: UserStart
06-06 13:18:04.252  1277  1314 I NotificationManager: android: cancelAsUser(716319171) by android
,06-06 13:18:04.262  1277  1314 I NotificationManager: android: cancelAsUser(895932782) by android
,06-06 13:18:04.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:04.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:05.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:05.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:06.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:06.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:07.392 10266 11453 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:07.392 10266 11453 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:18:07.392 10266 11453 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:07.392 10266 11453 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:18:07.392   477  1248 E BandwidthController: [LG DATA] No such appUid: 10125
06-06 13:18:07.392   477  1248 D DnsProxyListener: App 10125 tries DNS query. Accept family:0 protocol:0
,06-06 13:18:07.392   477 11454 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:18:07.392   477 11454 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:18:07.392   477 11454 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:18:07.392   477 11454 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:18:07.392   477 11454 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:18:07.392 10266 11453 I System.out: propertyValue:false
,06-06 13:18:07.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:07.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:07.772 10266 11453 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:18:07.772 10266 11453 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:18:08.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
,06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:08.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:09.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:09.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:10.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:10.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:10.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:18:10.942  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:18:10.942  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 280088474475; DSPS: 9345400; Offset : -5110499665
,06-06 13:18:11.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
06-06 13:18:11.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: SV count: 22 ephemerisMask: 0 almanacMask: 16826,
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 2 snr: 0.0 elev: 27.0 azimuth: 125.0   A
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 3 snr: 0.0 elev: 1.0 azimuth: 11.0   A
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 6 snr: 0.0 elev: 30.0 azimuth: 74.0   A,
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 12 snr: 0.0 elev: 82.0 azimuth: 338.0   A,
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 14 snr: 0.0 elev: 28.0 azimuth: 300.0   A,
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 15 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 17 snr: 0.0 elev: 5.0 azimuth: 43.0   A
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 74 snr: 0.0 elev: 78.0 azimuth: 54.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 73 snr: 0.0 elev: 30.0 azimuth: 115.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 66 snr: 0.0 elev: 16.0 azimuth: 337.0   A
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 75 snr: 0.0 elev: 35.0 azimuth: 310.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 65 snr: 0.0 elev: 11.0 azimuth: 282.0    
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 84 snr: 0.0 elev: 64.0 azimuth: 143.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 83 snr: 0.0 elev: 40.0 azimuth: 39.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 85 snr: 0.0 elev: 21.0 azimuth: 188.0    
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 67 snr: 0.0 elev: 0.0 azimuth: 0.0   A
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 72 snr: 0.0 elev: 0.0 azimuth: 0.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 202 snr: 0.0 elev: 8.0 azimuth: 112.0    
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 205 snr: 0.0 elev: 20.0 azimuth: 132.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 208 snr: 0.0 elev: 19.0 azimuth: 37.0    
06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 214 snr: 0.0 elev: 3.0 azimuth: 299.0    
,06-06 13:18:12.752  1277  3657 D GpsLocationProvider: sv: 215 snr: 0.0 elev: 42.0 azimuth: 56.0    
,06-06 13:18:16.882  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:16.882  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:16.922  5117  5696 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> BAD_AUTHENTICATION. Account: <ELLIDED:-818113082>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
06-06 13:18:16.922  5117  5696 E Auth    : elc: Long live credential not available.
06-06 13:18:16.922  5117  5696 E Auth    : 	at eld.a(SourceFile:3099)
06-06 13:18:16.922  5117  5696 E Auth    : 	at ejq.a(SourceFile:397)
06-06 13:18:16.922  5117  5696 E Auth    : 	at ejp.a(SourceFile:31369)
06-06 13:18:16.922  5117  5696 E Auth    : 	at ejp.a(SourceFile:313)
06-06 13:18:16.922  5117  5696 E Auth    : 	at fla.a(SourceFile:1201)
06-06 13:18:16.922  5117  5696 E Auth    : 	at fkz.a(SourceFile:530)
06-06 13:18:16.922  5117  5696 E Auth    : 	at fkz.a(SourceFile:196)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egp.a(SourceFile:284)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egp.a(SourceFile:204)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egu.a(SourceFile:1510)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egt.a(SourceFile:920)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egt.e(SourceFile:534)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egt.d(SourceFile:454)
06-06 13:18:16.922  5117  5696 E Auth    : 	at egr.b(SourceFile:568)
06-06 13:18:16.922  5117  5696 E Auth    : 	at jtq.a(SourceFile:82)
06-06 13:18:16.922  5117  5696 E Auth    : 	at jsg.a(SourceFile:57)
06-06 13:18:16.922  5117  5696 E Auth    : 	at bnq.a(SourceFile:6096)
06-06 13:18:16.922  5117  5696 E Auth    : 	at bjz.run(SourceFile:52)
06-06 13:18:16.922  5117  5696 E Auth    : 	at bjx.a(SourceFile:258)
06-06 13:18:16.922  5117  5696 E Auth    : 	at bjx.handleMessage(SourceFile:251)
06-06 13:18:16.922  5117  5696 E Auth    : 	at jxi.run(SourceFile:141)
06-06 13:18:16.922  5117  5696 E Auth    : 	at jxq.run(SourceFile:438)
06-06 13:18:16.922  5117  5696 E Auth    : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-06 13:18:16.922  5117  5696 E Auth    : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-06 13:18:16.922  5117  5696 E Auth    : 	at kca.run(SourceFile:17)
06-06 13:18:16.922  5117  5696 E Auth    : 	at java.lang.Thread.run(Thread.java:818)
,06-06 13:18:17.192  1277  1294 I art     : Explicit concurrent mark sweep GC freed 58411(3MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 57MB/86MB, paused 2.598ms total 210.756ms
,06-06 13:18:17.212  5117  5696 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,06-06 13:18:17.422  1277  3839 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:18:17.462  5117  5696 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:18:17.522  1277  4193 I ActivityManager: Start proc 11457:com.google.android.youtube/u0a124 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,06-06 13:18:17.562  5117  5696 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=UNKNOWN).  Giving up.
,06-06 13:18:17.572  5117 11128 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:17.572  5117 11128 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:18:17.572  5117 11128 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:17.572  5117 11128 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:18:17.572   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:18:17.572   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:18:17.572   477 11477 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:18:17.572   477 11477 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:18:17.572   477 11477 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:18:17.572   477 11477 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:18:17.572   477 11477 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:18:17.572  5117 11128 I System.out: propertyValue:false
,06-06 13:18:17.592  1277  4149 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:18:17.602 11457 11478 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-06 13:18:17.602 11457 11478 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-06 13:18:17.642 11457 11478 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x510
,06-06 13:18:17.642 11457 11478 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x8f
06-06 13:18:17.642 11457 11478 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x178
,06-06 13:18:17.642 11457 11478 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-06 13:18:17.682 11457 11478 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-06 13:18:17.702 11457 11483 D ChimeraCfgMgr: Reading stored module config
,06-06 13:18:17.722 11457 11483 D ChimeraFileApk: Primary ABI of requesting process is arm64-v8a
,06-06 13:18:17.722 11457 11483 D ChimeraFileApk: Classloading successful. Optimized code found.
,06-06 13:18:17.732 11457 11483 D DynamitePackage: Instantiated singleton DynamitePackage.
06-06 13:18:17.732 11457 11483 D DynamitePackage: Instantiating com.google.android.gms.ads.adshield.ChimeraAdShieldCreatorImpl
,06-06 13:18:17.772 11457 11457 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,06-06 13:18:17.782 11457 11457 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:17.782 11457 11457 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:18:17.812  1277  4128 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:18:17.942 11457 11457 I NotificationManager: com.google.android.youtube: cancel(2) by com.google.android.youtube
,06-06 13:18:17.952  1277  3751 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:18:17.972 11457 11457 W InstanceID/Rpc: Found 10006
,06-06 13:18:18.052  1277  3374 W ActivityManager: getRunningAppProcesses: caller 10124 does not hold REAL_GET_TASKS; limiting output
,06-06 13:18:18.092 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:18.092 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:18:18.092 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:18.092 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:18:18.102   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:18:18.102   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
06-06 13:18:18.102   477 11556 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:18:18.102   477 11556 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:18:18.102   477 11556 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:18:18.102   477 11556 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:18:18.102   477 11556 D libc-netbsd: res_queryN name = xxxxx succeed
06-06 13:18:18.102 11457 11552 I System.out: propertyValue:false
06-06 13:18:18.102 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:18.102 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:18:18.102  1277  4149 I ActivityManager: Killing 10809:com.google.android.play.games.ui/u0a114 (adj 15): empty #22
,06-06 13:18:18.322  5117  5696 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,06-06 13:18:30.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:18:30.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:18:30.952  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 300090288686; DSPS: 10000819; Offset : -5110485965
,06-06 13:18:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:18:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:18:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:18:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-06 13:18:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:18:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:18:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:18:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 289
06-06 13:18:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:18:32.942  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 293
,06-06 13:18:32.942  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:18:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:18:32.942  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:18:32.942  4025  4383 D LEDHandler: Battery Temp: 289, mChargingStatus=2, mChargingStop=false
,06-06 13:18:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:18:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,06-06 13:18:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:18:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:18:34.232  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b636739 type 2 when 303371 android} when 303371
,06-06 13:18:34.272  1277  1295 D LocationManagerService: getAllProviders()=[passive, gps, network]
,06-06 13:18:34.312  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:34.312  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:34.522  1277  4194 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:18:34.562  5117  5672 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:18:35.112   419   419 I rmt_storage: rmt_storage_connect_cb: clnt_h=0xa conn_h=0x7f86406060
06-06 13:18:35.112   419   419 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0xa: req_h=0xa msg_id=3: R/W request received
06-06 13:18:35.112   419   419 I rmt_storage: wakelock acquired: 1, error no: 42
,06-06 13:18:35.112   419  1197 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0xa Unblock worker thread (th_id: 547713671936)
,06-06 13:18:35.212   419  1197 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0xa: req_h=0xa msg_id=3: Bytes written = 1572864
06-06 13:18:35.212   419  1197 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0xa: req_h=0xa msg_id=3: Send response: res=0 err=0
06-06 13:18:35.212   419  1197 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0xa About to block rmt_storage client thread (th_id: 547713671936) wakelock released: 1, error no: 22
06-06 13:18:35.212   419  1197 I rmt_storage: 
,06-06 13:18:35.212   419   419 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0xa conn_h=0x7f86406060
,06-06 13:18:43.402  1277  3657 D Wiper_jni: wifiRequestEventCb invoked
,06-06 13:18:43.402  1277  4671 D LBSSystemMonitorService: handleMessage what - 2
06-06 13:18:43.402  1277  4671 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-06 13:18:43.402  1277  4671 E Wiper   : LocationManager.NETWORK_PROVIDER not enabled
,06-06 13:18:50.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:18:50.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:18:50.952  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 320092290658; DSPS: 10656245; Offset : -5110497866
,06-06 13:18:57.572  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:57.582  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:57.592  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:18:57.622  1277  1295 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:18:57.642  4990  5347 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:57.642  4990  5347 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:18:57.642  4990  5347 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:57.642  4990  5347 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:18:57.642   477  1248 E BandwidthController: [LG DATA] No such appUid: 10062
06-06 13:18:57.642   477  1248 D DnsProxyListener: App 10062 tries DNS query. Accept family:0 protocol:0
06-06 13:18:57.642   477 11568 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:18:57.642   477 11568 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:18:57.642   477 11568 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:18:57.642   477 11568 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:18:57.642   477 11568 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:18:57.642  4990  5347 I System.out: propertyValue:false
,06-06 13:18:57.742  4990  5347 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:18:57.742  4990  5347 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:19:00.032  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59988
,06-06 13:19:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:19:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:19:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:19:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:19:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:19:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:19:05.232  1277  6470 I LocationManagerService: remove 3b97cbf4
,06-06 13:19:05.242  1277  6470 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-06 13:19:05.242  1277  6470 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-06 13:19:05.242  1277  6470 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-06 13:19:05.242  1277  6470 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-06 13:19:05.242  1277  6470 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-06 13:19:10.122  1277  3175 D PowerManagerServiceEx: acquireWakeLockInternal: lock=409116303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1277
,06-06 13:19:10.122  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1787abe1 type 2 when 337302 android} when 337302
,06-06 13:19:10.152  5199  5199 D [Concierge][ConciergeService]: onStartCommand(). Type : 11
,06-06 13:19:10.162  1277  1277 D PowerManagerServiceEx: releaseWakeLockInternal: lock=409116303 [*alarm*], flags=0x0
,06-06 13:19:10.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:19:10.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:19:10.952  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 340094312734; DSPS: 11311671; Offset : -5110489846
,06-06 13:19:14.332  1277  3657 D GpsLocationProvider: reportStatus status: 4
,06-06 13:19:14.342  1277  1277 D LgeGpsIndicator: Recieve Intent: android.location.GPS_ENABLED_CHANGE, false
06-06 13:19:14.342  1277  3657 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1439 com.android.server.location.LgeGpsLocationProvider.reportStatus:544 <bottom of call stack> <bottom of call stack> <bottom of call stack> 
06-06 13:19:14.342  1277  1277 D LgeGpsIndicator: STATE_DONE
06-06 13:19:14.342  1277  1277 I LgeGpsLocationProvider: Intent - android.location.GPS_ENABLED_CHANGE
06-06 13:19:14.342  1277  1277 D LgeGpsLocationProvider: GPS_ENABLED_CHANGE_ACTION! , mNavigating =false
06-06 13:19:14.342  1277  3657 D LgeGpsLocationProvider: reportStatus, [LGE] GPS_ENGINE_STATUS_CHANGE false
,06-06 13:19:16.022  7068  7157 D LIA_SmartMoment_CTP_StepCounterDetected: currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
,06-06 13:19:30.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:19:30.952  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:19:30.952  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 360096917986; DSPS: 11967117; Offset : -5110509002
,06-06 13:19:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:19:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:19:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:19:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:19:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:19:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:19:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
,06-06 13:19:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:19:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:19:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:19:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:19:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 285
06-06 13:19:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:19:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:19:32.952  4025  4383 D LEDHandler: Battery Temp: 285, mChargingStatus=2, mChargingStop=false
06-06 13:19:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:19:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 288
06-06 13:19:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:19:33.712   589   589 I MSM-irqbalance: Decided to move IRQ170 from CPU2 to CPU3
,06-06 13:19:50.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:19:50.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:19:50.962  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 380099649437; DSPS: 12622566; Offset : -5110493589
,06-06 13:20:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59984
06-06 13:20:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:20:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:20:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:20:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:20:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:20:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:20:10.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:20:10.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:20:10.962  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 400102495471; DSPS: 13278019; Offset : -5110485613
,06-06 13:20:30.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:20:30.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:20:30.962  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 420105116036; DSPS: 13933465; Offset : -5110490053
,06-06 13:20:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:20:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:20:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:20:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:20:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-06 13:20:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:20:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:20:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 282
06-06 13:20:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:20:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:20:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:20:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 285
,06-06 13:20:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:20:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:20:32.952  4025  4383 D LEDHandler: Battery Temp: 282, mChargingStatus=2, mChargingStop=false
,06-06 13:20:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:20:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:20:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:20:34.592  7556  8615 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-06 13:20:50.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:20:50.962  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:20:50.962  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 440107752279; DSPS: 14588912; Offset : -5110508762
,06-06 13:21:00.032  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59990
06-06 13:21:00.032  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:21:00.032  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:21:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:21:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:21:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:21:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:21:10.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:21:10.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:21:10.972  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 460110516334; DSPS: 15244362; Offset : -5110491367
,06-06 13:21:30.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:21:30.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:21:30.972  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 480112858201; DSPS: 15899799; Offset : -5110499145
,06-06 13:21:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:21:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-06 13:21:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:21:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:21:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:21:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:21:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:21:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 282
06-06 13:21:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:21:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:21:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 285
06-06 13:21:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:21:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-06 13:21:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:21:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:21:32.952  4025  4383 D LEDHandler: Battery Temp: 282, mChargingStatus=2, mChargingStop=false
,06-06 13:21:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:21:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:21:50.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:21:50.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:21:50.972  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 500115620537; DSPS: 16555250; Offset : -5110513987
,06-06 13:22:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59982
06-06 13:22:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:22:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:22:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:22:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:22:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:22:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:22:10.642  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:22:10.662  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:22:10.672  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:22:10.952  1277  1295 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:22:10.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:22:10.972  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:22:10.972  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 520117864696; DSPS: 17210683; Offset : -5110497559
,06-06 13:22:10.992  5117  5136 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-06 13:22:11.002  1277  3751 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:22:11.032  7556 10888 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:22:11.032  7556 10888 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:22:11.032  7556 10888 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:22:11.032  7556 10888 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:22:11.032   477  1248 E BandwidthController: [LG DATA] No such appUid: 10006
06-06 13:22:11.032   477  1248 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-06 13:22:11.032   477 11603 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:22:11.032   477 11603 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:22:11.032   477 11603 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:22:11.032   477 11603 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:22:11.122   477 11603 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:22:11.122  7556 10888 I System.out: propertyValue:false
,06-06 13:22:11.252  7556 10888 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:22:11.252  7556 10888 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:22:30.982  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:22:30.982  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:22:30.982  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 540120486564; DSPS: 17866129; Offset : -5110499917
,06-06 13:22:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:22:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:22:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:22:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:22:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:22:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:22:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:22:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:22:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:22:32.952  4025  4383 D LEDHandler: Battery Temp: 279, mChargingStatus=2, mChargingStop=false
06-06 13:22:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:22:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 279
,06-06 13:22:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:22:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 281
,06-06 13:22:32.962  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-06 13:22:32.962  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:22:32.962  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:22:32.972  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:22:50.982  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:22:50.982  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:22:50.982  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 560123159264; DSPS: 18521577; Offset : -5110512893
,06-06 13:22:59.992  1277  3175 D PowerManagerServiceEx: acquireWakeLockInternal: lock=409116303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1277
,06-06 13:23:00.032  5199  5199 D [Concierge][ConciergeService]: onStartCommand(). Type : 11
,06-06 13:23:00.032  1277  1277 D PowerManagerServiceEx: releaseWakeLockInternal: lock=409116303 [*alarm*], flags=0x0
,06-06 13:23:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59986
06-06 13:23:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:23:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:23:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:23:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:23:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:23:00.042  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:23:10.982  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:23:10.982  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:23:10.982  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 580126132694; DSPS: 19177034; Offset : -5110499929
,06-06 13:23:18.252 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:18.252 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:18.252 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:18.252 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:23:18.252   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:23:18.252   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
,06-06 13:23:18.252   477 11612 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:23:18.252   477 11612 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:23:18.252   477 11612 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:23:18.252   477 11612 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:23:18.342   477 11612 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:23:18.342 11457 11552 I System.out: propertyValue:false
06-06 13:23:18.342 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:18.342 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:18.772 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:18.772 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:18.772 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:18.772 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:19.072 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:19.082 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:19.082 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:19.082 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:19.432 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:19.432 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:19.432 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:19.432 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:19.762 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:19.762 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:19.762 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:19.762 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:20.142 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:20.142 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:20.142 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:20.142 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:20.452 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:20.452 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:23:20.452 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:20.452 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:23:20.452   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:23:20.452   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
06-06 13:23:20.452   477 11619 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:23:20.452   477 11619 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:23:20.452   477 11619 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:23:20.452   477 11619 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:23:20.452   477 11619 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:23:20.452 11457 11552 I System.out: propertyValue:false
,06-06 13:23:20.452 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:20.462 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:20.792 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:20.792 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:20.792 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:20.792 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:21.202 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:21.202 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:21.212 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:21.212 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:21.502 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:21.502 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:21.502 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:21.502 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:21.762 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:21.762 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:21.772 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:21.772 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:22.042 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:22.052 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:22.052 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:22.052 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:22.402 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:22.402 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:22.402 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:22.402 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:22.782 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:23:22.782 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:22.782 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:22.782 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:23:22.782   477  1248 E BandwidthController: [LG DATA] No such appUid: 10124
06-06 13:23:22.782   477  1248 D DnsProxyListener: App 10124 tries DNS query. Accept family:0 protocol:0
,06-06 13:23:22.782   477 11628 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:23:22.782   477 11628 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-06 13:23:22.782   477 11628 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,06-06 13:23:22.782   477 11628 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-06 13:23:22.782   477 11628 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:23:22.792 11457 11552 I System.out: propertyValue:false
,06-06 13:23:22.792 11457 11552 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:23:22.792 11457 11552 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:23:30.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:23:30.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:23:30.992  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 600128503832; DSPS: 19832472; Offset : -5110509292
,06-06 13:23:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:23:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:23:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:23:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:23:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:23:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:23:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:23:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:23:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:23:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:23:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:23:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:23:32.952  4025  4383 D LEDHandler: Battery Temp: 278, mChargingStatus=2, mChargingStop=false
06-06 13:23:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 278
06-06 13:23:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:23:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:23:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 280
,06-06 13:23:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:23:50.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:23:50.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:23:50.992  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 620131716116; DSPS: 20487937; Offset : -5110501537
,06-06 13:24:00.032  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59991
,06-06 13:24:00.032  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:24:00.032  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:24:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:24:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:24:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:24:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:24:10.942  5117  6180 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-06 13:24:10.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:24:10.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:24:10.992  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 640134749755; DSPS: 21143396; Offset : -5110489085
,06-06 13:24:16.022  7068  7157 D LIA_SmartMoment_CTP_StepCounterDetected: currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
,06-06 13:24:30.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:24:30.992  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:24:30.992  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 660137514070; DSPS: 21798847; Offset : -5110501114
,06-06 13:24:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:24:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:24:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:24:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:24:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:24:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:24:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:24:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 276
06-06 13:24:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:24:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 277
,06-06 13:24:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:24:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:24:32.952  4025  4383 D LEDHandler: Battery Temp: 276, mChargingStatus=2, mChargingStop=false
,06-06 13:24:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:24:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:24:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:24:32.962  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,06-06 13:24:32.962  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:24:51.002  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:24:51.002  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:24:51.002  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 680140359843; DSPS: 22454300; Offset : -5110493685
,06-06 13:25:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59982
,06-06 13:25:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:25:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:25:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:25:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:25:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:25:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:25:11.002  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:25:11.002  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:25:11.002  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 700143670357; DSPS: 23109768; Offset : -5110479199
,06-06 13:25:31.002  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:25:31.002  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:25:31.002  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 720146362380; DSPS: 23765217; Offset : -5110503398
,06-06 13:25:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:25:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:25:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-06 13:25:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:25:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:25:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:25:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:25:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 276
06-06 13:25:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:25:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:25:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:25:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:25:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:25:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 277
06-06 13:25:32.952  4025  4383 D LEDHandler: Battery Temp: 276, mChargingStatus=2, mChargingStop=false
,06-06 13:25:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:25:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:25:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:25:51.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:25:51.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:25:51.012  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 740148787477; DSPS: 24420656; Offset : -5110489318
,06-06 13:26:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59982
,06-06 13:26:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:26:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:26:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:26:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:26:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:26:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:26:11.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:26:11.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:26:11.012  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 760152227157; DSPS: 25076129; Offset : -5110497683
,06-06 13:26:31.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:26:31.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:26:31.012  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 780155871732; DSPS: 25731609; Offset : -5110515269
,06-06 13:26:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:26:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:26:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:26:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:26:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:26:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:26:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
,06-06 13:26:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 274
06-06 13:26:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:26:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 275
,06-06 13:26:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:26:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:26:32.952  4025  4383 D LEDHandler: Battery Temp: 274, mChargingStatus=2, mChargingStop=false
,06-06 13:26:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:26:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:26:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:26:32.962  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
06-06 13:26:32.962  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:26:51.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:26:51.012  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:26:51.012  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 800158095058; DSPS: 26387041; Offset : -5110489574
,06-06 13:27:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59981
06-06 13:27:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:27:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:27:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:27:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:27:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:27:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:27:11.022  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:27:11.022  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:27:11.022  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 820160964061; DSPS: 27042495; Offset : -5110488832
,06-06 13:27:31.022  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:27:31.022  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:27:31.022  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 840163620668; DSPS: 27697942; Offset : -5110487775
,06-06 13:27:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:27:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:27:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:27:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:27:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:27:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:27:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:27:51.022  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:27:51.022  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:27:51.022  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 860165812379; DSPS: 28353374; Offset : -5110493069
,06-06 13:28:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59984
06-06 13:28:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:28:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:28:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:28:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:28:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:28:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:28:11.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:28:11.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:28:11.032  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 880168827319; DSPS: 29008833; Offset : -5110499214
,06-06 13:28:31.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:28:31.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:28:31.032  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 900171559135; DSPS: 29664283; Offset : -5110513771
,06-06 13:28:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:28:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:28:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-06 13:28:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:28:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:28:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:28:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:28:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 272
06-06 13:28:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:28:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 272
,06-06 13:28:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:28:32.962  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:28:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-06 13:28:32.962  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:28:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:28:32.962  4025  4383 D LEDHandler: Battery Temp: 272, mChargingStatus=2, mChargingStop=false
06-06 13:28:32.962  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:28:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:28:51.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:28:51.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:28:51.032  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 920173774804; DSPS: 30319715; Offset : -5110495473
,06-06 13:29:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59983
,06-06 13:29:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:29:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:29:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:29:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:29:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:29:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:29:11.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:29:11.032  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:29:11.032  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 940176320213; DSPS: 30975158; Offset : -5110483543
,06-06 13:29:16.022  7068  7157 D LIA_SmartMoment_CTP_StepCounterDetected: currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
,06-06 13:29:31.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:29:31.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:29:31.042  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 960179018122; DSPS: 31630607; Offset : -5110501828
,06-06 13:29:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:29:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:29:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:29:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:29:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:29:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
06-06 13:29:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
,06-06 13:29:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 272
06-06 13:29:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:29:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 272
,06-06 13:29:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-06 13:29:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:29:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:29:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
,06-06 13:29:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:29:32.952  4025  4383 D LEDHandler: Battery Temp: 272, mChargingStatus=2, mChargingStop=false
06-06 13:29:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:29:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED,
,06-06 13:29:51.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:29:51.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:29:51.042  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 980182362073; DSPS: 32286076; Offset : -5110484085
,06-06 13:30:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59982
06-06 13:30:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:30:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:30:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:30:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:30:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:30:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:30:11.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:30:11.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:30:11.042  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1000185005711; DSPS: 32941523; Offset : -5110495294
,06-06 13:30:31.042  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:30:31.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:30:31.052  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1020187893151; DSPS: 33596978; Offset : -5110506424
,06-06 13:30:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:30:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:30:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:30:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:30:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:30:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:30:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:30:51.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:30:51.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:30:51.052  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1040190821321; DSPS: 34252434; Offset : -5110508229
,06-06 13:31:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59985
,06-06 13:31:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:31:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:31:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:31:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:31:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:31:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:31:11.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:31:11.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:31:11.052  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1060193070219; DSPS: 34907867; Offset : -5110487765
,06-06 13:31:31.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:31:31.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:31:31.052  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1080195792660; DSPS: 35563316; Offset : -5110480764
,06-06 13:31:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:31:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:31:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:31:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:31:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-06 13:31:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:31:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:31:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 270
06-06 13:31:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
06-06 13:31:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:31:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 270
06-06 13:31:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:31:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:31:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:31:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:31:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:31:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:31:32.952  4025  4383 D LEDHandler: Battery Temp: 270, mChargingStatus=2, mChargingStop=false
,06-06 13:31:51.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:31:51.052  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:31:51.052  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1100198074996; DSPS: 36218751; Offset : -5110487637
,06-06 13:31:58.682  1277  3175 D PowerManagerServiceEx: acquireWakeLockInternal: lock=409116303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1277
,06-06 13:31:58.682  1277  3175 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b794c78 type 2 when 1107821 com.android.bluetooth} when 1107821
,06-06 13:31:58.702  4464  9813 W bt-smp  : Key(LSB ~ MSB) = e8 a9 6d f5 8a 0a a8 5d ae 6a 38 6f 56 7c 5c 21 
06-06 13:31:58.702  4464  9813 W bt-smp  : Plain text(LSB ~ MSB) = e9 1e 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-06 13:31:58.702  4464  9813 W bt-smp  : Encrypted text(LSB ~ MSB) = 48 9b 0c b3 48 59 1b 9e 17 80 61 34 b3 39 4f 32 
06-06 13:31:58.702  4464  9813 W bt-btm  : Stopping oneshot timer
,06-06 13:31:58.762  1277  3751 I ActivityManager: Start proc 11703:com.lge.clock/u0a16 for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider
,06-06 13:31:58.772  5199  5199 D [Concierge][ConciergeService]: onStartCommand(). Type : 11
,06-06 13:31:58.812 11703 11703 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-06 13:31:58.812 11703 11703 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@e03d395
,06-06 13:31:58.822  1277  4128 I ActivityManager: Killing 11034:com.google.android.configupdater/u0a64 (adj 15): empty #22
06-06 13:31:58.822  1277  1277 D PowerManagerServiceEx: releaseWakeLockInternal: lock=409116303 [*alarm*], flags=0x0
,06-06 13:31:59.322   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:31:59.322   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:31:59.322   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:31:59.332   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:31:59.332  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:31:59.332  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:31:59.332  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:31:59.332  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:31:59.332  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:32:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59979
06-06 13:32:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:32:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:32:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:32:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:32:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated(),
,06-06 13:32:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:32:11.062  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:32:11.062  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:32:11.062  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1120200325509; DSPS: 36874185; Offset : -5110495424
,06-06 13:32:31.062  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:32:31.062  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:32:31.062  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1140202918366; DSPS: 37529630; Offset : -5110496588
,06-06 13:32:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:32:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:32:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:32:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:32:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
06-06 13:32:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
,06-06 13:32:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:32:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 270
06-06 13:32:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:32:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 270
,06-06 13:32:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:32:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:32:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:32:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:32:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:32:32.952  4025  4383 D LEDHandler: Battery Temp: 270, mChargingStatus=2, mChargingStop=false
06-06 13:32:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:32:32.962  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:32:51.062  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:32:51.062  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:32:51.062  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1160205649139; DSPS: 38185080; Offset : -5110512762
,06-06 13:33:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59987
06-06 13:33:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:33:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:33:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
06-06 13:33:00.042  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:33:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:33:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate,
,06-06 13:33:11.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:33:11.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:33:11.072  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1180208647101; DSPS: 38840538; Offset : -5110504871
,06-06 13:33:31.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:33:31.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:33:31.072  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1200211317145; DSPS: 39495985; Offset : -5110490091
,06-06 13:33:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:33:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:33:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:33:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:33:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:33:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:33:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:33:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 270
,06-06 13:33:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:33:32.942  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 270
06-06 13:33:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:33:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:33:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:33:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:33:32.952  4025  4383 D LEDHandler: Battery Temp: 270, mChargingStatus=2, mChargingStop=false
06-06 13:33:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:33:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:33:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:33:37.282  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 270
06-06 13:33:37.282  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:33:37.282  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:33:37.282  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:33:37.282  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 270
06-06 13:33:37.282  4025  4383 D LEDHandler: Battery Temp: 270, mChargingStatus=2, mChargingStop=false
,06-06 13:33:37.282  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,06-06 13:33:37.282  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:33:37.282  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:33:37.292  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:33:37.292  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:33:49.132  1277  1314 I UsageStatsService: User[0] Flushing usage stats to disk
,06-06 13:33:51.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:33:51.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:33:51.072  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1220213961356; DSPS: 40151432; Offset : -5110500648
,06-06 13:33:58.232  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:33:58.252  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:33:58.262  5117  5117 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-06 13:33:58.292  1277  4193 I NotificationManager: android: cancelAsUser(2) by android
,06-06 13:33:58.292  4990  5347 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:33:58.292  4990  5347 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-06 13:33:58.292  4990  5347 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-06 13:33:58.292  4990  5347 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:33:58.302   477  1248 E BandwidthController: [LG DATA] No such appUid: 10062
06-06 13:33:58.302   477  1248 D DnsProxyListener: App 10062 tries DNS query. Accept family:0 protocol:0
06-06 13:33:58.302   477 11741 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-06 13:33:58.302   477 11741 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-06 13:33:58.302   477 11741 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-06 13:33:58.302   477 11741 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,06-06 13:33:58.392   477 11741 D libc-netbsd: res_queryN name = xxxxx succeed
,06-06 13:33:58.392  4990  5347 I System.out: propertyValue:false
,06-06 13:33:58.472  4990  5347 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-06 13:33:58.472  4990  5347 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-06 13:34:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59985
06-06 13:34:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:34:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:34:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:34:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:34:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:34:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:34:11.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:34:11.072  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:34:11.072  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1240216525671; DSPS: 40806876; Offset : -5110499837
,06-06 13:34:16.022  7068  7157 D LIA_SmartMoment_CTP_StepCounterDetected: currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
,06-06 13:34:31.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:34:31.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:34:31.082  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1260219289987; DSPS: 41462326; Offset : -5110482285
,06-06 13:34:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:34:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:34:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:34:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-06 13:34:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-06 13:34:32.952  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,06-06 13:34:32.952  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
06-06 13:34:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 270
,06-06 13:34:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:34:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:34:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 270
06-06 13:34:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:34:32.952  4025  4383 D LEDHandler: Battery Temp: 270, mChargingStatus=2, mChargingStop=false
06-06 13:34:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,06-06 13:34:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:34:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:34:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:34:32.962  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:34:51.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:34:51.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:34:51.082  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1280222134406; DSPS: 42117780; Offset : -5110506101
,06-06 13:35:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59983
06-06 13:35:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:35:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:35:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:35:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:35:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:35:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:35:11.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:35:11.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:35:11.082  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1300225231482; DSPS: 42773241; Offset : -5110491847
,06-06 13:35:31.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:35:31.082  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:35:31.082  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1320227926474; DSPS: 43428690; Offset : -5110512998
,06-06 13:35:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:35:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:35:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:35:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:35:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:35:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:35:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:35:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 270
06-06 13:35:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:35:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:35:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:35:32.952  4025  4383 D LEDHandler: Battery Temp: 270, mChargingStatus=2, mChargingStop=false
,06-06 13:35:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 270
06-06 13:35:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:35:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:35:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-06 13:35:32.962  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:35:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:35:51.092  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:35:51.092  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:35:51.092  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1340231023290; DSPS: 44084151; Offset : -5110498614
,06-06 13:36:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59982
06-06 13:36:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:36:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:36:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:36:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:36:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:36:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:36:11.092  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:36:11.092  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:36:11.092  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1360235020157; DSPS: 44739642; Offset : -5110498924
,06-06 13:36:31.092  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:36:31.092  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:36:31.092  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1380237614576; DSPS: 45395087; Offset : -5110498837
,06-06 13:36:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:36:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:36:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:36:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:36:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:36:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:36:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:36:32.952  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:36:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:36:32.952  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
06-06 13:36:32.952  4025  4383 D LEDHandler: Battery Temp: 267, mChargingStatus=2, mChargingStop=false
,06-06 13:36:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 267
06-06 13:36:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,06-06 13:36:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:36:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:36:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:36:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 267
,06-06 13:36:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:36:51.102  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:36:51.102  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:36:51.102  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1400240256652; DSPS: 46050534; Offset : -5110511583
,06-06 13:37:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59983
06-06 13:37:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:37:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:37:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:37:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:37:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:37:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:37:11.102  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:37:11.102  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:37:11.102  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1420243044405; DSPS: 46705985; Offset : -5110501112
,06-06 13:37:31.102  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:37:31.102  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:37:31.102  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1440246337001; DSPS: 47361453; Offset : -5110504180
,06-06 13:37:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:37:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:37:32.942   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:37:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:37:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:37:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:37:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:37:32.952  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 267
06-06 13:37:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:37:32.952  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:37:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
,06-06 13:37:32.952  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 267
06-06 13:37:32.952  4025  4383 D LEDHandler: Battery Temp: 267, mChargingStatus=2, mChargingStop=false
06-06 13:37:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:37:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction,
06-06 13:37:32.962  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:37:32.962  1277  3193 D WifiController: battery changed pluggedType: 2
,06-06 13:37:32.962  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:37:51.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:37:51.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:37:51.112  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1460248592827; DSPS: 48016887; Offset : -5110506603
,06-06 13:38:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59985
,06-06 13:38:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:38:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:38:00.042  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:38:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:38:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:38:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:38:11.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:38:11.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:38:11.112  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1480251247194; DSPS: 48672334; Offset : -5110507161
,06-06 13:38:31.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:38:31.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:38:31.112  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1500254277760; DSPS: 49327793; Offset : -5110497913
,06-06 13:38:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:38:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:38:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
06-06 13:38:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:38:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:38:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:38:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:38:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 267
06-06 13:38:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-06 13:38:32.942  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 267
,06-06 13:38:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-06 13:38:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%,
,06-06 13:38:32.952  4025  4383 D LEDHandler: Battery Temp: 267, mChargingStatus=2, mChargingStop=false
06-06 13:38:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:38:32.952  1277  3193 D WifiController: battery changed pluggedType: 2,
06-06 13:38:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
06-06 13:38:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-06 13:38:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:38:51.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:38:51.112  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:38:51.112  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1520256993429; DSPS: 49983242; Offset : -5110498985
,06-06 13:39:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59982
,06-06 13:39:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:39:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:39:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:39:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:39:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:39:00.062  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:39:11.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:39:11.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:39:11.122  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1540259578161; DSPS: 50638687; Offset : -5110507883
,06-06 13:39:16.022  7068  7157 D LIA_SmartMoment_CTP_StepCounterDetected: currentStep : 0.0 - standardStep : 0.0 = storedStep: 0.0
,06-06 13:39:31.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:39:31.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:39:31.122  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1560262405654; DSPS: 51294139; Offset : -5110488294
,06-06 13:39:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:39:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:39:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
,06-06 13:39:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:39:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:39:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:39:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-06 13:39:51.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:39:51.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:39:51.122  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1580265225021; DSPS: 51949592; Offset : -5110507009
,06-06 13:40:00.042  3340  3340 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged() nextTick: 59980
06-06 13:40:00.042  3340  3340 I KeyguardUpdateMonitor: called onTimeUpdated()
06-06 13:40:00.042  3340  3340 I [SystemUI]Clock: called onTimeUpdated()
,06-06 13:40:00.052  3340  3340 I LgeClockWidgetControlView: called onTimeUpdated()
,06-06 13:40:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:40:00.052  3340  3340 I [SystemUI]DateView: called onTimeUpdated()
,06-06 13:40:00.052  3340  3340 D KeyguardUpdateMonitor: handleTimeUpdate
,06-06 13:40:11.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:40:11.122  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:40:11.132  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1600267884128; DSPS: 52605039; Offset : -5110502490
,06-06 13:40:31.132  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-06 13:40:31.132  1277  1302 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-06 13:40:31.132  1277  1302 D sensors_hal_Time: tsOffsetIs: Apps: 1620270516829; DSPS: 53260485; Offset : -5110494612
,06-06 13:40:32.932   415   471 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
,06-06 13:40:32.932   477  1245 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'ALERT_NAME' not found
06-06 13:40:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-06 13:40:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-06 13:40:32.942  3340  3340 I [SystemUI]LGPowerUI: levelEx = 80, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-06 13:40:32.942  3340  3340 I [SystemUI]LGPowerUI: On Skip Timer : true
06-06 13:40:32.942  4025  4025 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: true, isFastChargerConnected: false
,06-06 13:40:32.942  3340  3340 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 80 ,temperature : 265
06-06 13:40:32.942  3340  3340 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:40:32.942  3340  3340 I [SystemUI]LGPowerUI: level = 80, plugType = 2, plugged = true, mCharging = true, temperature = 265
,06-06 13:40:32.952  4025  4383 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
,06-06 13:40:32.952  4025  4383 D LEDHandler: Battery Level Remaining: 80%
06-06 13:40:32.952  4025  4383 D LEDHandler: Battery Temp: 265, mChargingStatus=2, mChargingStop=false
,06-06 13:40:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,06-06 13:40:32.952  6383  6383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-06 13:40:32.952  4464  9725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-06 13:40:32.952  3340  3340 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-06 13:40:32.952  1277  3193 D WifiController: battery changed pluggedType: 2
,TIME-OUT KILL (timeout was 1400000ms)
```
