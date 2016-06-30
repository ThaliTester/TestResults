#### Test 757892682551a10_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
06-30 13:52:41.505  1849  2675 E NxpNfcJni: getReconnectState = 0x0
,06-30 13:52:45.208  6592  6592 D AndroidRuntime: 
06-30 13:52:45.208  6592  6592 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:52:45.213  6592  6592 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:45.329   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
06-30 13:52:45.466  1372  1372 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
--------- beginning of system
06-30 13:52:45.473   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{290b0ebd type 2 when 158849 com.android.systemui} when 158849
06-30 13:52:45.486  1779  1797 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-30 13:52:45.491  1779  1797 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 13:52:45.491  1779  1797 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 13:52:45.496  1779  1797 V TelecomServiceImpl: getCallState : 0
06-30 13:52:45.509  1779  1798 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-30 13:52:45.509  1779  1798 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 13:52:45.509  1779  1798 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 13:52:45.511  1372  1372 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
06-30 13:52:45.512  1372  1372 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
06-30 13:52:45.589  6592  6592 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:52:45.606   848  1899 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:52:45.638   848  1899 D ActivityManager: setTaskToReturnTo : TaskRecord{3b610cb2 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 13:52:45.638   848  1899 D ActivityManager: setTaskToReturnTo : TaskRecord{3b610cb2 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 13:52:45.655   848  1899 D WindowStateEx: AppWindowTokenEx init.. 
06-30 13:52:45.700   848  1899 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6612 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:52:45.701   848  1899 D InputDispatcher: Focus left window: Window{21d10fb5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-30 13:52:45.704  6592  6592 D AndroidRuntime: Shutting down VM
06-30 13:52:45.712   848  1288 V AlarmManager: RTC_WAKEUP set : Alarm{214ead5f type 0 when 1467287565627 com.google.android.googlequicksearchbox} when 1467287565627
06-30 13:52:45.713  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
06-30 13:52:45.743   848   848 V ActivityManager: Display changed displayId=0
06-30 13:52:45.746  1779  1779 D DSDPConnection: Display #0 changed.
06-30 13:52:45.867  6612  6612 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,06-30 13:52:45.966  6612  6612 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-30 13:52:46.011  6612  6612 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9406-9408)
06-30 13:52:46.012  6612  6612 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:46.043  6612  6612 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b145a99}
06-30 13:52:46.045  6612  6612 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:46.052  6612  6612 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:46.069  6612  6612 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:46.070  6612  6612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:46.074  6612  6612 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:46.137  6612  6612 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 13:52:46.146  6612  6612 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:46.146  6612  6612 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:46.147  6612  6612 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:52:46.147  6612  6612 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:52:46.147  6612  6612 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 13:52:46.147  6612  6612 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 13:52:46.147  6612  6612 I Adreno-EGL: Remote Branch: 
06-30 13:52:46.147  6612  6612 I Adreno-EGL: Local Patches: 
06-30 13:52:46.147  6612  6612 I Adreno-EGL: Reconstruct Branch: 
06-30 13:52:46.214   273  1302 V AudioPolicyService: registerClient() client 0xb40278c0, uid 10030
06-30 13:52:46.224   848  1051 D BluetoothManagerService: Message: 20
06-30 13:52:46.224   848  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c480c44:true
06-30 13:52:46.243  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:52:46.266   848   899 W ActivityManager: Activity pause timeout for ActivityRecord{1ddcd403 u0 com.test.thalitest/.MainActivity t241}
06-30 13:52:46.349  6612  6612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:46.361  6612  6612 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 13:52:46.369  6612  6612 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 13:52:46.373  6612  6612 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 13:52:46.373  6612  6612 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 13:52:46.390  6612  6612 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-30 13:52:46.398  6612  6612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:46.398  6612  6612 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:46.457  6612  6612 I Activity: Activity.onPostResume() called 
06-30 13:52:46.465  6612  6676 D OpenGLRenderer: Render dirty regions requested: true
06-30 13:52:46.465  6612  6676 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:52:46.473  6612  6676 D OpenGLRenderer: Enabling debug mode 0
06-30 13:52:46.488  6612  6612 D Atlas   : Validating map...
06-30 13:52:46.493   848  1915 D SplitWindow: check instance of lgWin Window{34690e74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:52:46.510  6612  6663 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-30 13:52:46.533   848  1050 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
06-30 13:52:46.535   848  1050 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
06-30 13:52:46.536  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
06-30 13:52:46.536  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
06-30 13:52:46.536  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
06-30 13:52:46.536  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-30 13:52:46.538   848  1050 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-30 13:52:46.538   848  1050 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-30 13:52:46.538   848  1050 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:52:46.538   848  1050 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c84db14,  pkg=WindowManager.LayoutParams
06-30 13:52:46.538   848  1050 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-30 13:52:46.550   848  2176 D InputDispatcher: Focus entered window: Window{34690e74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:52:46.582   848  1053 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +816ms (total +923ms)
06-30 13:52:46.582   848  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ddcd403 u0 com.test.thalitest/.MainActivity t241} time:159978
06-30 13:52:46.583   848  2148 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-30 13:52:46.601  6612  6612 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-30 13:52:46.601  6612  6612 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@171704b time:159997
06-30 13:52:46.643  6612  6612 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
06-30 13:52:46.653  1627  1627 E b       : Unable to connect to the editor to retrieve text... will retry later
06-30 13:52:46.681  6612  6612 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
06-30 13:52:46.711  6612  6612 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6612
06-30 13:52:46.853  6612  6612 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 13:52:47.179  6612  6678 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635606784
06-30 13:52:47.198  6612  6678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:47.198  6612  6678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:47.198  6612  6678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:47.198  6612  6678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:47.198  6612  6678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:47.198  6612  6678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c62531f added. We now have 1 listener(s)
06-30 13:52:47.202   848  2176 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:52:47.207  6612  6678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
06-30 13:52:47.210  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
06-30 13:52:47.211  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:47.212  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:47.219  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b6b0ca added. We now have 1 listener(s)
06-30 13:52:47.220  6612  6678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:52:47.229  2061  2080 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:52:47.230  6612  6678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 13:52:47.236  6612  6678 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-30 13:52:47.236  6612  6678 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
06-30 13:52:47.240  6612  6678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:52:47.240   848  1379 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:52:47.242  6612  6678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
06-30 13:52:47.249  2061  3455 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:52:47.249  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:52:47.249  6612  6678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:47.250  6612  6678 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:47.251  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:52:47.253  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:52:47.253  6612  6678 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:52:47.283  6612  6612 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:47.405  6612  6627 I art     : CheckpointMarkThreadRoots callback created = 0x9e966950
,06-30 13:52:47.451  6612  6627 I art     : CheckpointMarkThreadRoots callback created = 0xaaeaa180
,06-30 13:52:48.117  6612  6684 W jxcore-log: Initializing JXcore engine
,06-30 13:52:48.120  6612  6684 W jxcore-log: JXcore engine is ready
06-30 13:52:48.277  6684  6684 W Thread-779: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7288]" dev="sockfs" ino=7288 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 13:52:48.277  6684  6684 W Thread-779: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 13:52:48.277  6684  6684 W Thread-779: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5626]" dev="sockfs" ino=5626 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-30 13:52:48.277  6684  6684 W Thread-779: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,06-30 13:52:48.277  6684  6684 W Thread-779: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-30 13:52:48.277  6684  6684 W Thread-779: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32782]" dev="sockfs" ino=32782 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 13:52:48.312  6612  6684 W jxcore-log: Starting JXcore engine
,06-30 13:52:48.480  6612  6684 W jxcore-log: Platform android
06-30 13:52:48.480  6612  6684 W jxcore-log: 
06-30 13:52:48.480  6612  6684 W jxcore-log: Process ARCH arm
06-30 13:52:48.480  6612  6684 W jxcore-log: 
,06-30 13:52:48.798  6612  6684 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:48.798  6612  6684 I jxcore-log: 
06-30 13:52:48.798  6612  6684 W jxcore-log: JXcore engine is started
,06-30 13:52:48.801  6612  6678 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 13:52:48.803  6612  6612 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
06-30 13:52:50.334   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:52:55.339   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:52:59.065   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:52:59.065   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:52:59.065   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 172461636866; DSPS: 5749939; Offset : -3023965831
,06-30 13:53:00.095  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:53:00.095  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:53:00.095  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:53:00.099  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:53:00.099  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:53:00.100  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:53:00.101  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:53:00.344   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:04.777  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 13:53:04.777  6612  6684 I jxcore-log: 
,06-30 13:53:04.781  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 13:53:04.781  6612  6684 I jxcore-log: 
06-30 13:53:04.787  2061  2080 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:53:04.788  6612  6684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:53:04.792  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
,06-30 13:53:04.797  6612  6684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 13:53:04.800  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 13:53:04.800  6612  6684 I jxcore-log: 
06-30 13:53:04.802  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 13:53:04.802  6612  6684 I jxcore-log: 
06-30 13:53:05.335  6612  6684 I jxcore-log: Unit Test app is loaded
06-30 13:53:05.335  6612  6684 I jxcore-log: 
,06-30 13:53:05.348   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:05.352  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:53:05.352  6612  6684 I jxcore-log: 
06-30 13:53:05.358  6612  6612 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
06-30 13:53:05.359  6612  6684 I jxcore-log: My device name is: LGE-LG-D722
06-30 13:53:05.359  6612  6684 I jxcore-log: 
06-30 13:53:05.530  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:53:05.530  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1828b9cf added. We now have 2 listener(s)
06-30 13:53:05.530  6612  6678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:53:05.535  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.536  2061  3455 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.544  6612  6678 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:53:05.545  6612  6678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:53:05.545  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:53:05.546  6612  6678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,06-30 13:53:05.547  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1828b9cf removed from the list
06-30 13:53:05.548  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:53:05.548  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@370e5f5c added. We now have 2 listener(s)
06-30 13:53:05.548  6612  6678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:53:05.552  6612  6678 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:53:05.552  6612  6678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:53:05.553  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:53:05.553  6612  6678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:53:05.553  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@370e5f5c removed from the list
06-30 13:53:05.553  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:53:05.553  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f54d265 added. We now have 2 listener(s)
06-30 13:53:05.553  6612  6678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:53:05.559   848  1972 D WifiServiceImplEx: setWifiEnabled: false pid=6612, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,06-30 13:53:05.564   848  1972 D WifiService: setWifiEnabled: false pid=6612, uid=10030
,06-30 13:53:05.588   848  2176 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:53:05.592   848  1310 E WifiStateMachine: WifiStateMachine: Leaving Connected state
06-30 13:53:05.598   848  2176 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e8a185b mBinding = false
,06-30 13:53:05.603   848  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
06-30 13:53:05.608   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:05.609   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:53:05.611   848   848 D Ulp_jni : JNI:system_update. Event-4
,06-30 13:53:05.621   848  1051 D BluetoothManagerService: Message: 2
06-30 13:53:05.622  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
,06-30 13:53:05.623   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:05.623   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:53:05.623   848   848 D Ulp_jni : JNI:system_update. Event-4
06-30 13:53:05.626  6612  6678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:53:05.626   848  1051 D BluetoothManagerService: Sending off request.
06-30 13:53:05.631  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:53:05.631  6612  6678 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:53:05.632   848  1309 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:53:05.635  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.635   848  1309 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.636  6612  6678 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 13:53:05.636  6612  6678 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:53:05.636  2061  2080 D BluetoothAdapterService(344410431): disable() called...
06-30 13:53:05.638  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:53:05.641  2061  2080 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.642  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:05.643  2061  3455 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.644   848  2913 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:53:05.651   267  1048 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:53:05.656  2061  2207 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
06-30 13:53:05.656  2061  2207 D BluetoothAdapterProperties: Setting state to 13
06-30 13:53:05.656  2061  2207 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,06-30 13:53:05.657   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
06-30 13:53:05.661  2061  2207 D BluetoothAdapterService(344410431): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 13:53:05.669  2343  4376 V NativeCrypto: Read error: ssl=0xb04a5000: I/O error during system call, Connection timed out
06-30 13:53:05.686   848   848 D WifiHS20: hidePasspointNotification off =false
,06-30 13:53:05.691  2061  2207 D BluetoothAdapterProperties: onBluetoothDisable()
06-30 13:53:05.693  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 13:53:05.696  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.697   848  1051 D BluetoothManagerService: Message: 60
06-30 13:53:05.697   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
,06-30 13:53:05.698   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
06-30 13:53:05.699   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
06-30 13:53:05.699   848  1051 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
06-30 13:53:05.704   848  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
06-30 13:53:05.705   848  1317 D ConnectivityService: ignoring duplicate network state non-change
06-30 13:53:05.706   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:05.706   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:05.707   848  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
06-30 13:53:05.708  2061  2207 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
06-30 13:53:05.713  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,06-30 13:53:05.715   848   848 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:05.715   848   848 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:05.715   848   848 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:53:05.718  2061  2251 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 13:53:05.719  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:05.713 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:05.720  2343  4376 V NativeCrypto: SSL shutdown failed: ssl=0xb04a5000: I/O error during system call, Broken pipe
06-30 13:53:05.723  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:05.725  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,06-30 13:53:05.723  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:05.727  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 13:53:05.727  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 13:53:05.742   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:05.742   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 13:53:05.748  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 13:53:05.748  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
06-30 13:53:05.754   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:05.754   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 13:53:05.758   848   899 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6716 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 13:53:05.761  2061  2251 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:53:05.761  2061  2207 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
06-30 13:53:05.761  2061  2207 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
06-30 13:53:05.762   848   848 D WifiHS20: hidePasspointNotification off =false
06-30 13:53:05.763  2061  2207 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
06-30 13:53:05.765  2061  2207 D bt-btif : btsock_ctrl_hci_cleanup(L202): poll handle:4
06-30 13:53:05.766  2061  2207 I bt-btif : BTA_JvDeleteRecord
06-30 13:53:05.766  2061  2207 I bt-btif : BTA_JvRfcommStopServer
06-30 13:53:05.766  2061  2207 I bt-btif : BTA_JvDeleteRecord
06-30 13:53:05.766  2061  2207 I bt-btif : BTA_JvRfcommStopServer
,06-30 13:53:05.766  2061  3636 W bt-btif : invalid rfc slot id: 1
06-30 13:53:05.766  2061  2207 D IOP_DB_BT: db_close: nbr users 0
06-30 13:53:05.766  2061  2207 D IOP_DB_BT: db_close: free database
06-30 13:53:05.767   848   848 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:05.767   848   848 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:05.767   848   848 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:53:05.769   848   848 D WifiScanningService: SCAN_AVAILABLE : 1
06-30 13:53:05.769   848  1329 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.770  2061  3572 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
06-30 13:53:05.771  2061  2251 E bt-btif : btif_hf_upstreams_evt: wrong handle = 29735 
06-30 13:53:05.771  2061  3572 W bt-obex : Ignore event 10 in state 1
06-30 13:53:05.772  2061  2251 I bt-btif : HAL bt_op_callbacks->ops_state_cb
06-30 13:53:05.772  2061  2251 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:3
06-30 13:53:05.772  2061  3572 W bt-obex : Ignore event 10 in state 1
06-30 13:53:05.773  2061  2251 D OppService: onOpsStateChange() :3
06-30 13:53:05.774  2061  3572 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:53:05.774  2061  2061 D OppService: Recieved MESSAGE_OPS_DISABLE
06-30 13:53:05.775   848  1309 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.775   848  1309 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.782  2061  2207 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:Address
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:G3s-1
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
06-30 13:53:05.782  2061  2207 D btif_config_util: en,um_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
06-30 13:53:05.782  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:x
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:00:0F:F6
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
06-30 13:53:05.783   848   848 D RttService: SCAN_AVAILABLE : 1
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
06-30 13:53:05.783  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
06-30 13:53:05.784   848  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:$
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
06-30 13:53:05.784  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
06-30 13:53:05.785  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:A5-1
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
06-30 13:53:05.785  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
06-30 13:53:05.785  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:#
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:Nexus 6
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.786  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:05.785 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
06-30 13:53:05.786  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:XT1072
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.786  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:,
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:a
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:S5-1
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
06-30 13:53:05.787  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:	a
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:G4-1
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
06-30 13:53:05.788  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:a
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy S5)
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A5)
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.789  2061  2061 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
06-30 13:53:05.789  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
06-30 13:53:05.790  2061  2061 D BluetoothMapService: STATE_TURNING_OFF
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A3)
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:05.790  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:Note3-1
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.791  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
06-30 13:53:05.792  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
06-30 13:53:05.792  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L344): out, value:XT1039
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
,06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L344): out, value:	a
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
06-30 13:53:05.793  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
06-30 13:53:05.794  2343  4376 E GCM     : Wifi connection closed with errorCode 20
06-30 13:53:05.794  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:HTC One_M8
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:05.795  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.795  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:"
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
06-30 13:53:05.796  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:Note4-1
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
06-30 13:53:05.796  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.797  2061  2207 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
06-30 13:53:05.801  1862  1862 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:05.800  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.801  2061  2207 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L344): out, value:#
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
06-30 13:53:05.802  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
06-30 13:53:05.803  2061  2207 D btif_config_util: enum_config(L344): out, value:H
06-30 13:53:05.803  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:?C
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:Tab4
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.804  2061  2207 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:�h�
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:��h
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:Name, value type:string
06-30 13:53:05.805  2061  2207 D btif_config_util: enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:J���J�hrD�hrD�
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:��P
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L344): out, value:Galaxy S5-2
06-30 13:53:05.806  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:A3-1
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
06-30 13:53:05.807  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:$��
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:`��
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:���
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
06-30 13:53:05.808  2061  2207 D btif_config_util: enum_config(L344): out, value:�_
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:4g�
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:��f
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:4g�������v��
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:��\
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
06-30 13:53:05.809  2061  2207 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:05.820  2061  2061 V BluetoothMapService: Handler(): got msg=4
06-30 13:53:05.821  2061  2061 D BluetoothMapService: MAP Service closeService in
06-30 13:53:05.821  2061  2061 D BluetoothMapMasInstance: MAP Service shutdown
06-30 13:53:05.823  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.824  2061  3457 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:05.826   848  1915 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
06-30 13:53:05.827  2061  3642 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:53:05.838   848  1309 D LGWifiP2pService: P2pDisablingState
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
06-30 13:53:05.843  2061  3640 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
06-30 13:53:05.845  1862  1862 D WfdsService: WifiP2pState is changed : false
06-30 13:53:05.845   848  1309 D LGWifiP2pService: P2pDisablingState{ when=-44ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.845  1862  2136 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
06-30 13:53:05.845   848  1309 D LGWifiP2pService: p2p socket connection lost
06-30 13:53:05.845  2061  2061 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:53:05.846  2061  2061 V BluetoothMapService: MAP Service closeService out
06-30 13:53:05.846   848  1309 D LGWifiP2pService: P2pDisabledState
06-30 13:53:05.846  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 13:53:05.846  1372  1372 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
06-30 13:53:05.848   848  1309 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.848   848  1309 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.863   848  2912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-33ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.864   848  2912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-38ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.864   848  2912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 13:53:05.864  1862  2136 D WfdsJNI : doCommand: P2P_STOP_FIND
06-30 13:53:05.870  1862  1898 D WifiServiceExtension: isInternetCheckAvailable return false
06-30 13:53:05.884  1862  2136 D WfdsService: Set the WFDS Monitor: false
06-30 13:53:05.889   267  1048 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:53:05.892   848  1317 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
06-30 13:53:05.892   848  1317 D DSQN    : disableDataServiceNotify
06-30 13:53:05.892   848  1317 D DSQN    : stop dsqn bin
06-30 13:53:05.899  1862  2136 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:53:05.904  1862  2811 D CtrlSupplicant: Received on exit socket, terminate
06-30 13:53:05.904  1862  2811 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
06-30 13:53:05.905  1862  2136 D WfdsService: STATE : WfdsDisabledState - enter
06-30 13:53:05.905  1862  2136 D WfdsService: WFDS: Scanner is paused
06-30 13:53:05.911  1862  2136 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
06-30 13:53:05.911  1862  2811 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
06-30 13:53:05.911  1862  2811 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
06-30 13:53:05.915  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
,06-30 13:53:05.950  1862  2134 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,06-30 13:53:05.979   848  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
06-30 13:53:05.979   848  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:05.980   848  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:53:05.981   848  2913 D DhcpStateMachine: StoppedState
06-30 13:53:05.981   848  2913 D DhcpStateMachine: StoppedState{ when=-119ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:53:05.990   848  1317 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
06-30 13:53:05.990   848  1317 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:05.990  1372  1727 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
06-30 13:53:05.990   848  1317 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:05.991   848  1317 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
06-30 13:53:05.991   848  2912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.991   848  2912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:05.991   848  2912 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
06-30 13:53:05.991  3303  3625 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
06-30 13:53:05.992   848  1059 I ActivityManager: Process com.google.android.apps.docs (pid 6276) has died
06-30 13:53:05.994   848  1317 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.103/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
06-30 13:53:05.994   848  1317 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,06-30 13:53:05.997   848   848 D WifiHS20: hidePasspointNotification off =false
06-30 13:53:05.998   848  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:53:05.998  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
06-30 13:53:05.999  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:05.998 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:05.999  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:05.999  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:53:05.999   848   848 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:05.999   848   848 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:05.999   848   848 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:53:06.002  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.002  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.002  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 13:53:06.002  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 13:53:06.002  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 13:53:06.002  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
06-30 13:53:06.010  1911  1911 W QCNEJ   : |CORE| No family connected
,06-30 13:53:06.012   848  1317 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:06.012  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:06.013  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:06.013 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:06.013  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:06.014   848  1051 D Tethering: MasterInitialState.processMessage what=3
06-30 13:53:06.015   848  1308 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
06-30 13:53:06.016   848  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
06-30 13:53:06.019   848   848 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
06-30 13:53:06.020   848  1317 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:06.020   848  1317 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:06.020   848  1317 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:06.020   848   848 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
06-30 13:53:06.020   848   848 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
06-30 13:53:06.020   848  1051 D Tethering: MasterInitialState.processMessage what=3
06-30 13:53:06.021   848  1317 D NetworkManagementService: Removing idletimer
06-30 13:53:06.021   848  1310 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:06.021   848  1310 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 13:53:06.021   848  1308 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,06-30 13:53:06.023  1911  1911 W QCNEJ   : |CORE| No family connected
06-30 13:53:06.023  1911  1911 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:06.026  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:53:06.027  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:06.029  1779  1779 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 13:53:06.029  1911  1911 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
06-30 13:53:06.030  1779  1779 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:06.030  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:53:06.031   848  1317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:06.031  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:06.044  1372  1372 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,06-30 13:53:06.052  1372  1372 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
06-30 13:53:06.054  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.054  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.054  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 13:53:06.055  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.056  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.056  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 13:53:06.057  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.057  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.057  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 13:53:06.058  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,06-30 13:53:06.092  1372  1372 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
06-30 13:53:06.093  1372  1372 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,06-30 13:53:06.095  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.095  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.095  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 13:53:06.097  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.097  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.097  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
,06-30 13:53:06.134   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-30 13:53:06.136   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
,06-30 13:53:06.137  2677  2677 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
06-30 13:53:06.137  2677  2677 I wpa_supplicant: monitor socket send errors count : 1
06-30 13:53:06.137  2677  2677 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1862-2\x00 that cannot receive messages
06-30 13:53:06.138   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
06-30 13:53:06.138   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
06-30 13:53:06.139   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:06.139   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:06.154  2677  2677 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,06-30 13:53:06.156  2677  2677 W wpa_supplicant: USIM:  scard_deinit function
06-30 13:53:06.168   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:06.168   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:06.169   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 13:53:06.169   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,06-30 13:53:06.283  6716  6716 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:53:06.285   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 13:53:06.286  6716  6716 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
06-30 13:53:06.286  6716  6716 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:53:06.287  6716  6716 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:53:06.288  6716  6716 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 13:53:06.294   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
06-30 13:53:06.296  2677  2677 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,06-30 13:53:06.296   848  1051 D Tethering: InitialState.processMessage what=4
,06-30 13:53:06.301   848  1051 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,06-30 13:53:06.394  6716  6716 I IndexDatabaseHelper: Using schema version: 115
,06-30 13:53:06.397  6716  6716 I IndexDatabaseHelper: Index is fine
06-30 13:53:06.402   848  1310 D WifiOffDelayIfNotUsed: stopMonitoring
06-30 13:53:06.402  1862  1862 D WfdsService: Supplicant Connection state is changed : false
06-30 13:53:06.403  1862  2136 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
06-30 13:53:06.403  1862  2136 D WfdsService: Set the WFDS Monitor: false
06-30 13:53:06.403  1862  2136 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:53:06.406   848   848 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
06-30 13:53:06.406   848  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
06-30 13:53:06.408  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:53:06.409   848  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
06-30 13:53:06.411  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:06.409 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:06.411  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:06.412  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:06.413  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.413  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.413  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 13:53:06.413  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 13:53:06.414  2343  2790 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:06.415  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:06.540  6716  6716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,06-30 13:53:06.546  2061  2061 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:53:06.546  2061  2061 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:06.546  2061  2061 V BluetoothPbapReceiver: ***********state = 13
06-30 13:53:06.554  2061  2061 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,06-30 13:53:06.556  2061  2061 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:06.556  2061  2061 V BluetoothPbapService: state: 13
06-30 13:53:06.556  2061  2061 V BluetoothPbapService: Pbap Service closeService in
06-30 13:53:06.557  2061  2061 V BluetoothPbapService: successfully stopped pbap service
06-30 13:53:06.557  2061  2061 V BluetoothPbapService: Pbap Service closeService out
06-30 13:53:06.557  2061  2061 V BluetoothPbapService: Pbap Service onDestroy
06-30 13:53:06.557  2061  2061 V BluetoothPbapService: Pbap Service closeService in
06-30 13:53:06.557  2061  2061 V BluetoothPbapService: Pbap Service closeService out
06-30 13:53:06.557  2061  2061 D LGBluetoothPbapAdapter: [BTUI] cleanup
06-30 13:53:06.573  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:53:06.617  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:06.628   848  1051 D BluetoothManagerService: Message: 20
06-30 13:53:06.628   848  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@211c5dc2:true
,06-30 13:53:06.638  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:06.640   848  1949 D WifiServiceImplEx: setWifiEnabled: true pid=6612, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
,06-30 13:53:06.641   848  1949 D WifiService: setWifiEnabled: true pid=6612, uid=10030
06-30 13:53:06.646   848  1051 D BluetoothManagerService: Message: 30
06-30 13:53:06.651   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:06.651   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:53:06.651   848   848 D Ulp_jni : JNI:system_update. Event-4
06-30 13:53:06.652   848  1310 I LGFTMITEM: [GET_FTM][id=6], offset=12288
06-30 13:53:06.652   848  1051 D BluetoothManagerService: Message: 30
06-30 13:53:06.653   848  1310 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
06-30 13:53:06.653   848  1310 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
06-30 13:53:06.653   848  1310 E WifiHW  : band=b
06-30 13:53:06.653   848  1310 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
,06-30 13:53:06.655   267  1048 D SoftapController: Softap fwReload - Ok
06-30 13:53:06.657   848  1310 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:06.657   848  1310 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:06.657  6716  6716 D LocalBluetoothProfileManager: Adding local MAP profile
06-30 13:53:06.657   267  1048 D CommandListener: Setting iface cfg
06-30 13:53:06.657   267  1048 D CommandListener: Trying to bring down wlan0
06-30 13:53:06.658   267  1048 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:53:06.661  6716  6716 D BluetoothMap: Create BluetoothMap proxy object
06-30 13:53:06.661   848  1051 D BluetoothManagerService: Message: 30
06-30 13:53:06.662   848  1310 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
06-30 13:53:06.664   848  1310 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
06-30 13:53:06.665   848  1310 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,06-30 13:53:06.666  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:06.666  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:06.666 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:06.667  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:06.667   848  1051 D BluetoothManagerService: Message: 30
06-30 13:53:06.669   848   848 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
06-30 13:53:06.671  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:06.670  6716  6716 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
06-30 13:53:06.672  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:06.673  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:06.673  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:06.673  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 13:53:06.673  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 13:53:06.692  6716  6716 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,06-30 13:53:06.707  6748  6748 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-30 13:53:06.731  6716  6716 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,06-30 13:53:06.746  6716  6716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,06-30 13:53:06.757  6748  6748 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 13:53:06.757  6748  6748 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
06-30 13:53:06.759  6716  6716 D DockEventReceiver: finishStartingService: stopping service
,06-30 13:53:06.788  2061  3583 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
,06-30 13:53:06.789  2061  3572 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,06-30 13:53:06.789  2061  3572 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:53:06.789  2061  3572 W bt-btif : ag scb idx 1 not allocated
06-30 13:53:06.789  2061  3572 E bt-btif : BTA AG is already disabled, ignoring ...
06-30 13:53:06.789  2061  3572 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:53:06.789  2061  3572 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:53:06.789  2061  3572 W bt-btif : ag scb idx 1 not allocated
06-30 13:53:06.789  2061  3572 E bt-btif : BTA AG is already disabled, ignoring ...
06-30 13:53:06.789  2061  3572 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:53:06.789  2061  3572 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:53:06.789  2061  3574 D bt_hwcfg: hw_epilog_process
06-30 13:53:06.790  2061  2251 I bt_userial_vendor: device fd = 70 close
06-30 13:53:06.794  6716  6716 D BluetoothInputDevice: Proxy object connected
06-30 13:53:06.798  6716  6716 D HidProfile: Bluetooth service connected
06-30 13:53:06.800  2061  3457 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:06.800  6716  6716 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 13:53:06.801  6716  6716 D PanProfile: Bluetooth service connected
06-30 13:53:06.803  2061  2080 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
,06-30 13:53:06.806  2061  2251 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
06-30 13:53:06.806  6716  6716 D BluetoothMap: Proxy object connected
06-30 13:53:06.807  6716  6716 D MapProfile: Bluetooth service connected
06-30 13:53:06.807  6716  6716 D BluetoothMap: getConnectedDevices()
06-30 13:53:06.808  2061  3455 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:06.808  6716  6716 D BluetoothMap: Bluetooth is Not enabled
06-30 13:53:06.808  6716  6716 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 13:53:06.810  6716  6716 D LGBluetoothAuthorization: [BTUI] cancel All Notification
06-30 13:53:06.811  6716  6716 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
06-30 13:53:06.811  6716  6716 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
06-30 13:53:06.812  6716  6716 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
06-30 13:53:06.812  6716  6716 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
06-30 13:53:06.812  6716  6716 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
06-30 13:53:06.813  6716  6716 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
06-30 13:53:06.836   848  1379 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6755 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-30 13:53:06.907  6716  6716 D BluetoothPermissionRequest: onReceive
,06-30 13:53:06.912  2061  2251 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:06.915  6716  6716 D LGBluetoothAuthorization: [BTUI] cancel All Notification
06-30 13:53:06.915  6716  6716 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
06-30 13:53:06.915  6716  6716 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
06-30 13:53:06.916  6716  6716 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
06-30 13:53:06.916  6716  6716 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
06-30 13:53:06.917  6716  6716 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
06-30 13:53:06.917  6716  6716 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
06-30 13:53:06.923  2061  3572 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
06-30 13:53:06.923  2061  2251 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
,06-30 13:53:06.926  2061  2251 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
06-30 13:53:06.926  2061  2207 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
06-30 13:53:06.928  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.928  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:53:06.928  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.928  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:53:06.931  2061  2061 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
06-30 13:53:06.932  2061  2061 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
06-30 13:53:06.932  2061  2061 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
06-30 13:53:06.932  2061  2061 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
06-30 13:53:06.932  2061  2061 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: Unable to read settings
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:06.935  2061  2207 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:53:06.935  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-30 13:53:06.935  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
06-30 13:53:06.936  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.936  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:53:06.936  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.936  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-30 13:53:06.937  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 13:53:06.937  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
06-30 13:53:06.939  2061  2061 D HeadsetService: Received stop request...Stopping profile...
06-30 13:53:06.940  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.940  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
06-30 13:53:06.940  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.940  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:53:06.940  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-30 13:53:06.940  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
06-30 13:53:06.942  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.942  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:53:06.942  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.942  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:53:06.942  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-30 13:53:06.943  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
06-30 13:53:06.944  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.944  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
06-30 13:53:06.944  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.944  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:53:06.944  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
06-30 13:53:06.944  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
06-30 13:53:06.944  2061  2061 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:53:06.945  2061  3465 D HeadsetStateMachine: Exit Disconnected: -1
06-30 13:53:06.945  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.945  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
06-30 13:53:06.945  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.945  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:53:06.946  2061  2061 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:53:06.946  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
06-30 13:53:06.946  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
06-30 13:53:06.947  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.947  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:53:06.947  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.947  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:53:06.947  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:06.947  2061  2207 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
06-30 13:53:06.947  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
,06-30 13:53:06.950   848   848 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:06.950  1779  1779 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:06.952   848   848 D AudioService: onServiceDisconnected: Bluetooth profile: 1
06-30 13:53:06.952  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.952  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:53:06.952  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.952  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:53:06.953  2061  2207 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 13:53:06.953  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
06-30 13:53:06.953  1779  1779 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:06.953  1779  1779 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:06.954  2061  2061 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:53:06.955  2061  2061 D A2dpService: Received stop request...Stopping profile...
06-30 13:53:06.956  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.956  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
06-30 13:53:06.956  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.956  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 13:53:06.956  2061  3475 D A2dpStateMachine: Exit Disconnected: -1
06-30 13:53:06.957  2061  2207 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
06-30 13:53:06.957  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
06-30 13:53:06.958  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.958  2061  2207 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
06-30 13:53:06.958  2061  2207 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:06.958  2061  2207 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:06.959  2061  2207 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
06-30 13:53:06.959  2061  2207 D BluetoothAdapterService(344410431): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
06-30 13:53:06.960  2061  2207 D BluetoothAdapterState: Stopping profile services that were post enabled
,06-30 13:53:06.970  2061  2061 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
06-30 13:53:06.970  2061  2061 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:53:06.971  2061  2061 D LGBluetoothPowerControlManager: [BTUI] terminate
06-30 13:53:06.972   848  1051 D BluetoothManagerService: Message: 31
06-30 13:53:06.972  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:06.973   848   848 D BluetoothA2dp: Proxy object disconnected
06-30 13:53:06.973   848   848 D AudioService: onServiceDisconnected: Bluetooth profile: 2
06-30 13:53:06.974  2061  2061 D HidService: Received stop request...Stopping profile...
,06-30 13:53:06.975  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:06.976  2061  2061 D HealthService: Received stop request...Stopping profile...
06-30 13:53:06.976  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:06.977  2061  2061 D PanService: Received stop request...Stopping profile...
06-30 13:53:06.977  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:06.978  2061  2061 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:53:06.978  2061  2061 D BtGatt.GattService: Received stop request...Stopping profile...
06-30 13:53:06.979  2061  2061 D BtGatt.GattService: stop()
06-30 13:53:06.979  6716  6716 D BluetoothInputDevice: Proxy object disconnected
06-30 13:53:06.979  6716  6716 D HidProfile: Bluetooth service disconnected
06-30 13:53:06.979  2061  2061 D BtGatt.AdvertiseManager: advertise clients cleared
06-30 13:53:06.979  6716  6716 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:53:06.979  6716  6716 D PanProfile: Bluetooth service disconnected
06-30 13:53:06.980  2061  2061 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
06-30 13:53:06.980  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:06.981  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:06.981  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:06.981  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
06-30 13:53:06.981  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:06.981  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:06.981  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:06.981  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:06.982  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:06.984  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:06.984  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:06.984  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:06.986  2061  2061 D HeadsetStateMachine: Unbinding service...
,06-30 13:53:06.994  2061  2061 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:53:06.994  2061  2061 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:53:06.994  2061  2061 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:53:06.994  2061  2061 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:53:06.994  2061  2061 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-30 13:53:06.994  2061  2061 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:53:06.994  2061  2061 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:53:06.995  2061  2061 D BluetoothMapService: Received stop request...Stopping profile...
06-30 13:53:06.996  2061  2061 D BluetoothMapService: stop()
06-30 13:53:06.999  2061  2061 D BluetoothMapEmailAppObserver: deinitObservers()
06-30 13:53:06.999  2061  2061 D BluetoothMapEmailAppObserver: removeReceiver()
,06-30 13:53:07.002  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:07.005  2061  2061 D SapService: Received stop request...Stopping profile...
06-30 13:53:07.006  2061  2061 D SapService: Stopping Bluetooth SapService
06-30 13:53:07.006  2061  2061 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
06-30 13:53:07.006  2061  2061 D LGBluetoothSapManager: [BTUI] terminateSapManager
06-30 13:53:07.007  6716  6716 D BluetoothMap: Proxy object disconnected
06-30 13:53:07.007  6716  6716 D MapProfile: Bluetooth service disconnected
06-30 13:53:07.010  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
06-30 13:53:07.011  2061  2061 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:07.012  2061  2061 D **BluetoothFTPService: Received stop request...Stopping profile...
06-30 13:53:07.012  2061  2061 D **BluetoothFTPService: Stopping Bluetooth FTP Service
,06-30 13:53:07.012  2061  2061 V BluetoothFTPServiceJni: closeFtpServerNative
06-30 13:53:07.013  1779  1779 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
06-30 13:53:07.074   848  1915 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6778 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 13:53:07.084  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
,06-30 13:53:07.092   302   302 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 397us total 26.900ms
06-30 13:53:07.096  6755  6755 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:53:07.100  6755  6755 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:53:07.100  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:07.115   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 340us total 22.101ms
,06-30 13:53:07.138   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.873ms
,06-30 13:53:07.188   848  1915 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6799 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
06-30 13:53:07.192   848  1899 I ActivityManager: Killing 6151:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
06-30 13:53:07.254  2061  2061 D **OppService: Received stop request...Stopping profile...
06-30 13:53:07.254  2061  2061 D OppService: Stopping Bluetooth OppService
06-30 13:53:07.254  2061  2061 D OppService: cleanup OPP Service
06-30 13:53:07.255  2061  2061 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
06-30 13:53:07.255  2061  2061 W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
06-30 13:53:07.256  2061  2061 D OppService: remove callbacks and handler
06-30 13:53:07.256  2061  2061 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
06-30 13:53:07.256  2061  2061 D OppService: cleanup done
06-30 13:53:07.256  2061  2061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1487493f
,06-30 13:53:07.326  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.326  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.326  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
06-30 13:53:07.326  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.326  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.326  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.326  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.326  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.326  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.326  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.326  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.326  2061  2061 I BluetoothA2dpServiceJni: cleanupNative
06-30 13:53:07.326  2061  2061 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:07.327  2061  3634 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
06-30 13:53:07.327  2061  2061 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
,06-30 13:53:07.332   848  2016 W libprocessgroup: failed to open /acct/uid_10069/pid_6151/cgroup.procs: No such file or directory
06-30 13:53:07.334  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.334  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.334  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
06-30 13:53:07.334  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.334  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.334  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.334  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.334  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.334  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.335  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.335  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.338  2061  2061 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-30 13:53:07.338  2061  2061 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-30 13:53:07.338  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.338  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.338  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
06-30 13:53:07.338  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.338  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.338  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.338  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.338  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.339  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.339  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.339  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.339  2061  2061 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
06-30 13:53:07.339  2061  2061 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:53:07.339  2061  2061 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:53:07.340  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.340  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.340  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
06-30 13:53:07.340  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.340  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.340  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.340  2061  2061 D BluetoothAdapterState: isQuietMod,eServiceTurningOff()=false
06-30 13:53:07.340  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.340  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.340  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.340  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.340  2061  2061 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-30 13:53:07.340  2061  2061 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,06-30 13:53:07.341  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.341  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.341  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
06-30 13:53:07.341  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.341  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.341  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.341  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.341  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.342  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.342  2061  2061 V BluetoothMapService: Handler(): got msg=4
06-30 13:53:07.342  2061  2061 D BluetoothMapService: MAP Service closeService in
06-30 13:53:07.342  2061  2061 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:53:07.342  2061  2061 V BluetoothMapService: MAP Service closeService out
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
06-30 13:53:07.342  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.342  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.342  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.342  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.342  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.342  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.342  2061  2061 D BluetoothMapService: cleanup()
06-30 13:53:07.342  2061  2061 D BluetoothMapService: MAP Service closeService in
06-30 13:53:07.342  2061  2061 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:53:07.342  2061  2061 V BluetoothMapService: MAP Service closeService out
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.343  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.343  2061  2061 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
06-30 13:53:07.343  2061  2061 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.343  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.343  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.344  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.345  2061  2061 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.345  2061  2061 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.345  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.345  2061  2061 D BluetoothFTPService: cleanup FTP Service
06-30 13:53:07.345  2061  2061 V BluetoothFTPServiceJni: closeFtpServerNative
06-30 13:53:07.345  2061  2061 V BluetoothFTPServiceJni: cleanupNative
06-30 13:53:07.345  2061  2061 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...
06-30 13:53:07.345  2061  2061 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
06-30 13:53:07.345  2061  2061 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
06-30 13:53:07.345  2061  2061 D BluetoothFTPService: cleanup done
06-30 13:53:07.346  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - Message: 1
,06-30 13:53:07.346  2061  2061 D BluetoothAdapterService(344410431): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:07.346  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
06-30 13:53:07.346  2061  2061 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:07.346  2061  2061 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:07.346  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:07.346  2061  2061 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:07.346  2061  2061 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:07.346  2061  2061 D BluetoothAdapterService(344410431): onProfileServiceStateChange() - All profile services stopped...
06-30 13:53:07.346  2061  2207 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
06-30 13:53:07.346  2061  2207 D BluetoothAdapterProperties: Setting state to 10
06-30 13:53:07.346  2061  2207 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
06-30 13:53:07.346  2061  2207 D BluetoothAdapterService(344410431): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 13:53:07.347  2061  2061 D OppService: cleanup OPP Service
06-30 13:53:07.347  2061  2061 D OppService: remove callbacks and handler
06-30 13:53:07.347  2061  2061 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
06-30 13:53:07.347  2061  2061 D OppService: cleanup done
06-30 13:53:07.347   848  1051 D BluetoothManagerService: Message: 60
06-30 13:53:07.347   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
06-30 13:53:07.347   848  1051 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
06-30 13:53:07.347  2061  2207 I BluetoothAdapterState: Entering OffState
06-30 13:53:07.349  6716  6738 D BluetoothMap: onBluetoothStateChange: up=false
06-30 13:53:07.349  6716  6737 D BluetoothPan: onBluetoothStateChange on: false
06-30 13:53:07.350  6716  6738 D BluetoothPbap: onBluetoothStateChange: up=false
06-30 13:53:07.351  1779  1798 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:07.351  6716  6737 D BluetoothInputDevice: onBluetoothStateChange: up=false
06-30 13:53:07.352   848  1051 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:07.352   848  1051 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:53:07.352  1779  2336 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:07.353  1779  2684 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:07.355  2061  2076 D BluetoothAdapterService(344410431): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1e09cc0d
06-30 13:53:07.355   848  1051 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
06-30 13:53:07.355   848  1051 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,06-30 13:53:07.370   848  1051 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
06-30 13:53:07.370   848  1051 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
06-30 13:53:07.370   848  1051 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3e8a185b mBinding = false
,06-30 13:53:07.372   848  1051 D BluetoothManagerService: Sending unbind request.
06-30 13:53:07.373   848  1051 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
06-30 13:53:07.374  2061  2061 D BluetoothAdapterService(344410431): onUnbind() - calling cleanup
06-30 13:53:07.375  2061  2061 D BluetoothAdapterService(344410431): cleanup()
06-30 13:53:07.376  1862  1862 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:07.376  1372  1372 D BluetoothAdapter: 785038531: getState() :  mService = null. Returning STATE_OFF
06-30 13:53:07.376  1372  1372 D BluetoothAdapter: 785038531: getState() :  mService = null. Returning STATE_OFF
06-30 13:53:07.377  1862  2058 D LGBluetoothAPIService: Message: 2
06-30 13:53:07.377  1862  2058 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3dc4e07a mBinding = false
06-30 13:53:07.378  1862  2058 D LGBluetoothAPIService: Sending unbind request.
06-30 13:53:07.380  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 13:53:07.380  1372  1372 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
06-30 13:53:07.385  6778  6778 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:53:07.386  2343  2790 D BluetoothAdapter: 641833776: getState() :  mService = null. Returning STATE_OFF
06-30 13:53:07.387  2343  2790 D BluetoothAdapter: 641833776: getState() :  mService = null. Returning STATE_OFF
,06-30 13:53:07.390  2061  2061 D BluetoothAdapterService(344410431): cleanup() - Cleaning up adapter native
06-30 13:53:07.390  2061  2061 I bt-btif : btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
06-30 13:53:07.390  2061  2061 I GKI_LINUX: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:07.390  2061  2251 I bt-btif : HAL bt_hal_cbacks->thread_evt_cb
06-30 13:53:07.390  2061  2251 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_destroy_task(): task [BTIF] terminated
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_exit_task 2 done
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_exit_task 1 done
06-30 13:53:07.391  2061  2061 I GKI_LINUX: GKI_exit_task 0 done
06-30 13:53:07.392  2061  2061 I BluetoothServiceJni: cleanupNative: return from cleanup
06-30 13:53:07.392  2061  2061 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
06-30 13:53:07.392  6716  6716 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:53:07.393  2061  2061 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
06-30 13:53:07.393  6716  6716 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
06-30 13:53:07.393  6716  6716 D LGBluetoothEventManager: [BTUI] clear device connection state
06-30 13:53:07.393  2061  2061 D BluetoothAdapterService(344410431): cleanup() - Bluetooth process exited normally.
06-30 13:53:07.394  2061  2061 D BluetoothAdapterService(344410431): cleanup() done
06-30 13:53:07.396  2061  2061 I art     : System.exit called, status: 0
06-30 13:53:07.396  2061  2061 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
06-30 13:53:07.418   273  1302 V AudioFlinger: 2061 died, releasing its sessions
06-30 13:53:07.418   273  1302 V AudioFlinger:  pid 1779 @ 0
06-30 13:53:07.418   273  1302 V AudioFlinger:  pid 3113 @ 1
06-30 13:53:07.418   273  1302 V AudioFlinger:  pid 3113 @ 2
,06-30 13:53:07.421  6716  6716 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
06-30 13:53:07.422  1862  1862 D FMFRW_FmProxy: Fm Proxy object disconnected
06-30 13:53:07.442  6799  6799 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 13:53:07.524   848  1936 I ActivityManager: Process com.android.bluetooth (pid 2061) has died
,06-30 13:53:07.524   848  1936 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
06-30 13:53:07.524   848  1936 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
06-30 13:53:07.527   848  1972 I ActivityManager: Killing 6255:com.lge.eula/1000 (adj 15): empty #11
06-30 13:53:07.625   848  1379 W libprocessgroup: failed to open /acct/uid_1000/pid_6255/cgroup.procs: No such file or directory
,06-30 13:53:07.639  2343  2343 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,06-30 13:53:07.647  2343  2343 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 13:53:07.651  6716  6716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:53:07.673   848  1051 D BluetoothManagerService: Message: 20
06-30 13:53:07.673   848  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a859d04:true
,06-30 13:53:07.687   848  1059 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6822 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,06-30 13:53:07.689  6716  6716 D DockEventReceiver: finishStartingService: stopping service
06-30 13:53:07.690   848  1936 D WifiServiceImplEx: setWifiEnabled: false pid=6612, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
06-30 13:53:07.690   848  1936 D WifiService: setWifiEnabled: false pid=6612, uid=10030
,06-30 13:53:07.704   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 13:53:07.705   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 13:53:07.708   848  1051 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
06-30 13:53:07.709  6799  6799 D BluetoothAdapter: 344410431: getState() :  mService = null. Returning STATE_OFF
06-30 13:53:07.709  6799  6799 D BluetoothAdapter: 344410431: getState() :  mService = null. Returning STATE_OFF
06-30 13:53:07.711   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:07.711   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:53:07.711   848   848 D Ulp_jni : JNI:system_update. Event-4
,06-30 13:53:07.765  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,06-30 13:53:07.773  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:07.779  6755  6755 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:53:07.779  6755  6755 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:53:07.779  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 13:53:07.783  6748  6748 E wpa_supplicant: USIM:  scard_init function
,06-30 13:53:07.784  6822  6822 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
06-30 13:53:07.784  6822  6822 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:53:07.784  6822  6822 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
06-30 13:53:07.785  6822  6822 W ResourcesManager: Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
06-30 13:53:07.785  6748  6748 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 13:53:07.787   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-30 13:53:07.788   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
06-30 13:53:07.789   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:07.789   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:07.789   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-30 13:53:07.815  6822  6822 D BluetoothAdapterApp: Loading JNI Library
,06-30 13:53:07.829   848  1059 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6843 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 13:53:07.837  6748  6748 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
06-30 13:53:07.850  6748  6748 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,06-30 13:53:07.854   848  1310 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
06-30 13:53:07.854   848  1310 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
06-30 13:53:07.855   848   848 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:07.855   848   848 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:07.855   848   848 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:07.855   848   848 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:07.855   848   848 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:53:07.857   848   848 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
06-30 13:53:07.857   848   848 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
06-30 13:53:07.857   848  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
06-30 13:53:07.861  6822  6822 E BluetoothServiceJni: [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,06-30 13:53:07.867  6822  6822 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2a84e786 Instance Count = 1
06-30 13:53:07.870   848  1310 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
06-30 13:53:07.873  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:07.874  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:07.873 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:07.874  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:07.875  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:53:07.875   848  1310 D WifiStateMachine: enableVerboseLogging : level 2
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:07.875  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:07.876  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:07.876  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,06-30 13:53:07.876  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:07.876  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 13:53:07.876  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 13:53:07.878  6822  6822 D BluetoothAdapterApp: onCreate
06-30 13:53:07.879   848  1310 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:53:07.880  1862  1862 D WfdsService: Supplicant Connection state is changed : true
06-30 13:53:07.880   848  1310 D WifiNative-HAL: Setting external_sim to 1
06-30 13:53:07.880  1862  2136 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
06-30 13:53:07.880  1862  2136 D WfdsService: Set the WFDS Monitor: true
06-30 13:53:07.880  1862  2136 D WfdsMonitor: WfdsMonitorThread create
06-30 13:53:07.880  1862  2136 D WfdsMonitor: WFDS Monitor is created and started
06-30 13:53:07.880  1862  2136 D WfdsService: WiFi: Supplicant connection re-established
06-30 13:53:07.881   848  1310 I WifiNative-HAL: startHal
06-30 13:53:07.881   848  1310 D wifi    : setting scan oui 0x9daecfb8
06-30 13:53:07.881   848  1310 D WifiHAL : Sending mac address OUI
06-30 13:53:07.881   848  1310 E WifiHAL : failed to set scanning mac OUI; result = -95
06-30 13:53:07.881   848  1310 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 13:53:07.881   848  1310 I WifiNative-HAL: startHal
06-30 13:53:07.881   848  1310 D wifi    : setting scan oui 0x9daecfb8
06-30 13:53:07.881   848  1310 D WifiHAL : Sending mac address OUI
06-30 13:53:07.881   848  1310 E WifiHAL : failed to set scanning mac OUI; result = -95
06-30 13:53:07.884  1862  6852 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
06-30 13:53:07.885  1862  6852 E CtrlSupplicant: Succeed to open control connection
06-30 13:53:07.885  1862  6852 E CtrlSupplicant: Succeed to open monitor connection
06-30 13:53:07.888  1862  6852 D WfdsMonitor: Supplicant connection established
06-30 13:53:07.888  1862  2136 D WfdsService: Connected to the supplicant for wfds
06-30 13:53:07.902  6822  6822 I LGBluetoothServiceJni: classInitNative: succeeds
,06-30 13:53:07.904  6822  6822 D BtSettings.ProfileConfig: [BTUI] HeadsetServiceis supported
06-30 13:53:07.905  6822  6822 D BtSettings.ProfileConfig: Adding HeadsetService
06-30 13:53:07.905   848   848 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 13:53:07.906   848   848 D RttService: SCAN_AVAILABLE : 3
06-30 13:53:07.906   848  1329 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.906   848  1329 I WifiNative-HAL: startHal
06-30 13:53:07.906   848  1329 D wifi    : getting scan capabilities on interface[0] = 0x9daecfb8
06-30 13:53:07.906   848  1329 D WifiHAL : Creating message to get scan capablities; iface = 24
06-30 13:53:07.906   848  1329 D wifi    : failed to get capabilities : -95
06-30 13:53:07.906   848  1330 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.907   848  1329 E WifiScanningService: could not get scan capabilities
06-30 13:53:07.908   848  1309 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.909   848  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:07.909   848  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:07.909   267  1048 D CommandListener: Setting iface cfg
06-30 13:53:07.909   267  1048 D CommandListener: Trying to bring up p2p0
06-30 13:53:07.910   848  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
06-30 13:53:07.910   848  1309 D LGWifiP2pService: P2pEnablingState
06-30 13:53:07.910   848  1309 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.910   848  1309 D LGWifiP2pService: P2p socket connection successful
06-30 13:53:07.910   848  1309 D LGWifiP2pService: P2pEnabledState
06-30 13:53:07.911   848  1309 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
06-30 13:53:07.911   848  1309 D LGWifiP2pService: before postfix = G3s-1
06-30 13:53:07.911   848  1309 D WifiServerServiceExt: postfix byte check : 5
06-30 13:53:07.911   848  1309 D LGWifiP2pService: after postfix = G3s-1
06-30 13:53:07.912   848  1309 D WifiNative-HAL: p2pGetDeviceAddress
06-30 13:53:07.912   848  1309 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
06-30 13:53:07.913  6822  6822 D BtSettings.ProfileConfig: [BTUI] A2dpServiceis supported
06-30 13:53:07.915  1862  1862 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
06-30 13:53:07.915  1862  1862 D WfdsService: Update P2p Interface State: 3
06-30 13:53:07.915   848  1309 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
06-30 13:53:07.917  6822  6822 D BtSettings.ProfileConfig: Adding A2dpService
06-30 13:53:07.918   848   848 D WifiScanningService: SCAN_AVAILABLE : 1
06-30 13:53:07.918   848   848 D RttService: SCAN_AVAILABLE : 1
06-30 13:53:07.918   848  1329 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.918  6822  6822 D BtSettings.ProfileConfig: [BTUI] HidServiceis supported
06-30 13:53:07.918   848  1330 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.919  6822  6822 D BtSettings.ProfileConfig: Adding HidService
06-30 13:53:07.919   848  1310 E WifiStateMachine: Error! unhandled message{ when=-62ms what=132103 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.920  6822  6822 D BtSettings.ProfileConfig: [BTUI] HealthServiceis supported
06-30 13:53:07.920  6822  6822 D BtSettings.ProfileConfig: Adding HealthService
06-30 13:53:07.920   848  1310 E WifiStateMachine: Error! unhandled message{ when=-63ms what=132106 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.920  6822  6822 D LGBluetoothFeatureConf,ig: isSupportPan() :  mTargetOp=OPEN
06-30 13:53:07.921   848  1310 E WifiStateMachine: Error! unhandled message{ when=-64ms what=132096 arg1=-100 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.921  6822  6822 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
06-30 13:53:07.922  6822  6822 D BtSettings.ProfileConfig: [BTUI] PanServiceis supported
06-30 13:53:07.922  6822  6822 D BtSettings.ProfileConfig: Adding PanService
06-30 13:53:07.922   848  1310 E WifiStateMachine: Error! unhandled message{ when=-65ms what=132156 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.923  6822  6822 D BtSettings.ProfileConfig: [BTUI] GattServiceis supported
06-30 13:53:07.923  6822  6822 D BtSettings.ProfileConfig: Adding GattService
06-30 13:53:07.923   848  1310 E WifiStateMachine: Error! unhandled message{ when=-48ms what=132104 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.924  6822  6822 D BtSettings.ProfileConfig: [BTUI] BluetoothMapServiceis supported
06-30 13:53:07.925  6822  6822 D BtSettings.ProfileConfig: Adding BluetoothMapService
,06-30 13:53:07.927  6822  6822 V LGBluetoothServiceAdapter: [BTUI] region:EU country:EU
,06-30 13:53:07.927  6822  6822 D BtSettings.ProfileConfig: [BTUI] SapServiceis supported
06-30 13:53:07.927  6822  6822 D BtSettings.ProfileConfig: Adding SapService
06-30 13:53:07.928  6822  6822 D BtSettings.ProfileConfig: [BTUI] FTPServiceis supported
06-30 13:53:07.928  6822  6822 D BtSettings.ProfileConfig: Adding FTPService
06-30 13:53:07.929  6822  6822 E BtSettings.ProfileConfig: [BTUI] HeadsetClientServiceis NOT supported
06-30 13:53:07.930  6822  6822 D BtSettings.ProfileConfig: [BTUI] OppServiceis supported
06-30 13:53:07.930  6822  6822 D BtSettings.ProfileConfig: Adding OppService
06-30 13:53:07.935  6822  6822 D BtSettings.ProfileConfig: deviceMode from shared preference   -1
06-30 13:53:07.935  6822  6822 D BtSettings.ProfileConfig: checkAndAdjustDeviceModeConfiguration deviceMode1
06-30 13:53:07.935  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: Unable to read settings
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 13:53:07.942  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-30 13:53:07.945  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:53:07.945  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:53:07.946  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:53:07.947  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:53:07.948   848  1309 D LGWifiP2pService: sending p2p persistent groups changed broadcast
06-30 13:53:07.948   848  1309 D LGWifiP2pService: sending p2p connection changed broadcast
06-30 13:53:07.949   848  1309 D LGWifiP2pService: InactiveState
06-30 13:53:07.949   848  1309 D LGWifiP2pService: InactiveState{ when=-31ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.949   848  1309 D LGWifiP2pService: P2pEnabledState{ when=-31ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.949   848  1309 D LGWifiP2pService: P2pDisablingState
06-30 13:53:07.949   848  1309 D LGWifiP2pService: P2pDisablingState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.949   848  1309 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.949   848  1309 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.949   848  1309 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.950   848   848 E WifiServerServiceExt: No p2p device connected
06-30 13:53:07.950   848  1309 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.950   848  1309 D LGWifiP2pService: p2p socket connection lost
06-30 13:53:07.950   848  1309 D LGWifiP2pService: P2pDisabledState
06-30 13:53:07.951   267  1048 D CommandListener: Clearing all IP addresses on wlan0
06-30 13:53:07.952  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
,06-30 13:53:07.952  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
06-30 13:53:07.952  1862  1862 D WfdsService: WifiP2pState is changed : true
06-30 13:53:07.952  1862  2136 D WfdsService: Receive the WFDS_ENABLE Method
06-30 13:53:07.952  1862  2136 D WfdsService: Set the WFDS Monitor: true
06-30 13:53:07.952  1862  2136 D WfdsService: Connected to the supplicant for wfds
06-30 13:53:07.953  1862  2136 D WfdsJNI : doCommand: WFDS_SET TRUE
06-30 13:53:07.953  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:53:07.953  1862  1862 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
06-30 13:53:07.953  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:53:07.954  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 13:53:07.954  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:07.955  1862  1862 D WfdsService: isConnected: false
06-30 13:53:07.955  1862  1862 D WfdsService: WifiP2pState is changed : false
06-30 13:53:07.956   848  1309 D LGWifiP2pService: P2pDisabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.956   848  1309 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.956  6822  6822 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:53:07.956  1862  1862 D WfdsService: GroupInfoAvailable: mGroupInfo is null
06-30 13:53:07.957   848   848 D WifiHS20: hidePasspointNotification off =false
06-30 13:53:07.957  6822  6822 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:07.957   848  1309 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.957  6822  6822 V BluetoothPbapReceiver: ***********state = 10
06-30 13:53:07.957   848  1309 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:07.958   848   848 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:07.958   848   848 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:07.958   848   848 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
06-30 13:53:07.959  1372  1372 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
06-30 13:53:07.959  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,06-30 13:53:07.961  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:07.96 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:07.962  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:07.962  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:07.962  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:07.962  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
06-30 13:53:07.962  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
06-30 13:53:07.962  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
06-30 13:53:07.962  1372  1372 I [SystemUI]QuickSettingsHandler: Remote
06-30 13:53:07.963  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:07.964  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:07.963 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:07.964  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:07.966  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:07.966  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:07.966  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 13:53:07.966   848   848 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
06-30 13:53:07.966  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 13:53:07.967  6822  6822 V LGMDMManagerInternal: Create singleton instance
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:07.967  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:07.967  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 ,13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:07.968  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:07.968  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:08.044  6843  6843 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 13:53:08.089  6822  6822 I FmServiceJni: classInitNative: succeeds
,06-30 13:53:08.094  6822  6822 D FmService: FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@1d70419dservicecom.broadcom.fm.fmreceiver.FmService@1937f612
06-30 13:53:08.094  6822  6822 D FmNativehandler: start
06-30 13:53:08.096  6822  6822 D BluetoothRadioManager: [BTUI] getRadioManager()
06-30 13:53:08.099  6822  6822 D BluetoothRadioManager: [BTUI] BluetoothRadioManager()
06-30 13:53:08.102   848  1051 D BluetoothManagerService: Message: 20
06-30 13:53:08.102   848  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32a0046:true
,06-30 13:53:08.124   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
06-30 13:53:08.124   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 5
,06-30 13:53:08.125   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 10
06-30 13:53:08.125  6748  6748 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
06-30 13:53:08.125   267  1041 I Netd    : M: Get netlink event, ifname: p2p0 action: 7
06-30 13:53:08.126  6748  6748 W wpa_supplicant: USIM:  scard_deinit function
,06-30 13:53:08.126  1862  6852 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING ]
06-30 13:53:08.127   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:08.127   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:08.140  6822  6822 D BluetoothRadioManager: doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
06-30 13:53:08.152   848  1936 I ActivityManager: Process com.android.vending (pid 5525) has died
,06-30 13:53:08.155   848  1049 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:08.155   848  1049 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:08.160  6822  6822 V FmService: FM Service  onCreate
06-30 13:53:08.160  6822  6822 D FmService: Binding service...
06-30 13:53:08.162  1862  1862 D FMFRW_FmProxy: Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@2194f02b
06-30 13:53:08.167  6716  6716 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
06-30 13:53:08.171  6716  6716 D BluetoothPermissionRequest: onReceive
06-30 13:53:08.176  6716  6716 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 13:53:08.177  6716  6716 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,06-30 13:53:08.231  6822  6822 D BluetoothAdapterService: Set JNI Library before classInit
,06-30 13:53:08.239  6822  6822 D BluetoothAdapterService(463835660): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
06-30 13:53:08.239  6822  6822 D BluetoothAdapterService(463835660): onCreate()
06-30 13:53:08.240  6822  6822 D BluetoothAdapterState: make
06-30 13:53:08.247  6822  6822 I bluedroid: init
,06-30 13:53:08.247  6822  6865 I BluetoothAdapterState: Entering OffState
06-30 13:53:08.254  6822  6822 I bte_conf: Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
06-30 13:53:08.255  6822  6822 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
06-30 13:53:08.255  6822  6822 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
06-30 13:53:08.255  6822  6822 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
06-30 13:53:08.255  6822  6822 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
06-30 13:53:08.255  6822  6822 D bt-btif :  [BTUI] Load_abtddress
06-30 13:53:08.255  6822  6822 D BTIF_CORE: [BTUI] lge_wait_for_load_bluetooth_address : success!
06-30 13:53:08.255  6822  6822 D bt-btif : PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
06-30 13:53:08.256  6822  6822 D bt-btif : Got prior random BDA F8:95:C7:87:85:54
06-30 13:53:08.256  6822  6822 I bluedroid: get_profile_interface socket
06-30 13:53:08.256  6822  6822 I bluedroid: get_profile_interface map_client
06-30 13:53:08.256  6822  6868 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
06-30 13:53:08.256  6822  6822 E BluetoothServiceJni: Error getting mapclient interface
06-30 13:53:08.256  6822  6868 D bt-btif : btif task starting
06-30 13:53:08.256  6822  6868 D bt-btif : btif_associate_evt: notify ASSOCIATE_JVM
06-30 13:53:08.256  6822  6868 I bt-btif : btif_get_adapter_property 2
06-30 13:53:08.256  6822  6822 I bt-btif : btif_get_adapter_property 2
06-30 13:53:08.256  6822  6822 I bt-btif : btif_get_adapter_property 1
06-30 13:53:08.257  6822  6868 I bt-btif : execute storage request event : 3
06-30 13:53:08.257  6822  6868 D bt-btif : btif_storage_get_adapter_property property->type:2 
06-30 13:53:08.257  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 13:53:08.258  6822  6868 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
06-30 13:53:08.258  6822  6868 I bt-btif : execute storage request event : 3
06-30 13:53:08.258  6822  6868 D bt-btif : btif_storage_get_adapter_property property->type:1 
06-30 13:53:08.258  6822  6868 D bt-btif : in, bd addr:, prop type:1, len:512
06-30 13:53:08.258  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 13:53:08.260   848   848 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
06-30 13:53:08.260   848   848 D BluetoothManagerService: Stored Bluetooth name: G3s-1
,06-30 13:53:08.263  6822  6868 D BluetoothAdapterProperties: Name is: G3s-1
06-30 13:53:08.264  6822  6822 D BluetoothAdapterService: getAdapterService() - Service not available
06-30 13:53:08.264  6822  6822 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
06-30 13:53:08.265  6822  6822 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
06-30 13:53:08.266  6822  6822 D BluetoothAdapterService(463835660): onBind()
06-30 13:53:08.267  6869  6869 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
06-30 13:53:08.267  6869  6869 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
06-30 13:53:08.267  6869  6869 I LGFTMITEM: [GET_FTM][id=8], offset=16384
06-30 13:53:08.268  6869  6869 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
06-30 13:53:08.270  6822  6822 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
06-30 13:53:08.271  6822  6822 D BluetoothRadioManager: onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
06-30 13:53:08.276  6822  6864 D BluetoothRadioManager: Message: 40
06-30 13:53:08.276  6822  6864 D BluetoothRadioManager: MESSAGE_RADIO_SERVICE_CONNECTED: 1
06-30 13:53:08.276  6822  6864 D BluetoothRadioManager:  Turning on BT modules Radio on = false
,06-30 13:53:08.281  6822  6822 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:53:08.283  6822  6822 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:08.283  6869  6869 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
06-30 13:53:08.283  6869  6869 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
06-30 13:53:08.285   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
06-30 13:53:08.292   267  1041 I Netd    : M: Get netlink event, ifname: wlan0 action: 5
06-30 13:53:08.293  6748  6748 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
06-30 13:53:08.294   848  1051 D Tethering: InitialState.processMessage what=4
06-30 13:53:08.295   848  1051 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,06-30 13:53:08.300  6778  6778 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
06-30 13:53:08.305  2343  2343 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
06-30 13:53:08.311  2343  6871 D EasyUnlockInitService: Handling intent for initializer IntentService.
,06-30 13:53:08.315  2343  2343 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 13:53:08.343  2343  6871 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,06-30 13:53:08.397   848  1310 D WifiOffDelayIfNotUsed: stopMonitoring
06-30 13:53:08.398  1862  1862 D WfdsService: Supplicant Connection state is changed : false
,06-30 13:53:08.401  1911  1911 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:08.401  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:08.401  1911  1911 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-06-30 13:53:08.401 DNS addrs= 0.0.0.0, 0.0.0.0, 
06-30 13:53:08.401  1911  1911 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
06-30 13:53:08.402   848   848 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
06-30 13:53:08.402  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:08.402   848  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
06-30 13:53:08.402   848  1314 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
06-30 13:53:08.403  2343  2790 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:08.403  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
06-30 13:53:08.403  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 13:53:08.403  1372  1372 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
06-30 13:53:08.403  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
06-30 13:53:08.421  6843  6877 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-30 13:53:08.421  6843  6877 I Babel_SMS: MmsConfig.loadMmsSettings
06-30 13:53:08.423  6843  6877 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 13:53:08.423  6843  6877 I Babel_SMS: MmsConfig.loadFromDatabase
,06-30 13:53:08.475  6843  6877 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-30 13:53:08.475  6843  6877 I Babel_SMS: MmsConfig.loadFromResources
06-30 13:53:08.477  6843  6877 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-30 13:53:08.478  6843  6877 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-30 13:53:08.543  6843  6843 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-30 13:53:08.544  6843  6843 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-30 13:53:08.544  6843  6843 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-30 13:53:08.544  6843  6843 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-30 13:53:08.544  6843  6843 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-30 13:53:08.544  6843  6843 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-30 13:53:08.544  6843  6843 D SensorManager: found sensor: Motion Accel, handle=46
,06-30 13:53:08.578  6843  6859 W art     : Suspending all threads took: 5.639ms
,06-30 13:53:08.601  6843  6859 I art     : CheckpointMarkThreadRoots callback created = 0xaaf5a2d0
,06-30 13:53:08.620  6843  6843 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:08.623  6843  6843 I Babel_Crash: startup - clean
,06-30 13:53:08.643  6843  6859 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,06-30 13:53:08.647  6843  6880 I Babel   : deleted: false for 0
06-30 13:53:08.702   848  2215 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:53:08.702   848  2215 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,06-30 13:53:08.711   848  1051 D BluetoothManagerService: Message: 1
06-30 13:53:08.711   848  1051 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
06-30 13:53:08.712   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:08.712   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:53:08.712   848   848 D Ulp_jni : JNI:system_update. Event-4
06-30 13:53:08.716  6822  6822 D BluetoothAdapterService(463835660): onBind()
06-30 13:53:08.717   848   848 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,06-30 13:53:08.717   848  1051 D BluetoothManagerService: Message: 40
06-30 13:53:08.717   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
06-30 13:53:08.718  6822  6840 I bluedroid: config_hci_snoop_log
06-30 13:53:08.720  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:53:08.721   848  1051 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
06-30 13:53:08.721   848  1051 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
06-30 13:53:08.726  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:08.728  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:08.728  6822  6839 D BluetoothAdapterService(463835660): enable() - Enable called with quiet mode status =  false
06-30 13:53:08.728  6822  6865 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
06-30 13:53:08.728  6822  6865 D BluetoothAdapterProperties: Setting state to 11
06-30 13:53:08.728  6822  6865 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 13:53:08.729  6822  6865 D BluetoothAdapterService(463835660): updateAdapterState() - Broadcasting state to 1 receivers.
,06-30 13:53:08.729   848  1051 D BluetoothManagerService: Message: 60
06-30 13:53:08.729   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,06-30 13:53:08.729   848  1051 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
06-30 13:53:08.729  6822  6865 D BluetoothAdapterService(463835660): processStart()
06-30 13:53:08.729  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: Unable to read settings
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:53:08.730  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 13:53:08.730  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:53:08.730  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:53:08.730  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:53:08.730  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
06-30 13:53:08.730  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:53:08.731  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
06-30 13:53:08.731  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:53:08.731  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
06-30 13:53:08.731  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:53:08.731  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
06-30 13:53:08.731  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 13:53:08.731  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.f,tp.FTPService
06-30 13:53:08.731  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:08.731  6822  6865 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
06-30 13:53:08.732  1862  1862 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:08.732  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:08.733  6822  6865 D BluetoothAdapterService(463835660): processStart() - Make Bond State Machine
06-30 13:53:08.733  6822  6865 D BluetoothBondStateMachine: make
06-30 13:53:08.735  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:08.735  6716  6716 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
06-30 13:53:08.736  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 13:53:08.736  1372  1372 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
06-30 13:53:08.737  6822  6865 D BluetoothAdapterService: setAdapterService() - set to: null
06-30 13:53:08.737  6822  6883 I BluetoothBondStateMachine: StableState(): Entering Off State
06-30 13:53:08.737  6822  6865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:08.737  6822  6865 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
06-30 13:53:08.741  6755  6755 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:53:08.741  6755  6755 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:53:08.741  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:08.742  6822  6822 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:53:08.742  6822  6822 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:08.742  6822  6822 V BluetoothPbapReceiver: ***********state = 11
,06-30 13:53:08.744  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:08.744  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.744  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: Unable to read settings
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:08.745  6822  6865 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:53:08.745  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.745  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
06-30 13:53:08.752  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:08.752  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:53:08.752  6822  6822 D HeadsetService: Received start request. Starting profile...
06-30 13:53:08.752  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 13:53:08.752  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 13:53:08.752  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
06-30 13:53:08.752  6822  6822 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 13:53:08.755  6822  6822 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:53:08.756  6822  6822 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 13:53:08.756  6822  6822 D HeadsetStateMachine: make
,06-30 13:53:08.762  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:08.762  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
06-30 13:53:08.762  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:53:08.762  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-30 13:53:08.762  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
06-30 13:53:08.772  6843  6843 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,06-30 13:53:08.787  6843  6843 W AudioCapabilities: Unsupported mime audio/adpcm
,06-30 13:53:08.789  6716  6716 D BluetoothPermissionRequest: onReceive
06-30 13:53:08.801  6822  6822 D HeadsetStateMachine: max_hf_connections = 1
06-30 13:53:08.801  6822  6822 I bluedroid: get_profile_interface handsfree
06-30 13:53:08.801  6822  6822 I bt-btif : btif_hf_get_interface
06-30 13:53:08.801  6822  6822 I bt-btif : init
06-30 13:53:08.801  6822  6822 D bt-btif : max_hf_clients = 1
06-30 13:53:08.801  6822  6822 D bt-btif : btif_max_hf_clients = 1
06-30 13:53:08.801  6822  6822 D bt-btif : btif_enable_service: current services:0xa067f330
06-30 13:53:08.803  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:08.805  6822  6822 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
06-30 13:53:08.806   273  1632 V AudioPolicyService: registerClient() client 0xb40274e0, uid 1002
,06-30 13:53:08.807   273   273 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
06-30 13:53:08.808  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:08.808  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:53:08.808  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:53:08.808  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-30 13:53:08.808  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
06-30 13:53:08.809   273   273 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:53:08.809   273   273 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:53:08.812   273  1632 V AudioFlinger: registerClient() client 0xb3848058, pid 6822
06-30 13:53:08.812   273  1632 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-30 13:53:08.812   273  1632 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-30 13:53:08.812   273  1632 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
06-30 13:53:08.812  6822  6822 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
06-30 13:53:08.813  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:08.813  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
06-30 13:53:08.814  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:53:08.814  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
06-30 13:53:08.814  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
06-30 13:53:08.814  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:08.814  6843  6843 W AudioCapabilities: Unsupported mime audio/g726
06-30 13:53:08.816  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:08.817   273  1294 V AudioFlinger: thread 0xb56eb000 type 0 TID 1294 waking up
06-30 13:53:08.817   273  1292 V AudioFlinger: thread 0xb5651000 type 0 TID 1292 waking up
06-30 13:53:08.817   273  1298 V AudioFlinger: thread 0xb5735000 type 0 TID 1298 waking up
06-30 13:53:08.818   273  1292 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 13:53:08.818   273  1298 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 13:53:08.818   273  1294 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 13:53:08.818   273  1298 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
06-30 13:53:08.818   273  1292 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
06-30 13:53:08.818   273  1294 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
06-30 13:53:08.819   273  1294 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.819   273  1294 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.819   273  1294 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
06-30 13:53:08.819  6822  6839 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.819  6822  6839 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
06-30 13:53:08.819  1372  1400 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.819   273  1292 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.819   273  1292 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.820   273  1292 V AudioFlinger: processConfigEve,nts_l() DONE thread 0xb5651000
06-30 13:53:08.820   273  1298 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.820   273  1298 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.820   273  1298 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
,06-30 13:53:08.820  6822  6822 V ToneGenerator: Create Track: 0xb4909480
06-30 13:53:08.821  6822  6822 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
06-30 13:53:08.821  6822  6822 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
06-30 13:53:08.821  6822  6839 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.821  6822  6839 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
06-30 13:53:08.821  6822  6839 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.821  6822  6839 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
06-30 13:53:08.821   273  1362 I AudioFlinger: isAudioPlaybackHookOn() false
06-30 13:53:08.821  6822  6822 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
,06-30 13:53:08.822   848  1637 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.822   848  1637 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.822   848  1637 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.822   848  1637 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.822   848  1637 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.822   848  1637 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.822  2028  2052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.823  2028  2052 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.823  2028  2052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.823  2028  2052 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.823  2028  2052 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.823  2028  2052 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.823  3113  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.823  3113  3128 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.824  3113  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.824  1779  2336 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.824  3113  3128 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.824  1779  2336 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.824  6843  6843 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 13:53:08.824  3113  3128 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.824  1779  2336 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.824  3113  3128 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.824  1779  2336 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.824  1779  2336 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.824  1779  2336 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.824  1372  1400 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.822  2097  3941 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
06-30 13:53:08.824  2097  3941 V AudioSystem: ioConfigChanged() opening already existing output! 4
06-30 13:53:08.825  1372  1400 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.825  1372  1400 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.825  1372  1400 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.825  1372  1400 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.825  2097  3941 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
06-30 13:53:08.825  2097  3941 V AudioSystem: ioConfigChanged() opening already existing output! 2
06-30 13:53:08.825  2097  3941 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
06-30 13:53:08.825  2097  3941 V AudioSystem: ioConfigChanged() opening already existing output! 6
06-30 13:53:08.826  6843  6843 W AudioCapabilities: Unsupported mime audio/wma-voice
06-30 13:53:08.828   273  1632 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
06-30 13:53:08.829   273  1632 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
06-30 13:53:08.829   273  1632 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
06-30 13:53:08.829   273  1632 V AudioPolicyManagerEx: getOutput() returns output 2
06-30 13:53:08.829  6822  6822 V AudioSystem: getLatency() output 2, latency 50
06-30 13:53:08.829  6822  6822 V AudioSystem: getFrameCount() output 2, frameCount 960
06-30 13:53:08.830  6822  6822 V AudioTrack: createTrack_l() output 2 afLatency 50
06-30 13:53:08.830  6822  6822 V AudioTrack: Create normal PCM 0x1 Track
06-30 13:53:08.830   273  1362 V AudioFlinger: createTrack() lSessionId: 23
06-30 13:53:08.830   273  1362 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
06-30 13:53:08.830  6843  6843 W VideoCapabilities: Unsupported mime video/mjpg
06-30 13:53:08.830   273  1362 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
06-30 13:53:08.831   273  1292 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 13:53:08.832   273  1292 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
,06-30 13:53:08.832  6822  6822 V AudioTrack: Flags here  0x4 
06-30 13:53:08.832  6822  6822 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
06-30 13:53:08.833   273  1632 V AudioFlinger: acquiring 23 from 6822, for 6822
06-30 13:53:08.833   273  1632 V AudioFlinger:  added new entry for 23
06-30 13:53:08.833  6822  6822 V ToneGenerator: ToneGenerator INIT OK, time: 182229
06-30 13:53:08.833  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:08.834  6822  6885 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
06-30 13:53:08.834  6822  6885 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:53:08.834  6822  6885 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:53:08.837  6822  6885 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
06-30 13:53:08.839   273  1362 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6822
06-30 13:53:08.848  6843  6843 W VideoCapabilities: Unsupported mime video/theora
,06-30 13:53:08.870   273  1362 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
06-30 13:53:08.870   273  1362 V voice   : voice_set_parameters: enter: bt_samplerate=8000
06-30 13:53:08.870   273  1362 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
06-30 13:53:08.870   273  1362 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 13:53:08.870   273  1362 V voice   : voice_set_parameters: exit with code(0)
06-30 13:53:08.870   273  1362 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
06-30 13:53:08.870   273  1362 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
06-30 13:53:08.871   273  1362 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 13:53:08.871   273  1362 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 13:53:08.871   273  1362 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-30 13:53:08.871   273  1362 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 13:53:08.871  6822  6885 V ToneGenerator: ToneGenerator destructor
06-30 13:53:08.871  6822  6885 V ToneGenerator: stopTone
06-30 13:53:08.871  6822  6885 V ToneGenerator: Delete Track: 0xb4909480
,06-30 13:53:08.873  6822  6885 V AudioTrack: ~AudioTrack, releasing session id from 6822 on behalf of 6822
06-30 13:53:08.874   273  1302 V AudioFlinger: releasing 23 from 6822 for 6822
06-30 13:53:08.874   273  1302 V AudioFlinger:  decremented refcount to 0
06-30 13:53:08.874   273  1302 V AudioFlinger: purging stale effects
06-30 13:53:08.874   273  1302 V AudioFlinger: remove track (4099) and delete from mixer
06-30 13:53:08.874   273  1302 V AudioPolicyService: AudioCommandThread() adding release output 2
06-30 13:53:08.874   273  1302 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
06-30 13:53:08.874   273  1062 V AudioPolicyService: AudioCommandThread() waking up
06-30 13:53:08.874   273  1062 V AudioPolicyService: AudioCommandThread() processing release output 2
06-30 13:53:08.874   273  1062 V AudioPolicyManager: releaseOutput() 2
06-30 13:53:08.874   273  1062 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 13:53:08.874  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:08.874  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
06-30 13:53:08.874  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:53:08.875  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
06-30 13:53:08.875  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
06-30 13:53:08.875   273  1302 V AudioFlinger: PlaybackThread::Track destructor
06-30 13:53:08.875   273  1302 V AudioFlinger: removeClient_l() pid 6822, calling pid 273
06-30 13:53:08.915  6843  6843 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 13:53:08.924  6843  6843 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:53:08.925  6843  6843 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:08.932  6843  6843 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-30 13:53:08.933  6843  6843 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:53:08.934  6843  6843 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 13:53:08.948  6843  6843 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-30 13:53:08.964  6843  6843 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 13:53:08.974  6843  6843 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:08.976  6843  6843 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:08.981  6843  6843 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:08.988  6843  6843 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 13:53:09.016   848  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:53:09.018  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
06-30 13:53:09.020   848  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:09.025  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:09.026  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:09.026  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
06-30 13:53:09.027   848   848 D LocSvc_java: onReceive
06-30 13:53:09.027   848   848 D LocSvc_java: got connectivity action
06-30 13:53:09.027   848   848 D LocSvc_java: broadcast - no network connections
,06-30 13:53:09.027   848   848 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
06-30 13:53:09.027   848   848 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
06-30 13:53:09.028   848   848 D LocSvc_java: onReceive
06-30 13:53:09.028   848   848 D LocSvc_java: got connectivity action
06-30 13:53:09.028   848   848 D LocSvc_java: broadcast - no network connections
06-30 13:53:09.028   848   848 D LocSvc_java: Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
06-30 13:53:09.028   848   848 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
06-30 13:53:09.028   848   848 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-30 13:53:09.028   848   848 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-30 13:53:09.028   848   848 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 13:53:09.028   848   848 D LocSvc_java: getAGpsConnectionInfo connType - 4
06-30 13:53:09.028   848   848 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
06-30 13:53:09.028   848   848 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
06-30 13:53:09.029  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:09.031  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:09.039   848   898 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:09.052   848  2176 I art     : Explicit concurrent mark sweep GC freed 63415(3MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 2.688ms total 232.007ms
,06-30 13:53:09.056   848   898 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:09.063  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.065  6822  6822 D A2dpService: Received start request. Starting profile...
06-30 13:53:09.066  6822  6822 I BluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 13:53:09.066  6822  6822 V Avrcp   : make
06-30 13:53:09.067  6822  6822 D Avrcp   : [BTUI] Use Native AVRCP : init jni
06-30 13:53:09.067  6822  6822 I bluedroid: get_profile_interface avrcp
06-30 13:53:09.067  6822  6822 I bt-btif : btif_rc_get_interface
06-30 13:53:09.067  6822  6822 I bt-btif : ## init ##
,06-30 13:53:09.069  6822  6822 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
06-30 13:53:09.070  6822  6822 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 13:53:09.070  6822  6822 I LGBluetoothAvrcpServiceJni: initNative: succeeds
06-30 13:53:09.072  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:09.072  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:53:09.072  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:53:09.072  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
06-30 13:53:09.072  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
06-30 13:53:09.072  6822  6822 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
06-30 13:53:09.073  6843  6843 I vclib   : onServiceConnected
06-30 13:53:09.073  6843  6843 W Babel   : Attempted to change video mute state without an active call.
06-30 13:53:09.082  6822  6822 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
06-30 13:53:09.083  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:09.083  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:53:09.083  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:53:09.083  6822  6865 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 13:53:09.083  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,06-30 13:53:09.101  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:09.101  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
06-30 13:53:09.101  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 13:53:09.101  6822  6865 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
06-30 13:53:09.101  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
,06-30 13:53:09.112   848   898 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:53:09.115   848   898 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:53:09.131  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:09.131  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
06-30 13:53:09.131  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:09.131  6822  6865 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
06-30 13:53:09.131  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
,06-30 13:53:09.135  2028  2028 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,06-30 13:53:09.139  6822  6865 V LGMDMManager: Create singleton instance
06-30 13:53:09.140  6716  6716 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
06-30 13:53:09.140  6716  6716 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
06-30 13:53:09.140  6716  6716 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
06-30 13:53:09.140  6716  6716 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
06-30 13:53:09.142  6843  6843 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
06-30 13:53:09.142  6716  6716 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
06-30 13:53:09.160  6822  6865 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,06-30 13:53:09.215  6716  6716 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,06-30 13:53:09.215  6716  6716 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
06-30 13:53:09.215  6716  6716 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
06-30 13:53:09.215  6716  6716 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
06-30 13:53:09.215  6716  6716 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,06-30 13:53:09.218  6716  6716 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
06-30 13:53:09.228   848  1899 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
06-30 13:53:09.228   848  1899 E AudioService: No RCC entry present to update
,06-30 13:53:09.229  6822  6822 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
06-30 13:53:09.230  6822  6822 I BluetoothA2dpServiceJni: classInitNative
06-30 13:53:09.230  6822  6822 I BluetoothA2dpServiceJni: classInitNative: succeeds
06-30 13:53:09.230  6822  6822 D A2dpStateMachine: make
06-30 13:53:09.231  6822  6822 I bluedroid: get_profile_interface a2dp
06-30 13:53:09.231  6822  6822 I bt-btif : btif_av_get_src_interface
06-30 13:53:09.231  6822  6822 I bt-btif : init
06-30 13:53:09.231  6822  6822 D bt-btif : btif_enable_service: current services:0xa067f330
06-30 13:53:09.233  6822  6822 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
06-30 13:53:09.233  6822  6822 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
06-30 13:53:09.234  6822  6822 D LGBluetoothPowerControlManager: [BTUI] getInstance
06-30 13:53:09.235  6822  6822 D LGBluetoothPowerControlManager: [BTUI] init
06-30 13:53:09.265   848   866 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6895 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-30 13:53:09.267  6822  6822 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
06-30 13:53:09.304   848  1051 D BluetoothManagerService: Message: 30
,06-30 13:53:09.307  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.307  6822  6894 D A2dpStateMachine: Enter Disconnected: -2
06-30 13:53:09.308  6822  6822 I BluetoothHidServiceJni: classInitNative: succeeds
06-30 13:53:09.310  6822  6822 D HidService: Received start request. Starting profile...
06-30 13:53:09.310  6822  6822 I bluedroid: get_profile_interface hidhost
06-30 13:53:09.311  6822  6822 I bt-btif : btif_hh_get_interface
06-30 13:53:09.311  6822  6822 I bt-btif : init
06-30 13:53:09.311  6822  6822 D bt-btif : btif_enable_service: current services:0xa067f330
06-30 13:53:09.311  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.311  6822  6822 D HeadsetStateMachine: Proxy object connected
06-30 13:53:09.312  6822  6822 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
06-30 13:53:09.312  6822  6822 I BluetoothHealthServiceJni: classInitNative: succeeds
06-30 13:53:09.314  6822  6822 D HealthService: Received start request. Starting profile...
06-30 13:53:09.316  6822  6822 I bluedroid: get_profile_interface health
06-30 13:53:09.316  6822  6822 I bt-btif : btif_hl_get_interface
06-30 13:53:09.316  6822  6822 I bt-btif : init
06-30 13:53:09.316  6822  6822 D bt-btif : Process name (droid.bluetooth)
06-30 13:53:09.316  6822  6822 D bt-btif : btif_hl_soc_thread_init
06-30 13:53:09.316  6822  6822 D bt-btif : create_thread: entered
06-30 13:53:09.316  6822  6822 D bt-btif : create_thread: thread created successfully
06-30 13:53:09.316  6822  6906 D bt-btif : entered btif_hl_select_thread
06-30 13:53:09.316  6822  6906 D bt-btif : btif_hl_select_wakeup_init
06-30 13:53:09.316  6822  6906 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
06-30 13:53:09.316  6822  6906 D bt-btif : max_s=55 
06-30 13:53:09.317  6822  6906 D bt-btif : set curr_set = org_set 
06-30 13:53:09.317  6822  6822 I LGBluetoothHealthServiceJni: classInitNative: succeeds
06-30 13:53:09.317  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.318  6822  6822 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,06-30 13:53:09.320  6822  6822 D PanService: Received start request. Starting profile...
06-30 13:53:09.321  6822  6822 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 13:53:09.321  6822  6822 I bluedroid: get_profile_interface pan
06-30 13:53:09.321  6822  6822 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
,06-30 13:53:09.327  6822  6822 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
06-30 13:53:09.327  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.328  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.328  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.328  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
06-30 13:53:09.328  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.328  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.328  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.328  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.328  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.331  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.333  6822  6822 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
06-30 13:53:09.338  6822  6822 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:53:09.339  6822  6822 D BtGatt.GattService: Received start request. Starting profile...
06-30 13:53:09.339  6822  6822 D BtGatt.GattService: start()
,06-30 13:53:09.339  6822  6822 I bluedroid: get_profile_interface gatt
06-30 13:53:09.339  6822  6822 D BtGatt.AdvertiseManager: advertise manager created
06-30 13:53:09.345  6822  6822 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
06-30 13:53:09.345  6822  6822 D LGBluetoothGattAdapter: setGattService:  set to: null
06-30 13:53:09.345  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.347  6822  6885 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:53:09.347  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.347  6822  6885 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 13:53:09.347  6822  6822 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
06-30 13:53:09.348  6822  6885 D HeadsetStateMachine: Disconnected process message: 11, size: 0
06-30 13:53:09.348  6822  6822 V BluetoothMapService: BluetoothMapBinder()
06-30 13:53:09.349  6822  6822 D BluetoothMapService: Received start request. Starting profile...
06-30 13:53:09.349  6822  6822 D BluetoothMapService: start()
06-30 13:53:09.355  6822  6822 D BluetoothMapEmailSettingsLoader: Found 0 applications
06-30 13:53:09.355  6822  6822 D BluetoothMapEmailAppObserver: createReceiver()
,06-30 13:53:09.358  6822  6822 D BluetoothMapEmailAppObserver: initObservers()
06-30 13:53:09.358  6822  6822 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
06-30 13:53:09.366  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
,06-30 13:53:09.370  6822  6822 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
06-30 13:53:09.372  6822  6822 D SapService: Received start request. Starting profile...
06-30 13:53:09.372  6822  6822 D BluetoothSAPServiceJni: initializeNative(L175): sap
06-30 13:53:09.372  6822  6822 I bluedroid: get_profile_interface sap
06-30 13:53:09.372  6822  6822 I bt-btif : btif_sc_get_interface
06-30 13:53:09.372  6822  6822 I bt-btif : init
06-30 13:53:09.372  6822  6822 D bt-btif : btif_enable_service: current services:0xa067f330
06-30 13:53:09.372  6822  6822 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
06-30 13:53:09.372  6822  6822 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
06-30 13:53:09.373  6822  6822 D LGBluetoothSapManager: [BTUI] initSapManager
06-30 13:53:09.375  1779  1779 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
06-30 13:53:09.377  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.390  6822  6822 V BluetoothFTPServiceJni: classInitNative
,06-30 13:53:09.391  6822  6822 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
06-30 13:53:09.391  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.392  6822  6822 D BluetoothFTPService: BluetoothFtpBinder()
06-30 13:53:09.393  6822  6822 D **BluetoothFTPService: Received start request. Starting profile...
06-30 13:53:09.393  6822  6822 V BluetoothFTPService: FTP-Server Service start
06-30 13:53:09.397  6822  6822 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
06-30 13:53:09.397  6822  6822 I bluedroid: get_profile_interface ftp
06-30 13:53:09.397  6822  6822 I bt-btif : btif_fts_get_interface
06-30 13:53:09.397  6822  6822 I bt-btif : init
06-30 13:53:09.397  6822  6822 D bt-btif : btif_enable_service: current services:0xa067f330
06-30 13:53:09.397  6822  6822 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
06-30 13:53:09.397  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.398  6822  6822 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:53:09.398  6822  6822 E BluetoothOPPServiceJni: classInitNative
06-30 13:53:09.398  6822  6822 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
06-30 13:53:09.399  6822  6822 V OppService: Opp initBinder
06-30 13:53:09.399  6822  6822 D **OppService: Received start request. Starting profile...
06-30 13:53:09.400  6822  6822 D OppService: Starting OppService 
06-30 13:53:09.405  6822  6822 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
,06-30 13:53:09.406  6822  6822 V BluetoothOppNotification: send message
06-30 13:53:09.418  6822  6822 D BluetoothOppPreference: Dumping Names:  
06-30 13:53:09.418  6822  6822 D BluetoothOppPreference: {}
06-30 13:53:09.418  6822  6822 D BluetoothOppPreference: Dumping Channels:  
06-30 13:53:09.418  6822  6822 D BluetoothOppPreference: {}
,06-30 13:53:09.422  6822  6822 D OppService: Start()
06-30 13:53:09.422  6822  6822 W BluetoothOPPServiceJni: initOppNative
06-30 13:53:09.422  6822  6822 D BluetoothOPPServiceJni: initOppNative(L383): OPP
06-30 13:53:09.422  6822  6822 I bluedroid: get_profile_interface opp
06-30 13:53:09.422  6822  6822 I bt-btif : btif_op_get_interface
06-30 13:53:09.422  6822  6822 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 2098430
06-30 13:53:09.422  6822  6822 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
06-30 13:53:09.422  6822  6822 I bt-btif : btif_opp_init
06-30 13:53:09.422  6822  6822 D bt-btif : btif_enable_service: current services:0xa067f330
06-30 13:53:09.422  6822  6822 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
06-30 13:53:09.422  6822  6822 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 2098430
06-30 13:53:09.422  6822  6822 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@325b04d2
06-30 13:53:09.422  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:09.424  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.424  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.424  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-30 13:53:09.424  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.424  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.424  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.434  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.434  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-30 13:53:09.437  6822  6921 V OppService: pendingUpdate is :  true
,06-30 13:53:09.438  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.438  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.438  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.438  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
06-30 13:53:09.438  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.438  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.438  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.438  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.438  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.441  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.442  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.442  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.442  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-30 13:53:09.442  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.442  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.442  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.442  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.442  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.444  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.444  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.444  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.444  6822  6921 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
06-30 13:53:09.444  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
06-30 13:53:09.445  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.445  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.445  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.445  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.445  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.446  6822  6918 V OppService: Deleted complete outbound shares, number =  0
06-30 13:53:09.447  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.448  6822  6822 V PanService: [BTUI] SIM Extra State :ABSENT
06-30 13:53:09.448  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.448  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.448  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.Gatt,Service, state=12, doUpdate=true
06-30 13:53:09.448  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.448  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.448  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.449  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.449  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.449  6822  6921 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3372c859 on behalf of 
06-30 13:53:09.452  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.452  6822  6822 V BluetoothMapService: Handler(): got msg=1
06-30 13:53:09.454  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.454  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.454  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
06-30 13:53:09.454  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.454  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.454  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.454  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.454  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,06-30 13:53:09.457  6822  6921 V BluetoothOppNotification: update too frequent, put in queue
06-30 13:53:09.468  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:53:09.469  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,06-30 13:53:09.471  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:09.473  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.474  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.474  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.474  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
06-30 13:53:09.474  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.474  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.474  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.474  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.474  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.474  6822  6921 V OppService: pendingUpdate is :  false
06-30 13:53:09.474  6822  6921 E OppService: UpdateThread is Completed
06-30 13:53:09.475  6822  6918 V OppService: Deleted complete inbound failed shares, number = 0
06-30 13:53:09.476  6822  6918 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
06-30 13:53:09.476  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:09.476  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.476  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.477  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.477  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
06-30 13:53:09.477  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.477  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.477  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.477  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.477  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.478  6822  6918 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ec09c1e on behalf of 
06-30 13:53:09.480  6822  6822 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
06-30 13:53:09.480  6822  6822 V BluetoothOppNotification: new notify threadi!
06-30 13:53:09.480  6822  6822 V BluetoothOppNotification: send delay message
06-30 13:53:09.481  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:09.481  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:09.481  6822  6822 D Bluetoo,thAdapterService(463835660): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
06-30 13:53:09.481  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:09.481  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:09.481  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:09.481  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:09.481  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
06-30 13:53:09.481  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - All profile services started.
06-30 13:53:09.481  6822  6822 D BluetoothA2dp: Proxy object connected
06-30 13:53:09.481  6822  6822 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@34c7ccff
06-30 13:53:09.481  6822  6822 V OppService: ContentObserver received notification
06-30 13:53:09.482  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:09.482  6822  6865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
06-30 13:53:09.483  6822  6822 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:53:09.483  6822  6822 V OppService: ContentObserver received notification
06-30 13:53:09.483  6822  6865 I bluedroid: enable
06-30 13:53:09.483  6822  6865 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
06-30 13:53:09.483  6822  6865 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
06-30 13:53:09.484  6822  6865 I bt_hci_bdroid: init
06-30 13:53:09.484  6822  6865 I bt_vendor: init
06-30 13:53:09.484  6822  6865 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
06-30 13:53:09.484  6822  6865 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
06-30 13:53:09.485  6822  6822 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:09.485  6822  6924 V OppService: pendingUpdate is :  true
06-30 13:53:09.485  6822  6924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,06-30 13:53:09.486  6822  6865 I bt-btif : libbt-hci init returns 0
06-30 13:53:09.486  6822  6923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-30 13:53:09.487  6822  6925 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
06-30 13:53:09.487  6822  6925 I bt-btu  : btu_task pending for preload complete event
06-30 13:53:09.489  6822  6924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25c22acc on behalf of 
06-30 13:53:09.490  6822  6923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@227e9115 on behalf of 
06-30 13:53:09.490  6778  6778 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
06-30 13:53:09.494  6822  6923 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 13:53:09.496  2343  2343 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
06-30 13:53:09.496  6822  6924 V OppService: pendingUpdate is :  false
06-30 13:53:09.496  6822  6924 E OppService: UpdateThread is Completed
,06-30 13:53:09.499  2343  2343 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 13:53:09.501  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:09.504  6755  6755 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
06-30 13:53:09.504  6755  6755 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:53:09.504  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:09.505  6822  6923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 13:53:09.510  6895  6929 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:53:09.511  6895  6929 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:53:09.515  6822  6923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b565c2a on behalf of 
06-30 13:53:09.516  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,06-30 13:53:09.520  6822  6923 V BluetoothOppNotification: outbound: succ-0  fail-0
06-30 13:53:09.520  6822  6923 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-30 13:53:09.524  6895  6928 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:53:09.524  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:09.526  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 13:53:09.532  6822  6923 V BluetoothOppNotification: outbound notification was removed.
,06-30 13:53:09.532  6822  6923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-30 13:53:09.535  6822  6923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16563a1b on behalf of 
06-30 13:53:09.536  6822  6923 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 13:53:09.536  6822  6923 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
06-30 13:53:09.537  6822  6923 V BluetoothOppNotification: inbound notification was removed.
06-30 13:53:09.537  6822  6923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-30 13:53:09.538  6822  6923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@144d27b8 on behalf of 
06-30 13:53:09.572  6822  6927 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,06-30 13:53:09.576  6822  6927 D bt_userial_vendor: userial_vendor_open():UART is setup
06-30 13:53:09.576  6822  6927 I bt_userial_vendor: device fd = 67 open
06-30 13:53:09.587  6822  6927 D bt_hwcfg: hw_config_cback opcode:0x0c03
06-30 13:53:09.587  6822  6927 D bt_hwcfg: hw_config_cback state=1
,06-30 13:53:09.612  6822  6927 D bt_hwcfg: hw_config_cback opcode:0x0c14
06-30 13:53:09.612  6822  6927 D bt_hwcfg: hw_config_cback state=4
06-30 13:53:09.612  6822  6927 D bt_hwcfg: Chipset Name: BCM4334B0
06-30 13:53:09.612  6822  6927 D bt_hwcfg: Chipset BCM4334B0
,06-30 13:53:09.612  6822  6927 D bt_hwcfg: Target name = [BCM4334B0]
,06-30 13:53:09.613  6822  6927 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
06-30 13:53:09.618  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc45
06-30 13:53:09.618  6822  6927 D bt_hwcfg: hw_config_cback state=2
06-30 13:53:09.622  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-30 13:53:09.622  6822  6927 D bt_hwcfg: hw_config_cback state=3
06-30 13:53:09.622  6822  6927 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-30 13:53:09.648   848  2016 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6934 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:53:09.651  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc2e
06-30 13:53:09.651  6822  6927 D bt_hwcfg: hw_config_cback state=5
06-30 13:53:09.661  6799  6799 V LGMDMManager: Create singleton instance
,06-30 13:53:09.702  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.702  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.704  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.704  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.705  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.705  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.705  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.706  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.706  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.706  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.707  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.707  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.708  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.708  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.709  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.709  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.710  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.710  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.711  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.711  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.712  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.712   848  2176 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:53:09.712  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.712   848  2176 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24f68dbc mBinding = false
06-30 13:53:09.713  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.713  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.714  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.714  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.715  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.716  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.717  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.717  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.718  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.718  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.719  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.719  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.720  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.720  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.720  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.721  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.721  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.721  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.722  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.722  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.723   848  1051 D BluetoothManagerService: Message: 2
06-30 13:53:09.723  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.723  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.724  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.724  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.724  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:09.725  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.725  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.726   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:09.726   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,06-30 13:53:09.726   848   848 D Ulp_jni : JNI:system_update. Event-4
06-30 13:53:09.726  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.727  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.729  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.729  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.730  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.730  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.731  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.731  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.732  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.732  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.733  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.733  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.734  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.734  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.735  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.735  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.736  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.736  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.736  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.737  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.737  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.737  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.738  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.738  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.739  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.739  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.740  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.740  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.741  6799  6799 I AudioManager: getMode name:com.lge.qremote
06-30 13:53:09.741  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.741  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.742  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.742  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.743  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.743  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.744  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.744  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.745  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.745  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.745  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.745  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.746  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.746  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.746  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.746  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.747  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.747  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.748  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.748  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.749  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.749  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.749  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.749  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.750  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.750  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.750  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:09.750  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.750  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.751  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.751  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.752  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.752  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.753  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.753  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.754  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.754  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.755  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.755  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.755  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.755  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.757  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.757  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.757  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:09.757  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.757  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.758  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.758  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.759  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.759  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.760  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:09.760  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.760  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.761  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.761  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.762  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.762  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.763  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.763  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.763  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.763  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.764  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.764  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.764  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.764  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.765  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.765  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.766  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.766  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.767  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.767  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.769  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.769  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.770  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:09.770  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.770  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.770  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.772  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.772  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.773  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.773  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.773  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.773  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.774  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.774  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.775  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.775  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.776  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.776  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.776  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:09.776  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.777  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.777  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.778  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.778  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.778  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.778  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.780  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.780  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.781  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.781  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.783  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.783  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.783  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:53:09.784  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.784  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.784  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:53:09.785  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.785  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.785  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:09.786  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.786  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.786  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.786  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.787  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.787  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.788  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.788  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.789  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.789  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.789  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.789  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.790  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.790  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.790  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.790  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.790  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:09.791  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.791  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.792  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.792  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.793  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.793  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.794  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.794  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.795  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.795  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.796  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.796  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.796  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.796  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.797  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.797  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.798  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.798  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.799  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.799  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.800  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.800  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.801  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.801  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.801  6895  6953 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:53:09.802  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.802  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.803  6934  6934 D UEI.SmartControl: Quickset Services start...
06-30 13:53:09.803  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.803  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.804  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.804  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.805  6895  6954 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:53:09.806  6895  6954 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:53:09.806  6934  6934 I UEI.SmartControl: Manufacture = LGE
06-30 13:53:09.806  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.806  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.807  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.807  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.808  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.808  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.809  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.809  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.810  6934  6934 D UEI.SmartControl: File observer start...
06-30 13:53:09.810  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.810  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.811  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.811  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.812  6934  6934 E UEI.SmartControl: IR Port is disabled: false
06-30 13:53:09.812  6934  6934 D UEI.SmartControl: Starting file observer...
06-30 13:53:09.812  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.812  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.812  6934  6934 D UEI.SmartControl: Extracting JNI libs...
06-30 13:53:09.813  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.813  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.814  6934  6934 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
06-30 13:53:09.814  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.814  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.815  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.815  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.816  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.816  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.817  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.817  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.819  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.819  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.819  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.819  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.820  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.820  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.821  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.821  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.822  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.822  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.823  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.823  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.824  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.824  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.825  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.825  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.825  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.826  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.826  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.826  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.827  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.827  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.828  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.828  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.829  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.829  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.831  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.831  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.832  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.832  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.833  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.833  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.833  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.833  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.834  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.834  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.835  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.835  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.835  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.835  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.836  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.836  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.837  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.837  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.838  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.838  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.839  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.839  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.840  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.840  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.841  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.841  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.842  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.842  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.844  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.844  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.845  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.845  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.845  6329  6329 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
06-30 13:53:09.846  6329  6329 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
06-30 13:53:09.846  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.846  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.847  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.847  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.848  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.848  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.849  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.849  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.850  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.850  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.851  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.851  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.851  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.852  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.852  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.853  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.854  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.854  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.856  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.856  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.856  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.856  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.857  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.857  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.858  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.858  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.859  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.859  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.860  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:09.860  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.860  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.860  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.861  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.861  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.861  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.861  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.862  6329  6329 V [BNRBootReceiver]: Boot Receiver Return
06-30 13:53:09.862  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.862  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.863  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.863  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.863  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.864  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.864  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.864  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.865  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.865  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.865  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.865  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.867  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.867  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.868  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.868  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.868  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.869  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.869  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.869  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.869  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
06-30 13:53:09.870  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.870  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.871  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.871  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.871  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.871  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.872  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.872  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.872  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.872  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.873  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.873  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.873  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.873  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.874  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.874  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.874  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.874  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.875  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.875  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.875  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:09.875  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.875  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.876  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.876  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.877  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.877  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.879  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.879  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.880  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.880  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.880  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.880  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.881  6755  6755 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
06-30 13:53:09.881  6755  6755 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:53:09.881  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:09.881  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.881  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.882  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.882  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.883  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.883  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.884  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.884  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.885  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.885  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.886  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.886  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.887  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.887  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.888  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.888  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.889  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.889  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.891  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.891  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.891  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:09.892  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.892  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.893  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.893  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.893  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.893  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.894  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.894  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.895  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.895  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.896  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.896  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.896  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.897  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.897  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:09.897  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.897  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.898  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.898  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.899  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.899  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.899  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
06-30 13:53:09.899  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.899  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.900  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.900  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.902  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.902  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.903  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.903  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.904  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.904  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.905  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.905  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.906  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.906  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.907  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.907  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.908  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.908  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.909  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.909  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.910  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.910  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.911  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.911  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.911  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.911  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.912  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:53:09.912  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.912  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.912  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:53:09.913  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.913  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.914  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:09.914  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.914  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.915  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.915  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.916  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.916  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.916  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:09.917  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.917  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.918  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.918  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.919  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.919  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.919  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.919  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.920  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.920  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.920  6716  6716 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
06-30 13:53:09.921  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.921  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.922  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.922  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.923  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.923  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.924  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.924  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.924  6895  6957 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:53:09.925  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.925  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.925  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.925  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.926  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.926  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.926  6716  6716 D WiFiOffLoadBroadcast: MCCMNC not supported: null
06-30 13:53:09.928  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.928  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.929  6755  6755 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
06-30 13:53:09.929  6755  6755 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
06-30 13:53:09.929  6755  6755 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,06-30 13:53:09.931  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.931  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.932  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.932  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.933  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.933  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.934  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.934  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.935  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.935  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.936  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.936  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.937  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.937  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.937  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.937  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.938  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.938  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.939  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.939  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.940  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.940  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.941  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.941  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.942  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:09.942  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.943  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.943  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.944  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.944  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.945  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.945  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.946  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.946  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.947  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.947  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.948  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.948  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.949  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.949  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.950  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.950  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.951  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.951  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.952  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.952  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.952  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.952  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.953  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.953  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.954  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.954  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.954  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.954  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.956  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.956  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.957  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:09.957  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.958  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.958  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.959  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.959  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.960  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.960  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.961  6895  6958 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
06-30 13:53:09.961  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.961  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.961  6895  6958 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:53:09.962  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.962  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.963  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.963  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.963  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.963  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.964  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.964  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.965  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.965  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.966  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.966  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.966  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.966  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.968  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.968  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.969  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.969  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.970  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.970  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.971  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.971  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.972  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.972  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.973  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.973  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.974  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.974  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.975  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.975  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.975  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.975  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.976  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.976  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.976  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.976  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.977  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.977  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.978  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.978  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.979  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.979  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.980  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.980  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.981  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.982  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.982  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.982  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.983  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.983  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.983  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.983  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.984  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.984  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.986  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.986  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.987  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.987  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.988  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.988  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.989  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.989  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.991  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.991  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.992  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.992  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.993  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.993  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:09.994  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.994  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.995  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:09.995  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.995   848   865 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6959 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:53:09.996  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.997  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.998  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.998  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:09.999  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:09.999  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.000  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.000  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.001  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.001  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.001  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.001  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.002  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.002  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.002  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.002  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.002  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.002  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.003  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.003  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:10.003  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.003  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.003  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.003  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.004  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.004  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.005  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.005  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.005  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.005  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:10.005  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.006  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.006  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.006  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.006  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.006  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.007  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.007  6822  6927 D bt_hwcfg: hw_config_cback state=6
,06-30 13:53:10.008  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.008  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.008  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,06-30 13:53:10.008  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.009  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.009  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.010  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.010  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.010  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.010  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.011  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.011  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.011  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.011  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.012  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.012  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.012  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.012  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.013  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.013  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.013  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.013  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.014  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.014  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.014  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.014  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.015  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.015  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.015  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.015  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.015  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.015  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.016  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.016  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.016  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.016  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.017  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.017  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.017  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.017  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.018  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.018  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.018  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
06-30 13:53:10.018  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.018  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc4e
06-30 13:53:10.018  6822  6927 D bt_hwcfg: hw_config_cback state=6
06-30 13:53:10.025  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
,06-30 13:53:10.119  6822  6927 I bt_hwcfg: bt vendor lib: set UART baud 115200
06-30 13:53:10.119  6822  6927 D bt_hwcfg: Settlement delay -- 100 ms
06-30 13:53:10.119  6822  6927 I bt_hwcfg: Setting fw settlement delay to 100 
,06-30 13:53:10.224  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc45
,06-30 13:53:10.224  6822  6927 D bt_hwcfg: hw_config_cback state=2
,06-30 13:53:10.229  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc18
06-30 13:53:10.229  6822  6927 D bt_hwcfg: hw_config_cback state=7
06-30 13:53:10.229  6822  6927 I bt_hwcfg: bt vendor lib: set UART baud 4000000
06-30 13:53:10.229  6822  6927 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
06-30 13:53:10.252  6822  6927 D bt_hwcfg: hw_config_cback opcode:0xfc01
06-30 13:53:10.252  6822  6927 D bt_hwcfg: hw_config_cback state=8
06-30 13:53:10.252  6822  6927 I bt_hwcfg: vendor lib fwcfg completed
06-30 13:53:10.252  6822  6927 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
06-30 13:53:10.252  6822  6925 I bt-btu  : btu_task received preload complete event
,06-30 13:53:10.267  6934  6934 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
06-30 13:53:10.268  6934  6934 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-30 13:53:10.268  6934  6934 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_HCI,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
,06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_OBEX,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_AVCT,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_AVDT,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_AVRC,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_A2D,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_BNEP,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_BTM,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_GAP,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_PAN,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_SAP,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_SDP,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_GATT,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_SMP,2
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_BTIF,3
06-30 13:53:10.269  6822  6925 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
06-30 13:53:10.297  6959  6959 I MusicStore: Database version: 120
,06-30 13:53:10.319  6934  6934 I UEI.SmartControl: --- Selecting new region: 2
,06-30 13:53:10.322  6934  6934 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
06-30 13:53:10.326  6934  6934 D UEI.SmartControl: Platform has CIR...
06-30 13:53:10.326  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.329  6934  6934 D UEI.SmartControl: NO CIR support, need to check package...
06-30 13:53:10.330  6934  6934 I UEI.SmartControl: Model: LG-D722 uses JNI
,06-30 13:53:10.333  6934  6934 D UEI.SmartControl: QS Service created
06-30 13:53:10.353   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:10.360  6934  6934 E UEI.SmartControl: QS start get config
06-30 13:53:10.376   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:10.377   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 13:53:10.377   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:53:10.379  6959  6959 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 13:53:10.412  6934  6934 D UEI.SmartControl: Loading JNI Libs...
06-30 13:53:10.414  6934  6934 D UEI.SmartControl:  configuring local db...
,06-30 13:53:10.424  6822  6925 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
06-30 13:53:10.426  6822  6982 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 13:53:10.426  6822  6868 E bt-btif : warning : media task started media_task_refcnt 1 
,06-30 13:53:10.427  6822  6868 E bt-btif : Calling BTA_HhEnable
,06-30 13:53:10.428  6822  6868 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
06-30 13:53:10.428  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 13:53:10.428  6822  6925 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
06-30 13:53:10.428  6822  6925 W bt-smp  : Plain text(LSB ~ MSB) = 2f 05 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:53:10.428  6822  6925 W bt-smp  : Encrypted text(LSB ~ MSB) = 54 a1 9c a4 d8 63 63 4c 79 75 08 85 8f a2 ca dc 
06-30 13:53:10.428  6822  6868 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
06-30 13:53:10.428  6822  6925 W bt-btm  : Stopping oneshot timer
06-30 13:53:10.429   848   848 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
06-30 13:53:10.430  6822  6868 D BluetoothAdapterProperties: Name is: G3s-1
06-30 13:53:10.430   848   848 D BluetoothManagerService: Stored Bluetooth name: G3s-1
06-30 13:53:10.430  6822  6982 D BT_PROF_AUDIO: created moving average (N=100)
06-30 13:53:10.430  6822  6982 D BT_PROF_AUDIO: reset rate average
06-30 13:53:10.430  6822  6982 W bt-btif : overflow 0, enter 0, exit 0
06-30 13:53:10.431  6822  6868 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:53:10.431  6822  6868 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:53:10.441  6822  6868 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
06-30 13:53:10.441  6822  6868 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
06-30 13:53:10.442  6822  6868 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-30 13:53:10.443  6822  6868 I bt-btif : BTA_JvEnable
06-30 13:53:10.443  6822  6868 E bt-btif : btsock_vendor_hci_init: !vhci_init
06-30 13:53:10.443  6822  6868 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-30 13:53:10.444  6822  6868 D bt-btif : init_hci_slots(L136): in
06-30 13:53:10.444  6822  6868 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,06-30 13:53:10.444  6822  6868 D IOP_DB_BT: db_open: db_open : handle 2691209180l, read 11046 bytes onto local cache
06-30 13:53:10.445  6822  6868 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
06-30 13:53:10.445  6822  6868 D IOP_DB_BT: db_query: result 1
06-30 13:53:10.445  6822  6868 I         : iop_db_open: iop_db_open status 0
06-30 13:53:10.445  6822  6868 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
06-30 13:53:10.445  6822  6868 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
06-30 13:53:10.445  6822  6925 I bt-btif : bta_pan_co_init
06-30 13:53:10.445  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:10.446  6822  6868 D bte_conf: Device ID record 1 : primary
06-30 13:53:10.446  6822  6868 D bte_conf:   vendorId            = 00c4
06-30 13:53:10.446  6822  6868 D bte_conf:   vendorIdSource      = 0001
06-30 13:53:10.446  6822  6868 D bte_conf:   product             = 13a1
06-30 13:53:10.446  6822  6868 D bte_conf:   version             = 1000
06-30 13:53:10.446  6822  6868 D bte_conf:   clientExecutableURL = 
06-30 13:53:10.446  6822  6868 D bte_conf:   serviceDescription  = 
06-30 13:53:10.446  6822  6868 D bte_conf:   documentationURL    = 
06-30 13:53:10.446  6822  6868 D bte_conf: bte_load_did_conf no section named DID2.
06-30 13:53:10.447  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:10.447  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
06-30 13:53:10.448  6822  6868 E bt-btif : btif_hf_upstreams_evt: wrong handle = 8224 
06-30 13:53:10.448  6822  6868 I bt-btif : HAL bt_op_callbacks->opc_state_cb
06-30 13:53:10.448  6822  6868 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
06-30 13:53:10.448  6822  6865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 13:53:10.448  6822  6865 D BluetoothAdapterProperties: ScanMode =  20
06-30 13:53:10.448  6822  6865 D BluetoothAdapterProperties: State =  11
06-30 13:53:10.448  6822  6865 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
06-30 13:53:10.448  6822  6865 D BluetoothAdapterProperties: Setting state to 12
06-30 13:53:10.448  6822  6865 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
06-30 13:53:10.448  6822  6865 D BluetoothAdapterService(463835660): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 13:53:10.449  6822  6865 I BluetoothAdapterState: Entering On State
06-30 13:53:10.449  6822  6865 I BluetoothAdapterState: Entering On State from state = 11
06-30 13:53:10.450  6822  6865 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.450  6822  6865 D BluetoothAdapterService(463835660): isQuetModeEnabled() - Enabled = false
06-30 13:53:10.450  6822  6865 D BluetoothAdapterService(463835660): autoConnect() - Initiate auto connection on BT on...
06-30 13:53:10.450  6822  6865 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 13:53:10.450  6822  6868 D OppService: onOpcStateChange()
06-30 13:53:10.451  6822  6865 D LGBluetoothServiceAdapter: [BTUI] OnState
06-30 13:53:10.451  6822  6865 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
06-30 13:53:10.451  6822  6865 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
06-30 13:53:10.451  6822  6822 D OppService: Recieved MESSAGE_OPC_ENABLE
06-30 13:53:10.452  6822  6822 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
06-30 13:53:10.452  6822  6865 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.452  6822  6865 D BluetoothAdapterService(463835660): isQuetModeEnabled() - Enabled = false
06-30 13:53:10.452  6822  6865 D BluetoothAdapterService(463835660): autoConnect() - Initiate auto connection on BT on...
06-30 13:,53:10.452  6822  6865 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
06-30 13:53:10.452  6822  6868 I bt-btif : HAL bt_op_callbacks->ops_state_cb
06-30 13:53:10.452  6822  6868 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
06-30 13:53:10.452  6822  6868 D OppService: onOpsStateChange() :0
06-30 13:53:10.453  6822  6822 D OppService: Recieved MESSAGE_OPS_ENABLE
06-30 13:53:10.453  6822  6868 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
06-30 13:53:10.453  6822  6868 D BluetoothFTPServiceJni: operation_cmpl_callback(L192):  oper:3 status:0
06-30 13:53:10.453  6822  6868 I BluetoothFTPService: onFtpServerEnabled: /storage
06-30 13:53:10.453  6822  6868 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
06-30 13:53:10.454  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
,06-30 13:53:10.461  6822  6868 D BluetoothAdapterProperties: Scan Mode:21
06-30 13:53:10.461  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 13:53:10.461  6822  6868 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 13:53:10.464  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:10.465  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:10.465  6822  6927 D bt_h4   : vendor lib postload completed
06-30 13:53:10.466  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.467  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 13:53:10.470  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:10.470  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:10.471  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.472  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:10.481  6822  6822 V BluetoothOppNotification: new notify threadi!
06-30 13:53:10.481  6822  6822 V BluetoothOppNotification: send delay message
,06-30 13:53:10.483  6822  6989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
06-30 13:53:10.486  6822  6989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17442991 on behalf of 
06-30 13:53:10.486  6822  6989 V BluetoothOppNotification: mUpdateCompleteNotification = true
06-30 13:53:10.488  6822  6989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
06-30 13:53:10.490  6822  6989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d610f6 on behalf of 
06-30 13:53:10.493  6822  6989 V BluetoothOppNotification: outbound: succ-0  fail-0
,06-30 13:53:10.498  6822  6989 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
06-30 13:53:10.499  6822  6989 V BluetoothOppNotification: outbound notification was removed.
06-30 13:53:10.500  6822  6989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
06-30 13:53:10.500  6822  6989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f945cf7 on behalf of 
06-30 13:53:10.501  6822  6989 V BluetoothOppNotification: inbound: succ-0  fail-0
06-30 13:53:10.502  6822  6989 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
06-30 13:53:10.502  6822  6989 V BluetoothOppNotification: inbound notification was removed.
06-30 13:53:10.502  6822  6989 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
06-30 13:53:10.503  6822  6989 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34890764 on behalf of 
06-30 13:53:10.584   848  1972 I ActivityManager: Process com.google.android.gms.unstable (pid 6458) has died
,06-30 13:53:10.617   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:10.617   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 13:53:10.617   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:53:10.619  6959  6959 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 13:53:10.624   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:10.624   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 13:53:10.624   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:10.625  6959  6959 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 13:53:10.627  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.627   848  1051 D BluetoothManagerService: Sending off request.
06-30 13:53:10.627  6822  6840 D BluetoothAdapterService(463835660): disable() called...
,06-30 13:53:10.628  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.628  6822  6865 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
06-30 13:53:10.628  6822  6865 D BluetoothAdapterProperties: Setting state to 13
06-30 13:53:10.628  6822  6865 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
06-30 13:53:10.628  6822  6865 D BluetoothAdapterService(463835660): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 13:53:10.628  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.628   848  1051 D BluetoothManagerService: Message: 60
06-30 13:53:10.628   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
06-30 13:53:10.629   848  1051 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 10 receivers.
06-30 13:53:10.629  6822  6839 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 13:53:10.629  6822  6865 D BluetoothAdapterProperties: onBluetoothDisable()
06-30 13:53:10.629  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
06-30 13:53:10.629  6822  6865 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
06-30 13:53:10.629  6716  6738 D BluetoothMap: onBluetoothStateChange: up=true
06-30 13:53:10.630  6822  6868 D BluetoothAdapterProperties: Scan Mode:20
06-30 13:53:10.630  6822  6865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
06-30 13:53:10.630  6822  6865 I bt-btif : BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
06-30 13:53:10.630  6822  6865 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
06-30 13:53:10.631  6822  6865 D bt-btif : btsock_ctrl_hci_cleanup(L202): poll handle:4
06-30 13:53:10.631  6822  6865 D IOP_DB_BT: db_close: nbr users 0
06-30 13:53:10.631  6822  6865 D IOP_DB_BT: db_close: free database
06-30 13:53:10.631  6822  6925 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:10.632  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:10.632  6822  6865 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
06-30 13:53:10.632  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:BluezMigrationDone
06-30 13:53:10.632  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
06-30 13:53:10.632  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:BluezMigrationDone
06-30 13:53:10.632  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.632  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:Address
06-30 13:53:10.632  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L3,43): out, key:Adapter, value:Address
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:f8:95:c7:87:85:54
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:Name
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:Name
06-30 13:53:10.633  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:G3s-1
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:��8�\�婓��n�ScanMode
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:ScanMode
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:ScanMode
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:x
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:s!WE�(E��00:0F:F6
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:BMW,Audi,Parrot,Car
,06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
06-30 13:53:10.633  6822  6865 D btif_config_util: enum_config(L344): out, value:00:0F:F6
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6925 W bt-obex : Ignore event 10 in state 1
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
06-30 13:53:10.634  6822  6925 W bt-obex : Ignore event 10 in state 1
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
,06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.634  6822  6925 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:53:10.634  6612  6612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6868 E bt-btif : btif_hf_upstreams_evt: wrong handle = 8224 
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
06-30 13:53:10.634  6822  6868 I bt-btif : HAL bt_op_callbacks->ops_state_cb
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
06-30 13:53:10.634  6822  6868 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:3
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
06-30 13:53:10.634  6822  6868 D OppService: onOpsStateChange() :3
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L344): out, value:$
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
06-30 13:53:10.634  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:Galaxy S6-1
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
06-30 13:53:10.635  6612  6612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
,06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
06-30 13:53:10.635  6822  6822 D OppService: Recieved MESSAGE_OPS_DISABLE
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
06-30 13:53:10.635  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
,06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:A5-1
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
,06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
,06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
,06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:#
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L344): out, value:Nexus 6
06-30 13:53:10.636  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
,06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
,06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
,06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:XT1072
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
,06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
06-30 13:53:10.637  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
,06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
,06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
06-30 13:53:10.638  6716  6716 D BluetoothMap: Proxy object connected
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
06-30 13:53:10.638  6716  6716 D MapProfile: Bluetooth service connected
06-30 13:53:10.638  6716  6716 D BluetoothMap: getConnectedDevices()
,06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
06-30 13:53:10.638  6716  6738 D BluetoothPan: onBluetoothStateChange on: true
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.638  6716  6738 D BluetoothPan: onBluetoothStateChange call bindService
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
,06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:a
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:S5-1
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
06-30 13:53:10.638  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
,06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
06-30 13:53:10.638  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
,06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
06-30 13:53:10.639  6716  6716 D BluetoothMap: Bluetooth is Not enabled
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string,
,06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
,06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:	a
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:G4-1
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
,06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
,06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
06-30 13:53:10.639  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
,06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:a
,06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy S5)
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
,06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
,06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
,06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
06-30 13:53:10.640  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
06-30 13:53:10.641  6716  6737 D BluetoothPbap: onBluetoothStateChange: up=true
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
,06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A5)
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
,06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
06-30 13:53:10.641  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:Thali Test (Galaxy A3)
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
,06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
,06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
,06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:A
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:Thali Test's G2
,06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.642  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks,
,06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
,06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:	a
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
,06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:Note3-1
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
,06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
06-30 13:53:10.643  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
06-30 13:53:10.644  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.644  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
06-30 13:53:10.644  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
06-30 13:53:10.644  1779  1798 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:53:10.644  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
,06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.646  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L344): out, value:HTC Desire 820
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
,06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
,06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
06-30 13:53:10.647  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
,06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
06-30 13:53:10.654  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
,06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
,06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
06-30 13:53:10.655  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
,06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L344): out, value:�h�
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L344): out, value:��h
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:Name, value type:string
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L344): out, value:J���J�hrD�hrD�
,06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L344): out, value:��P
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
06-30 13:53:10.656  6822  6865 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
,06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
,06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L344): out, value:�
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L344): out, value:Galaxy S5-2
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
06-30 13:53:10.657  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
,06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L344): out, value:Z
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L344): out, value:
,06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L344): out, value:
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
06-30 13:53:10.658  6822  6865 D btif_config_util: enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
06-30 13:53:10.664  1779  1779 D BluetoothHeadset: Proxy object connected
,06-30 13:53:10.665   848  1051 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:53:10.665   848   848 D BluetoothHeadset: Proxy object connected
06-30 13:53:10.666  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.666   848  1051 D BluetoothA2dp: onBluetoothStateChange: up=true
06-30 13:53:10.667  1779  2336 D BluetoothHeadset: onBluetoothStateChange: up=true
06-30 13:53:10.667   848   848 D BluetoothA2dp: Proxy object connected
06-30 13:53:10.670  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.673  1779  1779 D BluetoothHeadset: Proxy object connected
06-30 13:53:10.674  1779  1798 D BluetoothHeadset: onBluetoothStateChange: up=true
,06-30 13:53:10.680  1779  1779 D BluetoothHeadset: Proxy object connected
06-30 13:53:10.681   848  1051 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
06-30 13:53:10.681   848  1051 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
06-30 13:53:10.682   848  1051 D BluetoothManagerService: Message: 60
06-30 13:53:10.682   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
06-30 13:53:10.682   848  1051 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
06-30 13:53:10.683  6716  6716 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 13:53:10.683  6716  6716 D PanProfile: Bluetooth service connected
06-30 13:53:10.686  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
,06-30 13:53:10.686   848   848 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
06-30 13:53:10.686   848  1051 D BluetoothManagerService: Message: 40
06-30 13:53:10.686   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
06-30 13:53:10.687  6716  6716 D BluetoothInputDevice: Proxy object connected
06-30 13:53:10.687  6716  6716 D HidProfile: Bluetooth service connected
06-30 13:53:10.688  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
,06-30 13:53:10.713  1862  1862 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.713  1862  2058 D LGBluetoothAPIService: Message: 1
06-30 13:53:10.713  1862  2058 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,06-30 13:53:10.713  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
,06-30 13:53:10.714  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.716  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 13:53:10.716  1372  1372 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
06-30 13:53:10.721  1862  1862 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.722  6822  6822 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.722  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.724  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.724  6612  6678 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:53:10.724  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:53:10.726  6716  6716 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,06-30 13:53:10.726  6716  6716 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
06-30 13:53:10.726  6822  6822 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.726  6822  6822 D BluetoothMapService: STATE_ON
06-30 13:53:10.726  6822  6822 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.726  6822  6822 D BluetoothMapService: STATE_TURNING_OFF
06-30 13:53:10.727  6822  6822 V BluetoothMapService: Handler(): got msg=4
06-30 13:53:10.727  6822  6822 D BluetoothMapService: MAP Service closeService in
06-30 13:53:10.730  6716  6716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:53:10.736  6716  6716 D DockEventReceiver: finishStartingService: stopping service
06-30 13:53:10.749  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.749  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
,06-30 13:53:10.750  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 13:53:10.751  1372  1372 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
06-30 13:53:10.754  6822  6822 D BluetoothMapMasInstance: MAP Service shutdown
06-30 13:53:10.754  6822  6822 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:53:10.754  6822  6822 V BluetoothMapService: MAP Service closeService out
06-30 13:53:10.775  1862  2058 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,06-30 13:53:10.791  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:10.792  6822  6822 V BluetoothPbapService: Pbap Service onCreate
06-30 13:53:10.792  6822  6822 V BluetoothPbapService: Starting PBAP service
,06-30 13:53:10.794  6822  6822 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.794  6934  6934 D UEI.SmartControl:  ---- Has DB8: true
06-30 13:53:10.795  6822  6822 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 13:53:10.796  6822  6822 V BluetoothPbapService: Pbap Service onBind
06-30 13:53:10.797  6822  6822 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.797  6822  6822 V BluetoothPbapService: state: 13
06-30 13:53:10.797  6822  6822 V BluetoothPbapService: Pbap Service closeService in
06-30 13:53:10.798  6716  6716 D BluetoothPbap: Proxy object connected
06-30 13:53:10.798  6822  6822 V BluetoothPbapService: successfully stopped pbap service
06-30 13:53:10.798  6822  6822 V BluetoothPbapService: Pbap Service closeService out
06-30 13:53:10.798  6716  6716 D PbapServerProfile: Bluetooth service connected
06-30 13:53:10.799  6822  6822 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:53:10.799  6822  6822 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.799  6822  6822 V BluetoothPbapReceiver: ***********state = 12
06-30 13:53:10.804  6716  6716 D BluetoothPbap: Proxy object disconnected
06-30 13:53:10.804  6716  6716 D PbapServerProfile: Bluetooth service disconnected
,06-30 13:53:10.811  6822  6822 D LGBluetoothAPIServer: [BTUI] onCreate()
06-30 13:53:10.811  6716  6716 D BluetoothPermissionRequest: onReceive
06-30 13:53:10.811  6822  6822 D LGBluetoothAPIServer: [BTUI] onBind()
06-30 13:53:10.812  6959  6959 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 13:53:10.812  6959  6959 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 13:53:10.815  6716  6716 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 13:53:10.815  6822  6822 V BluetoothPbapService: Pbap Service onDestroy
06-30 13:53:10.815  6822  6822 V BluetoothPbapService: Pbap Service closeService in
,06-30 13:53:10.816  6822  6822 V BluetoothPbapService: Pbap Service closeService out
06-30 13:53:10.816  6822  6822 D LGBluetoothPbapAdapter: [BTUI] cleanup
06-30 13:53:10.816  1862  1862 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
06-30 13:53:10.817  1862  2058 D LGBluetoothAPIService: Message: 100
06-30 13:53:10.817  1862  2058 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,06-30 13:53:10.821  6822  6822 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
06-30 13:53:10.824  6934  6934 D UEI.SmartControl: QS start statue = true Error code = 0
06-30 13:53:10.824  6934  6934 D UEI.SmartControl: QS version = v2.7.11.1_RC1
06-30 13:53:10.825  6934  6934 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-30 13:53:10.828  6934  6934 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
06-30 13:53:10.838  6822  6822 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,06-30 13:53:10.845  6822  6822 V BluetoothSapReceiver: [BTUI] checkServiceStart
06-30 13:53:10.847  6822  6822 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.848   848  1309 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:10.848   848  1309 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:10.885  6934  6934 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-30 13:53:10.885  6934  6934 D irrcClient: IrrcClient ++ 
06-30 13:53:10.885  6934  6934 D irrcClient: getIrrcService ++ 
,06-30 13:53:10.885  6934  6934 D irrcClient: getIrrcService -- 
06-30 13:53:10.885  6934  6934 D irrcClient: IrrcClient -- 
06-30 13:53:10.885  6934  6934 W irrc_jni: IRRCPlayer_nativeInit -- 
06-30 13:53:10.893  6934  6934 D UEI.SmartControl: Services init done
06-30 13:53:10.895  6934  6996 I UEI.SmartControl: Device manager: loading config....
06-30 13:53:10.903  6934  6934 D UEI.SmartControl: QS Service init finished
,06-30 13:53:10.907  6934  6934 D UEI.SmartControl: QS Service version name: 0.1.73
06-30 13:53:10.908  6934  6934 D UEI.SmartControl: QS Service version code: 1073
06-30 13:53:10.909  6934  6996 D UEI.SmartControl: Config is loaded...
06-30 13:53:10.909  2343  2343 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
06-30 13:53:10.917  2343  7001 D EasyUnlockInitService: Handling intent for initializer IntentService.
,06-30 13:53:10.919  2343  2343 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 13:53:10.923  6959  6959 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
06-30 13:53:10.924  6716  6716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:53:10.929  6822  6822 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:53:10.929  6822  6822 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.929  6822  6822 V BluetoothPbapReceiver: ***********state = 13
06-30 13:53:10.931  6822  6822 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,06-30 13:53:10.933  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:10.934  6822  6822 V BluetoothPbapService: Pbap Service onCreate
06-30 13:53:10.934  6822  6822 V BluetoothPbapService: Starting PBAP service
06-30 13:53:10.934  6822  6822 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:10.934  6822  6822 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
06-30 13:53:10.934  6822  6822 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.934  6822  6822 V BluetoothPbapService: state: 13
06-30 13:53:10.934  6822  6822 V BluetoothPbapService: Pbap Service closeService in
06-30 13:53:10.935  6822  6822 V BluetoothPbapService: successfully stopped pbap service
,06-30 13:53:10.935  6822  6822 V BluetoothPbapService: Pbap Service closeService out
06-30 13:53:10.936  6822  6822 V BluetoothPbapService: Pbap Service onDestroy
06-30 13:53:10.936  6822  6822 V BluetoothPbapService: Pbap Service closeService in
06-30 13:53:10.936  6822  6822 V BluetoothPbapService: Pbap Service closeService out
06-30 13:53:10.936  6822  6822 D LGBluetoothPbapAdapter: [BTUI] cleanup
06-30 13:53:10.937  6716  6716 D DockEventReceiver: finishStartingService: stopping service
06-30 13:53:10.941  2343  7001 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
06-30 13:53:10.941  6716  6716 D LGBluetoothAuthorization: [BTUI] cancel All Notification
06-30 13:53:10.941  6716  6716 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
06-30 13:53:10.942  6716  6716 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
06-30 13:53:10.942  6716  6716 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
06-30 13:53:10.943  6716  6716 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
06-30 13:53:10.943  6716  6716 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
06-30 13:53:10.944  6716  6716 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
,06-30 13:53:10.946  6716  6716 D BluetoothPermissionRequest: onReceive
06-30 13:53:10.946  6716  6716 D LGBluetoothAuthorization: [BTUI] cancel All Notification
06-30 13:53:10.946  6716  6716 I NotificationManager: com.android.settings: cancel(17301632) by com.android.settings
06-30 13:53:10.946  6716  6716 I NotificationManager: com.android.settings: cancel(-1000001) by com.android.settings
06-30 13:53:10.947  6716  6716 I NotificationManager: com.android.settings: cancel(-1000011) by com.android.settings
06-30 13:53:10.947  6716  6716 I NotificationManager: com.android.settings: cancel(-1000021) by com.android.settings
06-30 13:53:10.948  6716  6716 I NotificationManager: com.android.settings: cancel(-1000031) by com.android.settings
06-30 13:53:10.948  6716  6716 I NotificationManager: com.android.settings: cancel(-1000041) by com.android.settings
06-30 13:53:10.952  6934  6934 D UEI.SmartControl: Service requested: Control
06-30 13:53:10.954  6822  6822 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
06-30 13:53:10.955  6822  6822 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
06-30 13:53:10.955  6822  6822 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
06-30 13:53:10.955  6822  6822 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
06-30 13:53:10.955  6822  6822 I NotificationManager: com.android.bluetooth: cancel(-1) by com.android.bluetooth
06-30 13:53:10.959  6822  6822 V BluetoothSapReceiver: [BTUI] checkServiceStart
,06-30 13:53:10.961  6822  6822 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:10.967  2343  2343 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
06-30 13:53:10.970  2343  2343 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 13:53:10.992  6934  6995 D UEI.SmartControl:  ----- QS SDK is ready!!!
,06-30 13:53:10.999  6934  6995 I UEI.SmartControl: Notify AllClients services are ready: 0
06-30 13:53:11.002  6934  6934 D UEI.SmartControl: Request IControl service: devices are loaded...
06-30 13:53:11.005  6934  6934 D UEI.SmartControl: Internal service binding...
,06-30 13:53:11.008  6934  6951 D UEI.SmartControl: -----IControl: 11
06-30 13:53:11.009  6934  6951 D UEI.SmartControl: Caller: com.lge.qremote
06-30 13:53:11.010  6934  6951 D UEI.SmartControl: ------------ IControl registerCallback...
06-30 13:53:11.010  6934  6951 I UEI.SmartControl: Registering callback...
06-30 13:53:11.012  6934  6949 D UEI.SmartControl: -----IControl: 19
06-30 13:53:11.013  6934  6949 D UEI.SmartControl: Caller: com.lge.qremote
06-30 13:53:11.013  6934  6949 I UEI.SmartControl: Registering Services Ready callback...
06-30 13:53:11.014  6934  6949 I UEI.SmartControl: Notify client services are ready...
06-30 13:53:11.017  6934  6950 D UEI.SmartControl: -----IControl: 8
06-30 13:53:11.019  6934  6950 D UEI.SmartControl: Caller: com.lge.qremote
,06-30 13:53:11.043  6959  6959 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 13:53:11.043  6959  6959 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@673f3ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 13:53:11.044  6959  6959 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 13:53:11.045  6959  6959 D AndroidMusic: GMSCore installation verified
06-30 13:53:11.052  6959  6959 I ConfigStore: Config Database version: 1
,06-30 13:53:11.118  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-30 13:53:11.119  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:53:11.119  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:53:11.119  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:53:11.119  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:53:11.153   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:53:11.161  6959  6959 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
06-30 13:53:11.168  6959  6959 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-30 13:53:11.191  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:53:11.191  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,06-30 13:53:11.192  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:53:11.192  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:53:11.192  1862  2050 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
06-30 13:53:11.194  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
06-30 13:53:11.194  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:53:11.194  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
06-30 13:53:11.195  6329  6329 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 13:53:11.196   848  1316 D WifiController: battery changed pluggedType: 2
06-30 13:53:11.196  6822  6885 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:53:11.198  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:53:11.203  6959  6973 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1e2b0
,06-30 13:53:11.214   848  1915 I ActivityManager: Killing 6176:com.google.android.apps.plus/u0a86 (adj 15): empty #11
06-30 13:53:11.241  6959  6973 I art     : CheckpointMarkThreadRoots callback created = 0xaaf1e290
,06-30 13:53:11.364   848  1899 W libprocessgroup: failed to open /acct/uid_10086/pid_6176/cgroup.procs: No such file or directory
,06-30 13:53:11.414   848  1059 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7008 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 13:53:11.417   848  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=570302530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=848
,06-30 13:53:11.419   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{24bf90b9 type 2 when 184775 com.google.android.gms} when 184775
06-30 13:53:11.468   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a8fbc5f type 2 when 184778 com.google.android.gms} when 184778
,06-30 13:53:11.490  6959  6959 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-30 13:53:11.526  6959  6959 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 13:53:11.552  7008  7008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:53:11.552  7008  7008 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 13:53:11.555  7008  7008 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:53:11.576   848   865 I ActivityManager: Killing 2097:com.lge.music/u0a28 (adj 15): empty #11
,06-30 13:53:11.590   273   273 V AudioFlinger: 2097 died, releasing its sessions
06-30 13:53:11.591   273   273 V AudioFlinger:  pid 1779 @ 0
06-30 13:53:11.591   273   273 V AudioFlinger:  pid 3113 @ 1
,06-30 13:53:11.591   273   273 V AudioFlinger:  pid 3113 @ 2
06-30 13:53:11.636  6822  6932 W bt_userial: select_read return size <=0:0, exiting userial_read_thread
06-30 13:53:11.636  6822  6925 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:53:11.636  6822  6925 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:53:11.636  6822  6925 W bt-btif : ag scb idx 1 not allocated
06-30 13:53:11.636  6822  6925 E bt-btif : BTA AG is already disabled, ignoring ...
06-30 13:53:11.636  6822  6925 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
06-30 13:53:11.636  6822  6925 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
06-30 13:53:11.637  6822  6925 W bt-btif : ag scb idx 1 not allocated
06-30 13:53:11.637  6822  6925 E bt-btif : BTA AG is already disabled, ignoring ...
06-30 13:53:11.637  6822  6925 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:53:11.637  6822  6925 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
06-30 13:53:11.638  6822  6927 D bt_hwcfg: hw_epilog_process
06-30 13:53:11.639  6822  6868 I bt_userial_vendor: device fd = 67 close
,06-30 13:53:11.646   848  2215 W libprocessgroup: failed to open /acct/uid_10028/pid_2097/cgroup.procs: No such file or directory
06-30 13:53:11.651  6959  6978 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,06-30 13:53:11.656  6822  6868 E bt_vendor: [BTUI] Proto is enabled. Set Proto disable!!
,06-30 13:53:11.729  6612  6678 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:53:11.729  6612  6678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:53:11.730  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:53:11.730  6612  6678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:53:11.730  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f54d265 removed from the list
,06-30 13:53:11.741  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:53:11.741  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@322123eb added. We now have 2 listener(s)
06-30 13:53:11.741  6612  6678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:53:11.742  6612  6678 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:53:11.742  6612  6678 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:53:11.742  6612  6678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:53:11.742  6612  6678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:53:11.742  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@322123eb removed from the list
,06-30 13:53:11.757  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
06-30 13:53:11.757  6612  6678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23d01548 added. We now have 2 listener(s)
06-30 13:53:11.757  6612  6678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:53:11.761  6822  6868 I GKI_LINUX: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 100, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:11.761  6822  6925 W bt-btu  : btu_check_timer_queues_emtpy(btu_cb): timer_queue.p_first: 0xa0779264, timer_queue.p_last: 0xa0779264, last_ticks: 0, p_first->p_cback: 0x0, p_first->event: 0x32, p_first->in_use: 1
06-30 13:53:11.761  6822  6925 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,06-30 13:53:11.764  6822  6868 I GKI_LINUX: GKI_destroy_task(): task [BTU] terminated
06-30 13:53:11.765  6822  6868 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
06-30 13:53:11.765  6822  6865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
06-30 13:53:11.765  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.765  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 13:53:11.765  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.765  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: Unable to read settings
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:11.766  6822  6865 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:53:11.766  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
06-30 13:53:11.766   848   865 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:53:11.766  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
06-30 13:53:11.766   848   865 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24f68dbc mBinding = false
06-30 13:53:11.767   848  1051 D BluetoothManagerService: Message: 2
06-30 13:53:11.767   848  1051 D BluetoothManagerService: Sending off request.
06-30 13:53:11.767  6822  6840 D BluetoothAdapterService(463835660): disable() called...
06-30 13:53:11.767  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:11.767  6822  6840 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
06-30 13:53:11.768   848  1051 E BluetoothManagerService: IBluetooth.disable() returned false
06-30 13:53:11.768  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.768  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
06-30 13:53:11.768  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.768  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSett,ing: com.android.bluetooth.a2dp.A2dpService
06-30 13:53:11.768  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 13:53:11.768  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
06-30 13:53:11.769  6822  6822 D HeadsetService: Received stop request...Stopping profile...
06-30 13:53:11.769  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.769  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
06-30 13:53:11.769  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.769  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 13:53:11.769  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
06-30 13:53:11.769  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
06-30 13:53:11.770  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.770  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
06-30 13:53:11.770  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.770  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 13:53:11.770  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
06-30 13:53:11.770  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
06-30 13:53:11.771  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.771  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
06-30 13:53:11.771  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.771  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 13:53:11.771  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
06-30 13:53:11.771  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
06-30 13:53:11.772  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
,06-30 13:53:11.772  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
06-30 13:53:11.772  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.772  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 13:53:11.772  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
06-30 13:53:11.772  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
06-30 13:53:11.773  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.773  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 13:53:11.773  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.773  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 13:53:11.773  6822  6865 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,06-30 13:53:11.773  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
06-30 13:53:11.773  6822  6822 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:53:11.774  6822  6885 D HeadsetStateMachine: Exit Disconnected: -1
06-30 13:53:11.774  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.774  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
06-30 13:53:11.774  6822  6822 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:53:11.774  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.774  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 13:53:11.774  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
,06-30 13:53:11.774  6822  6865 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 13:53:11.774  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
06-30 13:53:11.776  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.776  1779  1779 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:11.776  1779  1779 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:11.776  1779  1779 D BluetoothHeadset: Proxy object disconnected
,06-30 13:53:11.778  6822  6822 D A2dpService: Received stop request...Stopping profile...
,06-30 13:53:11.779   848   848 D BluetoothHeadset: Proxy object disconnected
06-30 13:53:11.779   848   848 D AudioService: onServiceDisconnected: Bluetooth profile: 1
06-30 13:53:11.780  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
06-30 13:53:11.780  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.780  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
06-30 13:53:11.780  6822  6865 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
06-30 13:53:11.780  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
06-30 13:53:11.781  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.781  6822  6865 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
06-30 13:53:11.782  6822  6865 D BluetoothAdapterService: getQuietmodeRadioCount = 0
06-30 13:53:11.782  6822  6865 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.782  6822  6865 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
06-30 13:53:11.782  6822  6865 D BluetoothAdapterService(463835660): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
06-30 13:53:11.782  6822  6894 D A2dpStateMachine: Exit Disconnected: -1
06-30 13:53:11.782  6822  6865 D BluetoothAdapterState: Stopping profile services that were post enabled
06-30 13:53:11.785  7008  7008 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
06-30 13:53:11.788  6822  6822 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
06-30 13:53:11.788  6822  6822 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:53:11.788  6822  6822 D LGBluetoothPowerControlManager: [BTUI] terminate
06-30 13:53:11.790   848  1051 D BluetoothManagerService: Message: 31
06-30 13:53:11.790  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.791  6612  6678 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 13:53:11.791   848   848 D BluetoothA2dp: Proxy object disconnected
06-30 13:53:11.791   848   848 D AudioService: onServiceDisconnected: Bluetooth profile: 2
06-30 13:53:11.792  6822  6822 D HidService: Received stop request...Stopping profile...
06-30 13:53:11.792  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.792   848  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:53:11.792   848  1936 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@24f68dbc mBinding = false
06-30 13:53:11.795  6822  6822 D HealthService: Received stop request...Stopping profile...
06-30 13:53:11.796  6716  6716 D BluetoothInputDevice: Proxy object disconnected
06-30 13:53:11.797  6716  6716 D HidProfile: Bluetooth service disconnected
06-30 13:53:11.798  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.800  6822  6822 D PanService: Received stop request...Stopping profile...
06-30 13:53:11.801  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
,06-30 13:53:11.804  6716  6716 D BluetoothPan: BluetoothPAN Proxy object disconnected
06-30 13:53:11.804  6822  6822 D BtGatt.DebugUtils: handleDebugAction() action=null
06-30 13:53:11.805  6822  6822 D BtGatt.GattService: Received stop request...Stopping profile...
06-30 13:53:11.805  6822  6822 D BtGatt.GattService: stop()
06-30 13:53:11.805  6822  6822 D BtGatt.AdvertiseManager: advertise clients cleared
06-30 13:53:11.806  6822  6822 D LGBluetoothGattAdapter: [BTUI] LGBluetoothGattAdapter cleanup
06-30 13:53:11.806  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.807  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.807  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.807  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
06-30 13:53:11.807  6716  6716 D PanProfile: Bluetooth service disconnected
06-30 13:53:11.807  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.807  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.807  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.807  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.807  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.807  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.808  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.808  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,06-30 13:53:11.808  6822  6822 D BluetoothMapService: Received stop request...Stopping profile...
06-30 13:53:11.808  6822  6822 D BluetoothMapService: stop()
06-30 13:53:11.809  6822  6822 D BluetoothMapEmailAppObserver: deinitObservers()
06-30 13:53:11.809  6822  6822 D BluetoothMapEmailAppObserver: removeReceiver()
06-30 13:53:11.810  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.813  6822  6822 D HeadsetStateMachine: Unbinding service...
06-30 13:53:11.814  6822  6822 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:53:11.814  6822  6822 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:53:11.814  7008  7008 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
06-30 13:53:11.814  6822  6822 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
06-30 13:53:11.814  6822  6822 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
06-30 13:53:11.814  6822  6822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
06-30 13:53:11.814  6822  6822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
06-30 13:53:11.814  6822  6822 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
06-30 13:53:11.815   848  1051 D BluetoothManagerService: Message: 1
06-30 13:53:11.815   848  1051 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24f68dbc
06-30 13:53:11.817   848   848 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:53:11.817   848   848 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
06-30 13:53:11.817   848   848 D Ulp_jni : JNI:system_update. Event-4
06-30 13:53:11.817  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:11.817  6716  6716 D BluetoothMap: Proxy object disconnected
06-30 13:53:11.817  6822  6840 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
06-30 13:53:11.817   848  1051 E BluetoothManagerService: IBluetooth.enable() returned false
,06-30 13:53:11.817  6822  6822 D SapService: Received stop request...Stopping profile...
06-30 13:53:11.817  6716  6716 D MapProfile: Bluetooth service disconnected
06-30 13:53:11.817  6822  6822 D SapService: Stopping Bluetooth SapService
06-30 13:53:11.817  6822  6822 D LGBluetoothSapAdapter: [BTUI] LGBluetoothSapAdapter cleanup
06-30 13:53:11.818  6822  6822 D LGBluetoothSapManager: [BTUI] terminateSapManager
06-30 13:53:11.820  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.820   273  1298 V AudioFlinger: thread 0xb5735000 type 0 TID 1298 going to sleep
06-30 13:53:11.821  1779  1779 D LgeBluetoothSimManager: [BTUI] SAP_DISABLE_EVT
06-30 13:53:11.822  6822  6822 D **BluetoothFTPService: Received stop request...Stopping profile...
06-30 13:53:11.822  6822  6822 D **BluetoothFTPService: Stopping Bluetooth FTP Service
06-30 13:53:11.822  6822  6822 V BluetoothFTPServiceJni: closeFtpServerNative
06-30 13:53:11.822  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.823  6822  6822 D **OppService: Received stop request...Stopping profile...
06-30 13:53:11.824  6822  6822 D OppService: Stopping Bluetooth OppService
06-30 13:53:11.824  6822  6822 D OppService: cleanup OPP Service
06-30 13:53:11.824  6822  6822 W BluetoothOPPServiceJni: Cleaning up Bluetooth Opp Interface...
06-30 13:53:11.824  6822  6822 W BluetoothOPPServiceJni: Cleaning up Bluetooth OPP callback object
06-30 13:53:11.825  6822  6822 D OppService: remove callbacks and handler
06-30 13:53:11.825   273  1294 V AudioFlinger: thread 0xb56eb000 type 0 TID 1294 going to sleep
06-30 13:53:11.825  6822  6822 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
06-30 13:53:11.825  6822  6822 D OppService: cleanup done
06-30 13:53:11.825  6822  6822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ba5920c
06-30 13:53:11.825   273  1292 V AudioFlinger: thread 0xb5651000 type 0 TID 1292 going to sleep
06-30 13:53:11.826  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.826  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.826  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
06-30 13:53:11.826  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.826  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.826  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.826  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.826  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.826  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.826  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.826  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.826  6822  6822 I BluetoothA2dpServiceJni: cleanupNative
06-30 13:53:11.826  6822  6822 I GKI_LINUX: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
06-30 13:53:11.827  6822  6982 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
06-30 13:53:11.827  6822  6822 I GKI_LINUX: GKI_destroy_task(): task [A2DP-MEDIA] terminated
06-30 13:53:11.827  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.827  6822  6822 D BluetoothAdapterService(4638356,60): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.827  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.828  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.828  6822  6822 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
06-30 13:53:11.828  6822  6822 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.828  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.828  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.829  6822  6822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
06-30 13:53:11.829  6822  6822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:53:11.829  6822  6822 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
06-30 13:53:11.829  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.829  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.829  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.829  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.829  6822  6822 D BtSettings.ProfileCon,fig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.829  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.830  6822  6822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
06-30 13:53:11.830  6822  6822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.831  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.831  6822  6822 V BluetoothMapService: Handler(): got msg=4
06-30 13:53:11.831  6822  6822 D BluetoothMapService: MAP Service closeService in
06-30 13:53:11.831  6822  6822 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:53:11.831  6822  6822 V BluetoothMapService: MAP Service closeService out
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.831  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.831  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.832  6822  6822 D BluetoothMapService: cleanup()
06-30 13:53:11.832  6822  6822 D BluetoothMapService: MAP Service closeService in
06-30 13:53:11.832  6822  6822 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
06-30 13:53:11.832  6822  6822 V BluetoothMapService: MAP Service closeService out
06-30 13:53:11.832  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.832  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.832  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
06-30 13:53:11.832  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.832  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.832  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.832  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.832  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.832  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.832  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.832  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.832  6822  6822 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
06-30 13:53:11.832  6822  6822 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
06-30 13:53:11.833  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.833  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.833  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
06-30 13:53:11.833  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.833  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.833  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.833  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.833  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.833  6822  6822 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.833  6822  6822 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.833  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
06-30 13:53:11.833  6822  6822 D BluetoothFTPService: cleanup FTP Service
06-30 13:53:11.833  6822  6822 V BluetoothFTPServiceJni: closeFtpServerNative
06-30 13:53:11.833  6822  6822 V BluetoothFTPServiceJni: cleanupNative
06-30 13:53:11.833  6822  6822 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP Server Interface...
06-30 13:53:11.833  6822  6822 W BluetoothFTPServiceJni: Cleaning up Bluetooth FTP callback object
06-30 13:53:11.837  6822  6822 D BluetoothFTPService: BluetoothFtpBinder.cleanup()
06-30 13:53:11.837  6822  6822 D BluetoothFTPService: cleanup done
06-30 13:53:11.837  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - Message: 1
06-30 13:53:11.837  6822  6822 D BluetoothAdapterService(463835660): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
06-30 13:53:11.837  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
06-30 13:53:11.837  6822  6822 D BluetoothAdapterState: isTurningOnRadio()=false
06-30 13:53:11.837  6822  6822 D BluetoothAdapterState: isTurningOffRadio()=false
06-30 13:53:11.837  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
06-30 13:53:11.837  6822  6822 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
06-30 13:53:11.837  6822  6822 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
06-30 13:53:11.837  6822  6822 D BluetoothAdapterService(463835660): onProfileServiceStateChange() - All profile services stopped...
06-30 13:53:11.837  6822  6822 D OppService: cleanup OPP Service
06-30 13:53:11.837  6822  6822 D OppService: remove callbacks and handler
06-30 13:53:11.838  6822  6822 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
06-30 13:53:11.838  6822  6822 D OppService: cleanup done
06-30 13:53:11.838  6822  6865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
06-30 13:53:11.838  6822  6865 D BluetoothAdapterProperties: Setting state to 10
06-30 13:53:11.838  6822  6865 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
06-30 13:53:11.838  6822  6865 D BluetoothAdapterService(463835660): updateAdapterState() - Broadcasting state to 1 receivers.
06-30 13:53:11.839   848  1051 D BluetoothManagerService: Message: 60
06-30 13:53:11.839   848  1051 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
06-30 13:53:11.839  6822  6865 I BluetoothAdapterState: Entering OffState
06-30 13:53:11.839   848  1051 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
06-30 13:53:11.839  6716  6737 D BluetoothMap: onBluetoothStateChange: up=false
06-30 13:53:11.840  6716  6990 D BluetoothPan: onBluetoothStateChange on: false
06-30 13:53:11.840  6716  6738 D BluetoothPbap: onBluetoothStateChange: up=false
06-30 13:53:11.841  1779  1797 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:11.841  6716  6737 D BluetoothInputDevice: onBluetoothStateChange: up=false
06-30 13:53:11.842   848  1051 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:11.842   848  1051 D BluetoothA2dp: onBluetoothStateChange: up=false
06-30 13:53:11.842  1779  2336 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:11.843  1779  2684 D BluetoothHeadset: onBluetoothStateChange: up=false
06-30 13:53:11.843   848  1051 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
06-30 13:53:11.845  1862  1862 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:11.845  1862  2058 D LGBluetoothAPIService: Message: 2
06-30 13:53:11.845  1862  2058 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@19d98c88 mBinding = false
06-30 13:53:11.845  1862  2058 D LGBluetoothAPIService: Sending unbind request.
06-30 13:53:11.849  6822  6822 D LGBluetoothAPIServer: [BTUI] onUnbind()
06-30 13:53:11.849  6822  6822 D LGBluetoothAPIServer: [BTUI] cleanup() done
06-30 13:53:11.849  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:11.849  6822  6822 D LGBluetoothAPIServer: [BTUI] onDestroy()
06-30 13:53:11.850  6716  6716 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
06-30 13:53:11.850  6716  6716 D LGBluetoothEventManager: [BTUI] clear device connection state
06-30 13:53:11.852  6822  6922 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:11.853  6716  6716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
06-30 13:53:11.854  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:11.854  2343  2371 I art     : Explicit concurrent mark sweep GC freed 54485(3MB) AllocSpace objects, 29(487KB) LOS objects, 39% free, 15MB/25MB, paused 5.573ms total 171.004ms
06-30 13:53:11.855  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:11.857  1372  1372 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
06-30 13:53:11.857  1372  1372 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
06-30 13:53:11.860  6822  6822 V BluetoothPbapReceiver: PbapReceiver onReceive 
06-30 13:53:11.860  6822  6822 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:11.860  6822  6822 V BluetoothPbapReceiver: ***********state = 10
,06-30 13:53:11.866  6716  6716 D DockEventReceiver: finishStartingService: stopping service
06-30 13:53:11.876  6716  6716 D BluetoothPermissionRequest: onReceive
06-30 13:53:11.879  6716  6716 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
06-30 13:53:11.879  6716  6716 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
06-30 13:53:11.888  6822  6822 V BluetoothSapReceiver: [BTUI] checkServiceStart
,06-30 13:53:11.891  6822  6822 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
06-30 13:53:11.896  6778  6778 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,06-30 13:53:12.121  2343  2343 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,06-30 13:53:12.130  2343  7039 D EasyUnlockInitService: Handling intent for initializer IntentService.
06-30 13:53:12.131  2343  2343 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
06-30 13:53:12.142  2343  7039 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,06-30 13:53:12.212  7008  7008 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-30 13:53:12.234  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:12.234  6895  6895 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:53:12.236  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,06-30 13:53:12.239  6895  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:12.246  6895  7042 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:53:12.248  6895  7043 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:12.248  6895  7043 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,06-30 13:53:12.259  7008  7008 I HubEmail: JNI_OnLoad()
06-30 13:53:12.259  7008  7008 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:53:12.259  7008  7008 I HubEmail: registerNatives()
06-30 13:53:12.259  7008  7008 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:53:12.259  7008  7008 I HubEmail: registerNativeMethods()
06-30 13:53:12.259  7008  7008 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:53:12.259  7008  7008 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
06-30 13:53:12.287   848  1899 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7045 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,06-30 13:53:12.347  7008  7044 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:53:12.352   848   866 I ActivityManager: Killing 6843:com.google.android.talk/u0a61 (adj 15): empty #11
,06-30 13:53:12.487   848  2176 W libprocessgroup: failed to open /acct/uid_10061/pid_6843/cgroup.procs: No such file or directory
06-30 13:53:12.536  7045  7045 I AppUp4:AppBoxCP: onCreate
,06-30 13:53:12.539  7045  7045 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-30 13:53:12.548  7045  7045 I AppUp4:DB:  setFingerPrint start
,06-30 13:53:12.548  7045  7045 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-30 13:53:12.557  7045  7045 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-30 13:53:12.557  7045  7045 I AppUp4:DB:  SDK version = 21
06-30 13:53:12.557  7045  7045 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 13:53:12.558  7045  7045 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 13:53:12.563  7045  7045 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 13:53:12.564  7045  7045 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:12.565  7045  7045 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,06-30 13:53:12.565  7045  7045 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,06-30 13:53:12.571  7045  7045 I AppUp4:CustModeStarterReceiver: onReceive
06-30 13:53:12.571  7045  7045 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:12.575  7045  7045 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@313ad7e0
06-30 13:53:12.575  7045  7045 D AppUp4:CustFacade: isCustomizationCompleted : false
06-30 13:53:12.581  7045  7045 D AppUp4:CustFacade: isSimDevice : true
,06-30 13:53:12.583  7045  7045 D AppUp4:CustModeStarterReceiver: begin check event
06-30 13:53:12.583  7045  7045 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-30 13:53:12.583  7045  7045 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-30 13:53:12.586  7045  7062 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-30 13:53:12.586  7045  7062 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-30 13:53:12.586  7045  7062 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-30 13:53:12.587   848  1899 I ActivityManager: Killing 6329:com.lge.bnr/1000 (adj 15): empty #11
06-30 13:53:12.685   848  2148 W libprocessgroup: failed to open /acct/uid_1000/pid_6329/cgroup.procs: No such file or directory
,06-30 13:53:12.703  3113  3113 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,06-30 13:53:12.703  3113  3113 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:12.703  3113  3113 I LgeMiscReceiver: networkInfo.isConnected() = false
,06-30 13:53:12.748   848   865 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7067 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,06-30 13:53:12.881  7067  7067 D PhoneMonitor: Register our PhoneStateListener
,06-30 13:53:12.952   848  1309 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:53:12.952   848  1309 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 13:53:13.034   848  1379 I art     : Explicit concurrent mark sweep GC freed 47770(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.849ms total 141.447ms
,06-30 13:53:13.040  7067  7067 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
06-30 13:53:13.041  7067  7067 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
06-30 13:53:13.043   848  1865 I ActivityManager: Killing 6934:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,06-30 13:53:13.063  7067  7067 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,06-30 13:53:13.068  7067  7067 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-30 13:53:13.070  7067  7067 D TelephonyAutoProfiling: [parse] Load xml
06-30 13:53:13.076  7067  7067 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-30 13:53:13.076  7067  7067 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,06-30 13:53:13.088  7067  7067 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,06-30 13:53:13.149   848  1972 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7087 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,06-30 13:53:13.246   848  1897 W libprocessgroup: failed to open /acct/uid_10089/pid_6934/cgroup.procs: No such file or directory
06-30 13:53:13.246   848  1897 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,06-30 13:53:13.264  6799  6799 W System.err: android.os.DeadObjectException
,06-30 13:53:13.278  6799  6799 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 13:53:13.278  6799  6799 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
06-30 13:53:13.278  6799  6799 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:13.278  6799  6799 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 13:53:13.278  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:53:13.278  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:53:13.278  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 13:53:13.278  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 13:53:13.278  6799  6799 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
06-30 13:53:13.279  6799  6799 W System.err: android.os.DeadObjectException
06-30 13:53:13.279  6799  6799 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
06-30 13:53:13.279  6799  6799 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
06-30 13:53:13.279  6799  6799 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:53:13.279  6799  6799 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 13:53:13.279  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:53:13.279  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:53:13.279  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 13:53:13.279  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 13:53:13.279  6799  6799 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
06-30 13:53:13.324   848  1865 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7105 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:53:13.355   302   302 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 362us total 31.326ms
,06-30 13:53:13.369   848  2176 I ActivityManager: Killing 6799:com.lge.qremote/u0a106 (adj 15): empty #11
06-30 13:53:13.378   302   302 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.569ms
,06-30 13:53:13.400   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.070ms
,06-30 13:53:13.555   848  2148 W libprocessgroup: failed to open /acct/uid_10106/pid_6799/cgroup.procs: No such file or directory
,06-30 13:53:13.568  2851  2851 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:53:13
,06-30 13:53:13.572  2851  2851 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 13:53:13.572  2851  2851 D WeatherAncestor: connectivity changed - connection : true
06-30 13:53:13.572  2851  2851 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 13:53:13.572  2851  2851 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:53:13
06-30 13:53:13.574  2851  2851 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:13.574  2851  2851 D WeatherService: 2 : shouldTimeTickRegistered : false
06-30 13:53:13.592  7105  7105 D UEI.SmartControl: Quickset Services start...
,06-30 13:53:13.597  3303  3303 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
06-30 13:53:13.598  7105  7105 I UEI.SmartControl: Manufacture = LGE
06-30 13:53:13.601  7105  7105 D UEI.SmartControl: File observer start...
06-30 13:53:13.601  7105  7105 E UEI.SmartControl: IR Port is disabled: false
06-30 13:53:13.601  7105  7105 D UEI.SmartControl: Starting file observer...
06-30 13:53:13.602  7105  7105 D UEI.SmartControl: Extracting JNI libs...
06-30 13:53:13.602  7105  7105 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
06-30 13:53:13.617  3303  4860 I iu.UploadsManager: num queued entries: 0
,06-30 13:53:13.617  3303  4860 I iu.UploadsManager: num updated entries: 0
06-30 13:53:13.618  3303  4860 I iu.SyncManager: NEXT; no task
06-30 13:53:13.648  7105  7105 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-30 13:53:13.649  7105  7105 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-30 13:53:13.649  7105  7105 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-30 13:53:13.683  7105  7105 I UEI.SmartControl: --- Selecting new region: 2
06-30 13:53:13.683  7105  7105 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,06-30 13:53:13.685   848  1059 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7131 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
06-30 13:53:13.688  7105  7105 D UEI.SmartControl: Platform has CIR...
06-30 13:53:13.714  7105  7105 D UEI.SmartControl: NO CIR support, need to check package...
06-30 13:53:13.715  7105  7105 I UEI.SmartControl: Model: LG-D722 uses JNI
06-30 13:53:13.717  7105  7105 D UEI.SmartControl: QS Service created
,06-30 13:53:13.758  7105  7105 E UEI.SmartControl: QS start get config
06-30 13:53:13.773  7131  7131 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 13:53:13.816  7105  7105 D UEI.SmartControl: Loading JNI Libs...
06-30 13:53:13.819  7105  7105 D UEI.SmartControl:  configuring local db...
,06-30 13:53:13.857  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:53:13.857  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:53:13.858  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:53:13.858  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:53:13.859  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,06-30 13:53:13.870   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:53:13.989  7131  7158 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,06-30 13:53:13.992  7131  7158 I Babel_SMS: MmsConfig.loadMmsSettings
06-30 13:53:14.001  7131  7158 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 13:53:14.001  7131  7158 I Babel_SMS: MmsConfig.loadFromDatabase
,06-30 13:53:14.025  7131  7158 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-30 13:53:14.025  7131  7158 I Babel_SMS: MmsConfig.loadFromResources
06-30 13:53:14.029  7131  7158 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-30 13:53:14.030  7131  7158 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 13:53:14.044  7105  7105 D UEI.SmartControl:  ---- Has DB8: true
06-30 13:53:14.052  7105  7105 D UEI.SmartControl: QS start statue = true Error code = 0
06-30 13:53:14.053  7105  7105 D UEI.SmartControl: QS version = v2.7.11.1_RC1
,06-30 13:53:14.054  7105  7105 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-30 13:53:14.060  7105  7105 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
06-30 13:53:14.068  7105  7105 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-30 13:53:14.068  7105  7105 D irrcClient: IrrcClient ++ 
06-30 13:53:14.068  7105  7105 D irrcClient: getIrrcService ++ 
,06-30 13:53:14.069  7105  7105 D irrcClient: getIrrcService -- 
06-30 13:53:14.069  7105  7105 D irrcClient: IrrcClient -- 
06-30 13:53:14.069  7105  7105 W irrc_jni: IRRCPlayer_nativeInit -- 
06-30 13:53:14.074  7105  7105 D UEI.SmartControl: Services init done
06-30 13:53:14.076  7105  7162 I UEI.SmartControl: Device manager: loading config....
06-30 13:53:14.078  7105  7105 D UEI.SmartControl: QS Service init finished
06-30 13:53:14.079  7105  7105 D UEI.SmartControl: QS Service version name: 0.1.73
06-30 13:53:14.081  7105  7105 D UEI.SmartControl: QS Service version code: 1073
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-30 13:53:14.082  7105  7105 D UEI.SmartControl: Service requested: Control
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-30 13:53:14.082  7131  7131 D SensorManager: found sensor: Motion Accel, handle=46
06-30 13:53:14.091  7105  7162 D UEI.SmartControl: Config is loaded...
,06-30 13:53:14.124  7105  7105 D UEI.SmartControl: Request IControl service: devices are loaded...
,06-30 13:53:14.126  7105  7105 D UEI.SmartControl: Internal service binding...
06-30 13:53:14.134  7105  7161 D UEI.SmartControl:  ----- QS SDK is ready!!!
06-30 13:53:14.135  7105  7161 I UEI.SmartControl: Notify AllClients services are ready: 0
06-30 13:53:14.146  7131  7131 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 13:53:14.150  7131  7131 I Babel_Crash: startup - clean
06-30 13:53:14.182  7131  7164 I Babel   : deleted: false for 0
,06-30 13:53:14.185  7131  7145 I art     : CheckpointMarkThreadRoots callback created = 0xaaf4a4a0
06-30 13:53:14.241  7131  7145 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,06-30 13:53:14.274   848  1949 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7167 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:53:14.275   848   865 I ActivityManager: Killing 6755:com.lge.sync/1000 (adj 15): empty #11
06-30 13:53:14.364   848  2176 W libprocessgroup: failed to open /acct/uid_1000/pid_6755/cgroup.procs: No such file or directory
,06-30 13:53:14.383  7131  7131 W AudioCapabilities: Unsupported mime audio/x-lg-flac
06-30 13:53:14.389  7131  7131 W AudioCapabilities: Unsupported mime audio/adpcm
,06-30 13:53:14.390  7131  7131 W AudioCapabilities: Unsupported mime audio/g726
06-30 13:53:14.392  7131  7131 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 13:53:14.393  7131  7131 W AudioCapabilities: Unsupported mime audio/wma-voice
06-30 13:53:14.395  7131  7131 W VideoCapabilities: Unsupported mime video/mjpg
06-30 13:53:14.401  7131  7131 W VideoCapabilities: Unsupported mime video/theora
06-30 13:53:14.412  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 13:53:14.412  6612  6684 I jxcore-log: 
,06-30 13:53:14.432  7131  7131 W AudioCapabilities: Unsupported mime audio/evrc
,06-30 13:53:14.433  7131  7131 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 13:53:14.436  7131  7131 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:14.442  7131  7131 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-30 13:53:14.443  7131  7131 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:53:14.444  7131  7131 W AudioCapabilities: Unsupported mime audio/evrc
06-30 13:53:14.456  7131  7131 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-30 13:53:14.471  7131  7131 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 13:53:14.479  7131  7131 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:14.481  7131  7131 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:14.485  7131  7131 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 13:53:14.491  7131  7131 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:14.501  7131  7131 I vclib   : onServiceConnected
,06-30 13:53:14.502  7131  7131 W Babel   : Attempted to change video mute state without an active call.
06-30 13:53:14.509  7131  7184 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
06-30 13:53:14.524  7131  7131 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,06-30 13:53:14.535   848  1637 I ActivityManager: Killing 6959:com.google.android.music:main/u0a81 (adj 15): empty #11
06-30 13:53:14.624   848  1949 W libprocessgroup: failed to open /acct/uid_10081/pid_6959/cgroup.procs: No such file or directory
,06-30 13:53:14.702   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:14.702   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 13:53:14.702   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:14.704  7167  7188 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 13:53:14.708   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:14.708   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 13:53:14.708   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:14.708  7167  7188 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 13:53:14.718   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:14.718   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 13:53:14.718   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:14.718  7167  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 13:53:14.721   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:14.721   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 13:53:14.721   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:14.722  7167  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 13:53:14.730  7167  7167 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-30 13:53:14.730  7167  7167 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-30 13:53:14.730  7167  7167 I GAv4    :   adb logcat -s GAv4
,06-30 13:53:14.749  7167  7167 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,06-30 13:53:14.774  7167  7167 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-30 13:53:14.779  7167  7191 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
06-30 13:53:15.046  7167  7167 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,06-30 13:53:15.093  7167  7167 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8487-8489)
,06-30 13:53:15.094  7167  7167 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:53:15.101  7167  7167 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f706407}
06-30 13:53:15.102  7167  7167 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:53:15.102  7167  7167 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:53:15.118  7167  7167 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 13:53:15.120  7167  7167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:53:15.122  7167  7167 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:53:15.144  7167  7167 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-30 13:53:15.149  7167  7167 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:53:15.149  7167  7167 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:53:15.150  7167  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:53:15.150  7167  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:53:15.150  7167  7167 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 13:53:15.150  7167  7167 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 13:53:15.150  7167  7167 I Adreno-EGL: Remote Branch: 
06-30 13:53:15.150  7167  7167 I Adreno-EGL: Local Patches: 
06-30 13:53:15.150  7167  7167 I Adreno-EGL: Reconstruct Branch: 
06-30 13:53:15.223   273  1362 V AudioPolicyService: registerClient() client 0xb551c8a0, uid 10079
,06-30 13:53:15.226  7167  7222 W AudioManagerAndroid: Requires BLUETOOTH permission
06-30 13:53:15.236  7167  7167 I NSApplication: Starting up...
06-30 13:53:15.245  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 13:53:15.245  6612  6684 I jxcore-log: 
,06-30 13:53:15.287  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 13:53:15.287  6612  6684 I jxcore-log: 
,06-30 13:53:15.296  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 13:53:15.296  6612  6684 I jxcore-log: 
06-30 13:53:15.296   848   865 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7227 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:53:15.297   848   865 I ActivityManager: Killing 6716:com.android.settings/1000 (adj 15): empty #11
06-30 13:53:15.325  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 13:53:15.325  6612  6684 I jxcore-log: 
,06-30 13:53:15.333  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 13:53:15.333  6612  6684 I jxcore-log: 
,06-30 13:53:15.357   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:15.384   848  1915 W libprocessgroup: failed to open /acct/uid_1000/pid_6716/cgroup.procs: No such file or directory
,06-30 13:53:15.627   848   866 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7246 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:53:15.628   848   866 I ActivityManager: Killing 6778:com.lge.settings.easy/1000 (adj 15): empty #11
06-30 13:53:15.824   848  1865 W libprocessgroup: failed to open /acct/uid_1000/pid_6778/cgroup.procs: No such file or directory
,06-30 13:53:15.943  7246  7246 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:53:16.041   848  1317 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,06-30 13:53:16.384   848  1865 I ActivityManager: Process com.lge.email (pid 7008) has died
,06-30 13:53:16.451   848   865 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7277 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:53:16.680  7277  7277 I MusicStore: Database version: 120
,06-30 13:53:16.740   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:16.740   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,06-30 13:53:16.740   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:16.740  7277  7277 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 13:53:16.860   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:16.860   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 13:53:16.860   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:53:16.861  7277  7277 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 13:53:16.864   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:16.864   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
06-30 13:53:16.864   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:16.864  7277  7277 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
06-30 13:53:16.903  7277  7277 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 13:53:16.903  7277  7277 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 13:53:16.954  7277  7277 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 13:53:17.039  7277  7277 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 13:53:17.040  7277  7277 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@673f3ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 13:53:17.041  7277  7277 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 13:53:17.042  7277  7277 D AndroidMusic: GMSCore installation verified
,06-30 13:53:17.049  7277  7277 I ConfigStore: Config Database version: 1
,06-30 13:53:17.137  7277  7293 I art     : CheckpointMarkThreadRoots callback created = 0xb042d390
,06-30 13:53:17.166  7277  7277 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-30 13:53:17.176  7277  7277 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
06-30 13:53:17.179  7277  7293 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
06-30 13:53:17.225   848   866 I ActivityManager: Killing 6895:com.lge.lgdmsclient/1000 (adj 15): empty #11
,06-30 13:53:17.324   848  1899 W libprocessgroup: failed to open /acct/uid_1000/pid_6895/cgroup.procs: No such file or directory
,06-30 13:53:17.373   848  2148 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7307 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,06-30 13:53:17.430  7277  7277 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,06-30 13:53:17.442  7277  7277 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 13:53:17.485   848  1897 I ActivityManager: Killing 7045:com.lge.appbox.client/u0a11 (adj 15): empty #11
,06-30 13:53:17.506  7307  7307 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:53:17.507  7307  7307 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:53:17.508  7307  7307 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,06-30 13:53:17.547   848  1899 W libprocessgroup: failed to open /acct/uid_10011/pid_7045/cgroup.procs: No such file or directory
,06-30 13:53:17.555  7277  7298 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
06-30 13:53:17.645  7307  7307 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,06-30 13:53:17.661  7307  7307 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,06-30 13:53:17.846  7307  7307 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,06-30 13:53:17.917   848  1949 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7330 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,06-30 13:53:17.953  1862  2136 E CtrlSupplicant: 'WFDS_SET TRUE' command timed out.
06-30 13:53:17.954  1862  2136 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
,06-30 13:53:17.957  1862  2136 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
06-30 13:53:17.957  1862  2136 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
06-30 13:53:17.957  1862  2136 D WfdsService: selectPreferredScanChannel [6]
06-30 13:53:17.957  1862  2136 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
06-30 13:53:17.957  1862  2136 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
06-30 13:53:17.957  1862  2136 D WfdsJNI : doCommand: P2P_STOP_FIND
06-30 13:53:17.957  1862  2136 D WfdsJNI : wfds_send_command: [P2P_STOP_FIND] failed
06-30 13:53:17.957  1862  2136 D WfdsService: Set the WFDS Monitor: false
06-30 13:53:17.959  1862  6852 D CtrlSupplicant: Received on exit socket, terminate
06-30 13:53:17.959  1862  6852 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
06-30 13:53:17.960  1862  2136 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:53:17.960  1862  2136 D WfdsService: STATE : WfdsDisabledState - enter
06-30 13:53:17.960  1862  2136 D WfdsService: WFDS: Scanner is paused
06-30 13:53:17.962  1862  6852 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
06-30 13:53:17.962  1862  6852 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
06-30 13:53:17.963  1862  2136 D WfdsDiscoveryStore: Clear Discovery Method Map: ScanAlwaysMode false
06-30 13:53:17.965  1862  2136 W WfdsService: DefaultState - msg [9441285] is not handled
06-30 13:53:17.965  1862  2136 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
06-30 13:53:17.965  1862  2136 D WfdsService: Set the WFDS Monitor: false
06-30 13:53:17.965  1862  2136 D WfdsMonitor: WFDS Monitor is stopped
06-30 13:53:17.965  1862  2134 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
06-30 13:53:17.986  7307  7307 I HubEmail: JNI_OnLoad()
06-30 13:53:17.986  7307  7307 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:53:17.986  7307  7307 I HubEmail: registerNatives()
06-30 13:53:17.986  7307  7307 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:53:17.986  7307  7307 I HubEmail: registerNativeMethods()
06-30 13:53:17.986  7307  7307 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
06-30 13:53:17.987  7307  7307 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,06-30 13:53:17.998   848  1897 I ActivityManager: Killing 7067:com.google.android.setupwizard/u0a38 (adj 15): empty #11
06-30 13:53:18.125  7307  7347 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:18.125   848  1915 W libprocessgroup: failed to open /acct/uid_10038/pid_7067/cgroup.procs: No such file or directory
,06-30 13:53:18.132  7330  7330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:18.133  7330  7330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
06-30 13:53:18.137  7330  7330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,06-30 13:53:18.140  7330  7330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
06-30 13:53:18.156  7330  7349 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:53:18.159  7330  7349 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
06-30 13:53:18.167  7330  7348 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
06-30 13:53:18.178   848  1936 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7352 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,06-30 13:53:18.209   848  1899 I ActivityManager: Killing 7087:com.lge.drmservice/u0a51 (adj 15): empty #11
,06-30 13:53:18.294   848   865 W libprocessgroup: failed to open /acct/uid_10051/pid_7087/cgroup.procs: No such file or directory
,06-30 13:53:18.376  7352  7352 I AppUp4:AppBoxCP: onCreate
,06-30 13:53:18.381  7352  7352 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-30 13:53:18.389  7352  7352 I AppUp4:DB:  setFingerPrint start
06-30 13:53:18.390  7352  7352 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,06-30 13:53:18.397  7352  7352 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-30 13:53:18.398  7352  7352 I AppUp4:DB:  SDK version = 21
06-30 13:53:18.398  7352  7352 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 13:53:18.399  7352  7352 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 13:53:18.413  7352  7352 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
06-30 13:53:18.413  7352  7352 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,06-30 13:53:18.415  7352  7352 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
06-30 13:53:18.415  7352  7352 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
06-30 13:53:18.420  7352  7352 I AppUp4:CustModeStarterReceiver: onReceive
06-30 13:53:18.420  7352  7352 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:18.424  7352  7352 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@313ad7e0
06-30 13:53:18.424  7352  7352 D AppUp4:CustFacade: isCustomizationCompleted : false
,06-30 13:53:18.430  7352  7352 D AppUp4:CustFacade: isSimDevice : true
,06-30 13:53:18.432  7352  7352 D AppUp4:CustModeStarterReceiver: begin check event
06-30 13:53:18.432  7352  7352 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
06-30 13:53:18.432  7352  7352 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
06-30 13:53:18.434  7352  7369 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
06-30 13:53:18.434  7352  7369 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
06-30 13:53:18.434  7352  7369 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
06-30 13:53:18.436   848  1949 I ActivityManager: Killing 7105:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
06-30 13:53:18.696  3113  3113 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
06-30 13:53:18.696  3113  3113 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:18.696   848  2016 W libprocessgroup: failed to open /acct/uid_10089/pid_7105/cgroup.procs: No such file or directory
06-30 13:53:18.696  3113  3113 I LgeMiscReceiver: networkInfo.isConnected() = false
,06-30 13:53:18.741   848  1949 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7374 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,06-30 13:53:18.968  7374  7374 D PhoneMonitor: Register our PhoneStateListener
,06-30 13:53:18.994  7374  7374 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
06-30 13:53:18.995  7374  7374 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,06-30 13:53:18.998   848  1899 I ActivityManager: Killing 7131:com.google.android.talk/u0a61 (adj 15): empty #11
,06-30 13:53:19.018  7374  7374 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
06-30 13:53:19.022  7374  7374 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
06-30 13:53:19.024  7374  7374 D TelephonyAutoProfiling: [parse] Load xml
,06-30 13:53:19.030  7374  7374 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
06-30 13:53:19.031  7374  7374 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
06-30 13:53:19.034  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 13:53:19.034  6612  6684 I jxcore-log: 
06-30 13:53:19.037  7374  7374 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,06-30 13:53:19.053  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 13:53:19.053  6612  6684 I jxcore-log: 
,06-30 13:53:19.067  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 13:53:19.067  6612  6684 I jxcore-log: 
,06-30 13:53:19.069   848  1972 W libprocessgroup: failed to open /acct/uid_10061/pid_7131/cgroup.procs: No such file or directory
06-30 13:53:19.070   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:53:19.070   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:53:19.070   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 192465705296; DSPS: 6405432; Offset : -3023956942
06-30 13:53:19.105   848  1949 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7406 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,06-30 13:53:19.216   848  1865 I ActivityManager: Killing 7167:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,06-30 13:53:19.342  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 13:53:19.342  6612  6684 I jxcore-log: 
,06-30 13:53:19.475  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 13:53:19.475  6612  6684 I jxcore-log: 
,06-30 13:53:19.505   848  2215 W libprocessgroup: failed to open /acct/uid_10079/pid_7167/cgroup.procs: No such file or directory
,06-30 13:53:19.508  2851  2851 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:53:19
06-30 13:53:19.510  2851  2851 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 13:53:19.510  2851  2851 D WeatherAncestor: connectivity changed - connection : true
06-30 13:53:19.510  2851  2851 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 13:53:19.510  2851  2851 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:53:19
06-30 13:53:19.512  2851  2851 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
06-30 13:53:19.515  2851  2851 D WeatherService: 2 : shouldTimeTickRegistered : false
06-30 13:53:19.560   848  1379 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7429 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 13:53:19.583   302   302 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 298us total 25.407ms
,06-30 13:53:19.598  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 13:53:19.598  6612  6684 I jxcore-log: 
06-30 13:53:19.606   302   302 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.854ms
,06-30 13:53:19.611  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 13:53:19.611  6612  6684 I jxcore-log: 
,06-30 13:53:19.631   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 25.097ms
,06-30 13:53:19.677  7429  7429 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 13:53:19.878  7429  7456 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-30 13:53:19.878  7429  7456 I Babel_SMS: MmsConfig.loadMmsSettings
,06-30 13:53:20.003   848  1972 I art     : Explicit concurrent mark sweep GC freed 21063(1025KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.110ms total 147.500ms
,06-30 13:53:20.009  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 13:53:20.009  6612  6684 I jxcore-log: 
06-30 13:53:20.011  7429  7456 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 13:53:20.011  7429  7456 I Babel_SMS: MmsConfig.loadFromDatabase
06-30 13:53:20.034  7429  7456 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
06-30 13:53:20.034  7429  7456 I Babel_SMS: MmsConfig.loadFromResources
,06-30 13:53:20.039  7429  7456 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
06-30 13:53:20.040  7429  7456 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
06-30 13:53:20.050  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 13:53:20.050  6612  6684 I jxcore-log: 
,06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
06-30 13:53:20.055  7429  7448 I art     : CheckpointMarkThreadRoots callback created = 0xb042d7b0
06-30 13:53:20.055  7429  7429 D SensorManager: found sensor: Motion Accel, handle=46
06-30 13:53:20.058  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 13:53:20.058  6612  6684 I jxcore-log: 
06-30 13:53:20.067  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 13:53:20.067  6612  6684 I jxcore-log: 
,06-30 13:53:20.099  7429  7448 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,06-30 13:53:20.111  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 13:53:20.111  6612  6684 I jxcore-log: 
06-30 13:53:20.114  7429  7429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:53:20.117  7429  7429 I Babel_Crash: startup - clean
,06-30 13:53:20.147  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 13:53:20.147  6612  6684 I jxcore-log: 
,06-30 13:53:20.162  7429  7464 I Babel   : deleted: false for 0
,06-30 13:53:20.239   848  1637 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7466 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:53:20.298  7429  7429 W AudioCapabilities: Unsupported mime audio/x-lg-flac
06-30 13:53:20.300  7429  7429 W AudioCapabilities: Unsupported mime audio/adpcm
,06-30 13:53:20.305  7429  7429 W AudioCapabilities: Unsupported mime audio/g726
06-30 13:53:20.306  7429  7429 W AudioCapabilities: Unsupported mime audio/x-ms-wma
06-30 13:53:20.308  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 13:53:20.308  6612  6684 I jxcore-log: 
06-30 13:53:20.314  7429  7429 W AudioCapabilities: Unsupported mime audio/wma-voice
,06-30 13:53:20.317  7429  7429 W VideoCapabilities: Unsupported mime video/mjpg
06-30 13:53:20.317  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 13:53:20.317  6612  6684 I jxcore-log: 
06-30 13:53:20.320  7429  7429 W VideoCapabilities: Unsupported mime video/theora
06-30 13:53:20.349  7429  7429 W AudioCapabilities: Unsupported mime audio/evrc
06-30 13:53:20.351  7429  7429 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:53:20.352  7429  7429 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:20.359  7429  7429 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
06-30 13:53:20.360  7429  7429 W AudioCapabilities: Unsupported mime audio/qcelp
06-30 13:53:20.361  7429  7429 W AudioCapabilities: Unsupported mime audio/evrc
06-30 13:53:20.362   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
06-30 13:53:20.366  6612  6684 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 13:53:20.366  6612  6684 I jxcore-log: 
,06-30 13:53:20.384  6612  6684 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-30 13:53:20.388  6612  6684 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 13:53:20.388  6612  6684 I jxcore-log: 
06-30 13:53:20.395  7429  7429 W VideoCapabilities: Unsupported mime video/mp4v-esdp
06-30 13:53:20.443  7429  7429 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 13:53:20.452  7429  7429 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:20.454  7429  7429 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:20.459  7429  7429 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
06-30 13:53:20.466  7429  7429 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,06-30 13:53:20.475  7429  7429 I vclib   : onServiceConnected
06-30 13:53:20.475  7429  7429 W Babel   : Attempted to change video mute state without an active call.
06-30 13:53:20.486   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:20.486   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 13:53:20.486   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:20.486  7466  7466 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
06-30 13:53:20.486  7466  7466 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
06-30 13:53:20.486  7466  7466 I GAv4    :   adb logcat -s GAv4
06-30 13:53:20.486  7466  7487 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,06-30 13:53:20.490  7429  7488 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
06-30 13:53:20.493   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:20.493   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 13:53:20.493   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:20.493  7466  7487 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 13:53:20.498  7429  7429 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
06-30 13:53:20.503   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:20.503   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
06-30 13:53:20.503   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:20.504  7466  7490 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
06-30 13:53:20.506   244   382 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
06-30 13:53:20.506   244   382 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
06-30 13:53:20.506   244   382 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:53:20.507  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 13:53:20.507  6612  6684 I jxcore-log: 
06-30 13:53:20.507  7466  7490 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
06-30 13:53:20.508   848  1865 I ActivityManager: Killing 7227:com.android.chrome/u0a48 (adj 15): empty #11
06-30 13:53:20.509  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:53:20.509  6612  6684 I jxcore-log: 
,06-30 13:53:20.511  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:53:20.511  6612  6684 I jxcore-log: 
06-30 13:53:20.512  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.512  6612  6684 I jxcore-log: 
06-30 13:53:20.516  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.516  6612  6684 I jxcore-log: 
06-30 13:53:20.518  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:53:20.518  6612  6684 I jxcore-log: 
06-30 13:53:20.519  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
06-30 13:53:20.519  6612  6684 I jxcore-log: 
06-30 13:53:20.520  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.520  6612  6684 I jxcore-log: 
06-30 13:53:20.520  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.520  6612  6684 I jxcore-log: 
06-30 13:53:20.522  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.522  6612  6684 I jxcore-log: 
,06-30 13:53:20.523  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.523  6612  6684 I jxcore-log: 
06-30 13:53:20.524  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.524  6612  6684 I jxcore-log: 
,06-30 13:53:20.524  6612  6684 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 13:53:20.524  6612  6684 I jxcore-log: 
06-30 13:53:20.544   848  1899 W libprocessgroup: failed to open /acct/uid_10048/pid_7227/cgroup.procs: No such file or directory
,06-30 13:53:20.546  7466  7466 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
06-30 13:53:20.577  7466  7466 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,06-30 13:53:20.582  7466  7491 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
06-30 13:53:20.765  7466  7466 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,06-30 13:53:20.796  7466  7466 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4190-4192)
,06-30 13:53:20.796  7466  7466 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:53:20.802  7466  7466 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f706407}
06-30 13:53:20.802  7466  7466 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:53:20.803  7466  7466 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:53:20.815  7466  7466 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:53:20.816  7466  7466 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:53:20.817  7466  7466 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 13:53:20.834  7466  7466 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-30 13:53:20.839  7466  7466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:53:20.839  7466  7466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:53:20.841  7466  7466 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 13:53:20.841  7466  7466 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:53:20.841  7466  7466 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 13:53:20.841  7466  7466 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 13:53:20.841  7466  7466 I Adreno-EGL: Remote Branch: 
06-30 13:53:20.841  7466  7466 I Adreno-EGL: Local Patches: 
06-30 13:53:20.841  7466  7466 I Adreno-EGL: Reconstruct Branch: 
06-30 13:53:20.910  7466  7466 I NSApplication: Starting up...
,06-30 13:53:20.923   273  1362 V AudioPolicyService: registerClient() client 0xb57e71e0, uid 10079
,06-30 13:53:20.926  7466  7525 W AudioManagerAndroid: Requires BLUETOOTH permission
,06-30 13:53:20.964   848  1936 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7530 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:53:20.969   848  1936 I ActivityManager: Killing 7246:com.google.android.apps.plus/u0a86 (adj 15): empty #11
06-30 13:53:21.004   848  2016 W libprocessgroup: failed to open /acct/uid_10086/pid_7246/cgroup.procs: No such file or directory
,06-30 13:53:21.127   848  1897 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7549 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:53:21.128   848  1897 I ActivityManager: Killing 7277:com.google.android.music:main/u0a81 (adj 15): empty #11
,06-30 13:53:21.184   848  2148 W libprocessgroup: failed to open /acct/uid_10081/pid_7277/cgroup.procs: No such file or directory
,06-30 13:53:21.205  7549  7549 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:53:21.416   848  1379 I ActivityManager: Killing 7307:com.lge.email/u0a21 (adj 15): empty #11
,06-30 13:53:21.455   848  2176 W libprocessgroup: failed to open /acct/uid_10021/pid_7307/cgroup.procs: No such file or directory
,06-30 13:53:21.498   848   865 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7573 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,06-30 13:53:21.545  7573  7573 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,06-30 13:53:21.600   848  1051 D BluetoothManagerService: Message: 20
06-30 13:53:21.601   848  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2233a54c:true
,06-30 13:53:21.606  6822  6840 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:21.606  6822  6839 D BluetoothAdapterService(463835660): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@256607c2
06-30 13:53:21.731   848  2148 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7591 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 13:53:21.751  7573  7573 V LGMDMManager: Create singleton instance
,06-30 13:53:21.821  7591  7591 D UEI.SmartControl: Quickset Services start...
,06-30 13:53:21.825  7591  7591 I UEI.SmartControl: Manufacture = LGE
06-30 13:53:21.827  7591  7591 D UEI.SmartControl: File observer start...
06-30 13:53:21.827  7591  7591 E UEI.SmartControl: IR Port is disabled: false
06-30 13:53:21.828  7591  7591 D UEI.SmartControl: Starting file observer...
06-30 13:53:21.828  7591  7591 D UEI.SmartControl: Extracting JNI libs...
06-30 13:53:21.829  7591  7591 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,06-30 13:53:21.877  7573  7573 I AudioManager: getMode name:com.lge.qremote
,06-30 13:53:21.892  7591  7591 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,06-30 13:53:21.894  7591  7591 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
06-30 13:53:21.894  7591  7591 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
06-30 13:53:21.899   848   848 D PowerManagerServiceEx: releaseWakeLockInternal: lock=570302530 [*alarm*], flags=0x0
06-30 13:53:21.902  7573  7573 I AudioManager: getMode name:com.lge.qremote
06-30 13:53:21.911  2343  7615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:21.912  2343  7615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 13:53:21.918  2343  7615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:21.918  2343  7615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:53:21.919   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:53:21.919   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:53:21.919   267  7616 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 13:53:21.919   267  7616 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:53:21.919   267  7616 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 13:53:21.920   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 13:53:21.937  7591  7591 I UEI.SmartControl: --- Selecting new region: 2
,06-30 13:53:21.938  7591  7591 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,06-30 13:53:21.940  7591  7591 D UEI.SmartControl: Platform has CIR...
06-30 13:53:21.942  7591  7591 D UEI.SmartControl: NO CIR support, need to check package...
06-30 13:53:21.943  7591  7591 I UEI.SmartControl: Model: LG-D722 uses JNI
06-30 13:53:21.946  7591  7591 D UEI.SmartControl: QS Service created
06-30 13:53:21.971  7591  7591 E UEI.SmartControl: QS start get config
,06-30 13:53:22.021  7591  7591 D UEI.SmartControl: Loading JNI Libs...
,06-30 13:53:22.024  7591  7591 D UEI.SmartControl:  configuring local db...
06-30 13:53:22.309  7591  7591 D UEI.SmartControl:  ---- Has DB8: true
,06-30 13:53:22.324  7591  7591 D UEI.SmartControl: QS start statue = true Error code = 0
,06-30 13:53:22.328  7591  7591 D UEI.SmartControl: QS version = v2.7.11.1_RC1
06-30 13:53:22.329  7591  7591 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
06-30 13:53:22.334  7591  7591 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
06-30 13:53:22.349  7591  7591 W irrc_jni: IRRCPlayer_nativeInit ++ 
06-30 13:53:22.350  7591  7591 D irrcClient: IrrcClient ++ 
06-30 13:53:22.350  7591  7591 D irrcClient: getIrrcService ++ 
,06-30 13:53:22.353  7591  7591 D irrcClient: getIrrcService -- 
06-30 13:53:22.353  7591  7591 D irrcClient: IrrcClient -- 
06-30 13:53:22.353  7591  7591 W irrc_jni: IRRCPlayer_nativeInit -- 
06-30 13:53:22.365  7591  7591 D UEI.SmartControl: Services init done
,06-30 13:53:22.370  7591  7591 D UEI.SmartControl: QS Service init finished
06-30 13:53:22.372  7591  7591 D UEI.SmartControl: QS Service version name: 0.1.73
06-30 13:53:22.373  7591  7591 D UEI.SmartControl: QS Service version code: 1073
06-30 13:53:22.375  7591  7591 D UEI.SmartControl: Service requested: Control
06-30 13:53:22.377  7591  7621 I UEI.SmartControl: Device manager: loading config....
06-30 13:53:22.383  7591  7621 D UEI.SmartControl: Config is loaded...
,06-30 13:53:22.414  7591  7620 D UEI.SmartControl:  ----- QS SDK is ready!!!
,06-30 13:53:22.415  7591  7620 I UEI.SmartControl: Notify AllClients services are ready: 0
,06-30 13:53:22.426  7591  7591 D UEI.SmartControl: Request IControl service: devices are loaded...
,06-30 13:53:22.431  7591  7591 D UEI.SmartControl: Internal service binding...
06-30 13:53:22.438  7591  7606 D UEI.SmartControl: -----IControl: 11
,06-30 13:53:22.440  7591  7606 D UEI.SmartControl: Caller: com.lge.qremote
06-30 13:53:22.447  7591  7606 D UEI.SmartControl: ------------ IControl registerCallback...
06-30 13:53:22.448  7591  7606 I UEI.SmartControl: Registering callback...
06-30 13:53:22.449  7591  7607 D UEI.SmartControl: -----IControl: 19
06-30 13:53:22.451  7591  7607 D UEI.SmartControl: Caller: com.lge.qremote
06-30 13:53:22.451  7591  7607 I UEI.SmartControl: Registering Services Ready callback...
,06-30 13:53:22.453  7591  7607 I UEI.SmartControl: Notify client services are ready...
06-30 13:53:22.460  7591  7606 D UEI.SmartControl: -----IControl: 8
06-30 13:53:22.462  7591  7606 D UEI.SmartControl: Caller: com.lge.qremote
06-30 13:53:22.470  7573  7573 I AudioManager: getMode name:com.lge.qremote
,06-30 13:53:22.480   848  2176 I ActivityManager: Killing 7352:com.lge.appbox.client/u0a11 (adj 15): empty #11
06-30 13:53:22.514   848  2176 I ActivityManager: Killing 7330:com.lge.lgdmsclient/1000 (adj 15): empty #12
,06-30 13:53:22.544   848  1915 W libprocessgroup: failed to open /acct/uid_10011/pid_7352/cgroup.procs: No such file or directory
,06-30 13:53:22.548   848   866 W libprocessgroup: failed to open /acct/uid_1000/pid_7330/cgroup.procs: No such file or directory
06-30 13:53:22.553  7573  7573 I AudioManager: getMode name:com.lge.qremote
,06-30 13:53:22.589  7573  7573 I AudioManager: getMode name:com.lge.qremote
,06-30 13:53:25.367   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:27.404  7591  7622 D UEI.SmartControl: Internal timer expired: 1
,06-30 13:53:30.371   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:33.062   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{13e07e13 type 2 when 206444 com.google.android.gms} when 206444
,06-30 13:53:33.074  2343  7629 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:33.075  2343  7629 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:33.075  2343  7629 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:33.075  2343  7629 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 13:53:33.078   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:53:33.078   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:53:33.080   267  7630 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 13:53:33.080   267  7630 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:53:33.080   267  7630 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 13:53:33.082   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 13:53:35.376   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:39.070   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:53:39.070   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:53:39.070   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 212466556121; DSPS: 7060820; Offset : -3023959723
,06-30 13:53:40.380   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:45.385   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:50.390   290   345 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 13:53:53.560   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{32b1a850 type 2 when 218087 android} when 218087
,06-30 13:53:55.336   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{34cd3a49 type 2 when 228719 com.google.android.gms} when 228719
,06-30 13:53:55.344  2343  7640 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:55.344  2343  7640 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:53:55.345  2343  7640 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:53:55.345  2343  7640 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:53:55.345   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:53:55.346   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:53:55.346   267  7641 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 13:53:55.346   267  7641 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:53:55.347   267  7641 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 13:53:55.351   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 13:53:55.394   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:53:59.071   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:53:59.071   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:53:59.071   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 232467311582; DSPS: 7716205; Offset : -3023967463
,06-30 13:54:00.074  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:54:00.074  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:54:00.074  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:54:00.080  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:54:00.080  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:54:00.081  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:54:00.082  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:54:00.399   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:05.403   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:10.408   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:14.025  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:54:14.025  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:54:14.025  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:54:14.025  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:54:14.028  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:54:14.029   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:54:14.069  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
06-30 13:54:14.069  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:54:14.069  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
,06-30 13:54:14.074  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:54:14.074  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:54:14.074  1862  2050 D LEDHandler: Battery Temp: 305, mChargingStatus=5, mChargingStop=false
06-30 13:54:14.078   848  1316 D WifiController: battery changed pluggedType: 2
06-30 13:54:14.082  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:54:14.082  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,06-30 13:54:14.087  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:54:15.413   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:18.910  2343  3433 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:54:19.072   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:54:19.072   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:54:19.072   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 252468017304; DSPS: 8371588; Offset : -3023963150
,06-30 13:54:20.417   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:25.422   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:30.426   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:35.431   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:39.072   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:54:39.073   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:54:39.073   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 272468693025; DSPS: 9026970; Offset : -3023959076
,06-30 13:54:39.846   848  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=570302530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=848
,06-30 13:54:39.853   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{209a3f4e type 2 when 273230 com.google.android.gms} when 273230
06-30 13:54:39.867   848   848 D PowerManagerServiceEx: releaseWakeLockInternal: lock=570302530 [*alarm*], flags=0x0
,06-30 13:54:39.874  2343  7647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:54:39.874  2343  7647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:54:39.874  2343  7647 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:54:39.874  2343  7647 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:54:39.875   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:54:39.875   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:54:39.876   267  7648 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 13:54:39.876   267  7648 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:54:39.876   267  7648 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 13:54:39.878   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 13:54:40.435   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:45.440   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:50.444   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:55.449   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:54:59.073   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:54:59.073   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:54:59.073   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 292469378278; DSPS: 9682353; Offset : -3023975988
,06-30 13:55:00.041  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:55:00.041  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:55:00.041  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:55:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:55:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:55:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:55:00.047  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:55:00.453   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:05.458   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:10.463   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:14.183  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:55:14.184  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:55:14.184  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:55:14.184  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:55:14.188   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:55:14.194  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:55:14.225  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
06-30 13:55:14.225  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:55:14.225  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
,06-30 13:55:14.230  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:55:14.230  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 13:55:14.235  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:55:14.235  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:55:14.235  1862  2050 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
06-30 13:55:14.238   848  1316 D WifiController: battery changed pluggedType: 2
06-30 13:55:14.240  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-30 13:55:15.467   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:19.074   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:55:19.074   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:55:19.074   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 312470289938; DSPS: 10337743; Offset : -3023979672
,06-30 13:55:20.472   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:25.476   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:30.481   290   345 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 13:55:35.485   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:55:39.075   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:55:39.075   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:55:39.075   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 332471120190; DSPS: 10993130; Offset : -3023973396
,06-30 13:55:40.490   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:55:45.495   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:55:48.824   848  3149 I LocationManagerService: remove 2978c319
,06-30 13:55:48.828   848  3149 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-30 13:55:48.828   848  3149 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 13:55:48.829   848  3149 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 13:55:48.829   848  3149 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-30 13:55:48.829   848  3149 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 13:55:50.499   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:55:55.504   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:55:59.076   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:55:59.076   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:55:59.076   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 352471870079; DSPS: 11648514; Offset : -3023955798
,06-30 13:56:00.074  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:56:00.074  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:56:00.074  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:56:00.078  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:56:00.078  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:56:00.079  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:56:00.080  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:56:00.508   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:05.513   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:08.873   848  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=570302530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=848
,06-30 13:56:08.881   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{254ae86f type 2 when 362257 com.google.android.gms} when 362257
06-30 13:56:08.901   848   848 D PowerManagerServiceEx: releaseWakeLockInternal: lock=570302530 [*alarm*], flags=0x0
,06-30 13:56:08.906  2343  7657 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:56:08.907  2343  7657 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:56:08.907  2343  7657 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:56:08.907  2343  7657 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:56:08.908   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:56:08.908   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:56:08.909   267  7659 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 13:56:08.909   267  7659 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:56:08.909   267  7659 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 13:56:08.911   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 13:56:10.517   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:14.343  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-30 13:56:14.350  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:56:14.350  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:56:14.350  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:56:14.350  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:56:14.351   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:56:14.391  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
06-30 13:56:14.391  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:56:14.392  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
,06-30 13:56:14.396  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:56:14.397  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:56:14.397  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:56:14.397  1862  2050 D LEDHandler: Battery Temp: 301, mChargingStatus=5, mChargingStop=false
06-30 13:56:14.398  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 13:56:14.400  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:56:14.404   848  1316 D WifiController: battery changed pluggedType: 2
06-30 13:56:15.522   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:19.077   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:56:19.077   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:56:19.077   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 372472747050; DSPS: 12303903; Offset : -3023963940
,06-30 13:56:20.527   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:25.531   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:30.536   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:35.540   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:39.077   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:56:39.077   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:56:39.077   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 392473424907; DSPS: 12959285; Offset : -3023957522
,06-30 13:56:40.545   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:45.550   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:50.554   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:55.559   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:56:59.078   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:56:59.078   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:56:59.078   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 412474162764; DSPS: 13614670; Offset : -3023982580
,06-30 13:57:00.074  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:57:00.074  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:57:00.074  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:57:00.078  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:57:00.078  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:57:00.079  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:57:00.080  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:57:00.563   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:05.568   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:10.572   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:14.503   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:57:14.506  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:57:14.506  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:57:14.506  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:57:14.506  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:57:14.513  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:57:14.545  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
06-30 13:57:14.545  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:57:14.546  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,06-30 13:57:14.549  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:57:14.549  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 13:57:14.554  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:57:14.554  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:57:14.554  1862  2050 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
06-30 13:57:14.555  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:57:14.559   848  1316 D WifiController: battery changed pluggedType: 2
,06-30 13:57:15.577   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:19.079   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:57:19.079   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:57:19.079   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 432474900412; DSPS: 14270054; Offset : -3023977144
,06-30 13:57:20.582   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:25.586   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:30.591   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:35.595   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:39.079   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:57:39.079   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:57:39.080   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 452475666030; DSPS: 14925439; Offset : -3023974597
,06-30 13:57:40.600   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:45.604   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:50.609   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:55.614   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:57:59.080   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:57:59.080   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:57:59.080   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 472476349095; DSPS: 15580821; Offset : -3023963257
,06-30 13:58:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:58:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:58:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:58:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:58:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:58:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:58:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:58:00.618   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:05.623   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:10.627   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:14.676   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:58:14.684  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:58:14.684  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:58:14.685  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:58:14.685  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:58:14.685  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:58:15.634   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:19.081   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:58:19.081   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:58:19.081   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 492477042369; DSPS: 16236204; Offset : -3023971574
,06-30 13:58:20.639   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:25.643   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:30.648   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:35.652   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:39.082   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:58:39.082   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:58:39.082   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 512477800278; DSPS: 16891589; Offset : -3023976839
,06-30 13:58:40.657   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:45.661   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:50.666   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:55.671   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:58:59.082   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:58:59.082   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:58:59.082   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 532478486937; DSPS: 17546971; Offset : -3023961567
,06-30 13:59:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:59:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:59:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:59:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:59:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:59:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:59:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:59:00.675   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:05.680   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:06.897   848  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=570302530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=848
,06-30 13:59:06.906   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2890f97c type 2 when 540282 com.google.android.gms} when 540282
06-30 13:59:06.930   848   848 D PowerManagerServiceEx: releaseWakeLockInternal: lock=570302530 [*alarm*], flags=0x0
,06-30 13:59:06.935  2343  7699 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:59:06.936  2343  7699 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:59:06.936  2343  7699 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:59:06.936  2343  7699 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:59:06.937   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:59:06.937   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:59:06.938   267  7700 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 13:59:06.938   267  7700 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:59:06.938   267  7700 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 13:59:06.940   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 13:59:10.684   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:14.836  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:59:14.836  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:59:14.836  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:59:14.836  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:59:14.839  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:59:14.847   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:59:15.689   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:19.083   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:59:19.083   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:59:19.083   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 552479255731; DSPS: 18202357; Offset : -3023986022
,06-30 13:59:20.693   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:25.698   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:30.703   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:35.707   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:39.084   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:59:39.084   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:59:39.084   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 572480363954; DSPS: 18857753; Offset : -3023976640
,06-30 13:59:40.712   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:45.716   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:50.721   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:55.726   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 13:59:59.085   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:59:59.085   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:59:59.085   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 592481129414; DSPS: 19513138; Offset : -3023973702
,06-30 14:00:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:00:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:00:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:00:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:00:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:00:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:00:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:00:00.730   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:05.735   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:10.739   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:14.984  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:00:14.984  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:00:14.984  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:00:14.984  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:00:14.986   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:00:14.988  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:00:15.025  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 299
06-30 14:00:15.025  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:00:15.026  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 299
,06-30 14:00:15.029  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:00:15.029  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:00:15.030  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:00:15.030  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:00:15.030  1862  2050 D LEDHandler: Battery Temp: 299, mChargingStatus=5, mChargingStop=false
06-30 14:00:15.037   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:00:15.037  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:00:15.744   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:19.086   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:00:19.086   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:00:19.086   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 612481904615; DSPS: 20168523; Offset : -3023961415
,06-30 14:00:20.748   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:25.753   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:30.758   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:35.762   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:39.086   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:00:39.087   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:00:39.087   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 632482611534; DSPS: 20823906; Offset : -3023956373
,06-30 14:00:40.767   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:45.771   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:50.776   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:55.781   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:00:59.087   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:00:59.087   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:00:59.087   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 652483395329; DSPS: 21479292; Offset : -3023966296
,06-30 14:01:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:01:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:01:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:01:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:01:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:01:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:01:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:01:00.785   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:01:05.790   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:01:10.794   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:01:15.144  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:01:15.144  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:01:15.144  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:01:15.144  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:01:15.147  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:01:15.153   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:01:15.189  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
06-30 14:01:15.189  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:01:15.189  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
,06-30 14:01:15.193  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:01:15.193  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:01:15.195  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:01:15.195  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:01:15.195  1862  2050 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
06-30 14:01:15.198   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:01:15.200  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:01:15.799   290   345 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 14:01:19.088   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:01:19.088   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:01:19.088   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 672484094801; DSPS: 22134675; Offset : -3023968859
,06-30 14:01:20.803   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:25.808   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:30.813   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:35.817   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:39.089   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:01:39.089   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:01:39.089   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 692484842449; DSPS: 22790060; Offset : -3023984151
,06-30 14:01:40.822   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:45.826   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:50.831   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:55.835   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:01:59.089   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:01:59.089   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:01:59.089   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 712485503587; DSPS: 23445441; Offset : -3023963517
,06-30 14:02:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:02:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:02:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:02:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:02:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:02:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:02:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:02:00.840   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:05.845   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:10.849   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:15.304   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:02:15.307  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:02:15.307  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:02:15.307  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:02:15.307  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:02:15.309  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:02:15.346  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
06-30 14:02:15.346  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:02:15.347  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
,06-30 14:02:15.350  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:02:15.351  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:02:15.352  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:02:15.352  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:02:15.352  1862  2050 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
06-30 14:02:15.356   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:02:15.357  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:02:15.854   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:19.090   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:02:19.090   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:02:19.090   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 732486180246; DSPS: 24100823; Offset : -3023958506
,06-30 14:02:20.858   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:25.863   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:30.868   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:35.872   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:39.091   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:02:39.091   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:02:39.091   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 752486855655; DSPS: 24756205; Offset : -3023954588
,06-30 14:02:40.877   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:45.881   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:50.886   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:55.890   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:02:59.091   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:02:59.091   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:02:59.092   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 772487688512; DSPS: 25411593; Offset : -3023976041
,06-30 14:03:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:03:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:03:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:03:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:03:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:03:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:03:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:03:00.895   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:05.900   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:10.904   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:15.464  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,06-30 14:03:15.467  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:03:15.467  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:03:15.467  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:03:15.467  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:03:15.468   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:03:15.505  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
06-30 14:03:15.505  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:03:15.505  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,06-30 14:03:15.510  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:03:15.510  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:03:15.514  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:03:15.514  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:03:15.514  1862  2050 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
06-30 14:03:15.518   848  1316 D WifiController: battery changed pluggedType: 2
,06-30 14:03:15.522  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:03:15.909   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:19.092   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:03:19.092   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:03:19.092   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 792488362879; DSPS: 26066975; Offset : -3023972928
,06-30 14:03:20.913   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:25.918   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:30.923   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:35.927   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:39.093   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:03:39.093   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:03:39.093   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 812489126621; DSPS: 26722360; Offset : -3023972074
,06-30 14:03:40.932   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:45.936   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:50.941   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:55.945   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:03:59.094   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:03:59.094   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:03:59.094   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 832489941406; DSPS: 27377747; Offset : -3023981212
,06-30 14:04:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:04:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:04:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:04:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:04:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:04:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:04:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:04:00.950   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:05.955   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:10.959   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:15.623   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:04:15.626  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:04:15.626  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:04:15.626  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:04:15.626  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:04:15.633  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:04:15.665  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 14:04:15.665  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:04:15.665  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,06-30 14:04:15.669  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:04:15.669  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:04:15.674  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:04:15.675  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:04:15.675  1862  2050 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 14:04:15.675  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:04:15.679   848  1316 D WifiController: battery changed pluggedType: 2
,06-30 14:04:15.964   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:19.095   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:04:19.095   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:04:19.095   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 852491043274; DSPS: 28033143; Offset : -3023978237
,06-30 14:04:20.968   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:25.973   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:28.784  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:04:28.784  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:04:28.785  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:04:28.785  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:04:28.788  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:04:28.802   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:04:30.977   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:35.982   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:39.095   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:04:39.096   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:04:39.096   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 872491723214; DSPS: 28688525; Offset : -3023969529
,06-30 14:04:40.987   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:45.991   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:50.996   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:56.000   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:04:59.096   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:04:59.096   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:04:59.096   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 892492493675; DSPS: 29343910; Offset : -3023961954
,06-30 14:05:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:05:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:05:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:05:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:05:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:05:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:05:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:05:01.005   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:02.911   848  1288 D PowerManagerServiceEx: acquireWakeLockInternal: lock=570302530, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=848
,06-30 14:05:02.919   848  1288 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23a63205 type 2 when 896295 com.google.android.gms} when 896295
06-30 14:05:02.936  2343  7740 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 14:05:02.936  2343  7740 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 14:05:02.937  2343  7740 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 14:05:02.937  2343  7740 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 14:05:02.940   267  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 14:05:02.940   267  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 14:05:02.941   267  7741 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
06-30 14:05:02.941   267  7741 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 14:05:02.942   267  7741 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
06-30 14:05:02.942   848  1049 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
06-30 14:05:02.989   848   899 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7742 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 14:05:03.190  7742  7742 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-30 14:05:03.198  7742  7742 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1d70419d
06-30 14:05:03.200   848  1897 I ActivityManager: Killing 7374:com.google.android.setupwizard/u0a38 (adj 15): empty #11
06-30 14:05:03.285   848   848 D PowerManagerServiceEx: releaseWakeLockInternal: lock=570302530 [*alarm*], flags=0x0
,06-30 14:05:03.288   848  1379 W libprocessgroup: failed to open /acct/uid_10038/pid_7374/cgroup.procs: No such file or directory
06-30 14:05:06.009   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:11.014   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:15.784  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:05:15.784  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:05:15.784  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:05:15.784  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:05:15.787   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:05:15.788  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:05:15.829  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 14:05:15.829  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:05:15.829  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,06-30 14:05:15.833  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:05:15.833  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:05:15.834  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:05:15.835  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:05:15.835  1862  2050 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 14:05:15.838   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:05:15.840  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:05:16.019   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:19.097   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:05:19.097   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:05:19.097   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 912493253667; DSPS: 29999295; Offset : -3023965032
,06-30 14:05:21.023   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:26.028   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:31.032   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:36.037   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:39.098   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:05:39.098   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:05:39.098   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 932493931836; DSPS: 30654677; Offset : -3023958406
,06-30 14:05:41.042   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:46.046   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:51.051   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:56.055   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:05:59.098   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:05:59.098   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:05:59.098   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 952494614433; DSPS: 31310060; Offset : -3023977896
,06-30 14:06:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:06:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:06:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:06:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:06:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:06:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:06:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:06:01.060   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:06.064   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:11.069   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:15.944  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:06:15.944  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:06:15.944  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:06:15.944  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:06:15.946   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:06:15.948  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:06:15.985  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
06-30 14:06:15.985  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:06:15.986  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,06-30 14:06:15.989  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:06:15.989  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:06:15.990  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:06:15.990  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:06:15.990  1862  2050 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
06-30 14:06:15.997   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:06:15.997  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:06:16.073   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:19.099   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:06:19.099   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:06:19.099   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 972495373019; DSPS: 31965445; Offset : -3023981884
,06-30 14:06:21.078   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:26.083   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:31.087   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:36.092   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:39.100   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:06:39.100   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:06:39.100   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 992496105615; DSPS: 32620829; Offset : -3023981944
,06-30 14:06:41.096   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:46.101   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:51.106   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:56.110   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:06:59.101   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:06:59.101   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:06:59.101   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1012496778525; DSPS: 33276211; Offset : -3023980292
,06-30 14:07:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:07:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:07:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:07:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:07:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:07:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:07:00.047  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:07:01.115   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:06.119   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:11.124   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:16.104   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:07:16.107  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:07:16.107  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:07:16.107  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:07:16.114  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:07:16.107  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:07:16.131   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:19.101   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:07:19.101   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:07:19.101   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1032497552475; DSPS: 33931596; Offset : -3023969645
,06-30 14:07:21.135   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:26.140   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:31.144   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:36.149   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:39.102   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:07:39.102   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:07:39.102   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1052498300332; DSPS: 34586981; Offset : -3023984285
,06-30 14:07:41.154   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:46.158   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:51.163   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:56.167   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:07:59.103   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:07:59.103   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:07:59.103   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1072499056783; DSPS: 35242365; Offset : -3023960491
,06-30 14:08:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:08:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:08:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:08:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:08:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:08:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:08:00.047  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:08:01.172   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:06.176   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:11.181   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:16.186   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:16.263   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:08:16.273  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:08:16.273  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:08:16.273  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:08:16.273  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:08:16.273  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:08:16.309  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
06-30 14:08:16.309  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:08:16.309  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,06-30 14:08:16.313  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:08:16.314  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:08:16.315  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:08:16.315  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:08:16.315  1862  2050 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
06-30 14:08:16.317  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:08:16.320   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:08:19.104   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:08:19.104   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:08:19.104   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1092499883389; DSPS: 35897752; Offset : -3023957702
,06-30 14:08:21.190   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:26.195   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:31.199   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:36.215   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:39.104   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:08:39.104   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:08:39.104   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1112500594581; DSPS: 36553136; Offset : -3023978724
,06-30 14:08:41.219   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:46.224   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:51.228   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:56.233   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:08:59.105   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:08:59.105   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:08:59.105   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1132501355146; DSPS: 37208521; Offset : -3023981229
,06-30 14:09:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:09:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:09:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:09:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:09:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:09:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:09:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:09:01.237   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:06.242   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:11.247   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:16.251   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:16.424  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:09:16.424  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:09:16.424  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:09:16.424  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:09:16.426   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:09:16.427  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:09:16.465  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
06-30 14:09:16.465  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:09:16.466  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,06-30 14:09:16.469  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:09:16.469  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:09:16.470  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:09:16.470  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:09:16.470  1862  2050 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
06-30 14:09:16.475  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:09:16.478   848  1316 D WifiController: battery changed pluggedType: 2
,06-30 14:09:19.106   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:09:19.106   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:09:19.106   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1152502098159; DSPS: 37863905; Offset : -3023970795
,06-30 14:09:21.256   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:26.260   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:31.265   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:36.269   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:39.107   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:09:39.107   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:09:39.107   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1172502860391; DSPS: 38519290; Offset : -3023971580
,06-30 14:09:41.274   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:46.279   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:51.283   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:56.288   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:09:59.107   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:09:59.107   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:09:59.107   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1192503522206; DSPS: 39174672; Offset : -3023980605
,06-30 14:10:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:10:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:10:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:10:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:10:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:10:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:10:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:10:01.292   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:06.297   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:11.302   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:16.306   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:16.583   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:10:16.593  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:10:16.593  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:10:16.593  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:10:16.593  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:10:16.594  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:10:19.108   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:10:19.108   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:10:19.108   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1212504195220; DSPS: 39830054; Offset : -3023979419
,06-30 14:10:21.315   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:26.320   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:31.238   848   898 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:10:31.324   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:36.329   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:39.109   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:10:39.109   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:10:39.109   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1232505385264; DSPS: 40485453; Offset : -3023979613
,06-30 14:10:41.333   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:46.338   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:51.343   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:56.347   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:10:59.110   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:10:59.110   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:10:59.110   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1252506145985; DSPS: 41140838; Offset : -3023981623
,06-30 14:11:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:11:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:11:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:11:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:11:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:11:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:11:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:11:01.352   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:06.356   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:11.361   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:16.367   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:16.743  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:11:16.744  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,06-30 14:11:16.746   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:11:16.748  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:11:16.753  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:11:16.754  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:11:19.111   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:11:19.111   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:11:19.111   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1272506835769; DSPS: 41796220; Offset : -3023963565
,06-30 14:11:21.371   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:26.376   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:31.380   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:36.385   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:39.111   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:11:39.111   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:11:39.111   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1292507601386; DSPS: 42451605; Offset : -3023960575
,06-30 14:11:41.389   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:46.394   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:51.399   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:56.403   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:11:59.112   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:11:59.112   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:11:59.112   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1312508321535; DSPS: 43106989; Offset : -3023973030
,06-30 14:12:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:12:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:12:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:12:00.045  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:12:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:12:00.046  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:12:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:12:01.408   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:06.412   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:11.417   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:16.421   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:16.904  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:12:16.904  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:12:16.904  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:12:16.904  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:12:16.906   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:12:16.907  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:12:16.945  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
06-30 14:12:16.945  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:12:16.946  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,06-30 14:12:16.949  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:12:16.949  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:12:16.950  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:12:16.950  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:12:16.950  1862  2050 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
06-30 14:12:16.954  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:12:16.958   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:12:19.113   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:12:19.113   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:12:19.113   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1332508993454; DSPS: 43762371; Offset : -3023972315
,06-30 14:12:21.426   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:26.431   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:31.435   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:36.440   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:39.114   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:12:39.114   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:12:39.114   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1352509728655; DSPS: 44417755; Offset : -3023969693
,06-30 14:12:41.444   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:46.449   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:51.454   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:56.458   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:12:59.115   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:12:59.115   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:12:59.115   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1372510826200; DSPS: 45073151; Offset : -3023970755
,06-30 14:13:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:13:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:13:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:13:00.043  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:13:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:13:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:13:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:13:01.463   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:06.467   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:11.472   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:16.476   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:17.063   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:13:17.066  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:13:17.066  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:13:17.066  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:13:17.073  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:13:17.073  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:13:19.115   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:13:19.115   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:13:19.115   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1392511579682; DSPS: 45728536; Offset : -3023980289
,06-30 14:13:21.481   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:26.486   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:31.490   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:36.495   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:39.116   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:13:39.116   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:13:39.116   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1412512353893; DSPS: 46383921; Offset : -3023968992
,06-30 14:13:41.499   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:46.504   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:51.508   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:56.513   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:13:59.117   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:13:59.117   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:13:59.117   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1432513108886; DSPS: 47039306; Offset : -3023976600
,06-30 14:14:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:14:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:14:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:14:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:14:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:14:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:14:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:14:01.518   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:06.522   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:11.527   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:16.531   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:17.224  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:14:17.224  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:14:17.224  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:14:17.224  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 14:14:17.226   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:14:17.227  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:14:17.265  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
06-30 14:14:17.265  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:14:17.266  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,06-30 14:14:17.269  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:14:17.269  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:14:17.270  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:14:17.270  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:14:17.270  1862  2050 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
06-30 14:14:17.274  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:14:17.278   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:14:19.118   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:14:19.118   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:14:19.118   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1452513840649; DSPS: 47694690; Offset : -3023977571
,06-30 14:14:21.536   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:26.540   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:31.545   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:36.550   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:39.118   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:14:39.118   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:14:39.118   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1472514586474; DSPS: 48350074; Offset : -3023964012
,06-30 14:14:41.554   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:46.559   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:51.563   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:56.568   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:14:59.119   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:14:59.119   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:14:59.119   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1492515261935; DSPS: 49005456; Offset : -3023959938
,06-30 14:15:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:15:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:15:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:15:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:15:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:15:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:15:00.046  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:15:01.573   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:06.577   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:11.582   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:16.586   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:17.383   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 14:15:17.392  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:15:17.393  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:15:17.393  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:15:17.393  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:15:17.393  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:15:19.120   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:15:19.120   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:15:19.120   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1512516002032; DSPS: 49660841; Offset : -3023983119
,06-30 14:15:21.591   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:26.596   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:31.600   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:36.605   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:39.121   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:15:39.121   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:15:39.121   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1532516675045; DSPS: 50316223; Offset : -3023981102
,06-30 14:15:41.609   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:46.614   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:51.618   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:56.623   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:15:59.121   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:15:59.121   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:15:59.121   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1552517421964; DSPS: 50971607; Offset : -3023966370
,06-30 14:16:00.039  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 14:16:00.039  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 14:16:00.039  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,06-30 14:16:00.044  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 14:16:00.044  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:16:00.045  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
06-30 14:16:00.045  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 14:16:01.628   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:16:06.632   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:16:11.637   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 14:16:16.641   290   345 I ThermalEngine: Sensor:pa_therm0:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),06-30 14:16:17.545  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 14:16:17.546  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 14:16:17.546  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 14:16:17.546  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 14:16:17.549  1862  1862 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 14:16:17.563   481   481 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 14:16:17.597  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
06-30 14:16:17.597  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:16:17.597  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
06-30 14:16:17.604  1911  1911 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 14:16:17.604  1911  1911 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 14:16:17.607  1862  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 14:16:17.608  1862  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 14:16:17.608  1862  2050 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
06-30 14:16:17.613  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 14:16:17.636   848  1316 D WifiController: battery changed pluggedType: 2
06-30 14:16:17.950  7859  7859 D AndroidRuntime: 
06-30 14:16:17.950  7859  7859 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 14:16:17.966  7859  7859 D AndroidRuntime: CheckJNI is OFF
06-30 14:16:18.144   848  2176 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5df025a)
06-30 14:16:18.154   848  1317 D ConnectivityService: dumpNetworkRequest
06-30 14:16:18.155   848  1317 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 14:16:18.155   848  1317 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 14:16:18.158   848  1317 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 14:16:18.174   848  1897 I ActivityManager: Process com.google.android.gms (pid 3303) has died
06-30 14:16:18.295  7859  7859 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 14:16:18.335   848   899 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
06-30 14:16:18.337   848   899 I ActivityManager: Killing 6612:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
06-30 14:16:18.390   848   865 I WindowState: WIN DEATH: Window{34690e74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:16:18.435   848   865 D InputDispatcher: Focus left window: Window{34690e74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:16:18.435   848   865 D InputDispatcher: Window went away: Window{34690e74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 14:16:18.458   848   899 I ActivityManager:   Force finishing activity ActivityRecord{1ddcd403 u0 com.test.thalitest/.MainActivity t241}
06-30 14:16:18.468   848  1063 W PackageSettings: Skipping PackageSetting{3160b908 com.example.hello/10317} due to missing metadata
06-30 14:16:18.531   848  1897 W ActivityManager: Spurious death for ProcessRecord{1e479c8b 6612:com.test.thalitest/u0a30}, curProc for 6612: null
06-30 14:16:18.531   848  1063 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
06-30 14:16:18.534   848  1063 I ActivityManager:   Force finishing activity ActivityRecord{1ddcd403 u0 com.test.thalitest/.MainActivity t241 f}
06-30 14:16:18.534   848  1063 W ActivityManager: Duplicate finish request for ActivityRecord{1ddcd403 u0 com.test.thalitest/.MainActivity t241 f}
06-30 14:16:18.612   848  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 14:16:18.613  1911  1911 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
06-30 14:16:18.616  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
06-30 14:16:18.624  3645  3645 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 14:16:18.635  3645  3645 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-30 14:16:18.635  3645  3645 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
06-30 14:16:18.635  3645  3645 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
06-30 14:16:18.635  3645  3645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 14:16:18.635  3645  3645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 14:16:18.635  3645  3645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 14:16:18.635  3645  3645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 14:16:18.635  3645  3645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 14:16:18.635  3645  3645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 14:16:18.635  3645  3645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 14:16:18.635  3645  3645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 14:16:18.644  2343  2752 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 14:16:18.648  2028  2028 I art     : Explicit concurrent mark sweep GC freed 1837(116KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 3.370ms total 109.853ms
06-30 14:16:18.670   848   899 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7906 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 14:16:18.701  1948  1948 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
06-30 14:16:18.720  1948  1948 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
06-30 14:16:18.725   848  2176 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7923 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
06-30 14:16:18.797  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
06-30 14:16:18.799  1948  1948 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
06-30 14:16:18.800  1948  1948 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
06-30 14:16:18.804  1948  1948 I Activity: Activity.onPostResume() called 
06-30 14:16:18.824  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-30 14:16:18.838  7906  7906 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 14:16:18.839  7906  7906 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 14:16:18.840  7906  7906 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 14:16:18.841  1948  7941 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
06-30 14:16:18.845   848   848 I art     : Explicit concurrent mark sweep GC freed 73949(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/36MB, paused 11.883ms total 272.468ms
06-30 14:16:18.848   848  1063 I art     : WaitForGcToComplete blocked for 115.132ms for cause Explicit
06-30 14:16:18.888   848  1050 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
06-30 14:16:18.890   848  1050 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
06-30 14:16:18.891   848  1050 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-30 14:16:18.891   848  1050 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-30 14:16:18.891   848  1050 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 14:16:18.891   848  1050 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3c84db14,  pkg=WindowManager.LayoutParams
06-30 14:16:18.891   848  1050 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-30 14:16:18.893   848  1059 D InputDispatcher: Focus entered window: Window{21d10fb5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-30 14:16:18.903  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
06-30 14:16:18.910  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
06-30 14:16:18.910  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
06-30 14:16:18.910  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
06-30 14:16:18.910  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
06-30 14:16:18.910  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-30 14:16:18.913  7923  7923 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
06-30 14:16:18.925  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 14:16:18.933  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 14:16:18.935  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
06-30 14:16:18.954  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
06-30 14:16:18.959  1948  1948 I PhoneWindow: [setNavigationBarColor] color=0x 0
06-30 14:16:18.961  1372  1501 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 14:16:18.961  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:18.964  1372  1501 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 14:16:18.964  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:18.966  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:16:18.968  1372  1501 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 14:16:18.970   848  2215 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-30 14:16:18.971  1372  1501 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 14:16:18.971  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:18.973   848  2215 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6612 uid 10030
06-30 14:16:18.980  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-30 14:16:18.981  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:16:18.981  1372  1501 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 14:16:18.982  1372  1501 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 14:16:18.982  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:18.984  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:16:18.984  1372  1501 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 14:16:18.986  1372  1501 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 14:16:18.986  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:18.997  1372  1372 D KeyguardModel: handleShortcutListChanged...
06-30 14:16:18.998  1372  1501 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 14:16:18.998  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:19.000  1372  1501 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 14:16:19.000  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:19.005  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:16:19.006  1372  1501 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 14:16:19.010  1372  1501 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 14:16:19.010  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:19.013  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:16:19.013  1372  1501 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 14:16:19.015  1372  1501 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 14:16:19.015  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:19.017  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 14:16:19.017  1372  1501 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 14:16:19.018  1372  1501 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 14:16:19.019  1372  1501 D KeyguardModel: createShortcutInfo...
06-30 14:16:19.025   848   848 D administrator: Handling package changes for user 0
06-30 14:16:19.030  1372  1372 D KeyguardModel: handleShortcutListChanged...
06-30 14:16:19.045  1948  1948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@673f3ef time:1572441
06-30 14:16:19.064  2028  2028 I HotwordDetector: Closing mic
06-30 14:16:19.065   848  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c7f08d8 u0 com.lge.launcher2/.Launcher t240} time:1572461
06-30 14:16:19.100  1948  1948 I art     : Explicit concurrent mark sweep GC freed 3953(226KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 926us total 53.754ms
06-30 14:16:19.100  1948  1948 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
06-30 14:16:19.100  1627  1627 E b       : Unable to connect to the editor to retrieve text... will retry later
06-30 14:16:19.106  7906  7906 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
06-30 14:16:19.113  1948  1948 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
06-30 14:16:19.122   848  1005 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 14:16:19.122   848  1005 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 14:16:19.122   848  1005 D sensors_hal_Time: tsOffsetIs: Apps: 1572518064925; DSPS: 51626988; Offset : -3023964722
06-30 14:16:19.131  7906  7906 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
06-30 14:16:19.141  2028  2576 I HotwordRecognitionRnr: Stopping hotword detection.
06-30 14:16:19.266   848   848 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
06-30 14:16:19.267   848   848 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 14:16:19.278   848   848 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 14:16:19.285   848  1350 D TaskPersister: removeObsoleteFile: deleting file=241_task.xml
06-30 14:16:19.293   848  1063 I art     : Explicit concurrent mark sweep GC freed 13590(1740KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 5.500ms total 444.835ms
06-30 14:16:19.321  1849  1849 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-30 14:16:19.321  1849  1849 D LCardEmulationManager: getDefaultRoute
06-30 14:16:19.354  7859  7859 D AndroidRuntime: Shutting down VM
06-30 14:16:19.405   848  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7951 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 14:16:19.455  7906  7906 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
06-30 14:16:19.503   848   865 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7968 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-30 14:16:19.504   848   865 I ActivityManager: Killing 7406:com.lge.drmservice/u0a51 (adj 15): empty #11
06-30 14:16:19.534   848  1915 W libprocessgroup: failed to open /acct/uid_10051/pid_7406/cgroup.procs: No such file or directory
06-30 14:16:19.580   848  1897 I ActivityManager: Killing 7466:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
06-30 14:16:19.599  7968  7968 I AppUp4:AppBoxCP: onCreate
06-30 14:16:19.600  7968  7968 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-30 14:16:19.608  7968  7968 I AppUp4:DB:  setFingerPrint start
06-30 14:16:19.609  7968  7968 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
06-30 14:16:19.616  7968  7968 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
06-30 14:16:19.616  7968  7968 I AppUp4:DB:  SDK version = 21
06-30 14:16:19.617  7968  7968 I AppUp4:DB:  beforefinger == newfinger no write in DB
06-30 14:16:19.685   848  1949 W libprocessgroup: failed to open /acct/uid_10079/pid_7466/cgroup.procs: No such file or directory
06-30 14:16:19.688  7968  7968 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
06-30 14:16:19.716  7968  7968 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
06-30 14:16:19.766   848   865 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7992 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
06-30 14:16:19.766   848   865 I ActivityManager: Killing 6416:com.google.process.gapps/u0a6 (adj 15): empty #11
06-30 14:16:19.770  3645  3706 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: Error inserting f004=13 f005=7992 f002=1467288979769 f003=com.android.settings f006=1000
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:708)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2588)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3413)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
06-30 14:16:19.777  3645  3706 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3522)
06-30 14:16:19.792   302   302 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 22.314ms

```
