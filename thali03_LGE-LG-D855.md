#### Test 50650278c17c777_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/AndroidRuntime( 6158): 
D/AndroidRuntime( 6158): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6158): CheckJNI is OFF
D/AndroidRuntime( 6158): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1972): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{37fbc19 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{37fbc19 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  327): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6178 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6158): Shutting down VM
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1862): Display #0 changed.
D/SplitWindowPolicy( 1972): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1972): topRunningActivity=ActivityInfo{26860e7 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1972): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1972): topRunningActivity=ActivityInfo{2da1d494 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 27759(1221KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.745ms total 126.228ms
,D/ContextHelper( 6178): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6178): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6178): Loading: webviewchromium
I/LibraryLoader( 6178): Time to load native libraries: 3 ms (timestamps 7450-7453)
I/LibraryLoader( 6178): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6178): Binding Chromium to main looper Looper (main, tid 1) {351a15b0}
I/LibraryLoader( 6178): Expected native library version number "",actual native library version number ""
I/chromium( 6178): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6178): Initializing chromium process, renderers=0
W/art     ( 6178): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6178): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6178): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6178): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6178): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  310): registerClient() client 0xb57bc1e0, uid 10311
,I/Adreno-EGL( 6178): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6178): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6178): Build Date: 12/12/14 금
I/Adreno-EGL( 6178): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6178): Remote Branch: 
I/Adreno-EGL( 6178): Local Patches: 
I/Adreno-EGL( 6178): Reconstruct Branch: 
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12c58fdb:true
D/BluetoothAdapter( 6178): 81202217: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6178): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6178): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6178): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6178): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6178): CordovaWebView is running on device made by: LGE
W/art     ( 6178): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6178): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{3d08e4de u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 6178): Render dirty regions requested: true
I/OpenGLRenderer( 6178): Initialized EGL, version 1.4
D/OpenGLRenderer( 6178): Enabling debug mode 0
D/Atlas   ( 6178): Validating map...
D/SplitWindow( 1030): check instance of lgWin Window{16e5dbfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6178): LgDataFeature() Constructor: none
D/LgDataFeature( 6178): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/PhoneStatusBar( 1465): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1a604eb0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1465): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1465):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1465): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6178): Timeline: Activity_idle id: android.os.BinderProxy@d6e5199 time:307833
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +656ms (total +766ms)
I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{3d08e4de u0 com.test.thalitest/.MainActivity t4} time:307836
D/JsMessageQueue( 6178): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6178): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6178): 
I/chromium( 6178): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6178): 
D/jxcore_app_log( 6178): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435071744
D/JX-Cordova( 6178): jxcore cordova android initializing
E/GBMv2   (  327): DFP En is all cleared set to be enabled
E/GBMv2   (  327): Set value is all cleared set the max
I/GBMv2   (  327): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6178): Initializing JXcore engine
W/jxcore-log( 6178): JXcore engine is ready
W/jxcore-log( 6178): Starting JXcore engine
W/.test.thalitest( 6178): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8282]" dev="sockfs" ino=8282 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6178): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6178): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10380]" dev="sockfs" ino=10380 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6178): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6178): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[30222]" dev="sockfs" ino=30222 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6178): Platform android
W/jxcore-log( 6178): 
W/jxcore-log( 6178): Process ARCH arm
W/jxcore-log( 6178): 
,I/jxcore-log( 6178): JXcore Cordova bridge is ready!
I/jxcore-log( 6178): 
W/jxcore-log( 6178): JXcore engine is started
,I/jxcore-log( 6178): Toggling radios to true
I/jxcore-log( 6178): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiService( 1030): New client listening to asynchronous messages
,I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6249 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=6178, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=6178, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 310510285251; DSPS: 10316001; Offset : -4324122869
,E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
D/WifiServiceImplEx( 1030): disconnect pid=6178, uid=10311, packageName=com.test.thalitest
I/WifiUtil( 1030): gEnableBmps=1
D/WifiServiceImplEx( 1030): reconnect pid=6178, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6178): Radios toggled
I/jxcore-log( 6178): 
,W/ResourcesManager( 6249): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6249): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6249): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6249): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6249): Loading JNI Library
,D/SoftapController(  305): Softap fwReload - Ok
,D/CommandListener(  305): Setting iface cfg
D/CommandListener(  305): Trying to bring down wlan0
D/CommandListener(  305): Clearing all IP addresses on wlan0
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1030): InitialState.processMessage what=4
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/BluetoothAdapterApp( 6249): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b89a944 Instance Count = 1
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6288 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothAdapterApp( 6249): onCreate
,D/ProfileConfigQcom( 6249): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6249): Adding HeadsetService
D/ProfileConfigQcom( 6249): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6249): Adding A2dpService
D/ProfileConfigQcom( 6249): [BTUI] HidService is supported
D/ProfileConfigQcom( 6249): Adding HidService
D/ProfileConfigQcom( 6249): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6249): Adding HealthService
D/LGBluetoothFeatureConfig( 6249): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6249): [BTUI] PanService is supported
D/ProfileConfigQcom( 6249): Adding PanService
D/ProfileConfigQcom( 6249): [BTUI] GattService is supported
D/ProfileConfigQcom( 6249): Adding GattService
D/ProfileConfigQcom( 6249): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6249): Adding BluetoothMapService
D/ProfileConfigQcom( 6249): [BTUI] HeadsetClientService is NOT supported
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,W/ResourcesManager( 6288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/wpa_supplicant( 6306): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6306): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c07d684:true
,D/BluetoothAdapterState( 6249): make
I/LGFMServiceAdapter( 6249): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6249): init
I/BluetoothAdapterState( 6249): Entering OffState
W/bdaddr_loader( 6310): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6310): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/wpa_supplicant( 6306): Successfully initialized wpa_supplicant
I/bte_conf( 6249): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6249): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6249): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6249): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6249): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6249): get_profile_interface socket
I/GKI_LINUX( 6249): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid-qcom( 6249): get_profile_interface map_client
D/BluetoothAdapterProperties( 6249): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6249): Name is: G3-1
D/lge_bdaddr_loader( 6310): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6310): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6310): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6249): config_hci_snoop_log
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6249): Create singleton instance
D/lge_bdaddr_loader( 6310): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
,E/lge_bdaddr_loader( 6310): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6310): [BTUI] bdaddr_loader ::: END
I/wpa_supplicant( 6306): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6306): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterState( 6249): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6249): Setting state to 11
I/BluetoothAdapterState( 6249): Bluetooth adapter state changed: 10-> 11
I/LGBluetoothServiceJni( 6249): classInitNative: succeeds
,D/BluetoothManagerService( 1030): Message: 60
,D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1972): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothBondStateMachine( 6249): make
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/LGBluetoothServiceAdapter( 6249): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/LGBluetoothServiceAdapter( 6249): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 6249): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6249): StableState(): Entering Off State
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6288): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6288): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6288): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/WfdStateTracker( 1972): WfdStateTracker handleDirectStateChangedEvent: 1
E/BluetoothAdapterService( 6249): File transfer profiles supported!!
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
,D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/BluetoothAdapterService( 6249): File transfer profiles supported!!
D/BluetoothHeadset( 1862): Proxy object connected
D/BluetoothHeadset( 1862): Proxy object connected
D/BluetoothHeadset( 1862): Proxy object connected
D/BluetoothHeadset( 1030): Proxy object connected
D/HeadsetService( 6249): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6249): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6249): Version 1.6
E/BluetoothAdapterService( 6249): File transfer profiles supported!!
D/LGBluetoothFeatureConfig( 6249): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6249): classInitNative: succeeds
D/HeadsetStateMachine( 6249): make
E/BluetoothAdapterService( 6249): File transfer profiles supported!!
,E/BluetoothAdapterService( 6249): File transfer profiles supported!!
E/BluetoothAdapterService( 6249): File transfer profiles supported!!
E/BluetoothAdapterService( 6249): File transfer profiles supported!!
D/UsbSettingsControl( 6288): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6288): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 6288): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1030): Killing 5855:com.google.android.partnersetup/u0a8 (adj 15): empty #17
D/LgDataFeature( 6249): LgDataFeature() Constructor: none
D/LgDataFeature( 6249): LgDataFeature() Constructor Done, null
I/wpa_supplicant( 6306): rfkill: Cannot open RFKILL control device
D/HeadsetStateMachine( 6249): max_hf_connections = 1
I/bluedroid-qcom( 6249): get_profile_interface handsfree
,V/LGMDMManager( 6249): Create singleton instance
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5855/cgroup.procs: No such file or directory
V/ToneGenerator( 6249): ToneGenerator constructor: streamType=8, volume=1.000000
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6288): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6288): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6288): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6288): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6288): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6288): [AUTORUN] setTetherStatus() : status=false
V/AudioPolicyService(  310): registerClient() client 0xb57bc340, uid 1002
V/AudioPolicyManager(  310): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  310): AudioPolicyManagerEx: getOutputForDevice
,V/AudioPolicyManagerEx(  310): getOutput() returns output 2
V/AudioSystem( 6249): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  310): registerClient() client 0xb14331c0, pid 6249
V/AudioSystem(  310): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  310): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1862): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1862): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3299): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3299): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6249): ioConfigChanged() event 0, ioHandle 2
I/wpa_supplicant( 6306): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
V/AudioSystem(  310): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  310): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3299): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3299): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6249): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/ToneGenerator( 6249): Create Track: 0xb4928080
V/AudioTrack( 6249): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6249): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6249): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6249): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  310): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  310): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  310): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  310): getOutput() returns output 2
I/AudioFlinger(  310): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  310): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  310): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  310): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  310): getOutput() returns output 2
V/AudioSystem( 6249): getLatency() output 2, latency 50
V/AudioSystem( 6249): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6249): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  310): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  310): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  310): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  310): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  310): createTrack() lSessionId: 16
V/AudioTrack( 6249): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6306): wlan0: CTRL-EVENT-SCAN-STARTED 
I/BluetoothAdapterState( 6249): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioFlinger(  310): acquiring 16 from 6249, for 6249
V/AudioFlinger(  310):  added new entry for 16
V/ToneGenerator( 6249): ToneGenerator INIT OK, time: 311038
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/HeadsetStateMachine( 6249): Enter Disconnected: -2, size: 0
,E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
D/HeadsetPhoneState( 6249): [BTUI] listenForPhoneState : start = false
V/AudioSystem( 1862): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1862): ioConfigChanged() opening already existing output! 4
D/LGBluetoothHfpManager( 6249): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6249): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioSystem( 1465): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1465): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1465): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1465): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  310): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6249
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/audio_hw_primary(  310): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  310): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  310): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  310): voice_extn_compress_voip_set_parameters: exit
V/voice   (  310): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  310): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  310): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  310): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  310): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  310): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  310): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
V/ToneGenerator( 6249): ToneGenerator destructor
V/ToneGenerator( 6249): stopTone
V/ToneGenerator( 6249): Delete Track: 0xb4928080
V/AudioTrack( 6249): ~AudioTrack, releasing session id from 6249 on behalf of 6249
E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
V/AudioFlinger(  310): releasing 16 from 6249 for 6249
V/AudioFlinger(  310):  decremented refcount to 0
V/AudioFlinger(  310): purging stale effects
V/AudioPolicyService(  310): AudioCommandThread() adding release output 2
V/AudioPolicyService(  310): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  310): AudioCommandThread() waking up
V/AudioPolicyService(  310): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  310): releaseOutput() 2
V/AudioPolicyService(  310): AudioCommandThread() going to sleep
V/AudioFlinger(  310): PlaybackThread::Track destructor
V/AudioFlinger(  310): removeClient_l() pid 6249, calling pid 310
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_RECONNECT 0 0
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1030):  DefaultState CMD_RECONNECT 0 0
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1030): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1030):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1030): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed,( 1030): setPowerSaveActivated(false)
I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6319 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/BluetoothA2dp( 1030): Proxy object connected
D/A2dpService( 6249): Received start request. Starting profile...
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
I/BluetoothAvrcpServiceJni( 6249): classInitNative: succeeds
V/Avrcp   ( 6249): make
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
D/WifiConfigStore( 1030): Loading config and enabling all networks 
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
D/Avrcp   ( 6249): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6249): get_profile_interface avrcp
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1972): Waiting for WifiP2p enabling
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
V/AudioManager( 6249): registerRemoteController: size of Media player list: 0
E/AudioManager( 6249): No RCC entry present to update
E/RemoteController( 6249): Cannot set synchronization mode on an unregistered RemoteController
E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/BluetoothAvrcpQcomServiceJni( 6249): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6249): initQcomNative: succeeds
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
D/WifiNative-wlan0( 1030): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] [+] updateMediaPlayerInfo
D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1972): Supplicant Connection state is changed : true
D/WfdsService( 1972): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1972): Set the WFDS Monitor: true
D/WfdsMonitor( 1972): WfdsMonitorThread create
D/WfdsMonitor( 1972): WFDS Monitor is created and started
D/WfdsService( 1972): WiFi: Supplicant connection re-established
,D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989898dc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0xa01bfe
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9898985c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701bee
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1972): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1972): Succeed to open control connection
E/CtrlSupplicant( 1972): Succeed to open monitor connection
D/WfdsMonitor( 1972): Supplicant connection established
D/WfdsService( 1972): Connected to the supplicant for wfds
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6306): android_multicast_filter_startstop : multicast filter set
,D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [311,135,546 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/RttService( 1030): SCAN_AVAILABLE : 3
D/CommandListener(  305): Setting iface cfg
D/WifiScanningService( 1030): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  305): Trying to bring up p2p0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94e6799c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601b16
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
D/RttService( 1030): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1030): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1030): SET device_name G3-1: returned true
V/WfdStateTracker( 1972): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1972): WifiP2pState is changed : true
D/LGWifiP2pService( 1030): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1030): before postfix = G3-1
D/WifiServerServiceExt( 1030): postfix byte check : 4
D/LGWifiP2pService( 1030): after postfix = G3-1
D/WifiNative-p2p0( 1030): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1030): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1030): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WfdsService( 1972): Receive the WFDS_ENABLE Method
D/WfdsService( 1972): Set the WFDS Monitor: true
D/WfdsService( 1972): Connected to the supplicant for wfds
D/WfdsJNI ( 1972): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6306): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1972): doCommand: WFDS_GET_MAC_ADDRESS
D/WifiNative-p2p0( 1030): SET config_methods virtual_push_button physical_display keypad: returned true
I/wpa_supplicant( 6306): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WifiNative-p2p0( 1030): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1030): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1030): p2pGetDeviceAddress
D/WfdsJNI ( 1972): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1972): selectPreferredScanChannel [36]
D/WfdsService( 1972): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-HAL( 1030): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/WfdsService( 1972): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
,D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
D/WfdsService( 1972): isConnected: false
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6306): nWIFIDualbandAPConnection: 1
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1030):    returned OK
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1972): handleP2pThisDeviceChanged
D/WfdsService( 1972): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1972): Update P2p Interface State: 3
D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned false
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
D/LGWifiP2pService( 1030): InactiveState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-2ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1972): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
I/wpa_supplicant( 6306): [LGE_PATCH] driver_cmd() country:CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1972): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1972): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6306): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-12ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-13ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-13ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-13ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-13ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-13ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-13ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-13ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1030): No p2p device connected
W/WfdsService( 1972): DefaultState - msg [9441285] is not handled
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6306): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6306): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiService( 1030): New client listening to asynchronous messages
D/WfdsMonitor( 1972): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1972): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
W/Settings( 5381): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6306): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1030): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1030): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SCAN
D/WifiNative-wlan0( 1030): SCAN: returned false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=311178  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=311178  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6344 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6249): classInitNative
I/BluetoothA2dpServiceJni( 6249): classInitNative: succeeds
D/A2dpStateMachine( 6249): make
V/FormManager( 6319): Network unavailable.
I/bluedroid-qcom( 6249): get_profile_interface a2dp
I/GKI_LINUX( 6249): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/LGBluetoothA2dpServiceJni( 6249): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6249): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
I/BluetoothHidServiceJni( 6249): classInitNative: succeeds
W/FormManager( 6319): Network not available. Please check & try again.
D/A2dpStateMachine( 6249): Enter Disconnected: -2
D/HidService( 6249): Received start request. Starting profile...
I/bluedroid-qcom( 6249): get_profile_interface hidhost
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
V/FormManager( 6319): Network unavailable.
I/BluetoothHealthServiceJni( 6249): classInitNative: succeeds
D/HealthService( 6249): Received start request. Starting profile...
I/bluedroid-qcom( 6249): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6249): classInitNative: succeeds
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
I/BluetoothPanServiceJni( 6249): classInitNative(L105): succeeds
D/PanService( 6249): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6249): initializeNative(L110): pan
I/bluedroid-qcom( 6249): get_profile_interface pan
I/LGBluetoothPanAdapter( 6249): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
I/BtGatt.JNI( 6249): classInitNative(L901): classInitNative: Success!
,I/ActivityManager( 1030): Killing 5514:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BtGatt.DebugUtils( 6249): handleDebugAction() action=null
D/BtGatt.GattService( 6249): Received start request. Starting profile...
D/BtGatt.GattService( 6249): start()
I/bluedroid-qcom( 6249): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6249): advertise manager created
D/PCSuite ( 6344): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5514/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
,V/BluetoothPbapReceiver( 6249): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6249): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6249): ***********state = 11
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
I/LGBluetoothMapAdapter( 6249): [BTUI] getInstance : create [LGBluetoothMapAdapter]
,V/BluetoothMapService( 6249): BluetoothMapBinder()
D/BluetoothMapService( 6249): Received start request. Starting profile...
D/BluetoothMapService( 6249): start()
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1030): New client listening to asynchronous messages
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6374 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothMapEmailSettingsLoader( 6249): Found 0 applications
D/BluetoothMapEmailAppObserver( 6249): createReceiver()
D/BluetoothMapEmailAppObserver( 6249): initObservers()
D/BluetoothMapEmailAppObserver( 6249): getEnabledAccountItems()
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/HeadsetStateMachine( 6249): Proxy object connected
D/LGBluetoothHfpAdapter( 6249): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6249): Try to query the phonestate on bind
,D/BluetoothPhoneService.BluetoothLTECall( 1862):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1862): Proxy not attached to service
D/BluetoothHeadset( 1862): java.lang.Throwable
D/BluetoothHeadset( 1862): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1862): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1862): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1862): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1862): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1862): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1862): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1862): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1862): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1862): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1862): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothAdapterService( 6249): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6249): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6249): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6249): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 6249): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6249): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6249): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6249): [BTUI] SIM Extra State :ABSENT
D/LgDataFeature( 6288): LgDataFeature() Constructor: none
D/LgDataFeature( 6288): LgDataFeature() Constructor Done, null
D/BluetoothAdapterService( 6249): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6249): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6249): Handler(): got msg=1
D/BluetoothAdapterState( 6249): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6249): enable
I/GKI_LINUX( 6249): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6249): btu_task pending for preload complete event
I/bt_hci_bdroid( 6249): init
D/WiFiOffLoadUpdatePriority( 6288): remove : truetruetrue
I/bt_vendor( 6249): bt-vendor : init
I/bt_vendor( 6249): bt-vendor : get_bt_soc_type
E/bt_vendor( 6249): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6249): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6249): userial_init
D/bt_hci_bdroid( 6249): set_power 1
I/bt_vendor( 6249): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6249): Starting hciattach daemon
I/bt_vendor( 6249): try to set true
W/sh      ( 6394): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6394): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6288): remove1
V/WiFiOffLoadSharedPrefsUtils( 6288): save remove
I/qcom-bluetooth( 6396): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
E/wpa_supplicant( 6306): USIM:  scard_init function
I/wpa_supplicant( 6306): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989898cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x4018f6
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
D/WiFiOffLoadBroadcast( 6288): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6288): S: false, R: false
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=311482  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=311495  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1030):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6288): saved SSID: "NG700"
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
D/WiFiOffLoadUpdatePriority( 6288): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6288): private wpa: "NG700" 300
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6288, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1030):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1030):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1030):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1030):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1030): addOrUpdateNetwork: mThisIsFirstEnableing = false
,D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1030): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1030): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1030): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1030): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1030): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1030): will read network variables netId=0
E/WifiConfigStore( 1030): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1030):  writeKnownNetworkHistory() num networks:1 needWrite=false
I/qcom-bluetooth( 6402): /system/etc/init.qcom.bt.sh: Transport : smd 
E/ActivityThread( 6374): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6374): No ProfileInfo entries
I/LG Account v2.2( 6374): isEnabled: false
I/Feature ( 6374): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6374): [Lifetracker]Country: EU
I/Feature ( 6374): [Lifetracker]Operator: OPEN
I/Feature ( 6374): [Lifetracker]Ranking support: false
I/Feature ( 6374): [Lifetracker]Comfort support: false
I/Feature ( 6374): [Lifetracker]Accessory: true
I/Feature ( 6374): [Lifetracker]Health device: true
I/Feature ( 6374): [Lifetracker]Extra Pedometer: false
I/Feature ( 6374): [Lifetracker]Blood glucose device: false
I/Feature ( 6374): [Lifetracker]Device Number: 3
D/WiFiOffLoadUpdatePriority( 6288):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6288): configuration updated: 0
I/ActivityManager( 1030): Killing 5542:com.android.contacts/u0a19 (adj 15): empty #17
,I/qcom-bluetooth( 6405): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
E/WifiStateMachine( 1030):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
I/qcom-bluetooth( 6407): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6288): configuration saved: true
I/qcom-bluetooth( 6408): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/wpa_supplicant( 6306): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=311572  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=311572  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/qcom-bluetooth( 6409): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=311573
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=311574
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=311574
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=311574
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=311575
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=311575  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6306): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6306): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/qcom-bluetooth( 6410): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6412): ESOC framework not supported
E/Diag_Lib( 6412):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5542/cgroup.procs: No such file or directory
D/bthci_qcomm_linux( 6412): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6412): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6412): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6412): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6412): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6412): [BTUI]     Ref Clock: 32M
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/btqsocnvmtags( 6412): [BTUI] init_riva_entries: set NORMAL power settings
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=311607  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=311608  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=311608  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=311609
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=311609
D/WifiNative-wlan0( 1030): doString: [STATUS]
,D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
D/BluetoothPermissionRequest( 6288): onReceive
,D/LGBluetoothFeatureConfig( 6288):  get() - isFeatureLoaded : false
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10dcb30a:true
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/ActivityManager( 1030): Killing 5878:com.lge.email/u0a23 (adj 15): empty #17
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
,E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/LGBluetoothResetSettingReceiver( 6288): return without doing reset settings.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/CommandListener(  305): Setting iface cfg
I/rmt_storage(  302): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  302): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  302): wakelock acquired: 1, error no: 42
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5878/cgroup.procs: No such file or directory
D/LGBluetoothOppAdapter( 6249): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,D/DhcpStateMachine( 1030): StoppedState
,D/DhcpStateMachine( 1030): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=311761  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=311763  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=311766  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=311778  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PCSuite ( 6344): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=311779  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=311780  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/FormManager( 6319): Network unavailable.
W/FormManager( 6319): Network not available. Please check & try again.
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1952471270] from screen [on:0 period:-1952471270]
V/FormManager( 6319): Network unavailable.
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1952471268]
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989898bc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x902066
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 6344): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6344): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6344): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@aae1f12 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@aae1f12 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  302): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  302): 
,E/Diag_Lib(  899): [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/rmt_storage(  302): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6425 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
V/BluetoothFtpReceiver( 6249): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6249): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6249): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6249): SapReceiver onReceive 
V/BluetoothSapReceiver( 6249): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6249):  Bluetooth Adapter state = 11
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6442 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourcesManager( 6425): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6425): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,W/ResourcesManager( 6442): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6425): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6425): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6425): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6425): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6425): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6425): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/ActivityManager( 1030): Killing 5570:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/QRemote ( 6425): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6459): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6459): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6459): version 5.5.6 starting
E/dhcpcd  ( 6459): get_duid: m
D/dhcpcd  ( 6459): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6459): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5570/cgroup.procs: No such file or directory
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6425): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/QRemote ( 6425): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 6013): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 6013): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 6013): Boot Receiver Return
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6425): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6425): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6288): Not supported operator for automatic switch
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/dhcpcd  ( 6459): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6459): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6459): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/dhcpcd  ( 6459): wlan0: rebinding lease of 192.168.1.125
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/dhcpcd  ( 6459): wlan0: sending REQUEST (xid 0xbb9946f9), next in 3.68 seconds
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6288): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6288): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6288): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6288): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6288): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6288): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6288): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
,D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
,D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6425): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6425): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6425): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6425): LgDataFeature() Constructor: none
D/LgDataFeature( 6425): LgDataFeature() Constructor Done, null
,V/SoundPool( 6425): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6425): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6425): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6425): doLoad: loading sample sampleID=1
I/QRemote ( 6425): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6425): Start decode
V/MediaPlayer[Native]( 6425): decode(31, 10857164, 17813)
,D/UEI.SmartControl( 5911): QS Service created
V/MediaPlayerService(  310): decode(24, 10857164, 17813)
,W/BrunchPlayerTypeImpl(  310): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  310): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  310): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  310): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  310): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  310): player type = 3
V/AwesomePlayer(  310): AwesomePlayer create()
V/AwesomePlayer(  310): reset_l() 
V/AwesomePlayer(  310): cancelPlayerEvents
V/AwesomePlayer(  310): setAudioSink() 
V/AwesomePlayer(  310): reset_l() 
V/AudioCache(  310): notify(0xb5474680, 8, 0, 0)
V/AudioCache(  310): ignored
V/AwesomePlayer(  310): cancelPlayerEvents
D/Utils   (  310): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  310): setDataSource_l dataSource
V/LGParserOSAL(  310): SniffLGParser start
V/LGParserOSAL(  310): MainType:5, SubType=0
V/LGParserOSAL(  310): #### check Mime : application/ogg
V/LGParserOSAL(  310): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  310): Use LGExtractor :application/ogg 
D/QRemote ( 6425): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6425): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6425): Create singleton instance
,V/LGParserOSAL(  310): supported mime: application/ogg
V/AwesomePlayer(  310): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  310): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  310): mBitrate = -1 bits/sec
V/AwesomePlayer(  310): AudioTrack Setting
V/AwesomePlayer(  310): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  310): setAudioSource() 
V/MediaPlayerService(  310): prepare
V/AwesomePlayer(  310): prepareAsync_l() 
V/MediaPlayerService(  310): wait for prepare
V/AwesomePlayer(  310): onPrepareAsyncEvent() 
V/AwesomePlayer(  310): initAudioDecoder() 
W/Utils   (  310): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  310): isOffloadSupported()
V/AudioPolicyManager(  310): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  310): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  310): isAudioPlaybackHookOn() false
V/AwesomePlayer(  310): getUseOffload() = 0 
V/OMXCodec(  310): OMXCodec::Create
V/OMXCodec(  310): findMatchingCodecs()
V/OMXCodec(  310): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  310): matchingCodecs.size()=1
V/OMXCodec(  310): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  310): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  310): LG Codec Adapter start
V/OMXCodec(  310): OMXCodec Createtor
V/OMXCodec(  310): setComponentRole
V/OMXCodec(  310): configureCodec protected=0
V/LGCodecAdapter(  310): called getLGCodecSpecificData
V/LGCodecOSAL(  310): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  310): Called LGconfigureCodecMETA
V/LGCodecOSAL(  310): Called LGconfigureCodecMSG
V/LGCodecOSAL(  310): Not support LGCodec
V/OMXCodec(  310): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  310): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  310): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  310): Could not offload audio decode, try pcm offload
W/Utils   (  310): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  310): isOffloadSupported()
V/AudioPolicyManager(  310): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  310): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  310): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  310): init()
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  310): allocateBuffers
V/OMXCodec(  310): allocateBuffersOnPort portIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
V/OMXCodec(  310): allocateBuffersOnPort portIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb57fb060 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb57fb0b0 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated, buffer 0xb57fb2e0 on output port
V/OMXCodec(  310): init() mAsyncCompletion wait!!! 
V/OMXCodec(  310): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  310): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  310): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  310): finishAsyncPrepare_l() 
V/AudioCache(  310): notify(0xb5474680, 5, 0, 0)
V/AudioCache(  310): ignored
V/AudioCache(  310): notify(0xb5474680, 1, 0, 0)
V/AudioCache(  310): prepared
V/AudioCache(  310): wait - success
V/MediaPlayerService(  310): start
V/AwesomePlayer(  310): play_l() 
V/AwesomePlayer(  310): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  310): createAudioPlayer_l
V/AwesomePlayer(  310): seekAudioIfNecessary_l() 
V/AwesomePlayer(  310): startAudioPlayer_l() 
D/AudioPlayer(  310): start of Playback, useOffload 0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  310): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  310): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  310): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045044320
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045044400
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045044960
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  310): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  310): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  310): allocateBuffersOnPort portIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb57fb0b0 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb57fb060 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] allocated buffer 0xb152da60 on output port
V/OMXCodec(  310): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  310): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  310): notify(0xb5474680, 6, 0, 0)
V/AudioCache(  310): ignored
V/MediaPlayerService(  310): wait for playback complete
I/UEI.SmartControl( 5911): Service initServices...
,D/UEI.SmartControl( 5911): QS start get config
,V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac104000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac105000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac106000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac107000, 0xb178a000, 4096)
,V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac108000, 0xb178a000, 4096)
,V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac109000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac10a000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac10b000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac10c000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac10d000, 0xb178a000, 4096)
,V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac10e000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac10f000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac110000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac111000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac112000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac113000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac114000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac115000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac116000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac117000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac118000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac119000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac11a000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac11b000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac11c000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac11d000, 0xb178a000, 4096)
,V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac11e000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac11f000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac120000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac121000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac122000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac123000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac124000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac125000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac126000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac127000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac128000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac129000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac12a000, 0xb178a000, 4096)
,V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac12b000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac12c000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac12d000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac12e000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac12f000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac130000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac131000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac132000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac133000, 0xb178a000, 4096)
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac134000, 0xb178a000, 4096)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  310): write(0xb178a000, 4096)
V/AudioCache(  310): memcpy(0xac135000, 0xb178a000, 4096)
V/OMXCodec(  310): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  310): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  310): postAudioEOS() 
V/AudioCache(  310): write(0xb178a000, 280)
V/AudioCache(  310): memcpy(0xac136000, 0xb178a000, 280)
V/AwesomePlayer(  310): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  310): onStreamDone
V/AwesomePlayer(  310): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  310): notify(0xb5474680, 2, 0, 0)
V/AudioCache(  310): playback complete
V/AwesomePlayer(  310): pause_l() 
V/AudioCache(  310): notify(0xb5474680, 7, 0, 0)
V/AudioCache(  310): ignored
V/AwesomePlayer(  310): cancelPlayerEvents
V/AudioCache(  310): wait - success
V/MediaPlayerService(  310): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  310): Pause Playback at 1068125
,V/AwesomePlayer(  310): reset_l() 
V/AudioCache(  310): notify(0xb5474680, 8, 0, 0)
V/AudioCache(  310): ignored
V/AwesomePlayer(  310): cancelPlayerEvents
D/AudioPlayer(  310): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  310): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  310): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  310): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb152da60 on port 1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb57fb060 on port 1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeing buffer 0xb57fb0b0 on port 1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  310): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  310): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  310): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  310): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  310): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  310): AudioPlayer releasing audio source
D/AudioPlayer(  310): AudioPlayer done releasing audio source
V/AwesomePlayer(  310): reset_l() 
V/AwesomePlayer(  310): cancelPlayerEvents
V/AwesomePlayer(  310): ~AwesomePlayer call
V/AwesomePlayer(  310): reset_l() 
V/AwesomePlayer(  310): cancelPlayerEvents
V/SoundPool( 6425): close(31)
V/SoundPool( 6425): pointer = 0x9fffd000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1782
E/QC-QMI  ( 6412): qmi_client [6412] 13: failed to locate client data
,E/QC-QMI  (  474): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  474): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/UEI.SmartControl( 5911): Supports setup maps: true
D/UEI.SmartControl( 5911): QS start statue = true Error code = 0
,I/UEI.SmartControl( 5911): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5911): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5911): ### init IR Blaster...
,D/serial_port( 5911): Configuring serial port
E/UEI.SmartControl( 5911): UEIBLaster setting for 616
I/UEI.SmartControl( 5911): Setting serial record hearder size = 2
I/UEI.SmartControl( 5911): configuring settings for MAXQ616
I/UEI.SmartControl( 5911): Get version...
,I/qcom-bluetooth( 6478): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
D/UEI.SmartControl( 5911): serial port data available: 21
,I/qcom-bluetooth( 6479): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6249): bluetooth satus is on
D/bt_hci_bdroid( 6249): preload
,D/bt_userial_mct( 6249): userial_open(port:0)
I/bt_vendor( 6249): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6249): Done intiailizing UART
I/bt_vendor( 6249): Done intiailizing UART
I/bt_userial_mct( 6249): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6249): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6249): btu_task received preload complete event
D/bt_userial_mct( 6249): Entering userial_read_thread()
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6249): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6249): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6249): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6249): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6249): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6249): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6249): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6249): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6249): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6249): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6249): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6249): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6249): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6249): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6249): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6249): BTE_InitTraceLevels -- TRC_BTIF
D/UEI.SmartControl( 5911): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5911): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5911): QS saving settings...
D/UEI.SmartControl( 5911): IR Blaster version: 25672567
,D/UEI.SmartControl( 5911): serial port data available: 4
,W/bt-btm  ( 6249): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6249): BTM_SecRegister:p_cb_info->p_le_callback == 0xa020b061 
E/bt-btm  ( 6249): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020b061 
,E/bt-btif ( 6249): Calling BTA_HhEnable
E/bt-btif ( 6249): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6249): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x001b
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6249): Name is: G3-1
D/BluetoothAdapterProperties( 6249): Scan Mode:20
D/BluetoothAdapterProperties( 6249): Discoverable Timeout:120
,D/bt_hci_bdroid( 6249): postload
D/bt_hci_bdroid( 6249): Used up Tx Cmd credits
D/bt_hci_bdroid( 6249): Used up Tx Cmd credits
D/bt_hci_bdroid( 6249): Used up Tx Cmd credits
W/bt-l2cap( 6249): L2CAP - L2CA_Register() called for PSM: 0x000f
W/bt-smp  ( 6249): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6249): Plain text(LSB ~ MSB) = 43 87 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6249): Encrypted text(LSB ~ MSB) = ec 4b 3c 49 90 3c bd 2c 44 bb a3 79 15 56 68 b1 
D/bte_conf( 6249): Device ID record 1 : primary
D/bte_conf( 6249):   vendorId            = 00c4
D/bte_conf( 6249):   vendorIdSource      = 0001
D/bte_conf( 6249):   product             = 13a1
D/bte_conf( 6249):   version             = 1000
D/bte_conf( 6249):   clientExecutableURL = 
D/bte_conf( 6249):   serviceDescription  = 
D/bte_conf( 6249):   documentationURL    = 
W/bt-btm  ( 6249): Stopping oneshot timer
D/bte_conf( 6249): bte_load_did_conf no section named DID2.
W/sh      ( 6487): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/bt_mct  ( 6249): hci lib postload completed
W/sh      ( 6487): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothPanServiceJni( 6249): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6249): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6249): ScanMode =  20
D/BluetoothAdapterProperties( 6249): State =  11
D/BluetoothAdapterProperties( 6249): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6249): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6249): Setting state to 12
I/BluetoothAdapterState( 6249): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 6249): Entering On State
,D/btif_config_util( 6249): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-smp  ( 6249): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6249): Plain text(LSB ~ MSB) = 04 c0 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6249): Encrypted text(LSB ~ MSB) = ec 35 e0 76 8b 1f 6d 59 8f 7b 8b 99 8f 7c 33 a5 
W/bt-btm  ( 6249): Stopping oneshot timer
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=true
,W/ContextImpl( 5911): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/LGBluetoothServiceAdapter( 6249): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6249): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6249): [BTUI]         local_name: G3-1
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 6249): [BTUI] autoConnect() : not allowed
,D/BluetoothHeadset( 1862): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
,W/bt-smp  ( 6249): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6249): Plain text(LSB ~ MSB) = bb 2c 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6249): Encrypted text(LSB ~ MSB) = ba d4 18 d1 a0 ef 1c b7 04 f5 95 89 5e eb f3 58 
W/bt-btm  ( 6249): Stopping oneshot timer
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1972): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1972): Message: 1
D/LGBluetoothAPIService( 1972): MESSAGE_BOOT_COMPLETED
W/bt-smp  ( 6249): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6249): Plain text(LSB ~ MSB) = 2d 47 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6249): Encrypted text(LSB ~ MSB) = bb db 1f 5f fa 15 e8 3a 55 83 ee 08 08 77 df 7e 
W/bt-btm  ( 6249): Stopping oneshot timer
I/BluetoothMapService( 6249): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6249): STATE_ON
V/BluetoothMapService( 6249): Handler(): got msg=1
D/BluetoothMapMasInstance( 6249): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 6249): MAS initSocket()
,D/BluetoothMapMasInstance( 6249):   masId = 00
D/BluetoothMapMasInstance( 6249):   msgTypes = 0e
D/BluetoothMapMasInstance( 6249):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6249):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/LGBluetoothAPIService( 1972): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothDeviceModeControllManager( 6249): [BTUI] checkDeviceModeAndSet, sinkMode : false
W/BluetoothAdapter( 6249): getBluetoothService() called with no BluetoothManagerCallback
,D/LGBluetoothServiceAdapter( 6249): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6249): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6249): Accepting socket connection...
I/qcom-bt-wlan-coex( 6496): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/LGBluetoothAPIServer( 6249): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6249): [BTUI] onBind()
D/LGBluetoothAPIService( 1972): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1972): Message: 100
D/LGBluetoothAPIService( 1972): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/bt-smp  ( 6249): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6249): Plain text(LSB ~ MSB) = c6 47 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6249): Encrypted text(LSB ~ MSB) = eb 63 8e cb ab b0 a5 26 bf 0e e4 00 3c 0c 13 07 
W/bt-btm  ( 6249): Stopping oneshot timer
,I/UEI.SmartControl( 5911): Device manager: loading config....
D/UEI.SmartControl( 5911): ----------- loading internal config...
W/ContextImpl( 6288): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
,V/BluetoothPbapService( 6249): Pbap Service onCreate
V/BluetoothPbapService( 6249): Starting PBAP service
E/UEI.SmartControl( 5911): Loading SETTINGS...
D/LGBluetoothPbapAdapter( 6249): [BTUI] getInstance : create
V/BluetoothPbapService( 6249): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6249): state: 12
V/BluetoothPbapService( 6249): Handler(): got msg=1
V/BluetoothPbapService( 6249): Pbap Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6249): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6249): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6249): ***********state = 12
V/BluetoothPbapService( 6249): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6249): getBluetoothService() called with no BluetoothManagerCallback
E/UEI.SmartControl( 5911): Services init done
D/UEI.SmartControl( 5911): QS Service init finished
D/UEI.SmartControl( 5911): QS Service version name: 2.1.91
D/UEI.SmartControl( 5911): QS Service version code: 201091
D/UEI.SmartControl( 5911): Service requested: Control
D/UEI.SmartControl( 5911): Internal service binding...
D/LGBluetoothServiceAdapter( 6249): [BTUI] createSocketChannel FD=75 mFd=73
,V/BluetoothPbapService( 6249): Succeed to create listening socket 
V/BluetoothPbapService( 6249): Accepting socket connection...
D/LocalBluetoothProfileManager( 6288): Adding local A2DP profile
D/BluetoothManagerService( 1030): Message: 30
I/QRemote ( 6425): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5911): ------ IControl API: 11
,D/UEI.SmartControl( 5911): File observer start...
D/LocalBluetoothProfileManager( 6288): Adding local HEADSET profile
E/UEI.SmartControl( 5911): IR Port is disabled: false
D/UEI.SmartControl( 5911): Starting file observer...
I/UEI.SmartControl( 5911): Registering callback...
I/UEI.SmartControl( 5911): ------ IControl API: 19
I/UEI.SmartControl( 5911): Registering Services Ready callback...
D/BluetoothManagerService( 1030): Message: 30
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/BluetoothManagerService( 1030): Message: 30
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6288): Adding local MAP profile
D/BluetoothMap( 6288): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
D/LocalBluetoothProfileManager( 6288): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6249): Pbap Service onBind
,D/LGBluetoothUserBindClient( 6288): [BTUI] initUserBindClient
W/ContextImpl( 6288): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6288): finishStartingService: stopping service
,D/BluetoothA2dp( 6288): Proxy object connected
D/A2dpProfile( 6288): Bluetooth service connected
D/BluetoothHeadset( 6288): Proxy object connected
,D/HeadsetProfile( 6288): Bluetooth service connected
D/BluetoothInputDevice( 6288): Proxy object connected
D/HidProfile( 6288): Bluetooth service connected
D/BluetoothPan( 6288): BluetoothPAN Proxy object connected
D/PanProfile( 6288): Bluetooth service connected
D/BluetoothMap( 6288): Proxy object connected
D/MapProfile( 6288): Bluetooth service connected
D/BluetoothMap( 6288): getConnectedDevices()
V/BluetoothMapService( 6249): getConnectedDevices()
D/BluetoothPbap( 6288): Proxy object connected
D/PbapServerProfile( 6288): Bluetooth service connected
D/LGBluetoothUserBindClient( 6288): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6288): onReceive
D/LGBluetoothFeatureConfig( 6288): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6288): [BTUI] FileNotFound: readProperty
,D/LGBluetoothResetSettingReceiver( 6288): return without doing reset settings.
V/BluetoothOppReceiver( 6249): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6249): [BTUI] startOppService()
D/UEI.SmartControl( 5911): -- Open brand translation xml: brands_translations_ko
V/BluetoothOppManager( 6249): restoreApplicationData! falsefalsenullnull
,I/UEI.SmartControl( 5911): Notify AllClients services are ready: 0
I/QRemote ( 6425): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 5911): -----service ready thread exits
D/QRemote ( 6425): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6425): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6425): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6425): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5911): ------ IControl API: 8
D/QRemote ( 6425): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6425): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6425): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6425): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6425): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6425): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6425): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6425): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6425): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6425): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449746476004]
D/QRemote ( 6425): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1030): Killing 5760:com.android.defcontainer/u0a4 (adj 15): empty #17
D/LGBluetoothFeatureConfig( 6249): isPrivacyLogsEnabled : true
,V/BtOppService( 6249): onCreate
,V/BluetoothOppNotification( 6249): send message
V/BtOppService( 6249): Deleted complete outbound shares, number =  0
,V/BtOppService( 6249): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6249): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/QRemote ( 6425): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@bb47058 on behalf of 
D/BluetoothAdapterProperties( 6249): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6249): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
W/libprocessgroup( 1030): failed to open /acct/uid_10004/pid_5760/cgroup.procs: No such file or directory
,V/BtOppService( 6249): Starting RfcommListener
D/BluetoothAdapterProperties( 6249): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6249): getDeviceMode  deviceMode 0
D/BluetoothOppPreference( 6249): Dumping Names:  
D/BluetoothOppPreference( 6249): {}
D/BluetoothOppPreference( 6249): Dumping Channels:  
D/BluetoothOppPreference( 6249): {}
V/BtOppService( 6249): onStartCommand
V/QRemote ( 6425): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,V/BtOppService( 6249): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
E/QRemote ( 6425): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/BluetoothFtpReceiver( 6249): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
V/BluetoothFtpReceiver( 6249): BluetoothFtpReceiver Start Service
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
V/BluetoothOppNotification( 6249): new notify threadi!
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@34231a96 on behalf of 
V/BluetoothOppNotification( 6249): send delay message
V/BluetoothOppNotification( 6249): update too frequent, put in queue
V/BtOppService( 6249): ContentObserver received notification
V/BtOppService( 6249): ContentObserver received notification
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6249): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BtOppService( 6249): start RfcommListener
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@b103617 on behalf of 
V/BluetoothOppNotification( 6249): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@132c3a04 on behalf of 
V/BtOppService( 6249): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@69a1bed on behalf of 
V/BtOppService( 6249): RfcommListener started
V/BtOppRfcommListener( 6249): Starting RFCOMM listener....
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6249): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6249): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6249): Started RFCOMM listener....
I/BtOppRfcommListener( 6249): Accept thread started.
V/BtOppRfcommListener( 6249): Accepting connection...
V/BluetoothOppNotification( 6249): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6249): outbound notification was removed.
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@a6e4a22 on behalf of 
V/BluetoothOppNotification( 6249): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6249): inbound notification was removed.
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@3d81cb3 on behalf of 
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
,V/BluetoothFtpService( 6249): Ftp Service onCreate
I/BluetoothFtpService( 6249): Ftp Service onCreate
V/BluetoothFtpService( 6249): Ftp Service onStartCommand
V/BluetoothFtpService( 6249): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6249): Starting Listening on sockets
V/BluetoothSapReceiver( 6249): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6249): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6249): SapReceiver onReceive 
V/BluetoothSapReceiver( 6249): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6249):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6249): Calling SAP service start service with action = null
V/BluetoothFtpService( 6249): Handler(): got msg=1
V/BluetoothFtpService( 6249): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6249): Ftp Service initSocket
D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6249): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6249): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothFtpService( 6249): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6249): Run Accept thread
,D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
,V/BluetoothSapService( 6249): Sap Service onCreate
V/BluetoothSapService( 6249): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6249): state: 12
V/BluetoothSapService( 6249): Starting SAP server process
V/BluetoothSapService( 6249): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6249): Sap Service initRfcommSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6249): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6249): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6249): Succeed to create listening socket 
V/BluetoothSapService( 6249): Accepting socket connection...
W/sapd    ( 6519): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6519): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6519): Event pipe created
V/BT_SAP  ( 6519): create_server_socket qcom.sap.server
V/BT_SAP  ( 6519): created socket fd 6
,I/dhcpcd  ( 6459): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,I/dhcpcd  ( 6459): wlan0: leased 192.168.1.125 for 86400 seconds
,D/dhcpcd  ( 6459): wlan0: adding IP address 192.168.1.125/24
,D/dhcpcd  ( 6459): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 6459): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6459): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 6459): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6459): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 6459): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/DhcpStateMachine( 1030): RunningState
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1972): handleWifiStateChangedEvent: 1
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 3
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&,VZW800 Specifier: <-1>]
D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 28
,E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 3
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  305): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
,W/dsqn    ( 6559): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6559): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 6559): DSQN ssw
,V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/libc-netbsd(  305): res_queryN name = europe.pool.ntp.org succeed
,D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6344): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6344): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  305): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6425): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6425): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6425): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6344): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6344): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDataListener(  305): argv[0]=dsqncommand
D/LGDataListener(  305): argv[1]=wlan0
D/LGDataListener(  305): argv[2]=1
D/LGDataListener(  305): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
V/WiFiOffLoadBroadcast( 6288): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DSQN    ( 1030): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 6288): MCCMNC not supported: null
D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1030): NTP server returned: 1449746476814 (Thu Dec 10 12:21:16 GMT+01:00 2015) reference: 314040 certainty: 30 system time offset: -221
D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6425): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/LocSvc_java( 1030): reportXtraServer 
D/LocSvc_java( 1030):  server1=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1030):  server2=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1030):  server3=
I/QRemote ( 6425): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,D/LocSvc_java( 1030): xtraDownloadRequest
D/LocSvc_java( 1030): Sending msg: 6 arg1:0 arg2:1
I/QRemote ( 6425): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:21:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746477042], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746477025]}
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
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1862): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = xtra3.gpsOneXTRA.net, class = 1, type = 1
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothOppNotification( 6249): new notify threadi!
V/BluetoothOppNotification( 6249): send delay message
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@1dcec59c on behalf of 
,V/BluetoothOppNotification( 6249): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@23e7dba5 on behalf of 
V/BluetoothOppNotification( 6249): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6249): outbound notification was removed.
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@3542fb7a on behalf of 
,V/BluetoothOppNotification( 6249): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6249): inbound notification was removed.
V/BluetoothOppProvider( 6249): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6249): created cursor android.database.sqlite.SQLiteCursor@10806f2b on behalf of 
D/libc-netbsd(  305): res_queryN name = xtra3.gpsOneXTRA.net succeed
,D/LocSvc_java( 1030): calling native_inject_xtra_data
,D/LocSvc_java( 1030): Sending msg: 11 arg1:0 arg2:1
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1952468259] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-1952468253] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5207): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5275): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  305): res_queryN name = 2.android.pool.ntp.org succeed
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6599 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/art     (  338): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 18.126ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 15.733ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 12.775ms
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6618 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6599): onCreate
W/AppUp4:DB( 6599):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6599):  setFingerPrint start
I/AppUp4:DB( 6599):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6599):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6599):  SDK version = 21
I/AppUp4:DB( 6599):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6634 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6599): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6599): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6599): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6599): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6599): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6599): onReceive
I/GoogleURLConnFactory( 2135): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/AlarmManagerService( 1030): Setting time of day to sec=1449746479
W/AlarmManagerService( 1030): Unable to set rtc to 1449746479: Invalid argument
I/[SystemUI]Clock( 1465): onReceive = android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/LIA_Informant_Tips_DateChangeManager( 2679): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2679): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-10 12:21:19...... Request
I/LIA_Informant_Tips_LogTracer( 2679): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 109, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2679): DateInfo : SmartTips Total Working Day Count = 109
D/LIA_Informant_Tips_DateChangeManager( 2679): DateInfo : UserGuide Working Duration Count = 8
I/SecureClockService( 1972): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 2679): DateInfo : Last Date Check Time = 2015-12-10 12:21:19
I/art     ( 1030): Explicit concurrent mark sweep GC freed 77322(3MB) AllocSpace objects, 4(105KB) LOS objects, 33% free, 44MB/66MB, paused 4.230ms total 181.255ms
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2089): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/[LGHome]LGCalendarIcon( 2089): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/LgeClockWidgetControlView( 1465): time changed, timezoneChanged : false
D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/LgDataFeature( 6599): LgDataFeature() Constructor: none
D/LgDataFeature( 6599): LgDataFeature() Constructor Done, null
D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,I/ThermalEngine(  321): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3132): Thermal-Lib-Client: Client request sent
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
D/AppUp4:CustFacade( 6599): Context : android.app.ReceiverRestrictedContext@25fadbae
D/AppUp4:CustFacade( 6599): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6599): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6599): begin check event
I/AppUp4:CustModeStarterReceiver( 6599): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6599): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,I/AppConfig( 6634): Total System Memory = 2995761152
D/SystemHelper( 6634): region [EU], country [EU], operator [OPEN], sub-operator []
,D/AppUp4:CustModeStarterReceiver( 6599): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6599): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6599): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 5598:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5598/cgroup.procs: No such file or directory
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6660 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6618): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3346): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3990): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3346): DownloadService onCreate
,W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/DownloadManager( 3346): in removeSpuriousFiles
V/DownloadManager( 3346): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3346): created cursor android.database.sqlite.SQLiteCursor@7c396c5 on behalf of 3346
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3346): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3346): in trimDatabase
V/DownloadManager( 3346): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3346): created cursor android.database.sqlite.SQLiteCursor@795681a on behalf of 3346
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6687 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3346): DownloadService onStartCommand
V/DownloadManager( 3346): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3346): created cursor android.database.sqlite.SQLiteCursor@25376d28 on behalf of 3346
E/LGDMClient( 3990): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3346): processing inserted download 1
V/DownloadManager( 3346): processing inserted download 4
V/DownloadManager( 3346): processing inserted download 7
V/DownloadManager( 3346): processing inserted download 8
V/DownloadManager( 3346): processing inserted download 9
V/DownloadManager( 3346): processing inserted download 10
V/DownloadManager( 3346): processing inserted download 16
V/DownloadManager( 3346): processing inserted download 17
V/DownloadManager( 3346): processing inserted download 18
V/DownloadManager( 3346): processing inserted download 21
D/LGDMClient( 3990): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3990): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,E/GpsLocationProvider( 1030): No APN found to select.
V/DownloadManager( 3346): DownloadService onDestroy
W/GAV2    ( 6618): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ResourcesManager( 6687): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6687): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/BooksApp( 6618): Created application version: 3.2.35 (30235)
W/ResourcesManager( 6687): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/DriveInitializer( 2350): Background init thread started
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2350): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PerfProfileCollectorService( 2350): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 2350): removeStateFiles() called
,D/PerfProfileCollectorService( 2350): User is not opt-in to Usage & Diagnostics.
E/Ads     ( 2350): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,W/DriveInitializer( 2350): Background init thread ended
I/art     ( 2135): Explicit concurrent mark sweep GC freed 21176(1216KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 479us total 25.601ms
,I/LGEmail ( 6687): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6687): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=29.2, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:2679] from screen [on:0 period:-1952465564] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=29.2, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1952465562] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/Netstats( 2350): User is not opted-in to Usage & Diagnostics.
,E/Auth.Api.Credentials( 2350): [CredentialSyncAdapter] Unknown sync event.
I/BooksSync( 6618): Starting books sync
D/DelayedSyncController( 6660): Delaying sync.
,I/ActivityManager( 1030): Killing 5930:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/ResourceType( 6687): No package identifier when getting value for resource number 0x00000000
W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5930/cgroup.procs: No such file or directory
,D/serial_port( 5911): close(fd = 24)
I/UEI.SmartControl( 5911): Serial port is closed.
,I/ActivityManager( 1030): Killing 5627:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/LgDataFeature( 6687): LgDataFeature() Constructor: none
D/LgDataFeature( 6687): LgDataFeature() Constructor Done, null
,I/jxcore-log( 6178): Test app app.js loaded
I/jxcore-log( 6178): 
,I/Choreographer( 6178): Skipped 458 frames!  The application may be doing too much work on its main thread.
I/chromium( 6178): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5627/cgroup.procs: No such file or directory
I/chromium( 6178): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/eas_req ( 6687): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6618): started syncMyEbooks
,I/LgeMiscReceiver( 3299): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3299): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3299): networkInfo.isConnected() = true
D/PhoneState( 3299): setPdpRejectCasuse : false
I/HubEmail( 6687): JNI_OnLoad()
I/HubEmail( 6687): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6687): registerNatives()
I/HubEmail( 6687): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6687): registerNativeMethods()
I/HubEmail( 6687): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6687): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.google.com, class = 1, type = 1
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6758 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/Settings( 6687): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6687): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  305): res_queryN name = www.google.com succeed
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  305): res_queryN name = clients3.google.com succeed
D/UEI.SmartControl( 5911): Internal timer expired: 4
D/UEI.SmartControl( 5911): unbind internal service
,D/DrmBroadcastReceiver( 6758): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6758): 1  network is available. Sync DRM Time with NTP
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DrmService( 6758): Service onCreate
D/DrmService( 6758): Received new request = 2
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
I/DrmSntpClient( 6758): Start Sync process
D/DrmSntpClient( 6758): Server : 0
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6782 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  305): res_queryN name = static-avc.lglime.com succeed
D/libc-netbsd(  305): res_queryN name = pool.ntp.org succeed
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDrmClient( 6758): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  316): eDRM_SetDRMTime +++
I/LGDRM   (  316): [DRM] SET TIME : YR=2015, MON=12, DAY=10
I/LGDRM   (  316): [DRM] SET TIME : HR=11, MIN=21, SEC=20
,V/ILGDrmService(  316): eDRM_SetDRMTime ---
I/DrmSntpClient( 6758): Synched
D/DrmService( 6758): Completed !! request = 2
D/DrmService( 6758): Request count = 0
V/DrmService( 6758): Service onDestroy
I/ActivityManager( 1030): Killing 5991:com.lge.eula/1000 (adj 15): empty #17
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
I/art     ( 6782): Almond Protected OAT
,I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5991/cgroup.procs: No such file or directory
,E/BooksAccountManager( 6618): Authentication error
E/BooksAccountManager( 6618): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6618): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6618): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6618): null auth token
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com, class = 1, type = 1
I/art     ( 1030): Explicit concurrent mark sweep GC freed 28470(1297KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.074ms total 73.712ms
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
,D/WeatherApplication( 6782): removeAccount
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/WeatherApplication( 6782): Account.length = 0
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/WeatherApplication( 6782): OPERATOR:OPEN
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/WeatherAncestor( 6782): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:21:20
D/Weather.Utils( 6782): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6782): 2 : All the weather widget is gone.
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/UpdateThreadPoolManager( 6782): 2 : This is isUpdating : false
D/WeatherAncestor( 6782): connectivity changed - connection : true
,D/WeatherService( 6782): 2 : isServiceAlived():false forecastCache:null
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ForecastDataCache( 6782): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6782): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6782): 2 : Cache is not up-to-date, count: 0
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  305): res_queryN name = www.googleapis.com succeed
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/ContactsSyncAdapter( 2135): innerSync failed
D/ContactsSyncAdapter( 2135): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2135): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2135): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2135): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/Weather_cast( 6782): 2 : isUpdateNeedForAlarm : no city return false
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/WeatherAncestor( 6782): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:21:21
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|1,0005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6802 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6036:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_6036/cgroup.procs: No such file or directory
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26336, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 351229, reason: 10019
,D/DelayedSyncController( 6660): Delaying sync.
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ApiaryClient( 6618): Error response from books API: {
W/ApiaryClient( 6618):  "error": {
W/ApiaryClient( 6618):   "errors": [
W/ApiaryClient( 6618):    {
W/ApiaryClient( 6618):     "domain": "global",
W/ApiaryClient( 6618):     "reason": "required",
W/ApiaryClient( 6618):     "message": "Login Required",
W/ApiaryClient( 6618):     "locationType": "header",
W/ApiaryClient( 6618):     "location": "Authorization"
W/ApiaryClient( 6618):    }
W/ApiaryClient( 6618):   ],
W/ApiaryClient( 6618):   "code": 401,
W/ApiaryClient( 6618):   "message": "Login Required"
W/ApiaryClient( 6618):  }
W/ApiaryClient( 6618): }
W/ApiaryClient( 6618): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4652666995791747275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6618): Headers:
W/ApiaryClient( 6618): accept-encoding: [gzip]
W/ApiaryClient( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6618): gdata-version: 2
,I/WebViewFactory( 6802): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6846 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 6802): Loading: webviewchromium
I/LibraryLoader( 6802): Time to load native libraries: 2 ms (timestamps 8628-8630)
,I/LibraryLoader( 6802): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6802): Binding Chromium to main looper Looper (main, tid 1) {97f9ad1}
I/LibraryLoader( 6802): Expected native library version number "",actual native library version number ""
I/chromium( 6802): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6802): Initializing chromium process, renderers=0
W/art     ( 6802): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6802): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6802): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6802): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/ResourcesManager( 6846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/AudioPolicyService(  310): registerClient() client 0xb558a6e0, uid 10093
W/AudioManagerAndroid( 6802): Requires BLUETOOTH permission
I/Adreno-EGL( 6802): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6802): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6802): Build Date: 12/12/14 금
I/Adreno-EGL( 6802): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6802): Remote Branch: 
I/Adreno-EGL( 6802): Local Patches: 
I/Adreno-EGL( 6802): Reconstruct Branch: 
,I/NSApplication( 6802): Starting up...
,I/ActivityManager( 1030): Killing 5381:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_5381/cgroup.procs: No such file or directory
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/GLSActivity( 2135): [ac] getting account id
I/GLSUser ( 2135): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
,I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/iu.SyncManager( 2350): SYNC; picasa accounts
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
I/FormManager( 6319): Doesn't have value mapped with the "relatedAppInfo"
D/NetworkLogImpl( 2350): Loaded NetworkSpeedPredictor
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/SmartKeyboard is updated. So the next step schedule will be reserved.
D/libc-netbsd(  305): res_queryN name = mtalk.google.com succeed
I/iu.Environment( 2350): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2350): num queued entries: 0
,I/iu.UploadsManager( 2350): num updated entries: 0
I/iu.SyncManager( 2350): NEXT; no task
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5207): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/QuickCircle is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/GuestMode is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/SmartBulletin is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/DualWindow is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/QuadHD is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/QuickCircleCase is updated. So the next step schedule will be reserved.
I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6903 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/FormManager( 6319): MyGuide/MyGuideBoard/Initial/guestmode is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/Initial/oiscamera is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/Initial/textlink is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/QuickCircleApp is updated. So the next step schedule will be reserved.
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/FormManager( 6319): MyGuide/MyGuideBoard/OSUpgradeCard/OSUpgrade01 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/LGSmartWorld/Promotion1 is updated. So the next step schedule will be reserved.
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/FormManager( 6319): MyGuide/GBoard/SmartWorldCard/0 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/GBoard/SmartWorldCard/1 is updated. So the next step schedule will be reserved.
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
V/FormManager( 6319): MyGuide/GBoard/SmartWorldCard/2 is updated. So the next step schedule will be reserved.
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
V/FormManager( 6319): MyGuide/GBoard/SmartWorldEventCard is updated. So the next step schedule will be reserved.
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
V/FormManager( 6319): MyGuide/MyGuideBoard/OSUpgradeCard/OSUpgrade02 is updated. So the next step schedule will be reserved.
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 6319): smartworldcard_12th_001 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): smartworldcard_1th_001 is updated. So the next step schedule will be reserved.
D/ALBootInit( 6903): ====action==>android.intent.action.TIME_SET
V/FormManager( 6319): SmartWorldcard0122 is updated. So the next step schedule will be reserved.
,D/ALBootInit( 6903): Alarm ALBootInit: TIME_SET
V/FormManager( 6319): SmartWorldcard0205 is updated. So the next step schedule will be reserved.
D/Alarms  ( 6903): [setNextAlert] start
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/CurvedDesign is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/FrontCamera is updated. So the next step schedule will be reserved.
D/Alarms  ( 6903): [setNextAlert] (1)
D/Alarms  ( 6903):  minTime  = 0
D/Alarms  ( 6903):  -- OK multi -- 0
,E/jeny.kim( 6903): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6903): [setNextAlert]setNextAlert temp_AlarmLinkText + 
V/FormManager( 6319): SmartWorldcard0224 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): SmartWorldcard0304 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/DualWindowKR is updated. So the next step schedule will be reserved.
,I/CommonUtil( 6903): BUILD Country: EU
D/Alarms  ( 6903): broadcastToWidgetProvider : false
V/FormManager( 6319): SmartWorldcard0319 is updated. So the next step schedule will be reserved.
D/Alarms  ( 6903): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/FormManager( 6319): SmartWorldcard0416 is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/UserGuideFeatureList is updated. So the next step schedule will be reserved.
V/SettingsProvider( 1030): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6903): onReceive: android.intent.action.TIME_SET
,V/FormManager( 6319): SmartWorldcard0430 is updated. So the next step schedule will be reserved.
V/DigitalAppWidgetProvider( 6903): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3152bd4f
V/DigitalAppWidgetProvider( 6903): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3152bd4f
D/QuickCoverProvider( 6903): onReceiver
V/FormManager( 6319): MyGuide/MyGuideBoard/Initial/02 is updated. So the next step schedule will be reserved.
I/indal   ( 1412): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1412): SmartCoverWidgetContext createApplicationContext
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/QuickShot is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/SelfieLight is updated. So the next step schedule will be reserved.
D/WeatherAncestor( 6782): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:21:21
D/Weather.Utils( 6782): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6782): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6782): 2 : This is isUpdating : false
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/AudioShare is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/EventPocket is updated. So the next step schedule will be reserved.
D/GCM     ( 2135): Connected
,I/VacuumService( 2135): Vacuum at: now=1449746482007 tag=VacuumService
D/WeatherService( 6782): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3002dcdc
D/ForecastDataCache( 6782): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6782): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6782): 2 : Cache is up-to-date, count: 0
I/GoogleURLConnFactory( 2135): Using platform SSLCertificateSocketFactory
D/Weather_cast( 6782): 2 : set auto-update time : 12/10 15:21
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/smartpowersaver is updated. So the next step schedule will be reserved.
,D/WeatherAncestor( 6782): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:21:22
V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/gallery is updated. So the next step schedule will be reserved.
D/GCM     ( 2135): Message class com.google.f.a.a.p
V/FormManager( 6319): SmartWorldcard0611_G3 is updated. So the next step schedule will be reserved.
,W/Uploader( 2135): No account for auth token provided
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/lgbridge is updated. So the next step schedule will be reserved.
V/FormManager( 6319): SmartWorldcard0611_g4 is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): MyGuide/MyGuideBoard/PromotionCard/cameratip is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/Initial/01 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): MyGuide/MyGuideBoard/Initial/03 is updated. So the next step schedule will be reserved.
,I/ActivityManager( 1030): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6937 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/FormManager( 6319): SmartWorldcard0625 is updated. So the next step schedule will be reserved.
I/ActivityManager( 1030): Killing 4938:com.android.vending/u0a44 (adj 15): empty #17
V/FormManager( 6319): SmartWorldcard0626_G4 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): smartworldcard0702_g3 is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): SmartWorldcard0706_G4 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): LGSmartWorldcard0724 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): SmartWorldcard0813 is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): SmartWorldcard150924 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): Smartcard151015 is updated. So the next step schedule will be reserved.
V/FormManager( 6319): smartWorldtipscard_20151210_G4 is updated. So the next step schedule will be reserved.
,V/FormManager( 6319): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_4938/cgroup.procs: No such file or directory
D/TimeService( 6937): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746482212
D/        ( 6937): TimeServiceNative: User Time to be set is 1449746482212
D/QC-time-services( 6937): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6937): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 6937): Lib:time_genoff_operation: pargs->ts_val = 1449746482212
D/QC-time-services( 6937): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  357): Daemon: Connection accepted:time_genoff
D/QC-time-services(  357): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449746482212
D/QC-time-services(  357): Daemon:genoff_opr: Base = 2, val = 1449746482212, operation = 0
D/QC-time-services(  357): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/19/70 4:34:5
D/QC-time-services(  357): Daemon:Value read from RTC seconds = 9347645000
D/QC-time-services(  357): Daemon:new time 1449746482212 
D/QC-time-services(  357): Daemon: delta 1440398837212 genoff 1440398837212 
D/QC-time-services(  357): Daemon:genoff_persistent_update: Writing genoff = 1440398837212 to memory
D/QC-time-services(  357): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  357): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  357): Updating the TOD offset
D/QC-time-services(  357): Daemon:genoff_persistent_update: Writing genoff = 1440398837212 to memory
D/QC-time-services(  357): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  357): Daemon:time_persistent_memory_opr:Genoff write operation 
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/QC-time-services(  357): Daemon:Update to modem bit set
D/QC-time-services(  357): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  357): Daemon: Base = 2, Value being sent to MODEM = 1124434037212
E/QC-time-services( 6937): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  357): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  357): Daemon: Time-services: Waiting to acceptconnection
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/SmartKeyboard)
,D/libc-netbsd(  305): res_queryN name = play.googleapis.com succeed
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/QuickCircle)
I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6957 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1030): Killing 6013:com.lge.bnr/1000 (adj 15): empty #17
I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 32.818ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 19.569ms
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/GuestMode)
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 363us total 17.459ms
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/SmartBulletin)
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6013/cgroup.procs: No such file or directory
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/DualWindow)
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6618): Authentication error
E/BooksAccountManager( 6618): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6618): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6618): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6618): null auth token
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/QuadHD)
,W/Uploader( 2135): No account for auth token provided
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/QuickCircleCase)
,W/ApiaryClient( 6618): Error response from books API: {
W/ApiaryClient( 6618):  "error": {
W/ApiaryClient( 6618):   "errors": [
W/ApiaryClient( 6618):    {
W/ApiaryClient( 6618):     "domain": "global",
W/ApiaryClient( 6618):     "reason": "required",
W/ApiaryClient( 6618):     "message": "Login Required",
W/ApiaryClient( 6618):     "locationType": "header",
W/ApiaryClient( 6618):     "location": "Authorization"
W/ApiaryClient( 6618):    }
W/ApiaryClient( 6618):   ],
W/ApiaryClient( 6618):   "code": 401,
W/ApiaryClient( 6618):   "message": "Login Required"
W/ApiaryClient( 6618):  }
W/ApiaryClient( 6618): }
,W/ApiaryClient( 6618): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4652666995791747275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6618): Headers:
W/ApiaryClient( 6618): accept-encoding: [gzip]
W/ApiaryClient( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6618): gdata-version: 2
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/Initial/guestmode)
W/Uploader( 2135): No account for auth token provided
I/art     ( 1030): Explicit concurrent mark sweep GC freed 26939(1168KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.932ms total 154.239ms
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/Initial/oiscamera)
,W/ResourcesManager( 6957): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/Initial/textlink)
,W/Uploader( 2135):  no longer exists, so no auth token.
D/CalendarApplication( 6957): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6957): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6957): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@242d6b62, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2ddac4f3, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@351a15b0, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@4d70c29, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@25fadbae, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3152bd4f, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3002dcdc, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3eab41e5, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@391d04ba, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@aa7df6b, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@274eeac8, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@26d31761, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@f06b286, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@9e30747, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@9cbeb74, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1d48c89d, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2b8b7112, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@cbed0e3, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3764ae0, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@d6e5199, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@a2b8c5e, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@803983f, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1a5350c, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc96e55, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@c20106a, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@aa3795b, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@df695f8, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@97f9ad1, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3b26c936, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@16965037, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2bfb19a4, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3492130d, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2d0e42c2, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2b75b8d3, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@25a22c10, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@13d9d309, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1401c90e, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1ed90f2f, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3265f93c, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@7c396c5, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@795681a, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1e716f4b, lg_pr
D/GeneralP,referenceUtils( 6957): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/QuickCircleApp)
,D/Config  ( 6957): [init]
,I/Config  ( 6957): LGCalendar ver.4.40.16
I/Config  ( 6957): start check model
I/Config  ( 6957): start check native_ca
I/Config  ( 6957): Config Operator=OPEN, Country=EU
D/Config  ( 6957): [setDefaultValuesToPref]
D/Config  ( 6957): [parseProfiles]
,D/ProfilesParser( 6957): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6957): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6957): [updateProfiletoCountryInfo]
D/GeneralPreference( 6957): [checkAndMigrateOldPreference]
W/Uploader( 2135): No account for auth token provided
E/AgendaWidgetManager( 6957): [updateWidgets] 
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/OSUpgradeCard/OSUpgrade01)
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/LGSmartWorld/Promotion1)
,W/Uploader( 2135): No account for auth token provided
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/GBoard/SmartWorldCard/0)
,W/Uploader( 2135): No account for auth token provided
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/GBoard/SmartWorldCard/1)
,I/InitNotificationRingtoneService( 6957): Start InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6957): [onReceive]
D/CalendarWidgetProvider( 6957): [onReceive]
D/CalendarWidgetProvider( 6957): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,W/HolidayIntentService( 6957): onHandleIntent
D/HolidayDataLoader( 6957): readJsonAsset : holiday.json
D/CalendarTypeController( 6957): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6957): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/WeekWidgetProvider( 6957): [onReceive]
D/CalendarWidgetProvider( 6957): [onReceive]
D/CalendarWidgetProvider( 6957): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6957): [onUpdateAndInitCalendarTime]
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/GBoard/SmartWorldCard/2)
,I/AlertUtils( 6957): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/GBoard/SmartWorldEventCard)
,I/DigitalAppWidgetProvider( 6903): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6782): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:21:22
D/Weather.Utils( 6782): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6782): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6782): 2 : This is isUpdating : false
I/art     ( 3346): Explicit concurrent mark sweep GC freed 5381(328KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 404us total 34.264ms
,I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/Weather_cast( 6782): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6782): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:21:22
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
E/HolidayIntentService( 6957): onHandleIntent:holiday data empty
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/OSUpgradeCard/OSUpgrade02)
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6980 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(smartworldcard_12th_001)
I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6957): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6957): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6957): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6957): End InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager( 1030): Killing 6374:com.lge.lifetracker/u0a37 (adj 15): empty #17
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(smartworldcard_1th_001)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0122)
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_6374/cgroup.procs: No such file or directory
W/ResourcesManager( 6980): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0205)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/CurvedDesign)
,D/LgDataFeature( 6980): LgDataFeature() Constructor: none
D/LgDataFeature( 6980): LgDataFeature() Constructor Done, null
,I/Babel   ( 6980): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6980): MmsConfig.loadMmsSettings
,I/Babel   ( 6980): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6980): MmsConfig.loadFromDatabase
,E/Babel   ( 6980): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6980): MmsConfig.loadFromResources
E/Babel   ( 6980): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6980): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6980): Unsupported mime audio/evrc
,W/AudioCapabilities( 6980): Unsupported mime audio/qcelp
W/VideoCapabilities( 6980): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6980): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6980): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6980): Unsupported mime audio/evrc
W/VideoCapabilities( 6980): Unsupported mime video/x-ms-wmv
,W/ResourcesManager( 6980): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6980): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6980): Unsupported mime video/divx
W/VideoCapabilities( 6980): Unsupported mime video/divx311
W/VideoCapabilities( 6980): Unsupported mime video/divx4
W/VideoCapabilities( 6980): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6980): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6980): Unsupported mime audio/eac3
W/AudioCapabilities( 6980): Unsupported mime audio/ac3
W/AudioCapabilities( 6980): Unsupported mime audio/g726
W/AudioCapabilities( 6980): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6980): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6980): Unsupported mime audio/adpcm
V/JNIHelp ( 6980): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/VideoCapabilities( 6980): Unsupported mime video/theora
W/VideoCapabilities( 6980): Unsupported mime video/mjpg
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=19.6, 0.0, 0.0  rx=18.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1952462547] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=19.6, 0.0, 0.0  rx=18.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952462544] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
W/System  ( 6980): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6980): Installed default security provider GmsCore_OpenSSL
E/BooksAccountManager( 6618): Authentication error
E/BooksAccountManager( 6618): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6618): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6618): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6618): null auth token
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1412): Notification difference=198
,D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6618): Error response from books API: {
W/ApiaryClient( 6618):  "error": {
W/ApiaryClient( 6618):   "errors": [
W/ApiaryClient( 6618):    {
W/ApiaryClient( 6618):     "domain": "global",
W/ApiaryClient( 6618):     "reason": "required",
W/ApiaryClient( 6618):     "message": "Login Required",
W/ApiaryClient( 6618):     "locationType": "header",
W/ApiaryClient( 6618):     "location": "Authorization"
W/ApiaryClient( 6618):    }
W/ApiaryClient( 6618):   ],
W/ApiaryClient( 6618):   "code": 401,
W/ApiaryClient( 6618):   "message": "Login Required"
W/ApiaryClient( 6618):  }
W/ApiaryClient( 6618): }
,W/ApiaryClient( 6618): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4652666995791747275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6618): Headers:
W/ApiaryClient( 6618): accept-encoding: [gzip]
W/ApiaryClient( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6618): gdata-version: 2
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6980): UserRecoverableAuthException.
E/Babel   ( 6980): cfq: BadAuthentication
E/Babel   ( 6980): 	at cfn.a(Unknown Source)
E/Babel   ( 6980): 	at f.a(PG:191)
E/Babel   ( 6980): 	at ava.a(PG:88)
E/Babel   ( 6980): 	at ava.a(PG:128)
E/Babel   ( 6980): 	at bjs.a(PG:255)
E/Babel   ( 6980): 	at bep.a(PG:602)
E/Babel   ( 6980): 	at bep.a(PG:469)
E/Babel   ( 6980): 	at bpo.run(PG:1141)
E/Babel   ( 6980): Error getting auth token
,E/Babel   ( 6980): bxl
E/Babel   ( 6980): 	at f.a(PG:201)
E/Babel   ( 6980): 	at ava.a(PG:88)
E/Babel   ( 6980): 	at ava.a(PG:128)
E/Babel   ( 6980): 	at bjs.a(PG:255)
E/Babel   ( 6980): 	at bep.a(PG:602)
E/Babel   ( 6980): 	at bep.a(PG:469)
E/Babel   ( 6980): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6980): error sending REQ[fc:8; creat:1449704504045; type:bev-1788604]; took 111 ms (error code == 100)
E/Babel   ( 6980): Account registration failedRedacted-21
E/Babel   ( 6980): bph: null -- null
E/Babel   ( 6980): 	at ava.a(PG:120)
E/Babel   ( 6980): 	at ava.a(PG:128)
E/Babel   ( 6980): 	at bjs.a(PG:255)
E/Babel   ( 6980): 	at bep.a(PG:602)
E/Babel   ( 6980): 	at bep.a(PG:469)
E/Babel   ( 6980): 	at bpo.run(PG:1141)
I/Babel   ( 6980): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6980): Account sign in complete with state 106account: Redacted-21
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/FrontCamera)
,I/art     ( 6980): Note: end time exceeds epoch: 
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 2135): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/Babel   ( 6980): Unexpected exception while authenticating.
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
E/Babel   ( 6980): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6980): 	at cfn.b(Unknown Source)
E/Babel   ( 6980): 	at cfn.a(Unknown Source)
E/Babel   ( 6980): 	at f.a(PG:188)
E/Babel   ( 6980): 	at ava.b(PG:143)
E/Babel   ( 6980): 	at bnr.run(PG:5415)
E/Babel   ( 6980): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6980): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6980): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksSync( 6618): Soft error: 
E/BooksSync( 6618): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4652666995791747275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6618): Headers:
E/BooksSync( 6618): accept-encoding: [gzip]
E/BooksSync( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6618): gdata-version: 2
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6618): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6618): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6618): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6618): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6618): {
E/BooksSync( 6618):  "error": {
E/BooksSync( 6618):   "errors": [
E/BooksSync( 6618):    {
E/BooksSync( 6618):     "domain": "global",
E/BooksSync( 6618):     "reason": "required",
E/BooksSync( 6618):     "message": "Login Required",
E/BooksSync( 6618):     "locationType": "header",
E/BooksSync( 6618):     "location": "Authorization"
E/BooksSync( 6618):    }
E/BooksSync( 6618):   ],
E/BooksSync( 6618):   "code": 401,
E/BooksSync( 6618):   "message": "Login Required"
E/BooksSync( 6618):  }
E/BooksSync( 6618): }
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6618): 	... 8 more
,E/BooksSync( 6618): Sync error
E/BooksSync( 6618): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4652666995791747275&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6618): Headers:
E/BooksSync( 6618): accept-encoding: [gzip]
E/BooksSync( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6618): gdata-version: 2
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6618): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6618): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6618): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6618): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6618): {
E/BooksSync( 6618):  "error": {
E/BooksSync( 6618):   "errors": [
E/BooksSync( 6618):    {
E/BooksSync( 6618):     "domain": "global",
E/BooksSync( 6618):     "reason": "required",
E/BooksSync( 6618):     "message": "Login Required",
E/BooksSync( 6618):     "locationType": "header",
E/BooksSync( 6618):     "location": "Authorization"
E/BooksSync( 6618):    }
E/BooksSync( 6618):   ],
E/BooksSync( 6618):   "code": 401,
E/BooksSync( 6618):   "message": "Login Required"
E/BooksSync( 6618):  }
E/BooksSync( 6618): }
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6618): 	... 8 more
I/BooksSync( 6618): Finished books sync
I/ActivityManager( 1030): Killing 6442:com.lge.settings.easy/1000 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26321, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6442/cgroup.procs: No such file or directory
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0224)
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 50304(2MB) AllocSpace objects, 20(2MB) LOS objects, 50% free, 30MB/62MB, paused 1.337ms total 118.956ms
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2135): innerSync failed
D/ContactsSyncAdapter( 2135): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2135): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2135): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2135): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0304)
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 351229, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ThermalEngine(  321): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3132): Thermal-Lib-Client: Client request sent
,I/GAV2    ( 6618): Thread[GAThread,5,main]: No campaign data found.
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/DualWindowKR)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0319)
,I/GAV4    ( 6802): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=64.3, 0.0, 0.0  rx=59.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952459527] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=64.3, 0.0, 0.0  rx=59.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1952459513] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/ActivityManager( 1030): Killing 6344:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6344/cgroup.procs: No such file or directory
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0416)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/UserGuideFeatureList)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0430)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/Initial/02)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/QuickShot)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/SelfieLight)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/AudioShare)
,I/ActivityManager( 1030): Killing 5911:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6425): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6425): android.os.DeadObjectException
,W/System.err( 6425): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6425): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6425): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6425): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6425): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6425): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6425): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6425): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6425): android.os.DeadObjectException
W/System.err( 6425): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6425): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6425): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6425): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6425): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6425): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6425): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6425): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6425): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/EventPocket)
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5911/cgroup.procs: No such file or directory
W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6425): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6425): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7066 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6425): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 7066): Quickset Services start...
,I/UEI.SmartControl( 7066): Manufacture = LGE
D/UEI.SmartControl( 7066): Id = LGNevo
D/UEI.SmartControl( 7066): File observer start...
E/UEI.SmartControl( 7066): IR Port is disabled: false
D/UEI.SmartControl( 7066): Starting file observer...
D/UEI.SmartControl( 7066): Extracting JNI libs...
D/UEI.SmartControl( 7066): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7066): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7066): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7066): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7066): --- Selecting new region: 6
,I/UEI.SmartControl( 7066): Model = LG-D855
D/UEI.SmartControl( 7066): QS Service created
I/UEI.SmartControl( 7066): Service initServices...
,D/UEI.SmartControl( 7066): QS start get config
D/UEI.SmartControl( 7066): Loading JNI Libs...
,I/UEI.SmartControl( 7066): Supports setup maps: true
,D/UEI.SmartControl( 7066): QS start statue = true Error code = 0
I/UEI.SmartControl( 7066): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7066): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7066): ### init IR Blaster...
D/serial_port( 7066): Configuring serial port
E/UEI.SmartControl( 7066): UEIBLaster setting for 616
I/UEI.SmartControl( 7066): Setting serial record hearder size = 2
,I/UEI.SmartControl( 7066): configuring settings for MAXQ616
,I/UEI.SmartControl( 7066): Get version...
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=38.7, 0.0, 0.0  rx=37.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952456493] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=38.7, 0.0, 0.0  rx=37.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1952456492] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 7066): serial port data available: 21
,D/UEI.SmartControl( 7066): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7066): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7066): QS saving settings...
D/UEI.SmartControl( 7066): IR Blaster version: 25672567
,D/UEI.SmartControl( 7066): serial port data available: 4
,I/UEI.SmartControl( 7066): Device manager: loading config....
,W/ContextImpl( 7066): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 7066): ----------- loading internal config...
,E/UEI.SmartControl( 7066): Services init done
,D/UEI.SmartControl( 7066): QS Service init finished
D/UEI.SmartControl( 7066): QS Service version name: 2.1.91
,D/UEI.SmartControl( 7066): QS Service version code: 201091
D/UEI.SmartControl( 7066): Service requested: Control
,E/UEI.SmartControl( 7066): Loading SETTINGS...
D/UEI.SmartControl( 7066): Request IControl service: devices are loaded...
I/ActivityManager( 1030): Killing 6288:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 6425): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7066): ------ IControl API: 11
I/UEI.SmartControl( 7066): Registering callback...
,I/UEI.SmartControl( 7066): ------ IControl API: 19
I/UEI.SmartControl( 7066): Registering Services Ready callback...
D/UEI.SmartControl( 7066): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7066): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7066): -----service ready thread exits
,I/QRemote ( 6425): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/WifiService( 1030): Client connection lost with reason: 4
D/QRemote ( 6425): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6425): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6425): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6425): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7066): ------ IControl API: 8
D/QRemote ( 6425): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6425): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6425): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6425): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6425): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6425): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/smartpowersaver)
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6288/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7066): Internal service binding...
D/QRemote ( 6425): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/gallery)
,V/QRemote ( 6425): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6425): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6425): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449746489811]
D/QRemote ( 6425): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6425): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6425): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0611_G3)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/lgbridge)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0611_g4)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/PromotionCard/cameratip)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/Initial/01)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(MyGuide/MyGuideBoard/Initial/03)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0625)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0626_G4)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(smartworldcard0702_g3)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0706_G4)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(LGSmartWorldcard0724)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard0813)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(SmartWorldcard150924)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(Smartcard151015)
,V/FormManager( 6319): Succeeded to check a form history. But there is no updated form.(smartWorldtipscard_20151210_G4)
,I/ActivityManager( 1030): Killing 6599:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6599/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=27.8, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1952453476] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=27.8, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1952453463] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 330512141857; DSPS: 10971422; Offset : -4324132756
,D/UEI.SmartControl( 7066): Internal timer expired: 1
,D/UEI.SmartControl( 7066): unbind internal service
D/serial_port( 7066): close(fd = 25)
I/UEI.SmartControl( 7066): Serial port is closed.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=27.9, 0.0, 0.0  rx=24.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952450442] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-46 f=2412 sc=60 link=72 tx=27.9, 0.0, 0.0  rx=24.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952450439] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=14.0, 0.0, 0.0  rx=12.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952447415] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=14.0, 0.0, 0.0  rx=12.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1952447402] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
D/SplitUIService( 1879): replaced split : contains_com.google.android.talk / true
,I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7115 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1465): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
W/ResourcesManager( 2089): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/administrator( 1030): Handling package changes for user 0
D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
,I/AppUp4:AppBoxCP( 7115): onCreate
,W/AppUp4:DB( 7115):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7115):  setFingerPrint start
I/AppUp4:DB( 7115):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7115):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7115):  SDK version = 21
I/AppUp4:DB( 7115):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7115): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7115): onReceive
I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7115): LgDataFeature() Constructor: none
D/LgDataFeature( 7115): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7115): Context : android.app.ReceiverRestrictedContext@2ddac4f3
D/AppUp4:CustFacade( 7115): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7115): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7115): begin check event
I/AppUp4:CustModeStarterReceiver( 7115): Event For Nothing, skip.
W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7151 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6319:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_6319/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7151): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7151): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7151): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7151): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7151): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7151): BUILD Country: EU
I/SystemConfig( 7151): BUILD Operator: OPEN
,I/ActivityManager( 1030): Killing 6758:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_6758/cgroup.procs: No such file or directory
,I/SystemConfig( 7151): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7151): existFile = false
,I/SystemConfig( 7151): canReadFile = false
I/SystemConfig( 7151): systemFeature RCS result false
D/SystemConfig( 7151): refreshRcsSupport() :false
I/UpdateIcingCorporaServi( 4279): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7182 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ResourcesManager( 4279): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/LockScreenSettings( 7182): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/UpdateIcingCorporaServi( 4279): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
D/LockScreenSettings( 7182): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7182): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7182): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7182): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7182): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7182): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1030): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7211 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6802:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10093/pid_6802/cgroup.procs: No such file or directory
,D/Finsky  ( 7211): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7211): LgDataFeature() Constructor: none
D/LgDataFeature( 7211): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7211): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7251 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7211): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7211): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3346): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3346): created cursor android.database.sqlite.SQLiteCursor@1291ebe6 on behalf of 7211
D/Finsky  ( 7211): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7211): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 7211): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2350): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 7211): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1030): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7284 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6660:com.android.chrome/u0a57 (adj 15): empty #17
I/art     ( 1030): Explicit concurrent mark sweep GC freed 39553(1992KB) AllocSpace objects, 7(496KB) LOS objects, 33% free, 44MB/66MB, paused 2.570ms total 156.882ms
,W/ResourcesManager( 7251): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7251): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7251): VM with version 2.1.0 has multidex support
I/MultiDex( 7251): install
I/MultiDex( 7251): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_6660/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 2350): CP2 sync disabled
,V/JNIHelp ( 7251): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ResourcesManager( 7284): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7284): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityThread( 7251): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7251): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d60c13b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7251): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2135): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2135): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2350): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/MultiDex( 7284): VM with version 2.1.0 has multidex support
I/MultiDex( 7284): install
I/MultiDex( 7284): VM has multidex support, MultiDex support library is disabled.
,D/LocationInitializer( 2350): Restart initialization of location
V/JNIHelp ( 7284): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7284): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1030): Killing 6687:com.lge.email/u0a23 (adj 15): empty #17
,W/System  ( 7284): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d60c13b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7284): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6687/cgroup.procs: No such file or directory
,D/GCM     ( 2135): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
V/Finsky  ( 7211): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/AuthorizationBluetoothService( 2135): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2350): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7284): callingUid 10005, callindPid: 7284
D/LocationInitializer( 2350): Restart initialization of location
,E/MDM     ( 1827): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1827): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{13a03538 type 0 when 1449746501615 com.android.vending} when 1449746501615
D/Finsky  ( 7211): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/QRemote ( 6425): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6425): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1782
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1952444382] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1952444380] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7211): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7211): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7211): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7211): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7211): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7211): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1827): client connected with version: 7571000
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1952441362] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1952441348] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/ActivityManager( 1030): Killing 5207:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5207/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1952438329] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1952438325] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1af0b36b type 2 when 347515 android} when 347515
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952435301] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952435298] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 350514455495; DSPS: 11626858; Offset : -4324138585
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952432275] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1952432262] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952429242] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952429239] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{c3a0b61 type 0 when 1449746517023 com.android.vending} when 1449746517023
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 1.
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952426215] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1952426201] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3012] from screen [on:0 period:-1952423170] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952423167] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952420140] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952420137] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952417107] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1952417095] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/LEDHandler( 1972): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1972): Battery Level Remaining: 100%
D/LEDHandler( 1972): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6249): Disconnected process message: 10, size: 0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952414073] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1952414069] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 370516451060; DSPS: 12282284; Offset : -4324156841
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952411046] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1952411032] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952408011] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952408008] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{32a9d9f8 type 0 when 1449746537528 com.android.vending} when 1449746537528
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3f8f0c1a type 2 when 377553 android} when 377553
,I/BooksSync( 6618): Starting books sync
,D/BooksSync( 6618): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 22215(1240KB) AllocSpace objects, 3(432KB) LOS objects, 50% free, 30MB/62MB, paused 1.273ms total 70.187ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6618): Authentication error
E/BooksAccountManager( 6618): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6618): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6618): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6618): null auth token
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6618): Error response from books API: {
W/ApiaryClient( 6618):  "error": {
W/ApiaryClient( 6618):   "errors": [
W/ApiaryClient( 6618):    {
W/ApiaryClient( 6618):     "domain": "global",
W/ApiaryClient( 6618):     "reason": "required",
W/ApiaryClient( 6618):     "message": "Login Required",
W/ApiaryClient( 6618):     "locationType": "header",
W/ApiaryClient( 6618):     "location": "Authorization"
W/ApiaryClient( 6618):    }
W/ApiaryClient( 6618):   ],
W/ApiaryClient( 6618):   "code": 401,
W/ApiaryClient( 6618):   "message": "Login Required"
W/ApiaryClient( 6618):  }
W/ApiaryClient( 6618): }
W/ApiaryClient( 6618): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1709709590780191168&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6618): Headers:
W/ApiaryClient( 6618): accept-encoding: [gzip]
W/ApiaryClient( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6618): gdata-version: 2
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 33994(1494KB) AllocSpace objects, 1(144KB) LOS objects, 33% free, 44MB/66MB, paused 2.194ms total 146.300ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2135): innerSync failed
D/ContactsSyncAdapter( 2135): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2135): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2135): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2135): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 351229, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 443710, reason: 10019
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1952404989] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1952404988] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 6618): Authentication error
E/BooksAccountManager( 6618): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6618): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6618): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6618): null auth token
W/ApiaryClient( 6618): Error response from books API: {
W/ApiaryClient( 6618):  "error": {
W/ApiaryClient( 6618):   "errors": [
W/ApiaryClient( 6618):    {
W/ApiaryClient( 6618):     "domain": "global",
W/ApiaryClient( 6618):     "reason": "required",
W/ApiaryClient( 6618):     "message": "Login Required",
W/ApiaryClient( 6618):     "locationType": "header",
W/ApiaryClient( 6618):     "location": "Authorization"
W/ApiaryClient( 6618):    }
W/ApiaryClient( 6618):   ],
W/ApiaryClient( 6618):   "code": 401,
W/ApiaryClient( 6618):   "message": "Login Required"
W/ApiaryClient( 6618):  }
W/ApiaryClient( 6618): }
,W/ApiaryClient( 6618): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1709709590780191168&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6618): Headers:
W/ApiaryClient( 6618): accept-encoding: [gzip]
W/ApiaryClient( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6618): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6618): Authentication error
E/BooksAccountManager( 6618): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6618): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6618): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6618): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6618): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6618): Error response from books API: {
W/ApiaryClient( 6618):  "error": {
W/ApiaryClient( 6618):   "errors": [
W/ApiaryClient( 6618):    {
W/ApiaryClient( 6618):     "domain": "global",
W/ApiaryClient( 6618):     "reason": "required",
W/ApiaryClient( 6618):     "message": "Login Required",
W/ApiaryClient( 6618):     "locationType": "header",
W/ApiaryClient( 6618):     "location": "Authorization"
W/ApiaryClient( 6618):    }
W/ApiaryClient( 6618):   ],
W/ApiaryClient( 6618):   "code": 401,
W/ApiaryClient( 6618):   "message": "Login Required"
W/ApiaryClient( 6618):  }
W/ApiaryClient( 6618): }
,W/ApiaryClient( 6618): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1709709590780191168&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6618): Headers:
W/ApiaryClient( 6618): accept-encoding: [gzip]
W/ApiaryClient( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6618): gdata-version: 2
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1952401967] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952401964] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/BooksSync( 6618): Soft error: 
E/BooksSync( 6618): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1709709590780191168&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6618): Headers:
E/BooksSync( 6618): accept-encoding: [gzip]
E/BooksSync( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6618): gdata-version: 2
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6618): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6618): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6618): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6618): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6618): {
E/BooksSync( 6618):  "error": {
E/BooksSync( 6618):   "errors": [
E/BooksSync( 6618):    {
E/BooksSync( 6618):     "domain": "global",
E/BooksSync( 6618):     "reason": "required",
E/BooksSync( 6618):     "message": "Login Required",
E/BooksSync( 6618):     "locationType": "header",
E/BooksSync( 6618):     "location": "Authorization"
E/BooksSync( 6618):    }
E/BooksSync( 6618):   ],
E/BooksSync( 6618):   "code": 401,
E/BooksSync( 6618):   "message": "Login Required"
E/BooksSync( 6618):  }
E/BooksSync( 6618): }
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6618): 	... 8 more
,E/BooksSync( 6618): Sync error
E/BooksSync( 6618): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6618): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1709709590780191168&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6618): Headers:
E/BooksSync( 6618): accept-encoding: [gzip]
E/BooksSync( 6618): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6618): gdata-version: 2
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6618): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6618): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6618): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6618): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6618): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6618): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6618): {
E/BooksSync( 6618):  "error": {
E/BooksSync( 6618):   "errors": [
E/BooksSync( 6618):    {
E/BooksSync( 6618):     "domain": "global",
E/BooksSync( 6618):     "reason": "required",
E/BooksSync( 6618):     "message": "Login Required",
E/BooksSync( 6618):     "locationType": "header",
E/BooksSync( 6618):     "location": "Authorization"
E/BooksSync( 6618):    }
E/BooksSync( 6618):   ],
E/BooksSync( 6618):   "code": 401,
E/BooksSync( 6618):   "message": "Login Required"
E/BooksSync( 6618):  }
E/BooksSync( 6618): }
E/BooksSync( 6618): 
E/BooksSync( 6618): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6618): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6618): 	... 8 more
I/BooksSync( 6618): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 355092, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1952398935] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1952398924] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952395903] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952395900] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952392872] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952392869] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 390520460220; DSPS: 12937775; Offset : -4324145614
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952389847] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1952389837] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1952386824] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1952386813] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952383792] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952383789] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{c959ff7 type 0 when 1449746559241 com.android.vending} when 1449746559241
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952380761] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952380758] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1952377731] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952377728] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{c8b2401 type 2 when 407610 android} when 407610
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1952374707] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1952374704] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 410523620681; DSPS: 13593238; Offset : -4324128463
,I/jxcore-log( 6178): Toggling radios to false
I/jxcore-log( 6178): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15fcd2a6 mBinding = false
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/BluetoothManagerService( 1030): Message: 2
D/BluetoothManagerService( 1030): Sending off request.
D/LGBluetoothServiceAdapter( 6249): [BTUI] Precleanup
D/BluetoothAdapterState( 6249): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6249): Setting state to 13
I/BluetoothAdapterState( 6249): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6249): onBluetoothDisable()
I/BluetoothAdapterState( 6249): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 6249): Scan Mode:20
,D/BluetoothAdapterState( 6249): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 6249): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6249): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6249): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6249): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6249): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6249): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6249): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6249): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/btif_config_util( 6249): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothPbapService( 6249): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6249): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6249): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 6249): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x000f
,W/bt-btif ( 6249): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6249): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6249): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6249): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6249): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 12 -> 13
,I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7436 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1030): setWifiEnabled: false pid=6178, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: false pid=6178, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
I/BluetoothMapService( 6249): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 6249): STATE_TURNING_OFF
,V/BtOppService( 6249): Receiver DISABLED_ACTION 
V/BluetoothMapService( 6249): Handler(): got msg=4
D/BluetoothMapService( 6249): MAP Service closeService in
D/BluetoothMapMasInstance( 6249): MAP Service shutdown
D/LGBluetoothMapAdapter( 6249): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6249): MAP Service closeService out
I/BtOppRfcommListener( 6249): stopping Accept Thread
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
V/BtOppRfcommListener( 6249): close mBtServerSocket
V/BtOppRfcommListener( 6249): waiting for thread to terminate
I/BtOppRfcommListener( 6249): BluetoothSocket listen thread finished
D/LGBluetoothAPIService( 1972): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
V/BtOppRfcommListener( 6249): done waiting for thread to terminate
E/WifiStateMachine( 1030):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
I/jxcore-log( 6178): Radios toggled
I/jxcore-log( 6178): 
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  305): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1030): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7470 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2135): Read error: ssl=0xaf4d3400: I/O error during system call, Connection timed out
V/BtOppService( 6249): onDestroy
D/LGBluetoothOppAdapter( 6249): [BTUI] LGBluetoothOppAdapter cleanup
E/WifiStateMachine( 1030):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
V/NativeCrypto( 2135): SSL shutdown failed: ssl=0xaf4d3400: I/O error during system call, Broken pipe
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): ignoring duplicate network state non-change
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
V/WfdStateTracker( 1972): handleWifiStateChangedEvent: 0
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1030): SCAN_AVAILABLE : 1
D/RttService( 1030): SCAN_AVAILABLE : 1
D/WifiScanningService( 1030): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1030): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-22ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-22ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1030): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@194b84d4
D/LGWifiP2pService( 1030): P2pDisablingState
D/LGWifiP2pService( 1030): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): p2p socket connection lost
D/LGWifiP2pService( 1030): P2pDisabledState
E/WifiStateMachine( 1030):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6306): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1030): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1972): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1972): WifiP2pState is changed : false
D/WfdsService( 1972): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1972): Set the WFDS Monitor: false
D/WfdsMonitor( 1972): WFDS Monitor is stopped
D/WfdsService( 1972): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1972): Received on exit socket, terminate
E/CtrlSupplicant( 1972): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1972): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1972): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1972): DefaultState - msg [9441355] is not handled
W/WfdsService( 1972): DefaultState - msg [9445378] is not handled
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/CommandListener(  305): Clearing all IP addresses on wlan0
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1030): Dns fail occured do internet check.
D/DSQN    ( 1030): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1030): try Internet connection check
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
D/WifiNative-p2p0( 1030): doBoolean: TERMINATE
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1030): TERMINATE: returned true
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
,V/WfdStateTracker( 1972): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateDISCONNECTED
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/DSQN    ( 1030): ThreadInternetCheck internet check NOK 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
D/DSQN    ( 1030): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
W/ContextImpl( 1030): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (un,specified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1862): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1030): Removing idletimer
D/TelephonyNetworkFactory-1( 1862):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1030): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDataContinuityService( 1030): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7470): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7470): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/WifiServiceExtension( 1972): isInternetCheckAvailable return false
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 7470): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7470): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ActivityThread( 7436): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7436): No ProfileInfo entries
I/LG Account v2.2( 7436): isEnabled: false
I/Feature ( 7436): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7436): [Lifetracker]Country: EU
I/Feature ( 7436): [Lifetracker]Operator: OPEN
I/Feature ( 7436): [Lifetracker]Ranking support: false
I/Feature ( 7436): [Lifetracker]Comfort support: false
I/Feature ( 7436): [Lifetracker]Accessory: true
I/Feature ( 7436): [Lifetracker]Health device: true
I/Feature ( 7436): [Lifetracker]Extra Pedometer: false
I/Feature ( 7436): [Lifetracker]Blood glucose device: false
I/Feature ( 7436): [Lifetracker]Device Number: 3
,I/wpa_supplicant( 6306): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 6306): monitor socket send errors count : 1
I/wpa_supplicant( 6306): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1972-2\x00 that cannot receive messages
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
,I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7500 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6937:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.561ms
I/wpa_supplicant( 6306): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
W/wpa_supplicant( 6306): USIM:  scard_deinit function
E/WifiStateMachine( 1030):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=410951
E/WifiStateMachine( 1030):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=410951
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1030): InitialState.processMessage what=4
E/WifiStateMachine( 1030):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=410952  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1030):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=410953  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.066ms
I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 8.692ms
,D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6937/cgroup.procs: No such file or directory
E/WifiStateMachine( 1030):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_ON_QUIT 0 0
,W/ResourcesManager( 7500): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6306): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/PluginManager( 7500): init()
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1030): Disconnecting from the supplicant, no more events
,E/WifiStateMachine( 1030):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
W/ContextImpl( 7470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 6249): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6249): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6249): ***********state = 13
V/BluetoothPbapReceiver( 6249): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6249): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6249): state: 13
V/BluetoothPbapService( 6249): Pbap Service closeService in
V/BluetoothPbapService( 6249): successfully stopped pbap service
V/BluetoothPbapService( 6249): Pbap Service closeService out
,V/BluetoothPbapService( 6249): Pbap Service onDestroy
V/BluetoothPbapService( 6249): Pbap Service closeService in
V/BluetoothPbapService( 6249): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6249): [BTUI] cleanup
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c937332:true
D/BluetoothManagerService( 1030): Message: 30
,D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 7470): Adding local MAP profile
D/BluetoothMap( 7470): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 7470): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7470):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 7470): [BTUI] initUserBindClient
,W/ContextImpl( 7470): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 7470): finishStartingService: stopping service
,D/WfdsService( 1972): Supplicant Connection state is changed : false
,W/Settings( 6980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsService( 1972): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1972): Set the WFDS Monitor: false
D/WfdsMonitor( 1972): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1030): stopMonitoring
E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1972): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : this is not treated
W/Settings( 1827): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothInputDevice( 7470): Proxy object connected
D/HidProfile( 7470): Bluetooth service connected
D/BluetoothPan( 7470): BluetoothPAN Proxy object connected
D/PanProfile( 7470): Bluetooth service connected
D/BluetoothMap( 7470): Proxy object connected
D/MapProfile( 7470): Bluetooth service connected
D/BluetoothMap( 7470): getConnectedDevices()
D/BluetoothMap( 7470): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7470): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7470): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7470): onReceive
,D/LGBluetoothAuthorization( 7470): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 7470): return without doing reset settings.
,I/ActivityManager( 1030): Killing 6957:com.android.calendar/u0a13 (adj 15): empty #17
V/BluetoothOppReceiver( 6249): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6249): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 6249): [BTUI] cancel opp active transfer file notification
W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_6957/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6249): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6249): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 6249): Ftp Service onStartCommand
V/BluetoothFtpService( 6249): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6249): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6249): Shutdown
V/BluetoothFtpService( 6249): successfully stopped ftp service
V/BluetoothSapReceiver( 6249): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6249): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6249): SapReceiver onReceive 
V/BluetoothSapReceiver( 6249): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6249):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6249): Calling SAP service start service with action = null
V/BluetoothFtpService( 6249): Ftp Service onDestroy
V/BluetoothFtpService( 6249): Ftp Service closeService
I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7525 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6249): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6249): state: 13
V/BluetoothSapService( 6249): Stopping SAP server process
V/BluetoothSapService( 6249): Sap Service closeSapService in
V/BluetoothSapService( 6249): Close listen Socket : 
V/BluetoothSapService( 6249): Close rfcomm Socket : 
V/BluetoothSapService( 6249): Close sapd  Socket : 
V/BluetoothSapService( 6249): Sap Service closeSapService out
V/BluetoothSapService( 6249): Sap Service onDestroy
V/BluetoothSapService( 6249): Sap Service closeSapService in
V/BluetoothSapService( 6249): Close listen Socket : 
V/BluetoothSapService( 6249): Close rfcomm Socket : 
V/BluetoothSapService( 6249): Close sapd  Socket : 
V/BluetoothSapService( 6249): Sap Service closeSapService out
,W/ResourcesManager( 7525): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1030): Killing 6903:com.lge.clock/u0a10 (adj 15): empty #17
,W/ExternalStrings( 7500): load override strings
W/ExternalStrings( 7500): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7500): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7500): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7500): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7500): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7500): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7500): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7500): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7500): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7500): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7500): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7500): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7500): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7500): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7500): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7500): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7500): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 7500): onCreate
,D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_6903/cgroup.procs: No such file or directory
V/Signer  ( 7500): override build config not found
D/Signer  ( 7500): value of property debug is false
,D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7500): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7500): Create singleton instance
,D/LGMDMWrapper( 7500): LG MDM library v4.0.0 is available on this device.
,D/bt_hci_bdroid( 6249): cleanup
I/bt_lpm  ( 6249): LPM is already off!!!
I/bt_userial_mct( 6249): exiting userial_read_thread
D/bt_userial_mct( 6249): Leaving userial_evt_read_thread()
W/bt-btif ( 6249): ag scb idx 1 not allocated
E/bt-btif ( 6249): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6249): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6249): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x001b
,W/bt-l2cap( 6249): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6249): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6249): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6249): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6249): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6249): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6249): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6249): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6249): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 6249): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6249): hw_epilog_process
D/bt_hci_bdroid( 6249): cleanup Finalizing cleanup
D/bt_userial_mct( 6249): userial_close
E/bt_userial_mct( 6249): pthread_join() FAILED result:3
I/bt_vendor( 6249): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/bt_hci_bdroid( 6249): set_power 0
I/bt_vendor( 6249): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6249): bluetooth satus is on
I/bt_vendor( 6249): bt-vendor : resetting BT status
I/bt_vendor( 6249): Starting hciattach daemon
I/bt_vendor( 6249): try to set false
I/bt_vendor( 6249): Starting hciattach daemon
I/bt_vendor( 6249): try to set false
I/bt_vendor( 6249): cleanup
I/GKI_LINUX( 6249): gki_task task_id=0 [BTU] terminating
E/WifiStateMachine( 1030):  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1952371680] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
I/GKI_LINUX( 6249): GKI_exit_task 0 done
I/GKI_LINUX( 6249): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 6249): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6249): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 6249): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6249): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/HeadsetStateMachine( 6249): Exit Disconnected: -1
D/BluetoothHeadset( 1030): Proxy object disconnected
D/AudioService( 1030): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1862): Proxy object disconnected
D/BluetoothHeadset( 1862): Proxy object disconnected
D/BluetoothHeadset( 1862): Proxy object disconnected
D/A2dpService( 6249): Received stop request...Stopping profile...
D/A2dpStateMachine( 6249): Exit Disconnected: -1
,D/LGBluetoothAvrcpQcomAdapter( 6249): [BTUI] cleanup
D/BluetoothAdapterState( 6249): Stopping profile services that were post enabled
D/LGBluetoothA2dpAdapter( 6249): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6249): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
,D/BluetoothA2dp( 1030): Proxy object disconnected
D/AudioService( 1030): onServiceDisconnected: Bluetooth profile: 2
E/WifiStateMachine( 1030):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:-1952371657] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/HidService( 6249): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/BluetoothInputDevice( 7470): Proxy object disconnected
D/HidProfile( 7470): Bluetooth service disconnected
D/HealthService( 6249): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/HeadsetStateMachine( 6249): Unbinding service...
D/HeadsetPhoneState( 6249): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6249): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6249): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6249): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6249): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6249): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6249): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 6249): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/BtGatt.DebugUtils( 6249): handleDebugAction() action=null
,D/BtGatt.GattService( 6249): Received stop request...Stopping profile...
D/BtGatt.GattService( 6249): stop()
D/BtGatt.AdvertiseManager( 6249): advertise clients cleared
D/BluetoothPan( 7470): BluetoothPAN Proxy object disconnected
D/PanProfile( 7470): Bluetooth service disconnected
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
D/BluetoothMapService( 6249): Received stop request...Stopping profile...
D/BluetoothMapService( 6249): stop()
D/BluetoothMapEmailAppObserver( 6249): deinitObservers()
D/BluetoothMapEmailAppObserver( 6249): removeReceiver()
D/BluetoothAdapterService( 6249): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3152bd4f
I/BluetoothA2dpServiceJni( 6249): cleanupNative
I/GKI_LINUX( 6249): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6249): GKI_exit_task 2 done
I/GKI_LINUX( 6249): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6249): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6249): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6249): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6249): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6249): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6249): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6249): Cleaning up Bluetooth PAN callback object
D/BluetoothMap( 7470): Proxy object disconnected
D/MapProfile( 7470): Bluetooth service disconnected
V/BluetoothMapService( 6249): Handler(): got msg=4
D/BluetoothMapService( 6249): MAP Service closeService in
D/LGBluetoothMapAdapter( 6249): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6249): MAP Service closeService out
D/BluetoothAdapterState( 6249): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6249): Setting state to 10
I/BluetoothAdapterState( 6249): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothMapService( 6249): cleanup()
D/BluetoothMapService( 6249): MAP Service closeService in
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/LGBluetoothMapAdapter( 6249): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6249): MAP Service closeService out
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 6249): Entering OffState
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1862): onBluetoothStateChange: up=false
,D/BluetoothPbap( 7470): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=false
D/BluetoothMap( 7470): onBluetoothStateChange: up=false
D/BluetoothPan( 7470): onBluetoothStateChange on: false
D/BluetoothInputDevice( 7470): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1030): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1030): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1030): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1030): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@15fcd2a6 mBinding = false
D/BluetoothManagerService( 1030): Sending unbind request.
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1972): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1972): Message: 2
D/LGBluetoothFeatureConfig( 7470): isPrivacyLogsEnabled : true
,D/LGBluetoothAPIService( 1972): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@396685df mBinding = false
D/LGBluetoothAPIService( 1972): Sending unbind request.
E/LGBluetoothEventManager( 7470): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7470): [BTUI] clear device connection state
,I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/GKI_LINUX( 6249): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6249): GKI_exit_task 1 done
I/GKI_LINUX( 6249): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6249): cleanupNative: return from cleanup
I/art     ( 6249): --- WEIRD: removing null entry 246
W/art     ( 6249): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6249): Cleaning up Bluetooth Service callback object
D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
W/ContextImpl( 7470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapter( 1465): 151919073: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1465): 151919073: getState() :  mService = null. Returning STATE_OFF
,D/LGBluetoothSettingsDBObserver( 6249): [BTUI] unregister observer for LG device name DB
I/art     ( 6249): System.exit called, status: 0
I/AndroidRuntime( 6249): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  310): 6249 died, releasing its sessions
V/AudioFlinger(  310):  pid 1862 @ 0
V/AudioFlinger(  310):  pid 3299 @ 1
V/AudioFlinger(  310):  pid 3299 @ 2
,I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7557 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/DSQN    ( 1030): EVENT_INTERNET_CHECK_ENABLE received
,I/ActivityManager( 1030): Process com.android.bluetooth (pid 6249) has died
W/ActivityManager( 1030): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,D/LGBluetoothUserBindClient( 7470): [BTUI] onServiceDisconnected
W/ActivityThread( 7500): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1030): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7579 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
I/PCSuite ( 7557): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/DockEventReceiver( 7470): finishStartingService: stopping service
I/ActivityManager( 1030): Killing 6782:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
D/PCSuite ( 7557): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7557): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_6782/cgroup.procs: No such file or directory
,W/ResourcesManager( 7579): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 7579): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7579): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7579): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/WiFiOffLoadBroadcast( 7470): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/BluetoothAdapterApp( 7579): Loading JNI Library
D/LgDataFeature( 7470): LgDataFeature() Constructor: none
,D/LgDataFeature( 7470): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7470): MCCMNC not supported: null
D/BluetoothAdapterApp( 7579): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2b89a944 Instance Count = 1
,D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BluetoothAdapterApp( 7579): onCreate
I/QRemote ( 6425): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7557): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7557): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7557): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7470): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7470): MCCMNC not supported: null
D/ProfileConfigQcom( 7579): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7579): Adding HeadsetService
D/ProfileConfigQcom( 7579): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7579): Adding A2dpService
,D/ProfileConfigQcom( 7579): [BTUI] HidService is supported
,D/ProfileConfigQcom( 7579): Adding HidService
D/ProfileConfigQcom( 7579): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7579): Adding HealthService
D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/LGBluetoothFeatureConfig( 7579): isSupportPan() :  mTargetOp=OPEN
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ProfileConfigQcom( 7579): [BTUI] PanService is supported
D/ProfileConfigQcom( 7579): Adding PanService
D/ProfileConfigQcom( 7579): [BTUI] GattService is supported
D/ProfileConfigQcom( 7579): Adding GattService
D/ProfileConfigQcom( 7579): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7579): Adding BluetoothMapService
D/ProfileConfigQcom( 7579): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 7579): PbapReceiver onReceive 
I/QRemote ( 6425): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothPbapReceiver( 7579): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7579): ***********state = 10
V/LGMDMManagerInternal( 7579): Create singleton instance
D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7557): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7557): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7557): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7470): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7470): MCCMNC not supported: null
D/LgDataFeature( 7500): LgDataFeature() Constructor: none
D/LgDataFeature( 7500): LgDataFeature() Constructor Done, null
,D/QRemote ( 6425): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6425): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6425): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7606 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6980:com.google.android.talk/u0a72 (adj 15): empty #17
,W/ContextImpl( 7500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6980/cgroup.procs: No such file or directory
D/LGBluetoothUserBindClient( 7470): [BTUI] onServiceConnected
,D/BluetoothPermissionRequest( 7470): onReceive
D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/LGBluetoothUtils( 7470): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7470): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7470): return without doing reset settings.
D/LGBluetoothOppAdapter( 7579): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
V/BluetoothFtpReceiver( 7579): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
V/BluetoothSapReceiver( 7579): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7579): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7579): SapReceiver onReceive 
V/BluetoothSapReceiver( 7579): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7579):  Bluetooth Adapter state = 10
,D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7525): [BTUI] STATE_OFF : reset connected device information EasySettings
I/ActivityManager( 1030): Killing 7115:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/SiteAdvisor( 7500): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/PCSuite ( 7557): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_7115/cgroup.procs: No such file or directory
V/WiFiOffLoadBroadcast( 7470): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7606): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 7470): MCCMNC not supported: null
D/UsbSettingsReceiver( 7470): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7470): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7470): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7470): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/FormManager( 7606): Network unavailable.
D/UsbSettingsReceiver( 7470): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/FormManager( 7606): Network unavailable.
D/UsbSettingsControl( 7470): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7470): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7470): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7470): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7470): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7470): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1030): Killing 7151:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_7151/cgroup.procs: No such file or directory
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/PCSuite ( 7557): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7557): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7557): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7470): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7606): Network not available. Please check & try again.
V/FormManager( 7606): Network unavailable.
D/WiFiOffLoadBroadcast( 7470): MCCMNC not supported: null
V/FormManager( 7606): Network unavailable.
,D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5275): type=WIFI subType= reason=null isConnected=false
I/NetworkMonitor( 5275): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 7500): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7663 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7663): onCreate
W/AppUp4:DB( 7663):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7663):  setFingerPrint start
I/AppUp4:DB( 7663):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7663):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7663):  SDK version = 21
I/AppUp4:DB( 7663):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7663): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7663): onReceive
D/LgDataFeature( 7663): LgDataFeature() Constructor: none
D/LgDataFeature( 7663): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7663): Context : android.app.ReceiverRestrictedContext@25fadbae
D/AppUp4:CustFacade( 7663): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7663): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7663): begin check event
I/AppUp4:CustModeStarterReceiver( 7663): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7663): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7663): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7663): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7663): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1030): Killing 6634:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6634/cgroup.procs: No such file or directory
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7691 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7691): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7691): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7691): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7691): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7691): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7691): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7691): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7691): LgDataFeature() Constructor: none
D/LgDataFeature( 7691): LgDataFeature() Constructor Done, null
,D/eas_req ( 7691): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 7691): JNI_OnLoad()
I/HubEmail( 7691): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7691): registerNatives()
I/HubEmail( 7691): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7691): registerNativeMethods()
I/HubEmail( 7691): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7691): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/FormManager( 7606): Network not available. Please check & try again.
V/FormManager( 7606): Network unavailable.
V/FormManager( 7606): Network unavailable.
,W/Settings( 7691): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3299): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3299): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3299): networkInfo.isConnected() = false
I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7724 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7182:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_7182/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7744 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6846:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_6846/cgroup.procs: No such file or directory
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 71484(3MB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 4.311ms total 165.762ms
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7761 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7251:com.google.android.gms:car/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7251/cgroup.procs: No such file or directory
,I/art     ( 7761): Almond Protected OAT
,D/WeatherApplication( 7761): removeAccount
D/WeatherApplication( 7761): Account.length = 0
E/WeatherApplication( 7761): OPERATOR:OPEN
,D/WeatherAncestor( 7761): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:22:58
D/Weather.Utils( 7761): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7761): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7761): 2 : This is isUpdating : false
D/WeatherAncestor( 7761): connectivity changed - connection : true
D/WeatherService( 7761): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7761): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7761): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7761): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7761): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7761): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:22:58
,D/LGWifiP2pService( 1030): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7779 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 1030):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1030):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
I/ActivityManager( 1030): Killing 7284:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7284/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7779): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7779): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7779): Loading: webviewchromium
,I/LibraryLoader( 7779): Time to load native libraries: 5 ms (timestamps 6280-6285)
,I/LibraryLoader( 7779): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7779): Binding Chromium to main looper Looper (main, tid 1) {aa3795b}
,I/LibraryLoader( 7779): Expected native library version number "",actual native library version number ""
,I/chromium( 7779): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7779): Initializing chromium process, renderers=0
,W/art     ( 7779): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7779): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7779): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7779): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  310): registerClient() client 0xb558a5c0, uid 10093
W/AudioManagerAndroid( 7779): Requires BLUETOOTH permission
I/Adreno-EGL( 7779): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7779): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7779): Build Date: 12/12/14 금
I/Adreno-EGL( 7779): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7779): Remote Branch: 
I/Adreno-EGL( 7779): Local Patches: 
I/Adreno-EGL( 7779): Reconstruct Branch: 
,I/NSApplication( 7779): Starting up...
,I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7837 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6618:com.google.android.apps.books/u0a54 (adj 15): empty #17
,I/art     (  338): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 514us total 28.850ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 21.172ms
,I/art     (  338): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 575us total 21.655ms
,W/libprocessgroup( 1030): failed to open /acct/uid_10054/pid_6618/cgroup.procs: No such file or directory
W/ResourcesManager( 7837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2350): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2350): num queued entries: 0
I/iu.UploadsManager( 2350): num updated entries: 0
I/iu.SyncManager( 2350): NEXT; no task
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 7500): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7500): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7663): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7663): onReceive
,D/AppUp4:CustFacade( 7663): Context : android.app.ReceiverRestrictedContext@25fadbae
D/AppUp4:CustFacade( 7663): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7663): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7663): begin check event
I/AppUp4:CustModeStarterReceiver( 7663): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7691): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/GLSActivity( 2135): [ac] getting account id
,I/LgeMiscReceiver( 3299): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3299): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3299): networkInfo.isConnected() = false
I/GLSUser ( 2135): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/Settings( 7691): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 7606): Network not available. Please check & try again.
D/WeatherAncestor( 7761): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:22:59
V/FormManager( 7606): Network unavailable.
,D/Weather.Utils( 7761): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7761): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7761): 2 : This is isUpdating : false
D/WeatherAncestor( 7761): connectivity changed - connection : true
D/WeatherService( 7761): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3002dcdc
D/ForecastDataCache( 7761): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7761): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7761): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7761): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7761): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:22:59
V/FormManager( 7606): Network unavailable.
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{180a8c9b type 0 when 1449746583403 com.android.vending} when 1449746583403
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{e374838 type 2 when 420769 com.google.android.gms} when 420769
D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/GAV4    ( 7779): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager( 1030): Killing 7066:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6425): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6425): android.os.DeadObjectException
,W/System.err( 6425): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6425): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6425): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6425): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6425): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6425): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6425): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6425): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6425): android.os.DeadObjectException
W/System.err( 6425): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6425): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6425): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6425): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6425): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6425): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6425): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6425): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6425): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7066/cgroup.procs: No such file or directory
W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6425): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6425): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7917 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6425): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 7917): Quickset Services start...
,I/UEI.SmartControl( 7917): Manufacture = LGE
D/UEI.SmartControl( 7917): Id = LGNevo
D/UEI.SmartControl( 7917): File observer start...
E/UEI.SmartControl( 7917): IR Port is disabled: false
,D/UEI.SmartControl( 7917): Starting file observer...
D/UEI.SmartControl( 7917): Extracting JNI libs...
D/UEI.SmartControl( 7917): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7917): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7917): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7917): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7917): --- Selecting new region: 6
,I/UEI.SmartControl( 7917): Model = LG-D855
D/UEI.SmartControl( 7917): QS Service created
I/UEI.SmartControl( 7917): Service initServices...
,D/UEI.SmartControl( 7917): QS start get config
D/UEI.SmartControl( 7917): Loading JNI Libs...
,I/UEI.SmartControl( 7917): Supports setup maps: true
,D/UEI.SmartControl( 7917): QS start statue = true Error code = 0
I/UEI.SmartControl( 7917): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7917): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 7917): ### init IR Blaster...
,D/serial_port( 7917): Configuring serial port
E/UEI.SmartControl( 7917): UEIBLaster setting for 616
I/UEI.SmartControl( 7917): Setting serial record hearder size = 2
I/UEI.SmartControl( 7917): configuring settings for MAXQ616
I/UEI.SmartControl( 7917): Get version...
D/UEI.SmartControl( 7917): serial port data available: 21
,D/UEI.SmartControl( 7917): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7917): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 7917): QS saving settings...
D/UEI.SmartControl( 7917): IR Blaster version: 25672567
D/UEI.SmartControl( 7917): serial port data available: 4
,I/UEI.SmartControl( 7917): Device manager: loading config....
,D/UEI.SmartControl( 7917): ----------- loading internal config...
W/ContextImpl( 7917): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7917): Services init done
D/UEI.SmartControl( 7917): QS Service init finished
D/UEI.SmartControl( 7917): QS Service version name: 2.1.91
D/UEI.SmartControl( 7917): QS Service version code: 201091
,D/UEI.SmartControl( 7917): Service requested: Control
E/UEI.SmartControl( 7917): Loading SETTINGS...
D/UEI.SmartControl( 7917): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7917): -- Open brand translation xml: brands_translations_ko
,I/ActivityManager( 1030): Killing 6425:com.lge.qremote/u0a112 (adj 15): empty #17
I/UEI.SmartControl( 7917): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7917): -----service ready thread exits
W/libprocessgroup( 1030): failed to open /acct/uid_10112/pid_6425/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7917): Internal service binding...
D/UEI.SmartControl( 7917): Internal timer expired: 1
,D/UEI.SmartControl( 7917): unbind internal service
D/UEI.SmartControl( 7917): Service.onUnbind: IControl
,D/UEI.SmartControl( 7917): Service.onDestroy
D/UEI.SmartControl( 7917): Lock is in USE false
D/UEI.SmartControl( 7917): unbind internal service
W/System.err( 7917): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@391d04ba
W/System.err( 7917): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 7917): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7917): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7917): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7917): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7917): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7917): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 7917): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7917): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7917): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7917): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7917): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7917): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@391d04ba
D/serial_port( 7917): close(fd = 25)
I/UEI.SmartControl( 7917): Serial port is closed.
I/UEI.SmartControl( 7917): Serial port is closed.
I/UEI.SmartControl( 7917): Serial port is closed.
D/UEI.SmartControl( 7917): Blaster closed
D/UEI.SmartControl( 7917): Shut down QS...
D/UEI.SmartControl( 7917): Stopping QS lib
D/UEI.SmartControl( 7917): QS lib stop result = true
D/UEI.SmartControl( 7917): Stopped QS lib
D/UEI.SmartControl( 7917): Stopped file observer...
D/UEI.SmartControl( 7917): QS shutdown complete
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 430525201142; DSPS: 14248650; Offset : -4324135046
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{b620803 type 0 when 1449746603806 com.android.vending} when 1449746603806
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3e9d6d6 type 2 when 447485 android} when 447485
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 450526943426; DSPS: 14904067; Offset : -4324132108
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 470529271699; DSPS: 15559504; Offset : -4324153715
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{f64f7f3 type 0 when 1449746630207 com.android.vending} when 1449746630207
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7211): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 490531984088; DSPS: 16214953; Offset : -4324157495
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 510534125486; DSPS: 16870383; Offset : -4324152328
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 530535819958; DSPS: 17525798; Offset : -4324136452
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 550537698908; DSPS: 18181220; Offset : -4324149409
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 570539456088; DSPS: 18836637; Offset : -4324131732
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 590542422694; DSPS: 19492095; Offset : -4324155953
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 610544314875; DSPS: 20147517; Offset : -4324155731
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 630546492159; DSPS: 20802948; Offset : -4324145221
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7211): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 7211): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 650548628402; DSPS: 21458378; Offset : -4324145234
,I/ActivityManager( 1030): Killing 7436:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_7436/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 670550957926; DSPS: 22113814; Offset : -4324134994
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 690552854844; DSPS: 22769236; Offset : -4324130296
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 710555062129; DSPS: 23424669; Offset : -4324150664
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 730557127121; DSPS: 24080096; Offset : -4324130480
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 750559143259; DSPS: 24735522; Offset : -4324128528
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 770561960335; DSPS: 25390975; Offset : -4324149483
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 790563794390; DSPS: 26046395; Offset : -4324146509
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 810565860997; DSPS: 26701823; Offset : -4324155149
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 830567963229; DSPS: 27357252; Offset : -4324158500
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8043 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8043): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8043): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2ddac4f3
D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
I/ActivityManager( 1030): Killing 7525:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7525/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 850570273378; DSPS: 28012687; Offset : -4324136987
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 870572612901; DSPS: 28668124; Offset : -4324147527
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 890574507633; DSPS: 29323546; Offset : -4324144884
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 910576564813; DSPS: 29978973; Offset : -4324132381
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 930577799180; DSPS: 30634374; Offset : -4324149392
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 24886(1117KB) AllocSpace objects, 1(144KB) LOS objects, 33% free, 44MB/66MB, paused 3.311ms total 160.975ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7211): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 7211): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 950582511360; DSPS: 31289888; Offset : -4324136710
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{32f4824b type 0 when 1449747082673 com.google.android.gms} when 1449747082673
,D/Finsky  ( 7211): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{19fca541 type 0 when 1449747082738 com.android.vending} when 1449747082738
D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7211): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2350): Aggregate from 1449745282580 (log), 1449745282580 (data)
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7211): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 33771(2025KB) AllocSpace objects, 15(2MB) LOS objects, 50% free, 30MB/62MB, paused 1.365ms total 39.206ms
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7211): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7211): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7211): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7211): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
D/DeviceConnectionService( 1827): client connected with version: 7571000
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 970584370259; DSPS: 31945309; Offset : -4324139409
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{34680ef7 type 0 when 1449747137210 com.android.vending} when 1449747137210
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 990586267126; DSPS: 32600731; Offset : -4324134606
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{20b05da6 type 0 when 1449747157645 com.android.vending} when 1449747157645
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1010588348472; DSPS: 33256160; Offset : -4324159025
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030,
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3976a671 type 0 when 1449747183171 com.android.vending} when 1449747183171
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 3.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1030590685445; DSPS: 33911596; Offset : -4324141414
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{1954ab48 type 0 when 1449747205186 com.android.vending} when 1449747205186
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1050592769291; DSPS: 34567024; Offset : -4324132685
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1070595005689; DSPS: 35222458; Offset : -4324154692
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{19df8bdb type 0 when 1449747232515 com.android.vending} when 1449747232515
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7211): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1090597152973; DSPS: 35877888; Offset : -4324143665
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{750549a type 0 when 1449747260118 com.android.vending} when 1449747260118
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 21719(882KB) AllocSpace objects, 1(144KB) LOS objects, 33% free, 44MB/66MB, paused 2.239ms total 100.546ms
,D/Finsky  ( 7211): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7211): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7211): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1110599128278; DSPS: 36533313; Offset : -4324152002
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1130601316916; DSPS: 37188744; Offset : -4324130008
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1150603358940; DSPS: 37844171; Offset : -4324132636
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1170605276224; DSPS: 38499594; Offset : -4324137934
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1190607988300; DSPS: 39155043; Offset : -4324141871
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1210610847563; DSPS: 39810497; Offset : -4324151389
,I/UsageStatsService( 1030): User[0] Flushing usage stats to disk
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1972): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1972): Battery Level Remaining: 100%
D/LEDHandler( 1972): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1230612906826; DSPS: 40465924; Offset : -4324136700
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7211): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 7211): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1250614530829; DSPS: 41121337; Offset : -4324130154
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1270616453842; DSPS: 41776761; Offset : -4324160214
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1290618348522; DSPS: 42432182; Offset : -4324127185
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1310621244609; DSPS: 43087637; Offset : -4324130398
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1330623515017; DSPS: 43743072; Offset : -4324148600
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1350625634749; DSPS: 44398501; Offset : -4324134634
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1370627832502; DSPS: 45053933; Offset : -4324134198
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1390629746660; DSPS: 45709356; Offset : -4324142465
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1410632561393; DSPS: 46364808; Offset : -4324135505
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1430634809771; DSPS: 47020242; Offset : -4324145298
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1450636717888; DSPS: 47675664; Offset : -4324129428
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1470638882776; DSPS: 48331095; Offset : -4324131183
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1490641504904; DSPS: 48986541; Offset : -4324133567
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1510643686771; DSPS: 49641973; Offset : -4324149044
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1530645867753; DSPS: 50297404; Offset : -4324134731
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7211): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 7211): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1550647784620; DSPS: 50952827; Offset : -4324140550
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1570649413363; DSPS: 51608240; Offset : -4324129186
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1590651451429; DSPS: 52263667; Offset : -4324135902
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1610653365223; DSPS: 52919090; Offset : -4324144637
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1630655575997; DSPS: 53574522; Offset : -4324131103
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1650657620468; DSPS: 54229949; Offset : -4324131284
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1670659777543; DSPS: 54885380; Offset : -4324140853
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1690662375974; DSPS: 55540825; Offset : -4324136599
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1710664047945; DSPS: 56196240; Offset : -4324143016
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1730666356636; DSPS: 56851676; Offset : -4324153739
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,I/DigitalAppWidgetProvider( 8043): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 8043): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2ddac4f3
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1750668105169; DSPS: 57507093; Offset : -4324144656
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1770670888704; DSPS: 58162544; Offset : -4324138246
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1790673054634; DSPS: 58817975; Offset : -4324139064
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1810675172282; DSPS: 59473404; Offset : -4324127103
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1830677092587; DSPS: 60128827; Offset : -4324129458
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1030): Prepared write state in 12ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ProcessStatsService( 1030): Pruning old procstats: /data/system/procstats/state-2015-12-09-16-43-19.bin
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
W/ResourcesManager( 1412): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/PlayEventLogger( 7211): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7211): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7211): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7211): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 7211): Ignoring header User-Agent because its value was null.
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{34231a96 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1850678999142; DSPS: 60784250; Offset : -4324145510
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=662207778, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,D/[Concierge]Service( 2581): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=662207778 [*alarm*], flags=0x0
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1870681544238; DSPS: 61439693; Offset : -4324133217
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1890683536314; DSPS: 62095119; Offset : -4324155457
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1910685651931; DSPS: 62750548; Offset : -4324145553
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1930687857965; DSPS: 63405980; Offset : -4324136707
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1950690809885; DSPS: 64061437; Offset : -4324145122
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1970692875867; DSPS: 64716865; Offset : -4324154440
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 1990695047838; DSPS: 65372296; Offset : -4324148956
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2010697096164; DSPS: 66027723; Offset : -4324145360
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2030699260062; DSPS: 66683154; Offset : -4324148263
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2050701582345; DSPS: 67338590; Offset : -4324145315
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2070703771089; DSPS: 67994022; Offset : -4324153732
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2090705837227; DSPS: 68649449; Offset : -4324132454
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1972): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1972): Battery Level Remaining: 100%
D/LEDHandler( 1972): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 2110708055240; DSPS: 69304882; Offset : -4324142042
,TIME-OUT KILL (timeout was 1800000ms)
```
