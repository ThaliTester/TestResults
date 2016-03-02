#### Test 613623660556c10_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
,I/art     ( 2110): Explicit concurrent mark sweep GC freed 17965(994KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.763ms total 48.780ms
D/AndroidRuntime( 5975): 
D/AndroidRuntime( 5975): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5975): CheckJNI is OFF
D/AndroidRuntime( 5975): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1942): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{654f671 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{654f671 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6003 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1030): Focus left window: Window{131f7216 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 2063): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AndroidRuntime( 5975): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1854): Display #0 changed.
D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{14633784 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{1d410b6d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6003): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/WebViewFactory( 6003): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6003): Loading: webviewchromium
,I/LibraryLoader( 6003): Time to load native libraries: 4 ms (timestamps 5791-5795)
I/LibraryLoader( 6003): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6003): Binding Chromium to main looper Looper (main, tid 1) {236b831e}
,I/LibraryLoader( 6003): Expected native library version number "",actual native library version number ""
I/chromium( 6003): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6003): Initializing chromium process, renderers=0
,W/art     ( 6003): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6003): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  315): registerClient() client 0xb1427c40, uid 10311
,W/chromium( 6003): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6003): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6003): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@369f3773:true
D/BluetoothAdapter( 6003): 502147071: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6003): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6003): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6003): Build Date: 12/12/14 금
I/Adreno-EGL( 6003): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6003): Remote Branch: 
I/Adreno-EGL( 6003): Local Patches: 
I/Adreno-EGL( 6003): Reconstruct Branch: 
,W/chromium( 6003): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6003): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6003): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6003): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 6003): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6003): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6003): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 6003): CordovaWebView is running on device made by: LGE
,W/art     ( 6003): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6003): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6003): Render dirty regions requested: true
I/OpenGLRenderer( 6003): Initialized EGL, version 1.4
D/OpenGLRenderer( 6003): Enabling debug mode 0
,W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{21a98c56 u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6003): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{6faecd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6003): LgDataFeature() Constructor: none
D/LgDataFeature( 6003): LgDataFeature() Constructor Done, null
,D/WindowManager( 1030): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,I/[SystemUI]NavigationThemeResource( 1445): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22719796,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1030): Focus entered window: Window{6faecd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputMethodManagerService( 1030): setImestate : 0
,I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +618ms (total +733ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{21a98c56 u0 com.test.thalitest/.MainActivity t4} time:96213
,W/IInputConnectionWrapper( 6003): showStatusIcon on inactive InputConnection
I/Timeline( 6003): Timeline: Activity_idle id: android.os.BinderProxy@248c3ada time:96223
W/IInputConnectionWrapper( 6003): getTextBeforeCursor on inactive InputConnection
,E/b       ( 1688): Unable to connect to the editor to retrieve text... will retry later
W/IInputConnectionWrapper( 6003): getTextAfterCursor on inactive InputConnection
,D/JsMessageQueue( 6003): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6003): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6003): 
,D/jxcore_app_log( 6003): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435017856
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6003): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6003):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6003):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6003):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6003):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6003): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@391f91df added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Bluetooth MAC address: 58:3F:54:73:64:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33590e8a added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6003): addListener: New listener added - the number of listeners is now 1
D/WifiService( 1030): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6003): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6003): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6003): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6003): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6003): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 6003): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6003): 
,I/chromium( 6003): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 97383234759; DSPS: 3331760; Offset : -4306165864
,W/jxcore-log( 6003): Initializing JXcore engine
W/jxcore-log( 6003): JXcore engine is ready
,W/Thread-706( 6064): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[6065]" dev="sockfs" ino=6065 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-706( 6064): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-706( 6064): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7823]" dev="sockfs" ino=7823 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-706( 6064): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/Thread-706( 6064): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28321]" dev="sockfs" ino=28321 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6003): Starting JXcore engine
W/jxcore-log( 6003): Platform android
W/jxcore-log( 6003): 
W/jxcore-log( 6003): Process ARCH arm
W/jxcore-log( 6003): 
,I/jxcore-log( 6003): JXcore Cordova bridge is ready!
I/jxcore-log( 6003): 
W/jxcore-log( 6003): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6003): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  302): 
,I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  903): [IMS_FATAL]| 3347 | 914 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6003): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 6003): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 6003): BLE multiple advertisement supported
I/jxcore-log( 6003): 
I/jxcore-log( 6003): INFO testUtils Toggling radios to: true
I/jxcore-log( 6003): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
I/jxcore-log( 6003): Unit Test app is loaded
I/jxcore-log( 6003): 
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
I/chromium( 6003): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6067 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6003, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6003, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiServiceImplEx( 1030): disconnect pid=6003, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1030): reconnect pid=6003, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
,I/WifiUtil( 1030): gEnableBmps=1
W/ResourcesManager( 6067): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6067): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6067): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 6067): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6067): Loading JNI Library
,D/BluetoothAdapterApp( 6067): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@399d465d Instance Count = 1
,D/SoftapController(  308): Softap fwReload - Ok
,D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring down wlan0
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
,D/Tethering( 1030): InitialState.processMessage what=4
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6093 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
D/BluetoothAdapterApp( 6067): onCreate
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
V/WfdStateTracker( 1942): WfdStateTracker handleDirectStateChangedEvent: 1
,I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/wpa_supplicant( 6099): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6099): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ProfileConfigQcom( 6067): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6067): Adding HeadsetService
D/ProfileConfigQcom( 6067): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6067): Adding A2dpService
D/ProfileConfigQcom( 6067): [BTUI] HidService is supported
D/ProfileConfigQcom( 6067): Adding HidService
D/ProfileConfigQcom( 6067): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6067): Adding HealthService
D/LGBluetoothFeatureConfig( 6067): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6067): [BTUI] PanService is supported
D/ProfileConfigQcom( 6067): Adding PanService
D/ProfileConfigQcom( 6067): [BTUI] GattService is supported
D/ProfileConfigQcom( 6067): Adding GattService
D/ProfileConfigQcom( 6067): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6067): Adding BluetoothMapService
D/ProfileConfigQcom( 6067): [BTUI] HeadsetClientService is NOT supported
,I/wpa_supplicant( 6099): Successfully initialized wpa_supplicant
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3291b545:true
,D/BluetoothAdapterState( 6067): make
I/wpa_supplicant( 6099): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6099): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
I/LGFMServiceAdapter( 6067): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6067): init
I/BluetoothAdapterState( 6067): Entering OffState
I/bte_conf( 6067): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6067): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6067): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6067): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6067): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6067): get_profile_interface socket
I/bluedroid-qcom( 6067): get_profile_interface map_client
W/bdaddr_loader( 6127): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GKI_LINUX( 6067): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6067): config_hci_snoop_log
W/bdaddr_loader( 6127): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/lge_bdaddr_loader( 6127): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6127): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6127): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6127): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterProperties( 6067): Address is:58:3F:54:73:64:C0
,D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6067): Name is: G3-1
E/lge_bdaddr_loader( 6127): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6127): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6067): Create singleton instance
W/ResourcesManager( 6093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6093): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6093): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6093): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6093): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6093): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6099): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterState( 6067): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6067): Setting state to 11
,I/BluetoothAdapterState( 6067): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
I/[SystemUI]BluetoothHandler( 1445): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1942): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/LGBluetoothServiceJni( 6067): classInitNative: succeeds
D/BluetoothBondStateMachine( 6067): make
I/BluetoothBondStateMachine( 6067): StableState(): Entering Off State
,D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
D/LGBluetoothServiceAdapter( 6067): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
D/LGBluetoothServiceAdapter( 6067): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6067): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
,D/BluetoothHeadset( 1854): Proxy object connected
D/HeadsetService( 6067): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6067): classInitNative: succeeds
D/BluetoothHeadset( 1854): Proxy object connected
D/LGBluetoothHfpAdapter( 6067): Version 1.6
D/BluetoothHeadset( 1854): Proxy object connected
D/BluetoothHeadset( 1030): Proxy object connected
D/LGBluetoothFeatureConfig( 6067): isPrivacyLogsEnabled : true
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
I/BluetoothHeadsetServiceJni( 6067): classInitNative: succeeds
D/HeadsetStateMachine( 6067): make
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
,I/wpa_supplicant( 6099): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
E/BluetoothAdapterService( 6067): File transfer profiles supported!!
D/LgDataFeature( 6067): LgDataFeature() Constructor: none
D/LgDataFeature( 6067): LgDataFeature() Constructor Done, null
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6093): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6093): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6093): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/wpa_supplicant( 6099): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6099): wlan0: CTRL-EVENT-SCAN-STARTED 
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/HeadsetStateMachine( 6067): max_hf_connections = 1
I/bluedroid-qcom( 6067): get_profile_interface handsfree
V/ToneGenerator( 6067): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  315): registerClient() client 0xb1427d40, uid 1002
V/AudioPolicyManager(  315): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6067): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  315): registerClient() client 0xb12446b8, pid 6067
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1854): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1854): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2199): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2199): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3299): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3299): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1854): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1854): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2199): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2199): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1445): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1445): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1445): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1445): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6067): Create Track: 0xb4928a80
V/AudioTrack( 6067): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6067): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3299): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3299): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6067): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6067): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 6067): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6067): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/,AudioPolicyManagerEx(  315): getOutput() returns output 2
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6067): getLatency() output 2, latency 50
V/AudioSystem( 6067): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6067): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): createTrack() lSessionId: 16
V/AudioTrack( 6067): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  315): acquiring 16 from 6067, for 6067
V/AudioFlinger(  315):  added new entry for 16
V/ToneGenerator( 6067): ToneGenerator INIT OK, time: 103946
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
D/HeadsetStateMachine( 6067): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6067): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6067): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6067): [BTUI] change sampling rate to 8000 when device is disconnected
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
V/AudioFlinger(  315): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6067
D/audio_hw_primary(  315): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  315): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  315): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  315): voice_extn_compress_voip_set_parameters: exit
V/voice   (  315): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  315): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  315): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  315): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  315): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  315): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  315): adev_set_parameters: ERROR: set param called even when stream out is null
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
V/ToneGenerator( 6067): ToneGenerator destructor
V/ToneGenerator( 6067): stopTone
V/ToneGenerator( 6067): Delete Track: 0xb4928a80
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
D/BluetoothA2dp( 1030): Proxy object connected
D/A2dpService( 6067): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6067): classInitNative: succeeds
V/Avrcp   ( 6067): make
D/Avrcp   ( 6067): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6067): get_profile_interface avrcp
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
V/LGMDMManager( 6067): Create singleton instance
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
V/AudioTrack( 6067): ~AudioTrack, releasing session id from 6067 on behalf of 6067
V/AudioFlinger(  315): releasing 16 from 6067 for 6067
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): purging stale effects
V/AudioPolicyService(  315): AudioCommandThread() adding release output 2
V/AudioPolicyService(  315): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  315): AudioCommandThread() waking up
V/AudioPolicyService(  315): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  315): releaseOutput() 2
V/AudioPolicyService(  315): AudioCommandThread() going to sleep
V/AudioFlinger(  315): PlaybackThread::Track destructor
V/AudioFlinger(  315): removeClient_l() pid 6067, calling pid 315
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
W/Process ( 1030): Unable to open /proc/6133/status
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_RECONNECT 0 0
D/UsbSettingsControl( 6093): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : availableList=[wlan0]
E/WifiStateMachine( 1030):  DefaultState CMD_RECONNECT 0 0
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6093): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 6093): [AUTORUN] setTetherStatus() : status=false
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
I/ActivityManager( 1030): Killing 5607:com.google.android.apps.docs/u0a61 (adj 15): empty #17
V/AudioManager( 6067): registerRemoteController: size of Media player list: 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
I/BluetoothAdapterState( 6067): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/WifiNative-wlan0( 1030): doString: [DRIVER MACADDR]
E/AudioManager( 6067): No RCC entry present to update
E/RemoteController( 6067): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothAvrcpQcomServiceJni( 6067): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6067): initQcomNative: succeeds
D/WifiNative-wlan0( 1030):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1030): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1030): setPowerSaveActivated(false)
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] [+] updateMediaPlayerInfo
W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5607/cgroup.procs: No such file or directory
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
D/WfdService( 1942): Waiting for WifiP2p enabling
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6093): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6093): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6093): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
D/WifiStateMachine( 1030): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1030): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1030): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1030): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1030): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1030): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET serial_number LGD8553bed2d08
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0( 1030): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
,D/WfdsService( 1942): Supplicant Connection state is changed : true
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/UsbSettingsControl( 6093): [AUTORUN] getUsbConnected() : connected=true
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1942): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1942): Set the WFDS Monitor: true
W/Settings( 5357): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6093): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WfdsMonitor( 1942): WfdsMonitorThread create
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/UsbSettingsControl( 6093): [AUTORUN] setTetherStatus() : status=false
D/WfdsMonitor( 1942): WFDS Monitor is created and started
D/WfdsService( 1942): WiFi: Supplicant connection re-established
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989a58dc
E/CtrlSupplicant( 1942): Access OK "@android:wpa_wlan0"
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301ec2
I/WifiNative-HAL( 1030): Could not start hal
E/CtrlSupplicant( 1942): Succeed to open control connection
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/CtrlSupplicant( 1942): Succeed to open monitor connection
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989a585c
D/WfdsMonitor( 1942): Supplicant connection established
D/WfdsService( 1942): Connected to the supplicant for wfds
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401eb2
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6138 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6099): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [104,098,239 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/RttService( 1030): SCAN_AVAILABLE : 3
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94e6c99c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501eae
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/RttService( 1030): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring up p2p0
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
V/WfdStateTracker( 1942): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1942): WifiP2pState is changed : true
D/WfdsService( 1942): Receive the WFDS_ENABLE Method
D/WfdsService( 1942): Set the WFDS Monitor: true
D/WfdsService( 1942): Connected to the supplicant for wfds
D/WfdsJNI ( 1942): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6099): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1942): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6099): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1942): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1942): selectPreferredScanChannel [36]
D/WfdsService( 1942): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6099): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
D/WfdsService( 1942): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1942): isConnected: false
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1030): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_name G3-1
,D/WifiNative-p2p0( 1030): SET device_name G3-1: returned true
D/LGWifiP2pService( 1030): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1030): before postfix = G3-1
D/WifiServerServiceExt( 1030): postfix byte check : 4
D/LGWifiP2pService( 1030): after postfix = G3-1
D/WifiNative-p2p0( 1030): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1030): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1030): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SET conc_pref p2p
D/WifiService( 1030): New client listening to asynchronous messages
D/WifiNative-p2p0( 1030): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1030): p2pGetDeviceAddress
D/WifiNative-HAL( 1030): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] installed app name: Music
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6099): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6067): classInitNative
I/BluetoothA2dpServiceJni( 6067): classInitNative: succeeds
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
D/A2dpStateMachine( 6067): make
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
I/WfdStateTracker( 1942): handleP2pThisDeviceChanged
D/WifiNative-p2p0( 1030):    returned network id / ssid / bssid / flags
D/WfdsService( 1942): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
D/WfdsService( 1942): Update P2p Interface State: 3
I/bluedroid-qcom( 6067): get_profile_interface a2dp
I/GKI_LINUX( 6067): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
I/LGBluetoothA2dpServiceJni( 6067): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6067): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
D/A2dpStateMachine( 6067): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6067): classInitNative: succeeds
,D/HidService( 6067): Received start request. Starting profile...
I/bluedroid-qcom( 6067): get_profile_interface hidhost
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
I/BluetoothHealthServiceJni( 6067): classInitNative: succeeds
D/HealthService( 6067): Received start request. Starting profile...
D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
D/LGWifiP2pService( 1030): InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/bluedroid-qcom( 6067): get_profile_interface health
,D/LGWifiP2pService( 1030): P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
I/LGBluetoothHealthServiceJni( 6067): classInitNative: succeeds
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
I/wpa_supplicant( 6099): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6099): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6099): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/BluetoothPanServiceJni( 6067): classInitNative(L105): succeeds
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
I/wpa_supplicant( 6099): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/PanService( 6067): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6067): initializeNative(L110): pan
I/bluedroid-qcom( 6067): get_profile_interface pan
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6099): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6099): [LGE_PATCH] driver_cmd() country:CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6099): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6099): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.St,ateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-6ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-6ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-6ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-6ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1942): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
W/WfdsService( 1942): DefaultState - msg [9441285] is not handled
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1030): InactiveState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-7ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-6ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-6ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-6ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6099): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiServerServiceExt( 1030): No p2p device connected
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WifiNative-wlan0( 1030): SCAN: returned false
,I/LGBluetoothPanAdapter( 6067): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=104152  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/BtGatt.JNI( 6067): classInitNative(L901): classInitNative: Success!
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=104156  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/BtGatt.DebugUtils( 6067): handleDebugAction() action=null
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/BtGatt.GattService( 6067): Received start request. Starting profile...
D/BtGatt.GattService( 6067): start()
I/bluedroid-qcom( 6067): get_profile_interface gatt
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/BtGatt.AdvertiseManager( 6067): advertise manager created
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
,D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
I/LGBluetoothMapAdapter( 6067): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6067): BluetoothMapBinder()
D/BluetoothMapService( 6067): Received start request. Starting profile...
D/BluetoothMapService( 6067): start()
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6168 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothMapEmailSettingsLoader( 6067): Found 0 applications
D/BluetoothMapEmailAppObserver( 6067): createReceiver()
D/BluetoothMapEmailAppObserver( 6067): initObservers()
D/BluetoothMapEmailAppObserver( 6067): getEnabledAccountItems()
W/FormManager( 6138): Network not available. Please check & try again.
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
D/HeadsetStateMachine( 6067): Proxy object connected
D/LGBluetoothHfpAdapter( 6067): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6067): Try to query the phonestate on bind
V/FormManager( 6138): Network unavailable.
D/BluetoothPhoneService.BluetoothLTECall( 1854):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1854): Proxy not attached to service
D/BluetoothHeadset( 1854): java.lang.Throwable
D/BluetoothHeadset( 1854): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1854): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1854): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1854): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1854): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1854): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1854): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1854): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1854): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1854): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/BluetoothAdapterService( 6067): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6067): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6067): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/BluetoothPbapReceiver( 6067): PbapReceiver onReceive 
D/HeadsetStateMachine( 6067): Disconnected process message: 11, size: 0
V/FormManager( 6138): Network unavailable.
V/BluetoothPbapReceiver( 6067): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6067): ***********state = 11
D/BluetoothAdapterService( 6067): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6067): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6067): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6067): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6067): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6067): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6067): Handler(): got msg=1
D/BluetoothAdapterState( 6067): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6067): enable
I/bt_hci_bdroid( 6067): init
I/GKI_LINUX( 6067): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6067): btu_task pending for preload complete event
I/bt_vendor( 6067): bt-vendor : init
I/bt_vendor( 6067): bt-vendor : get_bt_soc_type
E/bt_vendor( 6067): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6067): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6067): userial_init
D/bt_hci_bdroid( 6067): set_power 1
I/bt_vendor( 6067): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6067): Starting hciattach daemon
I/bt_vendor( 6067): try to set true
W/sh      ( 6189): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/sh      ( 6189): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/qcom-bluetooth( 6192): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6190 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5686:com.lge.eula/1000 (adj 15): empty #17
D/PCSuite ( 6168): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5686/cgroup.procs: No such file or directory
I/qcom-bluetooth( 6215): /system/etc/init.qcom.bt.sh: Transport : smd 
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/qcom-bluetooth( 6216): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/WifiService( 1030): New client listening to asynchronous messages
I/qcom-bluetooth( 6220): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6221): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/ActivityThread( 6190): Failed to find provider info for com.lge.lgaccount.provider
D/LgDataFeature( 6093): LgDataFeature() Constructor: none
D/LgDataFeature( 6093): LgDataFeature() Constructor Done, null
W/LG Account v2.2( 6190): No ProfileInfo entries
I/LG Account v2.2( 6190): isEnabled: false
I/Feature ( 6190): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6190): [Lifetracker]Country: EU
I/Feature ( 6190): [Lifetracker]Operator: OPEN
I/Feature ( 6190): [Lifetracker]Ranking support: false
I/Feature ( 6190): [Lifetracker]Comfort support: false
I/Feature ( 6190): [Lifetracker]Accessory: true
I/Feature ( 6190): [Lifetracker]Health device: true
I/Feature ( 6190): [Lifetracker]Extra Pedometer: false
I/Feature ( 6190): [Lifetracker]Blood glucose device: false
I/Feature ( 6190): [Lifetracker]Device Number: 3
,I/ActivityManager( 1030): Killing 5785:com.lge.bnr/1000 (adj 15): empty #17
I/qcom-bluetooth( 6224): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WiFiOffLoadUpdatePriority( 6093): remove : truetruetrue
E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/qcom-bluetooth( 6225): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,I/libmdmdetect( 6228): ESOC framework not supported
E/Diag_Lib( 6228):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6228): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6228): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6228): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6228): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6228): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6228): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6228): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5785/cgroup.procs: No such file or directory
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6093): remove1
V/WiFiOffLoadSharedPrefsUtils( 6093): save remove
D/WiFiOffLoadBroadcast( 6093): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6093): S: false, R: false
E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/WiFiOffLoadUpdatePriority( 6093): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6093): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6093): private wpa: "NG700" 300
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6093, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1030):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1030):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1030):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1030):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1030): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1030): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1030): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1030): SET_NETWORK 0 proto WPA RSN: returned true
,D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1030): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1030): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1030): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1030): will read network variables netId=0
,E/WifiConfigStore( 1030): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1030):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6093):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6093): configuration updated: 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6093): configuration saved: true
D/BluetoothPermissionRequest( 6093): onReceive
,D/LGBluetoothFeatureConfig( 6093):  get() - isFeatureLoaded : false
E/wpa_supplicant( 6099): USIM:  scard_init function
I/wpa_supplicant( 6099): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@debdb9b:true
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/ActivityManager( 1030): Killing 5357:com.google.android.talk/u0a72 (adj 15): empty #17
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989a58cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x901be6
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
D/LGBluetoothResetSettingReceiver( 6093): return without doing reset settings.
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_5357/cgroup.procs: No such file or directory
,D/LGBluetoothOppAdapter( 6067): [BTUI] getInstance : create [LGBluetoothOppAdapter]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=104522  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=104534  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothFtpReceiver( 6067): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
,D/PCSuite ( 6168): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/BluetoothSapReceiver( 6067): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6067): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6067): SapReceiver onReceive 
V/BluetoothSapReceiver( 6067): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6067):  Bluetooth Adapter state = 11
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
I/wpa_supplicant( 6099): wlan0: Associated with f4:f2:6d:22:99:3e
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with f4:f2:6d:22:99:3e
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=104596  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=104597  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=104599
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=104600
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=104601
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=104602
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=104602
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=104603  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
I/wpa_supplicant( 6099): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6099): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6235 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/FormManager( 6138): Network not available. Please check & try again.
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=104630  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=104633  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     (  350): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 517us total 22.029ms
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=104637  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=104642
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=104643
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1030):    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,D/LGDMClient( 3999): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3999): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
W/ContextImpl( 3999): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 408us total 19.980ms
V/FormManager( 6138): Network unavailable.
,W/ContextImpl( 3999): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3999): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 370us total 17.153ms
,D/LGDMClient( 3999): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3999): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/MusicWidget( 2626): mDelayedStopHandler : unbind
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
V/FormManager( 6138): Network unavailable.
,I/MusicBrowser( 2199): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2199): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2199): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2199): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2199): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/MusicBrowser( 2199): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1030):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@11485dfccom.lge.music.MediaPlaybackService$5@155afc85
,D/MusicBrowser( 2199): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
W/ResourcesManager( 6235): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/MusicBrowser( 2199): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3b07451b
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2199): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
I/MusicBrowser( 2199): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2199): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/ActivityManager( 1030): Killing 5516:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,W/ResourcesManager( 6254): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  308): Setting iface cfg
D/PluginManager( 6254): init()
,D/AuthorizationBluetoothService( 2110): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5516/cgroup.procs: No such file or directory
,I/MusicBrowser( 2199): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2199): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2199): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2199): reset
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1030): WaitBeforeStartState
V/MediaPlayer[Native]( 2199): setListener
V/MediaPlayer[Native]( 2199): disconnect
V/MediaPlayer[Native]( 2199): destructor
V/AudioFlinger(  315): releasing 13 from 2199 for -1
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): purging stale effects
V/MediaPlayer[Native]( 2199): disconnect
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=104882  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=104883  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
D/MusicBrowser( 2199): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=104884  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
I/SmartShareClient( 2199): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2199): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2199): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2199): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2199): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2199): [SmartShareManagerClient] unregisterListener: 613169882
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
W/SmartShareClient( 2199): [SmartShareManagerClient] unregisterListener invalid listener: 613169882
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
I/SmartShareClient( 2199): [SmartShareManagerClient] terminate service: 2199/MediaPlaybackService/200076121
,E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=104898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=104898  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=104899  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/HomeCloudIF( 2199): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2199): [SmartShareManagerClient] unbindService context:android.app.Application@283fab0b
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:914971269] from screen [on:0 period:914971269]
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:914971270]
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989a58bc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x502226
I/WifiNative-HAL( 1030): Could not start hal
V/CloudHub( 2199): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/CloudHub( 2199): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2199): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2199): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
I/ActivityManager( 1030): Killing 5534:com.android.contacts/u0a19 (adj 15): empty #17
I/CloudHub( 2199): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5534/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3407437b target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3407437b target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
,W/ExternalStrings( 6254): load override strings
,W/ExternalStrings( 6254): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6254): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6254): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6254): 	at com.mcafee.plugin.ak.d(Unknown Source)
,W/ExternalStrings( 6254): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6254): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6254): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6254): 	,at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6254): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6254): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6254): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344),
W/ExternalStrings( 6254): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6254): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6254): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6254): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6254): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6254): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6254): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6254): onCreate
,V/Signer  ( 6254): override build config not found
D/Signer  ( 6254): value of property debug is false
,D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,D/LGMDMWrapper( 6254): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 6254): Create singleton instance
,D/LGMDMWrapper( 6254): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 6168): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :f4:f2:6d:22:99:3e
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,D/PCSuite ( 6168): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6168): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
W/dhcpcd  ( 6281): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6281): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 5096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/dhcpcd  ( 6281): version 5.5.6 starting
E/dhcpcd  ( 6281): get_duid: m
D/dhcpcd  ( 6281): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6281): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
I/ActivityManager( 1030): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6289 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1030): Killing 5583:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/dhcpcd  ( 6281): getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
D/dhcpcd  ( 6281): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
D/dhcpcd  ( 6281): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6281): wlan0: rebinding lease of 192.168.1.109
D/dhcpcd  ( 6281): wlan0: sending REQUEST (xid 0x7e068454), next in 4.29 seconds
I/dhcpcd  ( 6281): wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,W/ActivityThread( 6254): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/dhcpcd  ( 6281): wlan0: leased 192.168.1.109 for 172800 seconds
D/dhcpcd  ( 6281): wlan0: adding IP address 192.168.1.109/24
,D/dhcpcd  ( 6281): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6281): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6281): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5583/cgroup.procs: No such file or directory
D/dhcpcd  ( 6281): getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
D/dhcpcd  ( 6281): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
D/dhcpcd  ( 6281): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/QC-QMI  ( 6228): qmi_client [6228] 13: failed to locate client data
E/QC-QMI  (  461): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  461): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/[BNRBootReceiver]( 6289): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 6289): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 6289): Boot Receiver Return
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
W/MainApplication( 6289): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
I/qcom-bluetooth( 6324): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/qcom-bluetooth( 6333): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6093): Not supported operator for automatic switch
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/bt_vendor( 6067): bluetooth satus is on
D/bt_hci_bdroid( 6067): preload
,D/bt_userial_mct( 6067): userial_open(port:0)
I/bt_vendor( 6067): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6067): Done intiailizing UART
I/bt_vendor( 6067): Done intiailizing UART
I/bt_userial_mct( 6067): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6067): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6067): btu_task received preload complete event
D/bt_userial_mct( 6067): Entering userial_read_thread()
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x001f
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6067): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6067): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6067): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6067): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6067): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6067): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6067): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6067): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6067): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6067): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6067): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6067): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6067): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6067): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6067): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6067): BTE_InitTraceLevels -- TRC_BTIF
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5096): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/bt-btm  ( 6067): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6067): BTM_SecRegister:p_cb_info->p_le_callback == 0xa0222061 
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
E/bt-btm  ( 6067): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0222061 
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/bt-btif ( 6067): Calling BTA_HhEnable
E/bt-btif ( 6067): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x001b
D/BluetoothAdapterProperties( 6067): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x0013
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6093): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6093): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6093): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6067): Name is: G3-1
D/BluetoothAdapterProperties( 6067): Scan Mode:20
D/UsbSettingsControl( 6093): [AUTORUN] getUsbConnected() : connected=true
D/BluetoothAdapterProperties( 6067): Discoverable Timeout:120
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : availableList=[wlan0]
D/bt_hci_bdroid( 6067): postload
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6093): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6093): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/bt_hci_bdroid( 6067): Used up Tx Cmd credits
D/UsbSettingsControl( 6093): [AUTORUN] setTetherStatus() : status=false
W/bt-l2cap( 6067): L2CAP - L2CA_Register() called for PSM: 0x000f
W/bt-smp  ( 6067): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6067): Plain text(LSB ~ MSB) = fb b3 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6067): Encrypted text(LSB ~ MSB) = 35 80 73 16 b2 67 f9 fd f9 bb 93 0a 3d 10 e1 fd 
W/bt-btm  ( 6067): Stopping oneshot timer
D/bt_hci_bdroid( 6067): Used up Tx Cmd credits
D/bt_hci_bdroid( 6067): Used up Tx Cmd credits
D/bt_hci_bdroid( 6067): Used up Tx Cmd credits
D/bt_hci_bdroid( 6067): Used up Tx Cmd credits
D/bt_hci_bdroid( 6067): Used up Tx Cmd credits
E/bt_mct  ( 6067): hci lib postload completed
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/bte_conf( 6067): Device ID record 1 : primary
D/bte_conf( 6067):   vendorId            = 00c4
D/bte_conf( 6067):   vendorIdSource      = 0001
D/bte_conf( 6067):   product             = 13a1
,D/bte_conf( 6067):   version             = 1000
D/bte_conf( 6067):   clientExecutableURL = 
D/bte_conf( 6067):   serviceDescription  = 
D/bte_conf( 6067):   documentationURL    = 
D/bte_conf( 6067): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6067): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6067): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6067): ScanMode =  20
D/BluetoothAdapterProperties( 6067): State =  11
D/BluetoothAdapterProperties( 6067): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6067): [BTUI] state:11, scanmode:20, timeout:120
W/bt-smp  ( 6067): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
D/BluetoothAdapterProperties( 6067): Setting state to 12
W/bt-smp  ( 6067): Plain text(LSB ~ MSB) = de 88 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/BluetoothAdapterState( 6067): Bluetooth adapter state changed: 11-> 12
W/bt-smp  ( 6067): Encrypted text(LSB ~ MSB) = 79 2f f7 3f 9d d8 a4 1e 8c 54 1e bb ca dd 29 0a 
W/bt-btm  ( 6067): Stopping oneshot timer
W/sh      ( 6346): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6346): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/btif_config_util( 6067): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/BluetoothManagerService( 1030): Message: 60
I/BluetoothAdapterState( 6067): Entering On State
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1854): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1854): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1854): onBluetoothStateChange: up=true
,E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothServiceAdapter( 6067): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6067): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6067): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6067): [BTUI] autoConnect() : not allowed
I/[SystemUI]BluetoothHandler( 1445): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
W/bt-smp  ( 6067): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6067): Plain text(LSB ~ MSB) = b7 e0 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6067): Encrypted text(LSB ~ MSB) = 3f fb 61 58 0a 43 7c de cc 2b 87 b4 9b 3d a5 58 
W/bt-btm  ( 6067): Stopping oneshot timer
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1942): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothAPIService( 1942): Message: 1
D/LGBluetoothAPIService( 1942): MESSAGE_BOOT_COMPLETED
I/ActivityManager( 1030): Killing 5640:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/bt-smp  ( 6067): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6067): Plain text(LSB ~ MSB) = 87 d6 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6067): Encrypted text(LSB ~ MSB) = 68 5b d7 b3 05 ed e4 2f f6 a3 aa 5b a6 63 7a 0c 
W/bt-btm  ( 6067): Stopping oneshot timer
,W/bt-smp  ( 6067): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6067): Plain text(LSB ~ MSB) = 7c 5c 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6067): Encrypted text(LSB ~ MSB) = d8 87 22 cb ec e0 28 61 95 60 ab 5c fa f7 d5 28 
W/bt-btm  ( 6067): Stopping oneshot timer
W/ContextImpl( 6093): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 5
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6099): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1030): RunningState
D/LgDataFeature( 6254): LgDataFeature() Constructor: none
,D/LgDataFeature( 6254): LgDataFeature() Constructor Done, null
D/LGBluetoothDeviceModeControllManager( 6067): [BTUI] checkDeviceModeAndSet, sinkMode : false
I/qcom-bt-wlan-coex( 6354): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/BluetoothAdapterProperties( 6067): Discoverable Timeout:120
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/LGBluetoothDeviceModeControllManager( 6067): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
I/BluetoothMapService( 6067): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6067): STATE_ON
V/BluetoothPbapReceiver( 6067): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6067): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6067): ***********state = 12
,I/LGBluetoothAPIService( 1942): [BTUI] LGBluetoothAPIService Binding Success
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5640/cgroup.procs: No such file or directory
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
V/BluetoothPbapService( 6067): Pbap Service onCreate
V/BluetoothPbapService( 6067): Starting PBAP service
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothPbapAdapter( 6067): [BTUI] getInstance : create
,D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
V/BluetoothPbapService( 6067): action: android.bluetooth.adapter.action.STATE_CHANGED
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
V/BluetoothPbapService( 6067): state: 12
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1445): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
V/WfdStateTracker( 1942): handleWifiStateChangedEvent: 1
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100,
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 3
,D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1854): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1854):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
,E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/LGBluetoothAPIServer( 6067): [BTUI] onCreate()
V/BluetoothMapService( 6067): Handler(): got msg=1
D/BluetoothMapMasInstance( 6067): Map Service startRfcommSocketListener
D/LGBluetoothAPIServer( 6067): [BTUI] onBind()
D/BluetoothMapMasInstance( 6067): MAS initSocket()
D/BluetoothMapMasInstance( 6067):   masId = 00
D/BluetoothMapMasInstance( 6067):   msgTypes = 0e
D/BluetoothMapMasInstance( 6067):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6067):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6067): getBluetoothService() called with no BluetoothManagerCallback
I/StatusBar.NetworkController( 1445): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1445): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothServiceAdapter( 6067): [BTUI] createSocketChannel FD=73 mFd=0
,V/BluetoothMapMasInstance( 6067): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6067): Accepting socket connection...
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
W/dsqn    ( 6364): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6364): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
E/DSQN    ( 6364): DSQN ssw
,D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 1030): Explicit concurrent mark sweep GC freed 71958(3MB) AllocSpace objects, 4(70KB) LOS objects, 33% free, 43MB/65MB, paused 1.614ms total 81.047ms
V/BluetoothPbapService( 6067): Handler(): got msg=1
,V/BluetoothPbapService( 6067): Pbap Service startRfcommSocketListener
D/BluetoothAdapterProperties( 6067): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6067): getDeviceMode  deviceMode 0
D/LGBluetoothAPIService( 1942): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1942): Message: 100
D/LocalBluetoothProfileManager( 6093): Adding local A2DP profile
D/LGBluetoothAPIService( 1942): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService( 1030): Message: 30
V/BluetoothPbapService( 6067): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LocalBluetoothProfileManager( 6093): Adding local HEADSET profile
W/BluetoothAdapter( 6067): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6067): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6067): Succeed to create listening socket 
V/BluetoothPbapService( 6067): Accepting socket connection...
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org succeed
D/BluetoothManagerService( 1030): Message: 30
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/LocalBluetoothProfileManager( 6093): Adding local MAP profile
D/BluetoothMap( 6093): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6093): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6067): Pbap Service onBind
D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/LGBluetoothUserBindClient( 6093): [BTUI] initUserBindClient
W/ContextImpl( 6093): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/libc-netbsd(  308): res_queryN name = europe.pool.ntp.org succeed
D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/DockEventReceiver( 6093): finishStartingService: stopping service
D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/SiteAdvisor( 6254): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/BluetoothA2dp( 6093): Proxy object connected
D/A2dpProfile( 6093): Bluetooth service connected
D/BluetoothHeadset( 6093): Proxy object connected
,D/HeadsetProfile( 6093): Bluetooth service connected
D/BluetoothInputDevice( 6093): Proxy object connected
D/HidProfile( 6093): Bluetooth service connected
D/BluetoothPan( 6093): BluetoothPAN Proxy object connected
,D/PanProfile( 6093): Bluetooth service connected
D/BluetoothMap( 6093): Proxy object connected
D/MapProfile( 6093): Bluetooth service connected
D/BluetoothMap( 6093): getConnectedDevices()
V/BluetoothMapService( 6067): getConnectedDevices()
D/BluetoothPbap( 6093): Proxy object connected
D/PbapServerProfile( 6093): Bluetooth service connected
D/LGBluetoothUserBindClient( 6093): [BTUI] onServiceConnected
,D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
D/BluetoothPermissionRequest( 6093): onReceive
D/LGBluetoothFeatureConfig( 6093): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6093): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6093): return without doing reset settings.
V/BluetoothOppReceiver( 6067): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6067): [BTUI] startOppService()
D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1030): NTP server returned: 1456908886039 (Wed Mar 02 09:54:46 GMT+01:00 2016) reference: 105958 certainty: 28 system time offset: 368
D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
D/LocSvc_java( 1030): reportXtraServer 
D/LocSvc_java( 1030):  server1=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1030):  server2=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1030):  server3=
V/BluetoothOppManager( 6067): restoreApplicationData! falsefalsenullnull
D/LocSvc_java( 1030): xtraDownloadRequest
D/LocSvc_java( 1030): Sending msg: 6 arg1:0 arg2:1
,D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = xtra2.gpsOneXTRA.net, class = 1, type = 1
D/LGBluetoothFeatureConfig( 6067): isPrivacyLogsEnabled : true
V/BtOppService( 6067): onCreate
V/BluetoothOppNotification( 6067): send message
,D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BtOppService( 6067): Starting RfcommListener
D/BluetoothOppPreference( 6067): Dumping Names:  
D/BluetoothOppPreference( 6067): {}
D/BluetoothOppPreference( 6067): Dumping Channels:  
D/BluetoothOppPreference( 6067): {}
V/BtOppService( 6067): onStartCommand
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/BluetoothFtpReceiver( 6067): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6067): BluetoothFtpReceiver Start Service
V/BtOppService( 6067): Deleted complete outbound shares, number =  0
V/BluetoothOppNotification( 6067): new notify threadi!
V/BluetoothOppNotification( 6067): send delay message
V/BtOppService( 6067): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BtOppService( 6067): Deleted complete inbound failed shares, number = 0
V/BtOppService( 6067): start RfcommListener
V/BluetoothOppProvider( 6067): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@12ecf406 on behalf of 
V/BtOppService( 6067): RfcommListener started
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6067): Starting RFCOMM listener....
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@3e1eac7 on behalf of 
,W/BluetoothAdapter( 6067): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6067): [BTUI] createSocketChannel FD=80 mFd=75
V/BtOppRfcommListener( 6067): Started RFCOMM listener....
I/BtOppRfcommListener( 6067): Accept thread started.
V/BtOppRfcommListener( 6067): Accepting connection...
V/BluetoothOppNotification( 6067): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@19a3c8f4 on behalf of 
V/BtOppService( 6067): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/LGDataListener(  308): argv[0]=dsqncommand
D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@32af181d on behalf of 
V/BluetoothOppNotification( 6067): outbound: succ-0  fail-0
,D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/BluetoothOppNotification( 6067): outbound notification was removed.
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@31544a92 on behalf of 
D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
V/BluetoothFtpService( 6067): Ftp Service onCreate
I/BluetoothFtpService( 6067): Ftp Service onCreate
V/BluetoothFtpService( 6067): Ftp Service onStartCommand
V/BluetoothFtpService( 6067): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6067): Starting Listening on sockets
V/BtOppService( 6067): ContentObserver received notification
V/BluetoothOppNotification( 6067): inbound: succ-0  fail-0
V/BluetoothSapReceiver( 6067): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6067): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6067): SapReceiver onReceive 
V/BluetoothSapReceiver( 6067): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6067):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6067): Calling SAP service start service with action = null
V/BtOppService( 6067): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@18ae8060 on behalf of 
V/BluetoothOppNotification( 6067): update too frequent, put in queue
V/BtOppService( 6067): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6067): inbound notification was removed.
V/BtOppService( 6067): ContentObserver received notification
V/BluetoothFtpService( 6067): Handler(): got msg=1
V/BluetoothFtpService( 6067): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6067): Ftp Service initSocket
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/BluetoothAdapter( 6067): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BtOppService( 6067): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Mar 2016 08:54:46 GMT], X-Android-Received-Millis=[1456908885756], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1456908885732]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
D/ConnectivityService( 1030): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1854): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1854):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/BluetoothFtpService( 6067): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6067): Run Accept thread
D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
,D/AuthorizationBluetoothService( 2110): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/BluetoothAdapterService( 6067): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd0e9cc
V/BluetoothSapService( 6067): Sap Service onCreate
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@deb428c on behalf of 
V/BluetoothSapService( 6067): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6067): state: 12
V/BluetoothSapService( 6067): Starting SAP server process
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@1fba2dd5 on behalf of 
V/BluetoothOppNotification( 6067): update too frequent, put in queue
V/BluetoothSapService( 6067): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6067): Sap Service initRfcommSocket
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
V/BtOppService( 6067): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/sapd    ( 6394): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6394): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
W/BluetoothAdapter( 6067): getBluetoothService() called with no BluetoothManagerCallback
,D/libc-netbsd(  308): res_queryN name = xtra2.gpsOneXTRA.net succeed
D/LGBluetoothServiceAdapter( 6067): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6067): Succeed to create listening socket 
V/BluetoothSapService( 6067): Accepting socket connection...
V/BT_SAP  ( 6394): Event pipe created
V/BT_SAP  ( 6394): create_server_socket qcom.sap.server
V/BT_SAP  ( 6394): created socket fd 6
D/TelephonyIcons( 1445): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5096): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6168): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6168): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5096): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5096): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5096): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6168): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6168): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6093): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6093): MCCMNC not supported: null
D/QRemote ( 5096): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5096): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 5096): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5096): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5096): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LocSvc_java( 1030): calling native_inject_xtra_data
D/LocSvc_java( 1030): Sending msg: 11 arg1:0 arg2:1
,E/WifiStateMachine( 1030):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
D/ConnectivityService( 1030): identical MTU - not setting
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1445): CM callback handler got msg 524295,
V/BluetoothOppNotification( 6067): new notify threadi!,
V/BluetoothOppNotification( 6067): send delay message,
,V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@3fa99ea on behalf of 
,V/BluetoothOppNotification( 6067): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@19504db on behalf of 
V/BluetoothOppNotification( 6067): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6067): outbound notification was removed.
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@304ffb78 on behalf of 
V/BluetoothOppNotification( 6067): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6067): inbound notification was removed.
V/BluetoothOppProvider( 6067): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6067): created cursor android.database.sqlite.SQLiteCursor@277cd251 on behalf of 
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:914974343] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:914974352] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1445): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6003): My device name is: LGE-LG-D855
I/jxcore-log( 6003): 
,V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AlarmManagerService( 1030): Setting time of day to sec=1456908888
W/AlarmManagerService( 1030): Unable to set rtc to 1456908888: Invalid argument
I/NetworkMonitor( 5261): type=WIFI subType= reason=null isConnected=true
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,I/SecureClockService( 1942): Intent.ACTION_TIME_CHANGED 
I/CalendarProvider2( 5872): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5872): Scheduling check of next Alarm
I/[SystemUI]Clock( 1445): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1445): time changed, timezoneChanged : false
D/LIA_Informant_Tips_DateChangeManager( 2731): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2731): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-03-02 09:54:48...... Request
I/LIA_Informant_Tips_LogTracer( 2731): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 177, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2731): DateInfo : SmartTips Total Working Day Count = 177
D/LIA_Informant_Tips_DateChangeManager( 2731): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2731): DateInfo : Last Date Check Time = 2016-03-02 09:54:48
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2063): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2063): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 2
I/[LGHome]LGCalendarIcon( 2063): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 2
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6254): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6425 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/[Concierge]Service( 2606): onStartCommand(). Type : 9
I/GoogleURLConnFactory( 2110): Using platform SSLCertificateSocketFactory
,I/AppUp4:AppBoxCP( 6425): onCreate
W/AppUp4:DB( 6425):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6425):  setFingerPrint start
I/AppUp4:DB( 6425):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6425):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6425):  SDK version = 21
I/AppUp4:DB( 6425):  beforefinger == newfinger no write in DB
I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6449 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6425): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6425): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6425): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6425): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6425): [onReceive] request level :IDLE....
I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6467 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/AppUp4:CustModeStarterReceiver( 6425): onReceive
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
,W/ResourcesManager( 6467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6467): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 6467): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6425): LgDataFeature() Constructor: none
D/LgDataFeature( 6425): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6425): Context : android.app.ReceiverRestrictedContext@1dee27ff
D/AppUp4:CustFacade( 6425): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6425): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6425): begin check event
I/AppUp4:CustModeStarterReceiver( 6425): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6425): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
D/AppUp4:CustModeStarterReceiver( 6425): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6425): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6425): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 5661:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/AppConfig( 6467): Total System Memory = 2995761152
D/SystemHelper( 6467): region [EU], country [EU], operator [OPEN], sub-operator []
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5661/cgroup.procs: No such file or directory
D/LGDMClient( 3999): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3999): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3999): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6489 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 3999): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3354): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3354): DownloadService onCreate
,I/DownloadManager( 3354): in removeSpuriousFiles
V/DownloadManager( 3354): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3354): created cursor android.database.sqlite.SQLiteCursor@8156cfb on behalf of 3354
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
,I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3354): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3354): in trimDatabase
V/DownloadManager( 3354): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 3999): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3999): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3354): created cursor android.database.sqlite.SQLiteCursor@3d761118 on behalf of 3354
D/LGDMClient( 3999): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3999): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6514 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ReaderUtils( 6449): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
V/DownloadManager( 3354): DownloadService onStartCommand
V/DownloadManager( 3354): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/GpsLocationProvider( 1030): No APN found to select.
W/ContextImpl( 3999): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3354): created cursor android.database.sqlite.SQLiteCursor@10c18956 on behalf of 3354
E/LGDMClient( 3999): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3354): processing inserted download 1
,D/LGDMClient( 3999): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3999): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3354): processing inserted download 4
V/DownloadManager( 3354): processing inserted download 7
V/DownloadManager( 3354): processing inserted download 8
V/DownloadManager( 3354): processing inserted download 9
,I/ActivityManager( 1030): Killing 5751:com.google.android.gms:car/u0a5 (adj 15): empty #17
,V/DownloadManager( 3354): processing inserted download 10
W/ResourcesManager( 6514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/DownloadManager( 3354): processing inserted download 16
W/ResourcesManager( 6514): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/DownloadManager( 3354): processing inserted download 17
W/ResourcesManager( 6514): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6514): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/DownloadManager( 3354): processing inserted download 18
V/DownloadManager( 3354): processing inserted download 21
V/DownloadManager( 3354): processing inserted download 22
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_5751/cgroup.procs: No such file or directory
,V/DownloadManager( 3354): DownloadService onDestroy
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{390f2201 type 0 when 1456908889510 com.android.vending} when 1456908889510
I/LGEmail ( 6514): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/GAV2    ( 6449): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6449): Created application version: 3.2.35 (30235)
,D/DelayedSyncController( 6489): Delaying sync.
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/DriveInitializer( 2316): Background init thread started
D/LGEmail ( 6514): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2316): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/DriveInitializer( 2316): Awaiting to be initialized
,I/PhenotypeFlagCommitter( 2110): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
W/ResourceType( 6514): No package identifier when getting value for resource number 0x00000000
,E/Auth.Api.Credentials( 2316): [CredentialSyncAdapter] Unknown sync event.
,D/LgDataFeature( 6514): LgDataFeature() Constructor: none
D/LgDataFeature( 6514): LgDataFeature() Constructor Done, null
,W/DriveInitializer( 2316): Background init thread ended
I/BooksSync( 6449): Starting books sync
,I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3173): Thermal-Lib-Client: Client request sent
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 38284(1792KB) AllocSpace objects, 3(88KB) LOS objects, 33% free, 44MB/66MB, paused 1.437ms total 102.734ms
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2110): Vacuum at: now=1456908889887 tag=VacuumService
,D/eas_req ( 6514): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 6514): JNI_OnLoad()
I/HubEmail( 6514): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6514): registerNatives()
I/HubEmail( 6514): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6514): registerNativeMethods()
I/HubEmail( 6514): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6514): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6514): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3299): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3299): action = android.net.conn.CONNECTIVITY_CHANGE
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/LgeMiscReceiver( 3299): networkInfo.isConnected() = true
D/PhoneState( 3299): setPdpRejectCasuse : false
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6576 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.google.com, class = 1, type = 1
E/Ads     ( 2316): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
D/BooksSync( 6449): started syncMyEbooks
,D/libc-netbsd(  308): res_queryN name = www.google.com succeed
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
D/DrmBroadcastReceiver( 6576): Receive CONNECTIVITY_ACTION
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
D/DrmBroadcastReceiver( 6576): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6576): Service onCreate
D/DrmService( 6576): Received new request = 2
I/DrmSntpClient( 6576): Start Sync process
D/DrmSntpClient( 6576): Server : 0
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6601 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
I/art     ( 6601): Almond Protected OAT
D/libc-netbsd(  308): res_queryN name = pool.ntp.org succeed
,I/art     ( 2110): Explicit concurrent mark sweep GC freed 27515(1501KB) AllocSpace objects, 4(87KB) LOS objects, 51% free, 30MB/62MB, paused 1.054ms total 31.594ms
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6618 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/LGDrmClient( 6576): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  324): eDRM_SetDRMTime +++
I/LGDRM   (  324): [DRM] SET TIME : YR=2016, MON=3, DAY=2
I/LGDRM   (  324): [DRM] SET TIME : HR=8, MIN=54, SEC=50
,V/FormManager( 6138): There are no updated forms. The schedule will be deleted.
V/FormManager( 6138): Alarm would be updated, because LastCheckTime has been updated.
V/ILGDrmService(  324): eDRM_SetDRMTime ---
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1030): Killing 5399:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DrmSntpClient( 6576): Synched
D/DrmService( 6576): Completed !! request = 2
D/DrmService( 6576): Request count = 0
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_5399/cgroup.procs: No such file or directory
V/DrmService( 6576): Service onDestroy
,D/WeatherApplication( 6601): removeAccount
D/WeatherApplication( 6601): Account.length = 0
E/WeatherApplication( 6601): OPERATOR:OPEN
I/ActivityManager( 1030): Killing 5891:com.android.calendar/u0a13 (adj 15): empty #17
D/WeatherAncestor( 6601): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:50
,D/Weather.Utils( 6601): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6601): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6601): 2 : This is isUpdating : false
D/WeatherAncestor( 6601): connectivity changed - connection : true
D/WeatherService( 6601): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6601): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6601): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6601): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6601): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6601): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:50
,W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_5891/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6641 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5872:com.android.providers.calendar/u0a14 (adj 15): empty #17
,I/art     (  350): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 11.787ms
I/art     (  350): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 202us total 8.921ms
,I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.980ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10014/pid_5872/cgroup.procs: No such file or directory
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1030): intercepted: 0|com.google.android.gms|1|null|10005,none
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1445): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1445): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do add job
D/LgeQuickCoverNotificationData( 1398): add : 2
D/LgeQuickCoverNotificationData( 1398): do add job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
D/Finsky  ( 5711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5711): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1030): Killing 2199:com.lge.music/u0a34 (adj 15): empty #17
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
V/AudioFlinger(  315): 2199 died, releasing its sessions
V/AudioFlinger(  315):  pid 1854 @ 0
V/AudioFlinger(  315):  pid 3299 @ 1
V/AudioFlinger(  315):  pid 3299 @ 2
,W/libprocessgroup( 1030): failed to open /acct/uid_10034/pid_2199/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GLSActivity( 2110): [ac] getting account id
,I/GLSUser ( 2110): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
W/ApiaryClient( 6449): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3165107585111794204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2437 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:3363] from screen [on:0 period:914977746] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2437 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:914977747] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2110): innerSync failed
D/ContactsSyncAdapter( 2110): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2110): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2110): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2110): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2110): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.andro,id.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26358, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 141895, reason: 10019
,I/WebViewFactory( 6641): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6641): Loading: webviewchromium
I/LibraryLoader( 6641): Time to load native libraries: 3 ms (timestamps 1132-1135)
I/LibraryLoader( 6641): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6641): Binding Chromium to main looper Looper (main, tid 1) {22032aa6}
,I/LibraryLoader( 6641): Expected native library version number "",actual native library version number ""
I/chromium( 6641): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6641): Initializing chromium process, renderers=0
W/art     ( 6641): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6641): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6641): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6641): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 25977(1105KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.597ms total 105.695ms
V/AudioPolicyService(  315): registerClient() client 0xb152c1e0, uid 10093
,W/AudioManagerAndroid( 6641): Requires BLUETOOTH permission
I/Adreno-EGL( 6641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6641): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6641): Build Date: 12/12/14 금
I/Adreno-EGL( 6641): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6641): Remote Branch: 
I/Adreno-EGL( 6641): Local Patches: 
I/Adreno-EGL( 6641): Reconstruct Branch: 
,D/DelayedSyncController( 6489): Delaying sync.
,I/GoogleURLConnFactory( 2316): Using platform SSLCertificateSocketFactory
I/NSApplication( 6641): Starting up...
,I/ActivityManager( 1030): Killing 6289:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6289/cgroup.procs: No such file or directory
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.SyncManager( 2316): SYNC; picasa accounts
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/NetworkLogImpl( 2316): Loaded NetworkSpeedPredictor
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
I/iu.Environment( 2316): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  308): res_queryN name = mtalk.google.com succeed
W/SubscribedFeeds( 2316): Hard error
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/iu.UploadsManager( 2316): num queued entries: 0
I/iu.UploadsManager( 2316): num updated entries: 0
I/iu.SyncManager( 2316): NEXT; no task
D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2316): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 26359, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 143358, reason: Periodic
I/GcmGroups( 2316): Failed to subscribe to group.
I/GcmGroups( 2316): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2316): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2316): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2316): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2316): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2316): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2316): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2316): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2316): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PostponalbeReceiver( 6254): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6729 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GcmGroups( 2316): Groups upload failed, retrying in 24000:00:00
I/ActivityManager( 1030): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6746 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,D/ALBootInit( 6729): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6729): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6729): [setNextAlert] start
D/Alarms  ( 6729): [setNextAlert] (1)
,D/Alarms  ( 6729):  minTime  = 0
D/Alarms  ( 6729):  -- OK multi -- 0
E/jeny.kim( 6729): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 6729): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6729): BUILD Country: EU
,D/Alarms  ( 6729): broadcastToWidgetProvider : false
D/Alarms  ( 6729): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1030): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6729): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6729): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3cd0e9cc
V/DigitalAppWidgetProvider( 6729): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3cd0e9cc
D/QuickCoverProvider( 6729): onReceiver
I/indal   ( 1398): SmartCoverWidgetContext createApplicationContext
,I/indal   ( 1398): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6601): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 9:54:51
D/Weather.Utils( 6601): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6601): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6601): 2 : This is isUpdating : false
D/WeatherService( 6601): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2bf7e415
,D/ForecastDataCache( 6601): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6601): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6601): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6601): 2 : set auto-update time : 3/2 12:54
D/WeatherAncestor( 6601): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 9:54:51
W/AbstractGoogleClient( 6746): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1030): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6768 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6235:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6235/cgroup.procs: No such file or directory
,D/TimeService( 6768): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456908891957
D/        ( 6768): TimeServiceNative: User Time to be set is 1456908891957
,D/QC-time-services( 6768): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6768): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6768): Lib:time_genoff_operation: pargs->ts_val = 1456908891957
D/QC-time-services( 6768): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  366): Daemon: Connection accepted:time_genoff
D/QC-time-services(  366): Daemon:Received base = 2, unit = 1, operation = 0,value = 1456908891957
D/QC-time-services(  366): Daemon:genoff_opr: Base = 2, val = 1456908891957, operation = 0
D/QC-time-services(  366): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/11/70 2:6:7
D/QC-time-services(  366): Daemon:Value read from RTC seconds = 16509967000
D/QC-time-services(  366): Daemon:new time 1456908891957 
D/QC-time-services(  366): Daemon: delta 1440398924957 genoff 1440398924957 
D/QC-time-services(  366): Daemon:genoff_persistent_update: Writing genoff = 1440398924957 to memory
D/QC-time-services(  366): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  366): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  366): Updating the TOD offset
D/QC-time-services(  366): Daemon:genoff_persistent_update: Writing genoff = 1440398924957 to memory
D/QC-time-services(  366): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  366): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  366): Daemon:Update to modem bit set
D/QC-time-services(  366): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  366): Daemon: Base = 2, Value being sent to MODEM = 1124434124957
E/QC-time-services( 6768): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  366): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  366): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1030): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6789 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6806 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1030): Killing 6168:com.lge.sync/1000 (adj 15): empty #17
D/GCM     ( 2110): Connected
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6168/cgroup.procs: No such file or directory
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 2110): Message class com.google.f.a.a.p
W/ResourcesManager( 6789): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6806): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/CalendarProvider2( 6789): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@399d465d
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/CalendarApplication( 6806): CalendarApplication.onCreate()
D/CalendarProvider2( 6789): [getOrCreateCalendarAlarmManager]
,D/PreferenceKeysParser( 6806): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6806): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@128be4a3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3e4c33a0, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@beceb59, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@236b831e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1dee27ff, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3cd0e9cc, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf7e415, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3d48b32a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3b07451b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2708d6b8, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1a7fac91, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3816d7f6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@15cb17f7, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@28d0a664, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@8e180cd, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@28d07d82, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3b8f3c93, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2d23c4d0, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@27125cc9, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@78cefce, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2f670eef, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@11485dfc, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@155afc85, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@248c3ada, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@283fab0b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1ebb5de8, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@35d3dc01, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@22032aa6, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@14bbece7, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@37dc7094, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@19a1373d, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea74b32, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@d07083, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@235a0200, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@5ef0a39, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3cfae87e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@391f91df, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@225d3e2c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@cad10f5, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@33590e8a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@8156cfb, lg_preferences_rec,ent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7611
I/CalendarProvider2( 6789): Created com.android.providers.calendar.CalendarAlarmManager@236b831e(com.android.providers.calendar.CalendarProvider2@399d465d)
D/GeneralPreferenceUtils( 6806): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6806): [init]
I/Config  ( 6806): LGCalendar ver.4.40.16
I/Config  ( 6806): start check model
I/Config  ( 6806): start check native_ca
I/Config  ( 6806): Config Operator=OPEN, Country=EU
,D/Config  ( 6806): [setDefaultValuesToPref]
D/Config  ( 6806): [parseProfiles]
D/ProfilesParser( 6806): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6806): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6806): [updateProfiletoCountryInfo]
D/GeneralPreference( 6806): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6806): [updateWidgets] 
,I/InitNotificationRingtoneService( 6806): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6806): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
W/ApiaryClient( 6449): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3165107585111794204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,I/AlertUtils( 6806): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/art     ( 3354): Explicit concurrent mark sweep GC freed 4608(296KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 325us total 16.921ms
,I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6806): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6806): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
W/HolidayIntentService( 6806): onHandleIntent
,I/AlertUtils( 6806): set default noti to content://media/internal/audio/media/41
D/HolidayDataLoader( 6806): readJsonAsset : holiday.json
D/MonthWidgetProvider( 6806): [onReceive]
D/CalendarWidgetProvider( 6806): [onReceive]
D/CalendarWidgetProvider( 6806): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6806): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6806): [onReceive]
D/CalendarWidgetProvider( 6806): [onReceive]
D/CalendarWidgetProvider( 6806): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6806): [onUpdateAndInitCalendarTime]
I/InitNotificationRingtoneService( 6806): End InitializeAlertRingtoneService.onHandleIntent
,E/HolidayIntentService( 6806): onHandleIntent:holiday data empty
,I/ActivityManager( 1030): Killing 5814:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 5096): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5096): android.os.DeadObjectException
W/System.err( 5096): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5096): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5096): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5096): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5096): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5096): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5096): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5096): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5096): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5096): android.os.DeadObjectException
W/System.err( 5096): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5096): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5096): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5096): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5096): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5096): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5096): 	at android.os.Handler.dispatchMessage(Handler.java:95)
I/art     ( 2316): Explicit concurrent mark sweep GC freed 17870(1290KB) AllocSpace objects, 21(336KB) LOS objects, 49% free, 32MB/64MB, paused 883us total 37.505ms
W/System.err( 5096): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5096): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5096): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5096): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5096): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5096): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,E/libprocessgroup( 1030): failed to kill 1 processes for processgroup 5814
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6003): 
,W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 5096): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5096): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5096): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,W/ContextImpl( 4229): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 20864(883KB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 1.441ms total 124.107ms
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DigitalAppWidgetProvider( 6729): onReceive: android.intent.action.ALARM_CHANGED
D/GCM     ( 2110): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/WeatherAncestor( 6601): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 9:54:53
D/Weather.Utils( 6601): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6601): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6601): 2 : This is isUpdating : false
D/Weather_cast( 6601): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6601): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 9:54:53
D/UEI.SmartControl( 6838): Quickset Services start...
I/UEI.SmartControl( 6838): Manufacture = LGE
D/UEI.SmartControl( 6838): Id = LGNevo
D/UEI.SmartControl( 6838): File observer start...
E/UEI.SmartControl( 6838): IR Port is disabled: false
D/UEI.SmartControl( 6838): Starting file observer...
D/UEI.SmartControl( 6838): Extracting JNI libs...
D/UEI.SmartControl( 6838): --- this system supports 32-bit or 64-bit only
,I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6876 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6838): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6838): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6838): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6838): --- Selecting new region: 6
I/UEI.SmartControl( 6838): Model = LG-D855
D/UEI.SmartControl( 6838): QS Service created
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/CalendarSyncAdapter( 6746): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6746): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6746): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6746): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6746): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6746): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6746): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6746): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6746): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6746): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6746): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6746): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6746): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6746): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6746): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6746): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6746): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6746): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6746): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6746): 	... 12 more
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count,=3
I/ActivityManager( 1030): Killing 6093:com.android.settings/1000 (adj 15): empty #17
I/UEI.SmartControl( 6838): Service initServices...
D/WifiService( 1030): Client connection lost with reason: 4
D/UEI.SmartControl( 6838): QS start get config
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgDataFeature( 6876): LgDataFeature() Constructor: none
,D/LgDataFeature( 6876): LgDataFeature() Constructor Done, null
D/UEI.SmartControl( 6838): Loading JNI Libs...
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6093/cgroup.procs: No such file or directory
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 26359, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 145318, reason: Periodic
I/ActivityManager( 1030): Killing 5096:com.lge.qremote/u0a112 (adj 15): empty #17
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 6838): Supports setup maps: true
D/UEI.SmartControl( 6838): QS start statue = true Error code = 0
I/UEI.SmartControl( 6838): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6838): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6838): ### init IR Blaster...
,D/serial_port( 6838): Configuring serial port
E/UEI.SmartControl( 6838): UEIBLaster setting for 616
I/UEI.SmartControl( 6838): Setting serial record hearder size = 2
I/UEI.SmartControl( 6838): configuring settings for MAXQ616
I/UEI.SmartControl( 6838): Get version...
D/UEI.SmartControl( 6838): serial port data available: 21
,W/libprocessgroup( 1030): failed to open /acct/uid_10112/pid_5096/cgroup.procs: No such file or directory
I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6003): 
,D/UEI.SmartControl( 6838): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6838): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6838): QS saving settings...
,D/UEI.SmartControl( 6838): IR Blaster version: 25672567
D/UEI.SmartControl( 6838): serial port data available: 4
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/UEI.SmartControl( 6838): Services init done
D/UEI.SmartControl( 6838): QS Service init finished
D/UEI.SmartControl( 6838): QS Service version name: 2.1.91
E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/HttpHelper( 6449): null auth token
D/UEI.SmartControl( 6838): QS Service version code: 201091
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/UEI.SmartControl( 6838): Service requested: Control
I/UEI.SmartControl( 6838): Device manager: loading config....
D/UEI.SmartControl( 6838): ----------- loading internal config...
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
I/Babel   ( 6876): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6876): MmsConfig.loadMmsSettings
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/BaseAppContext( 2316): Using Auth Proxy for data requests.
I/Babel   ( 6876): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6876): MmsConfig.loadFromDatabase
D/UEI.SmartControl( 6838): Request IControl service: devices are loaded...
,E/UEI.SmartControl( 6838): Loading SETTINGS...
D/UEI.SmartControl( 6838): Service.onUnbind: IControl
D/UEI.SmartControl( 6838): Service.onDestroy
D/UEI.SmartControl( 6838): Lock is in USE false
D/UEI.SmartControl( 6838): unbind internal service
D/serial_port( 6838): close(fd = 25)
D/UEI.SmartControl( 6838): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6838): Serial port is closed.
I/UEI.SmartControl( 6838): Serial port is closed.
D/UEI.SmartControl( 6838): Blaster closed
D/UEI.SmartControl( 6838): Shut down QS...
D/UEI.SmartControl( 6838): Stopping QS lib
D/UEI.SmartControl( 6838): QS lib stop result = true
D/UEI.SmartControl( 6838): Stopped QS lib
D/UEI.SmartControl( 6838): Stopped file observer...
D/UEI.SmartControl( 6838): QS shutdown complete
D/UEI.SmartControl( 6838): QS Service created
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
I/UEI.SmartControl( 6838): Notify AllClients services are ready: 11
D/UEI.SmartControl( 6838): -----service ready thread exits
I/UEI.SmartControl( 6838): Service initServices...
D/UEI.SmartControl( 6838): QS start get config
,E/Babel   ( 6876): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6876): MmsConfig.loadFromResources
E/Babel   ( 6876): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6876): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6876): Unsupported mime audio/evrc
W/AudioCapabilities( 6876): Unsupported mime audio/qcelp
W/VideoCapabilities( 6876): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6876): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6876): Unsupported mime audio/qcelp
W/AudioCapabilities( 6876): Unsupported mime audio/evrc
W/VideoCapabilities( 6876): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6876): Unsupported mime video/divx
W/VideoCapabilities( 6876): Unsupported mime video/divx311
W/VideoCapabilities( 6876): Unsupported mime video/divx4
I/art     ( 2110): Explicit concurrent mark sweep GC freed 34046(1891KB) AllocSpace objects, 18(2MB) LOS objects, 50% free, 30MB/62MB, paused 1.034ms total 45.568ms
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6003): 
,W/Settings( 6876): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6003): 
W/BaseAppContext( 2316): Using Auth Proxy for data requests.
W/VideoCapabilities( 6876): Unsupported mime video/mp4v-esdp
,W/BaseAppContext( 2316): Using Auth Proxy for data requests.
W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
W/ApiaryClient( 6449): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3165107585111794204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
I/VideoCapabilities( 6876): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6876): Unsupported mime audio/eac3
W/BaseAppContext( 2316): Using Auth Proxy for data requests.
,W/AudioCapabilities( 6876): Unsupported mime audio/ac3
W/AudioCapabilities( 6876): Unsupported mime audio/g726
W/AudioCapabilities( 6876): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6876): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6876): Unsupported mime audio/adpcm
W/VideoCapabilities( 6876): Unsupported mime video/theora
W/VideoCapabilities( 6876): Unsupported mime video/mjpg
I/jxcore-log( 6003): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6003): 
I/jxcore-log( 6003): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6003): 
I/io.jxcore.node.ConnectivityInfo( 6003): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6003):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6003):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6003):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6003):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6003):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 6003):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 6003):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 6003):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 6003): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
I/jxcore-log( 6003): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6003): 
W/ResourcesManager( 6876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6876): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6876): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6876): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1030): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6915 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6876): Note: end time exceeds epoch: 
,I/UEI.SmartControl( 6838): Supports setup maps: true
,D/UEI.SmartControl( 6838): QS start statue = true Error code = 0
I/UEI.SmartControl( 6838): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6838): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6838): ### init IR Blaster...
D/serial_port( 6838): Configuring serial port
E/UEI.SmartControl( 6838): UEIBLaster setting for 616
I/UEI.SmartControl( 6838): Setting serial record hearder size = 2
I/UEI.SmartControl( 6838): configuring settings for MAXQ616
I/UEI.SmartControl( 6838): Get version...
D/UEI.SmartControl( 6838): serial port data available: 21
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6838): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6838): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6838): QS saving settings...
D/UEI.SmartControl( 6838): IR Blaster version: 25672567
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2b303432 type 2 when 113818 com.android.providers.calendar} when 113818
D/CalendarProviderBroadcastReceiver( 6789): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6789): [IntentService] WakeLock acquire, start IntentSerivce
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 6915): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Babel   ( 6876): UserRecoverableAuthException.
,E/Babel   ( 6876): cfq: BadAuthentication
E/Babel   ( 6876): 	at cfn.a(Unknown Source)
E/Babel   ( 6876): 	at f.a(PG:191)
E/Babel   ( 6876): 	at ava.a(PG:88)
E/Babel   ( 6876): 	at ava.a(PG:128)
E/Babel   ( 6876): 	at bjs.a(PG:255)
E/Babel   ( 6876): 	at bep.a(PG:602)
E/Babel   ( 6876): 	at bep.a(PG:469)
E/Babel   ( 6876): 	at bpo.run(PG:1141)
E/Babel   ( 6876): Error getting auth token
E/Babel   ( 6876): bxl
E/Babel   ( 6876): 	at f.a(PG:201)
E/Babel   ( 6876): 	at ava.a(PG:88)
E/Babel   ( 6876): 	at ava.a(PG:128)
E/Babel   ( 6876): 	at bjs.a(PG:255)
E/Babel   ( 6876): 	at bep.a(PG:602)
E/Babel   ( 6876): 	at bep.a(PG:469)
E/Babel   ( 6876): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6876): error sending REQ[fc:24; creat:1456842878542; type:bev-505488501]; took 98 ms (error code == 100)
E/Babel   ( 6876): Account registration failedRedacted-21
D/UEI.SmartControl( 6838): serial port data available: 4
E/Babel   ( 6876): bph: null -- null
E/Babel   ( 6876): 	at ava.a(PG:120)
E/Babel   ( 6876): 	at ava.a(PG:128)
E/Babel   ( 6876): 	at bjs.a(PG:255)
E/Babel   ( 6876): 	at bep.a(PG:602)
E/Babel   ( 6876): 	at bep.a(PG:469)
E/Babel   ( 6876): 	at bpo.run(PG:1141)
I/Babel   ( 6876): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6876): Account sign in complete with state 106account: Redacted-21
D/CalendarProvider2( 6789): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6789): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6789): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6789): (284) automatic index on view_events(_id)
I/art     ( 6876): Note: end time exceeds epoch: 
,D/CalendarProvider2( 6789): [IntentService] Release Lock
D/CalendarProvider2( 6789): CalendarProviderIntentService.onDestroy()
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/UEI.SmartControl( 6838): Device manager: loading config....
D/UEI.SmartControl( 6838): ----------- loading internal config...
W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6838): Services init done
D/UEI.SmartControl( 6838): QS Service init finished
D/UEI.SmartControl( 6838): QS Service version name: 2.1.91
D/UEI.SmartControl( 6838): QS Service version code: 201091
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UEI.SmartControl( 6838): Loading SETTINGS...
D/UEI.SmartControl( 6838): Service requested: Control
,I/ActivityManager( 1030): Killing 6190:com.lge.lifetracker/u0a37 (adj 15): empty #17
D/UEI.SmartControl( 6838): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6838): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6838): -----service ready thread exits
,I/Gmail   ( 6915): getAccountsCursor
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_6190/cgroup.procs: No such file or directory
,E/ActivityThread( 6838): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3b07451b that was originally bound here
E/ActivityThread( 6838): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@3b07451b that was originally bound here
E/ActivityThread( 6838): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 6838): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 6838): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 6838): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 6838): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6838): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6838): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6838): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6838): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/ActivityThread( 6838): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 6838): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 6838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6838): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6838): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/ActivityThread( 6838): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6838): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6838): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/ActivityThread( 6838): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/ActivityManager( 1030): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1030): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/UEI.SmartControl( 6838): Internal service binding...
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2110): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/Babel   ( 6876): Unexpected exception while authenticating.
E/Babel   ( 6876): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6876): 	at cfn.b(Unknown Source)
E/Babel   ( 6876): 	at cfn.a(Unknown Source)
E/Babel   ( 6876): 	at f.a(PG:188)
E/Babel   ( 6876): 	at ava.b(PG:143)
E/Babel   ( 6876): 	at bnr.run(PG:5415)
E/Babel   ( 6876): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6876): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6876): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/Gmail   ( 6915): Observing account changes for notifications
W/GAV2    ( 6915): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ActivityManager( 1030): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/Gmail   ( 6915): Sync started for account: account:61035162
,E/Gmail   ( 6915): Error finding the version of the Email provider.....
E/Gmail   ( 6915): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6915): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6915): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 6915): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 6915): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6915): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6915): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6915): We do not support migrating this version of the Email provider.
I/Gmail   ( 6915): getAccountsCursor
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=32.4, 0.0, 0.0  rx=27.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:914980754] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=32.4, 0.0, 0.0  rx=27.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:914980755] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/SQLiteLog( 6915): (283) recovered 1658 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 6915): notifyAccountChanged
,I/Gmail   ( 6915): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6915): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6915): notifyAccountChanged
I/Gmail   ( 6915): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6915): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6915): getAccountsCursor
I/Gmail   ( 6915): getAccountsCursor
I/Gmail   ( 6915): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 18246(828KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.050ms total 68.367ms
,W/ResourcesManager( 6915): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6915): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6915): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6915): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6915): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
I/Gmail   ( 6915): notifyAccountChanged
,I/Gmail   ( 6915): getAccountsCursor
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Gmail   ( 6915): notifyAccountChanged
,I/Gmail   ( 6915): getAccountsCursor
,W/Gmail   ( 6915): Sync complete for account: account:61035162
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1030): Killing 6425:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 26360, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 144664, reason: Periodic
D/UEI.SmartControl( 6838): Internal timer expired: 2
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6425/cgroup.procs: No such file or directory
,E/BooksSync( 6449): Soft error: 
E/BooksSync( 6449): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3165107585111794204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6449): Headers:
E/BooksSync( 6449): accept-encoding: [gzip]
E/BooksSync( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6449): gdata-version: 2
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6449): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6449): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6449): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6449): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6449): {
E/BooksSync( 6449):  "error": {
E/BooksSync( 6449):   "errors": [
E/BooksSync( 6449):    {
E/BooksSync( 6449):     "domain": "global",
E/BooksSync( 6449):     "reason": "required",
E/BooksSync( 6449):     "message": "Login Required",
E/BooksSync( 6449):     "locationType": "header",
E/BooksSync( 6449):     "location": "Authorization"
E/BooksSync( 6449):    }
E/BooksSync( 6449):   ],
E/BooksSync( 6449):   "code": 401,
E/BooksSync( 6449):   "message": "Login Required"
E/BooksSync( 6449):  }
E/BooksSync( 6449): }
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6449): 	... 8 more
,E/BooksSync( 6449): Sync error
E/BooksSync( 6449): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3165107585111794204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6449): Headers:
E/BooksSync( 6449): accept-encoding: [gzip]
E/BooksSync( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6449): gdata-version: 2
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6449): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6449): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6449): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6449): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6449): {
E/BooksSync( 6449):  "error": {
E/BooksSync( 6449):   "errors": [
E/BooksSync( 6449):    {
E/BooksSync( 6449):     "domain": "global",
E/BooksSync( 6449):     "reason": "required",
E/BooksSync( 6449):     "message": "Login Required",
E/BooksSync( 6449):     "locationType": "header",
E/BooksSync( 6449):     "location": "Authorization"
E/BooksSync( 6449):    }
E/BooksSync( 6449):   ],
E/BooksSync( 6449):   "code": 401,
E/BooksSync( 6449):   "message": "Login Required"
E/BooksSync( 6449):  }
E/BooksSync( 6449): }
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6449): 	... 8 more
,I/BooksSync( 6449): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26321, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1030): Killing 5711:com.android.vending/u0a44 (adj 15): empty #17
I/GAV2    ( 6449): Thread[GAThread,5,main]: No campaign data found.
,I/GoogleHttpClient( 5261): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_5711/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=6979 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6979): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/MusicSyncAdapter( 5261): Sync failed due to an authentication issue.
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 26360, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 147046, reason: Periodic
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5261): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5261): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5261): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5261): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager( 1030): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7004 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ArtDownloadService( 5261): Setting cache size 0
,W/ArtDownloadService( 5261): Setting cache size 0
I/ActivityManager( 1030): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7024 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/DocsApplication( 7004): Installing DEX configuration.
D/DexInstaller( 7004): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/art     (  350): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 203us total 10.085ms
,I/PackageInfoHelper( 7004): Provided clientMode=RELEASE, packageInfo=PackageInfo{399d465d com.google.android.apps.docs}
I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.135ms
D/TAG     ( 7004): onCreate()
D/CrossAppStateProvider( 7004): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.728ms
,D/LgDataFeature( 6979): LgDataFeature() Constructor: none
D/LgDataFeature( 6979): LgDataFeature() Constructor Done, null
W/ResourcesManager( 7024): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7024): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5261): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/MultiDex( 7024): VM with version 2.1.0 has multidex support
I/MultiDex( 7024): install
I/MultiDex( 7024): VM has multidex support, MultiDex support library is disabled.
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5261): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/MusicLeanback( 5261): Conditions not met for autocaching.
I/MusicLeanback( 5261): Stop autocaching.
,I/art     ( 2110): Explicit concurrent mark sweep GC freed 17395(999KB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 1.012ms total 23.532ms
,V/JNIHelp ( 7024): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7024): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7024): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b9bf048: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7024): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2110): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2110): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2316): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/PlayMovies( 6979): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/WearableService( 7024): callingUid 10005, callindPid: 7024
,E/MDM     ( 1816): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/PlayMovies( 6979): TransferService.onCreate:52 creating transfer service
D/WearableClient( 5261): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5261): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5261): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
W/AudioCapabilities( 6979): Unsupported mime audio/evrc
,W/AudioCapabilities( 6979): Unsupported mime audio/qcelp
W/VideoCapabilities( 6979): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6979): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6979): Unsupported mime audio/qcelp
W/AudioCapabilities( 6979): Unsupported mime audio/evrc
W/VideoCapabilities( 6979): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6979): Unsupported mime video/divx
W/VideoCapabilities( 6979): Unsupported mime video/divx311
W/VideoCapabilities( 6979): Unsupported mime video/divx4
W/VideoCapabilities( 6979): Unsupported mime video/mp4v-esdp
,D/LocationInitializer( 2316): Restart initialization of location
,I/VideoCapabilities( 6979): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6979): Unsupported mime audio/eac3
W/AudioCapabilities( 6979): Unsupported mime audio/ac3
W/AudioCapabilities( 6979): Unsupported mime audio/g726
W/AudioCapabilities( 6979): Unsupported mime audio/wma-voice
,W/AudioCapabilities( 6979): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6979): Unsupported mime audio/adpcm
W/VideoCapabilities( 6979): Unsupported mime video/theora
W/VideoCapabilities( 6979): Unsupported mime video/mjpg
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6979): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/ResourcesManager( 2316): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/PlayMovies( 6979): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 6979): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6979): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 6979): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 6979): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 6979): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 6979): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 6979): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 6979): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/ActivityManager( 1030): Killing 6138:com.lge.formmanager/u0a26 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 26360, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 147901, reason: Periodic
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_6138/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Killing 6576:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_6576/cgroup.procs: No such file or directory
,I/SyncAdapterService( 6641): Ignoring sync request for non-current account
,I/GAV4    ( 6641): Thread[GAThread,5,main]: No campaign data found.
,E/Auth.Api.Credentials( 2316): [CredentialSyncAdapter] Unknown sync event.
,D/ChimeraCfgMgr( 2316): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 28466(1304KB) AllocSpace objects, 9(656KB) LOS objects, 33% free, 44MB/66MB, paused 1.376ms total 69.918ms
,I/ReminderSync( 2316): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=266:priority=5:group=main]
,D/LgDataFeature( 7004): LgDataFeature() Constructor: none
D/LgDataFeature( 7004): LgDataFeature() Constructor Done, null
,I/GCoreUlr( 1816): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1816): Using Auth Proxy for data requests.
,I/GLSUser ( 1816): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 1816): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,W/GAV2    ( 7004): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiService( 1030): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@29510072}
,E/GCoreUlr( 1816): 
E/GCoreUlr( 1816): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1816): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1816): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1816): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1816): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1816): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1816): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1816): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1816): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1816): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1816): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1816): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1816): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = ssl.gstatic.com, class = 1, type = 1
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 26360, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 148790, reason: Periodic
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2110): innerSync failed
D/ContactsSyncAdapter( 2110): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2110): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2110): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2110): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2110): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
D/libc-netbsd(  308): res_queryN name = ssl.gstatic.com succeed
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398):, isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 141895, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
W/PsynchoHelperImpl( 7004): Error fetching or saving configuration
W/PsynchoHelperImpl( 7004): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7004): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7004): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7004): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7004): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7004): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7004): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7004): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7004): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7004): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7004): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7004): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7004): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7004): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7004): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7004): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7004): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7004): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=26.7, 0.0, 0.0  rx=21.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:914983768] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=26.7, 0.0, 0.0  rx=21.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:914983769] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/HttpIssuerBase( 7004): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 7004): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7004): java.io.IOException
E/HttpIssuerBase( 7004): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7004): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7004): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7004): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7004): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7004): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7004): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7004): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7004): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7004): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7004): 	at agP.run(LegacySyncManager.java:416)
E/SyncManager( 7004): AuthenticatorException
E/SyncManager( 7004): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7004): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7004): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7004): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7004): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7004): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GAV2    ( 7004): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1030): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@29510072}
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 26360, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,I/ActivityManager( 1030): Killing 6467:com.android.gallery3d/u0a27 (adj 15): empty #17
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 149145, reason: Periodic
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6467/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 117384679647; DSPS: 3987168; Offset : -4306190324
I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3173): Thermal-Lib-Client: Client request sent
,E/UEI.SmartControl( 6838): file observer is disposed!
,D/serial_port( 6838): close(fd = 24)
I/UEI.SmartControl( 6838): Serial port is closed.
D/UEI.SmartControl( 6838): Internal timer expired: 3
D/UEI.SmartControl( 6838): unbind internal service
D/UEI.SmartControl( 6838): Service.onUnbind: IControl
D/UEI.SmartControl( 6838): Service.onDestroy
D/UEI.SmartControl( 6838): Lock is in USE false
D/UEI.SmartControl( 6838): unbind internal service
I/UEI.SmartControl( 6838): Serial port is closed.
I/UEI.SmartControl( 6838): Serial port is closed.
D/UEI.SmartControl( 6838): Blaster closed
D/UEI.SmartControl( 6838): Shut down QS...
D/UEI.SmartControl( 6838): Stopping QS lib
D/UEI.SmartControl( 6838): QS lib stop result = true
D/UEI.SmartControl( 6838): Stopped QS lib
D/UEI.SmartControl( 6838): QS shutdown complete
,I/ActivityManager( 1030): Killing 6489:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_6489/cgroup.procs: No such file or directory
,I/GAV2    ( 6915): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6003): 
I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6003): 
I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 6003): 
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=23.8, 0.0, 0.0  rx=18.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:914986779] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=23.8, 0.0, 0.0  rx=18.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:914986790] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
I/ActivityManager( 1030): Killing 6618:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_6618/cgroup.procs: No such file or directory
,I/GAV2    ( 7004): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 6003): 
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=9.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:914989807] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=9.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:914989810] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1445): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1871): replaced split : contains_com.google.android.talk / true
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1871): split_name #11 / not available #0
I/SplitUIService( 1871): split app #11
,I/[LGHome]EVENT( 2063): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7122 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1445): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 2063): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1445): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[SystemUI]QPairHandler( 1445): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1445): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1445): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
W/ResourcesManager( 2063): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/administrator( 1030): Handling package changes for user 0
,I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 7122): onCreate
W/AppUp4:DB( 7122):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7122):  setFingerPrint start
I/AppUp4:DB( 7122):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7122):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7122):  SDK version = 21
I/AppUp4:DB( 7122):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7122): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7122): onReceive
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/administrator( 1030): Handling package changes for user 0
D/LgDataFeature( 7122): LgDataFeature() Constructor: none
D/LgDataFeature( 7122): LgDataFeature() Constructor Done, null
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
D/AppUp4:CustFacade( 7122): Context : android.app.ReceiverRestrictedContext@3e4c33a0
D/AppUp4:CustFacade( 7122): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7122): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7122): begin check event
I/AppUp4:CustModeStarterReceiver( 7122): Event For Nothing, skip.
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7158 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6514:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6514/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2063): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 2063): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7158): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7158): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7158): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7158): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7158): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7158): BUILD Country: EU
I/SystemConfig( 7158): BUILD Operator: OPEN
,I/ActivityManager( 1030): Killing 6254:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6254/cgroup.procs: No such file or directory
,I/SystemConfig( 7158): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7158): existFile = false
I/SystemConfig( 7158): canReadFile = false
I/SystemConfig( 7158): systemFeature RCS result false
D/SystemConfig( 7158): refreshRcsSupport() :false
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:914992834] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:914992835] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/ActivityManager( 1030): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7181 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7181): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7181): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7181): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7181): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7181): Total System Memory = 2995761152
,D/SystemHelper( 7181): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1030): Killing 6768:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6768/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4269): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7204 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ResourcesManager( 4269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4269): UpdateCorporaTask done [took 99 ms] updated apps [took 99 ms] 
,I/LockScreenSettings( 7204): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7227 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6806:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_6806/cgroup.procs: No such file or directory
,W/ResourcesManager( 7227): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7250 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GLSActivity( 2110): [ac] getting account id
,I/GLSUser ( 2110): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 37716(1870KB) AllocSpace objects, 8(512KB) LOS objects, 33% free, 44MB/66MB, paused 2.653ms total 142.309ms
,D/Finsky  ( 7250): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7250): LgDataFeature() Constructor: none
D/LgDataFeature( 7250): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7250): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7298 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7250): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7250): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7298): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7298): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7250): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager( 1030): Killing 6729:com.lge.clock/u0a10 (adj 15): empty #17
D/Finsky  ( 7250): [1] 2.run: Finished loading 1 libraries.
I/MultiDex( 7298): VM with version 2.1.0 has multidex support
I/MultiDex( 7298): install
,I/MultiDex( 7298): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_6729/cgroup.procs: No such file or directory
,V/DownloadManager( 3354): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3354): created cursor android.database.sqlite.SQLiteCursor@344726c4 on behalf of 7250
I/AppUp4:CustModeStarterReceiver( 7122): onReceive
D/PackageBroadcastService( 2316): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 7250): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/AppUp4:CustFacade( 7122): Context : android.app.ReceiverRestrictedContext@3e4c33a0
D/AppUp4:CustFacade( 7122): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7122): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7122): begin check event
I/AppUp4:CustModeStarterReceiver( 7122): Event For Nothing, skip.
V/JNIHelp ( 7298): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 7250): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PeopleContactsSync( 2316): CP2 sync disabled
I/UpdateIcingCorporaServi( 4269): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7204): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true,
D/LockScreenSettings( 7204): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7204): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/PackageBroadcastService( 2316): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/PeopleContactsSync( 2316): CP2 sync disabled
,W/ActivityThread( 7298): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7298): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b9bf048: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7298): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2110): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2110): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2316): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7024): callingUid 10005, callindPid: 7024
,D/LocationInitializer( 2316): Restart initialization of location
E/MDM     ( 1816): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/UpdateIcingCorporaServi( 4269): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,I/art     ( 2110): Explicit concurrent mark sweep GC freed 17754(1035KB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 1.417ms total 39.238ms
,V/Finsky  ( 7250): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=864324786, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/Finsky  ( 7250): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1e80df80 type 0 when 1456908908843 com.android.vending} when 1456908908843
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=864324786 [*alarm*], flags=0x0
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7250): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:914995852] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:914995854] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
W/Finsky  ( 7250): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7250): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7250): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7250): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7250): [1] DailyHygiene.reschedule: Scheduling new run in 738 minutes (failures=5)
,D/DeviceConnectionService( 1816): client connected with version: 7571000
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:914998873] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:914998876] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030): Killing 6601:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_6601/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Killing 6746:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10069/pid_6746/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2437 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915001899] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2437 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915001902] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 137386315369; DSPS: 4642581; Offset : -4306173154
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915004925] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:915004934] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{aeeb7d3 type 2 when 139273 android} when 139273
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915007955] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:915007964] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915010990] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915010993] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:915014023] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915014026] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915017050] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915017053] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915020082] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915020085] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915023109] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915023112] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 157391699892; DSPS: 5298118; Offset : -4306189957
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3a2c56d4 type 0 when 1456908929228 com.android.vending} when 1456908929228
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7250): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7250): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7250): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915026137] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915026147] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915029161] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915029164] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915032184] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915032194] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915035216] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:915035229] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{17d28596 type 2 when 169305 android} when 169305
,I/BooksSync( 6449): Starting books sync
,D/BooksSync( 6449): started syncMyEbooks
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1030): Explicit concurrent mark sweep GC freed 38935(1701KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.875ms total 171.171ms
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2110): innerSync failed
D/ContactsSyncAdapter( 2110): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2110): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2110): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2110): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2110): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2110): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2110): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 141895, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 231500, reason: 10019
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
,W/ApiaryClient( 6449): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6105797968969108018&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/HttpHelper( 6449): null auth token
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
W/ResourcesManager( 1398): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1398): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
,D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
,W/ApiaryClient( 6449): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6105797968969108018&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915038249] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915038252] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
,D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
,W/ApiaryClient( 6449): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6105797968969108018&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,E/BooksSync( 6449): Soft error: 
E/BooksSync( 6449): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6105797968969108018&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6449): Headers:
E/BooksSync( 6449): accept-encoding: [gzip]
E/BooksSync( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6449): gdata-version: 2
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6449): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6449): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6449): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6449): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6449): {
E/BooksSync( 6449):  "error": {
E/BooksSync( 6449):   "errors": [
E/BooksSync( 6449):    {
E/BooksSync( 6449):     "domain": "global",
E/BooksSync( 6449):     "reason": "required",
E/BooksSync( 6449):     "message": "Login Required",
E/BooksSync( 6449):     "locationType": "header",
E/BooksSync( 6449):     "location": "Authorization"
E/BooksSync( 6449):    }
E/BooksSync( 6449):   ],
E/BooksSync( 6449):   "code": 401,
E/BooksSync( 6449):   "message": "Login Required"
E/BooksSync( 6449):  }
E/BooksSync( 6449): }
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6449): 	... 8 more
,E/BooksSync( 6449): Sync error
E/BooksSync( 6449): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6105797968969108018&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6449): Headers:
E/BooksSync( 6449): accept-encoding: [gzip]
E/BooksSync( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6449): gdata-version: 2
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6449): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6449): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6449): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6449): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6449): {
E/BooksSync( 6449):  "error": {
E/BooksSync( 6449):   "errors": [
E/BooksSync( 6449):    {
E/BooksSync( 6449):     "domain": "global",
E/BooksSync( 6449):     "reason": "required",
E/BooksSync( 6449):     "message": "Login Required",
E/BooksSync( 6449):     "locationType": "header",
E/BooksSync( 6449):     "location": "Authorization"
E/BooksSync( 6449):    }
E/BooksSync( 6449):   ],
E/BooksSync( 6449):   "code": 401,
E/BooksSync( 6449):   "message": "Login Required"
E/BooksSync( 6449):  }
E/BooksSync( 6449): }
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6449): 	... 8 more
I/BooksSync( 6449): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 144777, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915041274] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915041277] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 177393699676; DSPS: 5953543; Offset : -4306173893
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915044289] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915044292] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{971377e type 0 when 1456908957845 com.android.vending} when 1456908957845
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7250): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7250): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7250): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915047318] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915047321] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915050343] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915050346] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915053371] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915053374] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915056399] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915056402] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915059427] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915059431] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915062458] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915062461] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 197395756908; DSPS: 6608971; Offset : -4306192065
I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  302): 
,I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,E/Diag_Lib(  903): [IMS_FATAL]| 3347 | 914 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915065487] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915065491] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=864324786, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3ca1a230 type 2 when 199363 android} when 199363
,D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=864324786 [*alarm*], flags=0x0
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{30187c2e type 0 when 1456908980249 com.android.vending} when 1456908980249
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2110): Explicit concurrent mark sweep GC freed 26598(1580KB) AllocSpace objects, 10(1440KB) LOS objects, 50% free, 30MB/62MB, paused 1.524ms total 35.751ms
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7250): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7250): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7250): [1] 5.onFinished: Scheduling replication attempt 5.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915068517] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:915068529] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915071549] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915071552] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915074575] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915074585] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915077608] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915077611] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915080636] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915080646] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915083667] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915083671] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 217397839609; DSPS: 7264399; Offset : -4306184610
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915086703] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915086706] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915089731] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915089734] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915092757] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915092761] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2c39f760 type 2 when 187809 android} when 187809
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{21324cde type 0 when 1456909001159 com.android.vending} when 1456909001159
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7250): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7250): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7250): [1] 5.onFinished: Giving up after 6 failures.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915095787] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915095790] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915098818] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915098822] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{6e9f890 type 2 when 233991 android} when 233991
,I/BooksSync( 6449): Starting books sync
,D/BooksSync( 6449): started syncMyEbooks
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
,W/ApiaryClient( 6449): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1369273604845607099&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915101845] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:915101856] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  },
W/ApiaryClient( 6449): }
,W/ApiaryClient( 6449): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1369273604845607099&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do just update job
D/LgeQuickCoverNotificationData( 1398): showAll3
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1398): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1398): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6449): Authentication error
E/BooksAccountManager( 6449): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6449): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6449): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6449): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6449): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{3e1eac7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6449): Error response from books API: {
W/ApiaryClient( 6449):  "error": {
W/ApiaryClient( 6449):   "errors": [
W/ApiaryClient( 6449):    {
W/ApiaryClient( 6449):     "domain": "global",
W/ApiaryClient( 6449):     "reason": "required",
W/ApiaryClient( 6449):     "message": "Login Required",
W/ApiaryClient( 6449):     "locationType": "header",
W/ApiaryClient( 6449):     "location": "Authorization"
W/ApiaryClient( 6449):    }
W/ApiaryClient( 6449):   ],
W/ApiaryClient( 6449):   "code": 401,
W/ApiaryClient( 6449):   "message": "Login Required"
W/ApiaryClient( 6449):  }
W/ApiaryClient( 6449): }
,W/ApiaryClient( 6449): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1369273604845607099&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6449): Headers:
W/ApiaryClient( 6449): accept-encoding: [gzip]
W/ApiaryClient( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6449): gdata-version: 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 237399933559; DSPS: 7919828; Offset : -4306196426
,E/BooksSync( 6449): Soft error: 
E/BooksSync( 6449): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1369273604845607099&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6449): Headers:
E/BooksSync( 6449): accept-encoding: [gzip]
E/BooksSync( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6449): gdata-version: 2
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6449): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6449): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6449): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6449): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6449): {
E/BooksSync( 6449):  "error": {
E/BooksSync( 6449):   "errors": [
E/BooksSync( 6449):    {
E/BooksSync( 6449):     "domain": "global",
E/BooksSync( 6449):     "reason": "required",
E/BooksSync( 6449):     "message": "Login Required",
E/BooksSync( 6449):     "locationType": "header",
E/BooksSync( 6449):     "location": "Authorization"
E/BooksSync( 6449):    }
E/BooksSync( 6449):   ],
E/BooksSync( 6449):   "code": 401,
E/BooksSync( 6449):   "message": "Login Required"
E/BooksSync( 6449):  }
E/BooksSync( 6449): }
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6449): 	... 8 more
,E/BooksSync( 6449): Sync error
E/BooksSync( 6449): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6449): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1369273604845607099&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6449): Headers:
E/BooksSync( 6449): accept-encoding: [gzip]
E/BooksSync( 6449): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6449): gdata-version: 2
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6449): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6449): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6449): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6449): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6449): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6449): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6449): {
E/BooksSync( 6449):  "error": {
E/BooksSync( 6449):   "errors": [
E/BooksSync( 6449):    {
E/BooksSync( 6449):     "domain": "global",
E/BooksSync( 6449):     "reason": "required",
E/BooksSync( 6449):     "message": "Login Required",
E/BooksSync( 6449):     "locationType": "header",
E/BooksSync( 6449):     "location": "Authorization"
E/BooksSync( 6449):    }
E/BooksSync( 6449):   ],
E/BooksSync( 6449):   "code": 401,
E/BooksSync( 6449):   "message": "Login Required"
E/BooksSync( 6449):  }
E/BooksSync( 6449): }
E/BooksSync( 6449): 
E/BooksSync( 6449): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6449): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6449): 	... 8 more
I/BooksSync( 6449): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 233991, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915104877] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:915104889] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915107905] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915107915] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:915110930] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915110933] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915113955] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915113965] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]LGPowerUI( 1445): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1445): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1445): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1445): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1030): battery changed pluggedType: 2
D/LEDHandler( 1942): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1942): Battery Level Remaining: 100%
D/LEDHandler( 1942): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 6067): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1445): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3999): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3999): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915116984] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915116987] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915120014] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915120017] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915123042] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915123045] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 257403375063; DSPS: 8575300; Offset : -4306172813
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:915126062] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:915126063] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915129081] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915129084] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=864324786, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1676a3fa type 2 when 264034 android} when 264034
D/[Concierge]Service( 2606): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=864324786 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915132107] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915132111] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915135135] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:915135145] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915138165] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:915138166] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915141179] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915141182] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 277405419534; DSPS: 9230727; Offset : -4306173098
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:915144208] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915144211] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915147237] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:915147246] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915150265] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:915150277] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915153299] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915153302] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915156329] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915156332] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:915159357] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:915159361] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915162387] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:915162398] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 297407483537; DSPS: 9886155; Offset : -4306184133
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:915165418] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915165421] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1445): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1445): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1445): called onTimeUpdated()
I/[SystemUI]Clock( 1445): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
,I/[SystemUI]DateView( 1445): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1445): handleTimeUpdate
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:915168449] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:915168452] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/jxcore-log( 6003): Reconnected to the test server
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): --= Surplus to requirements =--
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): ****TEST TOOK:  ms ****
I/jxcore-log( 6003): 
,I/jxcore-log( 6003): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6003): 
,D/AndroidRuntime( 7495): 
D/AndroidRuntime( 7495): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7495): CheckJNI is OFF
D/AndroidRuntime( 7495): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1030): Killing 6003:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1030): WIN DEATH: Window{6faecd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Focus left window: Window{6faecd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1030): Window went away: Window{6faecd5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1030): Skipping PackageSetting{2e06f4c4 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1030):   Force finishing activity ActivityRecord{21a98c56 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
,W/ActivityManager( 1030): Spurious death for ProcessRecord{3d62dab 6003:com.test.thalitest/u0a311}, curProc for 6003: null
,D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{6c5a4fa co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2063): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2063): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1942): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2063): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1942): topRunningActivity=ActivityInfo{2dc79aab co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2063): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,D/ActionManagerService( 1905): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2731): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2063): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/KeyguardModel( 1445): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,E/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 2731): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2009): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4269): Explicit concurrent mark sweep GC freed 29116(1684KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 599us total 61.487ms
,I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7526 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/GeofencerStateMachine( 1816): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4229): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 4229): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4229): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4229): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4229): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4229): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4229): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4229): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4229): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4229): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4229): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4229): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]LGActivityUtil( 2063): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2063): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1445): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1445): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1445): createShortcutInfo...
I/[LGHome]EVENT( 2063): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2063): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/KeyguardModel( 1445): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1445): createShortcutInfo...
D/ActionManagerService( 1905): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2731): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2731): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.mms: Resource ID #0x0
,I/GBoardWebViewUtils( 2063): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2063): , create_time: 1430558575574
I/GBoardWebViewUtils( 2063): , expire_time: 0
I/GBoardWebViewUtils( 2063): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2063): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2063): , display: false
I/GBoardWebViewUtils( 2063): , animation: false }
I/GBoardWebViewUtils( 2063): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2063): , create_time: 1430558575600
I/GBoardWebViewUtils( 2063): , expire_time: 0
I/GBoardWebViewUtils( 2063): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2063): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2063): , display: false
I/GBoardWebViewUtils( 2063): , animation: false }
I/GBoardWebViewUtils( 2063): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2063): , create_time: 1455195785688
I/GBoardWebViewUtils( 2063): , expire_time: 0
I/GBoardWebViewUtils( 2063): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2063): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2063): , display: false
I/GBoardWebViewUtils( 2063): , animation: false }
D/KeyguardModel( 1445): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1445): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1445): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1445): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WallpaperManager( 2063): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/WindowManager( 1030): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]NavigationThemeResource( 1445): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1445): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1445):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1445): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22719796,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1445): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1445): createShortcutInfo...
,D/InputDispatcher( 1030): Focus entered window: Window{131f7216 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/SplitUIManager( 1871): split_name #11 / not available #0
D/SplitUIService( 1871): removed split : 
D/KeyguardModel( 1445): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1445): createShortcutInfo...
I/[LGHome]GBoardWebView( 2063): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1445): handleShortcutListChanged...
,D/KeyguardModel( 1445): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1445): createShortcutInfo...
D/KeyguardModel( 1445): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1445): createShortcutInfo...
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1445): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1445): createShortcutInfo...
,W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1445): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1445): createShortcutInfo...
D/SplitUIManager( 1871): split_name #11 / not available #0
I/SplitUIService( 1871): split app #11
W/ResourceType( 1445): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1445): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1445): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1445): createShortcutInfo...
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/KeyguardModel( 1445): handleShortcutListChanged...
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2063): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2063): [Launcher.java:5349:onStop()]onStop
I/[LGHome]EVENT( 2063): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2063): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2063): notifyExtViewAvailable
,W/ResourcesManager( 7526): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     ( 1030): Explicit concurrent mark sweep GC freed 70420(3MB) AllocSpace objects, 11(1072KB) LOS objects, 33% free, 44MB/67MB, paused 2.240ms total 238.747ms
,I/art     ( 1030): WaitForGcToComplete blocked for 155.122ms for cause Explicit
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6067): [BTUI] [-] updateMediaPlayerInfo
D/PluginManager( 7526): init()
D/administrator( 1030): Handling package changes for user 0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/InputMethodManagerService( 1030): setImestate : 0
W/InputMethodManagerService( 1030): Got RemoteException sending setActive(false) notification to pid 6003 uid 10311
,I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1030): removeObsoleteFile: deleting file=4_task.xml
,I/[LGHome]Launcher.Model( 2063): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{359e5933 u0 com.lge.launcher2/.Launcher t3} time:303614
W/IInputConnectionWrapper( 2063): getTextBeforeCursor on inactive InputConnection
E/b       ( 1688): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]Launcher.Model( 2063): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2063): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2063): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/art     ( 1030): Explicit concurrent mark sweep GC freed 9725(580KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.071ms total 217.096ms
,I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 2063): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2063): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2063): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2606): onStartCommand(). Type : 8
D/[Concierge]Service( 2606): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2606): Update widget ID : 11
D/[Concierge]WidgetView( 2063): change position of spinner
I/[Concierge]WidgetView( 2063): initWebView(). Time : 1456909083714
D/[Concierge]Service( 2606): onStartCommand(). Type : 0
I/[Concierge]WebView( 2063): Return exist ConciergeWebView. Reuse : 789777757
D/[Concierge]WidgetView( 2063): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2063): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2063): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@7a19d45
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2063): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2063): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2063): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2063): Widget kill message received. Destory myself. My : 1456908807533, New one : 1456909083714
D/[Concierge]WidgetView( 2063): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2063): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/AndroidRuntime( 7495): Shutting down VM
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2063): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2063): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2063): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2063): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2063): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2063): Timeline: Activity_idle id: android.os.BinderProxy@1212c190 time:303790
,W/ExternalStrings( 7526): load override strings
W/ExternalStrings( 7526): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7526): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7526): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7526): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7526): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7526): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7526): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7526): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7526): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7526): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7526): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7526): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7526): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7526): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7526): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7526): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7526): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7526): onCreate
V/Signer  ( 7526): override build config not found
,D/Signer  ( 7526): value of property debug is false
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7526): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 7526): Create singleton instance
D/LGMDMWrapper( 7526): LG MDM library v4.0.0 is available on this device.
,I/chromium( 2063): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/PostponalbeReceiver( 7526): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 7526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/GBoardtInterface( 2063): onReloaded()
I/GBoardWebViewClient( 2063): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2731): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2731): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/ActionManagerService( 1905): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2731): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2731): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1905): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2731): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2731): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2731): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2731): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2731): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/AppUp4:PreloadHelper( 7122): added Exclude : com.test.thalitest
I/ActivityManager( 1030): Killing 6838:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/GBoardUriUtils( 2063): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2063): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2063): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2063): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2063): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2063): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
W/ActivityThread( 7526): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/SQLiteDatabase( 7526): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7526): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7526): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteDatabase( 7526): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7526): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7526): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7526): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7526): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7526): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQ,LiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7526): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7526): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7526): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7526): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7526): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7526): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7526): Opened lockedapplications in read-only mode

```
