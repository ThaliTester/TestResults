#### Test 506502789252e15_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 292828878482; DSPS: 9736269; Offset : -4312603453
,D/AndroidRuntime( 6195): 
D/AndroidRuntime( 6195): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6195): CheckJNI is OFF
D/AndroidRuntime( 6195): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1961): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{193e5f9b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{193e5f9b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6214 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6195): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1868): Display #0 changed.
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{3d39fdb4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{2a360ddd co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6214): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6214): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6214): Loading: webviewchromium
I/LibraryLoader( 6214): Time to load native libraries: 3 ms (timestamps 4909-4912)
I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6214): Binding Chromium to main looper Looper (main, tid 1) {89b00c9}
,I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
I/chromium( 6214): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6214): Initializing chromium process, renderers=0
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6214): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  315): registerClient() client 0xb1427820, uid 10311
,D/BluetoothManagerService( 1032): Message: 20
,D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c7bc74d:true
D/BluetoothAdapter( 6214): 145933262: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6214): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6214): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6214): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6214): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6214): Build Date: 12/12/14 금
I/Adreno-EGL( 6214): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6214): Remote Branch: 
I/Adreno-EGL( 6214): Local Patches: 
I/Adreno-EGL( 6214): Reconstruct Branch: 
,W/chromium( 6214): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6214): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6214): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6214): CordovaWebView is running on device made by: LGE
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6214): Render dirty regions requested: true
I/OpenGLRenderer( 6214): Initialized EGL, version 1.4
W/ActivityManager( 1032): Activity pause timeout for ActivityRecord{d921f38 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 6214): Enabling debug mode 0
,D/Atlas   ( 6214): Validating map...
,D/SplitWindow( 1032): check instance of lgWin Window{128d445f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6214): LgDataFeature() Constructor: none
,D/LgDataFeature( 6214): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@365a7227,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1467): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1467): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1467):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1467): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6214): Timeline: Activity_idle id: android.os.BinderProxy@d3dbc7e time:295419
I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +697ms (total +803ms)
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{d921f38 u0 com.test.thalitest/.MainActivity t4} time:295422
,D/JsMessageQueue( 6214): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6214): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6214): 
,D/jxcore_app_log( 6214): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434825984
D/JX-Cordova( 6214): jxcore cordova android initializing
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6214): Initializing JXcore engine
W/jxcore-log( 6214): JXcore engine is ready
,W/jxcore-log( 6214): Starting JXcore engine
,W/.test.thalitest( 6214): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10582]" dev="sockfs" ino=10582 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6214): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6214): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[8477]" dev="sockfs" ino=8477 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6214): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6214): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28127]" dev="sockfs" ino=28127 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6214): Background sticky concurrent mark sweep GC freed 123900(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.689ms total 136.671ms
W/jxcore-log( 6214): Platform android
W/jxcore-log( 6214): 
W/jxcore-log( 6214): Process ARCH arm
W/jxcore-log( 6214): 
I/jxcore-log( 6214): JXcore Cordova bridge is ready!
I/jxcore-log( 6214): 
W/jxcore-log( 6214): JXcore engine is started
I/jxcore-log( 6214): Toggling radios to true
I/jxcore-log( 6214): 
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1032): Message: 1
D/BluetoothManagerService( 1032): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/WifiService( 1032): New client listening to asynchronous messages
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
I/ActivityManager( 1032): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6302 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1032): setWifiEnabled: true pid=6214, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1032): setWifiEnabled: true pid=6214, uid=10311
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1032): disconnect pid=6214, uid=10311, packageName=com.test.thalitest
D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
E/WifiStateMachine( 1032):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1032): reconnect pid=6214, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6214): Radios toggled
I/jxcore-log( 6214): 
E/WifiStateMachine( 1032):  InitialState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1032):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1032): [GET_FTM][id=6], offset=12288
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1032): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1032): unknown target_country: EU , set to default
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1032): gEnableBmps=1
W/ResourcesManager( 6302): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6302): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6302): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6302): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6302): Loading JNI Library
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/SoftapController(  310): Softap fwReload - Ok
D/Tethering( 1032): InitialState.processMessage what=4
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring down wlan0
D/CommandListener(  310): Clearing all IP addresses on wlan0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1032): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6340 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1032): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterApp( 6302): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e67e4cd Instance Count = 1
E/WifiHW  ( 1032): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
D/BluetoothAdapterApp( 6302): onCreate
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1032): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1032): connecting to supplicant
E/WifiHW  ( 1032): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [2]
W/wpa_supplicant( 6349): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6349): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ProfileConfigQcom( 6302): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6302): Adding HeadsetService
D/ProfileConfigQcom( 6302): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6302): Adding A2dpService
D/ProfileConfigQcom( 6302): [BTUI] HidService is supported
D/ProfileConfigQcom( 6302): Adding HidService
D/ProfileConfigQcom( 6302): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6302): Adding HealthService
D/LGBluetoothFeatureConfig( 6302): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6302): [BTUI] PanService is supported
D/ProfileConfigQcom( 6302): Adding PanService
D/ProfileConfigQcom( 6302): [BTUI] GattService is supported
D/ProfileConfigQcom( 6302): Adding GattService
D/ProfileConfigQcom( 6302): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6302): Adding BluetoothMapService
D/ProfileConfigQcom( 6302): [BTUI] HeadsetClientService is NOT supported
I/wpa_supplicant( 6349): Successfully initialized wpa_supplicant
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e6779ae:true
D/BluetoothAdapterState( 6302): make
I/LGFMServiceAdapter( 6302): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6302): init
I/bte_conf( 6302): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6302): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6302): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6302): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6302): [BTUI] lge_load_bluetooth_address
,I/bluedroid-qcom( 6302): get_profile_interface socket
I/bluedroid-qcom( 6302): get_profile_interface map_client
I/wpa_supplicant( 6349): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6349): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
I/BluetoothAdapterState( 6302): Entering OffState
I/GKI_LINUX( 6302): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6362): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6362): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6302): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6302): Name is: G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/lge_bdaddr_loader( 6362): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6362): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6362): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6362): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
I/bluedroid-qcom( 6302): config_hci_snoop_log
D/BluetoothManagerService( 1032): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1032): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6362): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6362): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6302): Create singleton instance
W/ResourcesManager( 6340): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6340): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterState( 6302): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6302): Setting state to 11
I/BluetoothAdapterState( 6302): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 10 -> 11
,I/LGBluetoothServiceJni( 6302): classInitNative: succeeds
D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1467): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6302): make
I/BluetoothBondStateMachine( 6302): StableState(): Entering Off State
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/LGBluetoothServiceAdapter( 6302): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/LGBluetoothServiceAdapter( 6302): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6302): [BTUI] register observer for LG device name DB
,I/wpa_supplicant( 6349): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService( 6302): File transfer profiles supported!!
E/BluetoothAdapterService( 6302): File transfer profiles supported!!
D/BluetoothHeadset( 1868): Proxy object connected
D/BluetoothHeadset( 1032): Proxy object connected
D/BluetoothHeadset( 1868): Proxy object connected
D/BluetoothHeadset( 1868): Proxy object connected
D/HeadsetService( 6302): Received start request. Starting profile...
,I/LGBluetoothHeadsetServiceJni( 6302): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6302): Version 1.6
D/LGBluetoothFeatureConfig( 6302): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6302): classInitNative: succeeds
D/HeadsetStateMachine( 6302): make
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6340): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/BluetoothAdapterService( 6302): File transfer profiles supported!!
,E/BluetoothAdapterService( 6302): File transfer profiles supported!!
D/UsbSettingsControl( 6340): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6340): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/BluetoothAdapterService( 6302): File transfer profiles supported!!
D/UsbSettingsControl( 6340): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1032): Killing 5518:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LgDataFeature( 6302): LgDataFeature() Constructor: none
D/LgDataFeature( 6302): LgDataFeature() Constructor Done, null
,I/wpa_supplicant( 6349): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-SCAN-STARTED 
W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5518/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 6302): max_hf_connections = 1
I/bluedroid-qcom( 6302): get_profile_interface handsfree
V/ToneGenerator( 6302): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  315): registerClient() client 0xb558a880, uid 1002
V/AudioPolicyManager(  315): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6302): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,V/AudioFlinger(  315): registerClient() client 0xb5581868, pid 6302
V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1868): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1868): ioConfigChanged() opening already existing output! 2
,V/AudioSystem(  315): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  315): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6302): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1467): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1467): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1467): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1868): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1868): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1467): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3319): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3319): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3319): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3319): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6302): Create Track: 0xb4928080
V/AudioTrack( 6302): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6302): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6340): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/AudioSystem( 6302): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
V/AudioSystem( 6302): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6302): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  315): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  315): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  315): AudioPolicyManagerEx: getOutputForDevice
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/AudioPolicyManagerEx(  315): getOutput() returns output 2
E/BluetoothAdapterService( 6302): File transfer profiles supported!!
V/AudioSystem( 6302): getLatency() output 2, latency 50
V/AudioSystem( 6302): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6302): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  315): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  315): createTrack() lSessionId: 16
V/AudioTrack( 6302): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,D/UsbSettingsControl( 6340): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6340): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6340): [AUTORUN] setTetherStatus() : status=false
V/AudioFlinger(  315): acquiring 16 from 6302, for 6302
V/AudioFlinger(  315):  added new entry for 16
V/ToneGenerator( 6302): ToneGenerator INIT OK, time: 298478
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/HeadsetStateMachine( 6302): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6302): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6302): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6302): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  315): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6302
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
V/ToneGenerator( 6302): ToneGenerator destructor
V/ToneGenerator( 6302): stopTone
,V/ToneGenerator( 6302): Delete Track: 0xb4928080
V/AudioTrack( 6302): ~AudioTrack, releasing session id from 6302 on behalf of 6302
V/AudioFlinger(  315): releasing 16 from 6302 for 6302
V/AudioFlinger(  315):  decremented refcount to 0
V/AudioFlinger(  315): purging stale effects
V/AudioPolicyService(  315): AudioCommandThread() adding release output 2
V/AudioPolicyService(  315): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  315): AudioCommandThread() waking up
E/BluetoothAdapterService( 6302): File transfer profiles supported!!
V/AudioPolicyService(  315): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  315): releaseOutput() 2
V/AudioPolicyService(  315): AudioCommandThread() going to sleep
V/AudioFlinger(  315): PlaybackThread::Track destructor
V/AudioFlinger(  315): removeClient_l() pid 6302, calling pid 315
I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6369 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/BluetoothA2dp( 1032): Proxy object connected
,D/A2dpService( 6302): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6302): classInitNative: succeeds
V/LGMDMManager( 6302): Create singleton instance
V/Avrcp   ( 6302): make
D/Avrcp   ( 6302): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6302): get_profile_interface avrcp
I/BluetoothAdapterState( 6302): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioManager( 6302): registerRemoteController: size of Media player list: 0
,E/AudioManager( 6302): No RCC entry present to update
E/RemoteController( 6302): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6302): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6302): initQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] [+] updateMediaPlayerInfo
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/ActivityManager( 1032): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6392 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6369): Network not available. Please check & try again.
V/FormManager( 6369): Network unavailable.
V/FormManager( 6369): Network unavailable.
,I/ActivityManager( 1032): Killing 5540:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5540/cgroup.procs: No such file or directory
,I/wpa_supplicant( 6349): [LGE_PATCH]scan interval[0] = 2 sec.
,W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] installed app name: Music
,D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6302): classInitNative
,I/BluetoothA2dpServiceJni( 6302): classInitNative: succeeds
D/A2dpStateMachine( 6302): make
I/bluedroid-qcom( 6302): get_profile_interface a2dp
I/GKI_LINUX( 6302): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6302): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6302): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/A2dpStateMachine( 6302): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6302): classInitNative: succeeds
D/HidService( 6302): Received start request. Starting profile...
I/bluedroid-qcom( 6302): get_profile_interface hidhost
,D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
I/BluetoothHealthServiceJni( 6302): classInitNative: succeeds
D/HealthService( 6302): Received start request. Starting profile...
I/bluedroid-qcom( 6302): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6302): classInitNative: succeeds
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
V/BluetoothPbapReceiver( 6302): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6302): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6302): ***********state = 11
I/BluetoothPanServiceJni( 6302): classInitNative(L105): succeeds
D/PanService( 6302): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6302): initializeNative(L110): pan
I/bluedroid-qcom( 6302): get_profile_interface pan
,D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6418 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/LGBluetoothPanAdapter( 6302): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/HeadsetStateMachine( 6302): Proxy object connected
D/LGBluetoothHfpAdapter( 6302): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6302): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1868):  call mBluetoothHeadset.phoneStateChanged()
I/BtGatt.JNI( 6302): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6302): handleDebugAction() action=null
,D/BtGatt.GattService( 6302): Received start request. Starting profile...
D/BtGatt.GattService( 6302): start()
I/bluedroid-qcom( 6302): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6302): advertise manager created
,W/BluetoothHeadset( 1868): Proxy not attached to service
D/BluetoothHeadset( 1868): java.lang.Throwable
D/BluetoothHeadset( 1868): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1868): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1868): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1868): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1868): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1868): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1868): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1868): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 20.740ms
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
I/LGBluetoothMapAdapter( 6302): [BTUI] getInstance : create [LGBluetoothMapAdapter]
D/WifiService( 1032): New client listening to asynchronous messages
V/BluetoothMapService( 6302): BluetoothMapBinder()
D/BluetoothMapService( 6302): Received start request. Starting profile...
D/BluetoothMapService( 6302): start()
,D/BluetoothMapEmailSettingsLoader( 6302): Found 0 applications
D/BluetoothMapEmailAppObserver( 6302): createReceiver()
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.441ms
D/BluetoothMapEmailAppObserver( 6302): initObservers()
D/BluetoothMapEmailAppObserver( 6302): getEnabledAccountItems()
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/HeadsetStateMachine( 6302): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 6302): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6302): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 6302): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6302): Profile still not running:com.android.bluetooth.gatt.GattService
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 15.598ms
D/BluetoothAdapterService( 6302): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6302): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6302): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6302): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6302): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6302): Handler(): got msg=1
D/BluetoothAdapterState( 6302): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6302): enable
I/bt_hci_bdroid( 6302): init
,I/GKI_LINUX( 6302): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6302): btu_task pending for preload complete event
I/bt_vendor( 6302): bt-vendor : init
I/bt_vendor( 6302): bt-vendor : get_bt_soc_type
E/bt_vendor( 6302): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6302): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6302): userial_init
D/bt_hci_bdroid( 6302): set_power 1
I/bt_vendor( 6302): bt-vendor : BT_VND_OP_POWER_CTRL: On
,I/bt_vendor( 6302): Starting hciattach daemon
I/bt_vendor( 6302): try to set true
W/sh      ( 6442): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6442): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LgDataFeature( 6340): LgDataFeature() Constructor: none
,D/LgDataFeature( 6340): LgDataFeature() Constructor Done, null
,I/qcom-bluetooth( 6443): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/WiFiOffLoadUpdatePriority( 6340): remove : truetruefalse
D/WiFiOffLoadUpdatePriority( 6340): remove2
V/WiFiOffLoadSharedPrefsUtils( 6340): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 6340): save remove
D/WiFiOffLoadBroadcast( 6340): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6340): S: false, R: true
I/ActivityManager( 1032): Killing 5870:com.lge.email/u0a23 (adj 15): empty #17
I/qcom-bluetooth( 6451): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6452): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6454): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6455): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6456): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6457): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6459): ESOC framework not supported
,E/Diag_Lib( 6459):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5870/cgroup.procs: No such file or directory
,D/bthci_qcomm_linux( 6459): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6459): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6459): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6459): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6459): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6459): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6459): [BTUI] init_riva_entries: set NORMAL power settings
E/ActivityThread( 6418): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6418): No ProfileInfo entries
I/LG Account v2.2( 6418): isEnabled: false
I/Feature ( 6418): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6418): [Lifetracker]Country: EU
I/Feature ( 6418): [Lifetracker]Operator: OPEN
I/Feature ( 6418): [Lifetracker]Ranking support: false
I/Feature ( 6418): [Lifetracker]Comfort support: false
I/Feature ( 6418): [Lifetracker]Accessory: true
I/Feature ( 6418): [Lifetracker]Health device: true
I/Feature ( 6418): [Lifetracker]Extra Pedometer: false
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
I/Feature ( 6418): [Lifetracker]Blood glucose device: false
I/Feature ( 6418): [Lifetracker]Device Number: 3
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1032):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1032): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1032):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1032): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1032): setPowerSaveActivated(false)
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1032): doBoolean: SET update_config 1
D/WfdService( 1961): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1032): SET update_config 1: returned true
D/WifiConfigStore( 1032): Loading config and enabling all networks 
D/WifiNative-wlan0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1032):    returned network id / ssid / bssid / flags 0	NG700	any	
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [3]
,I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : state:0 event:3
E/WifiConfigStore( 1032): readNetworkVariablesFromSupplicantFile key=psk
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiConfigStore( 1032): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1032): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiStateMachine( 1032): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1032): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1032): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1032): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1032): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1032): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1032): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1032): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1032): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1961): Supplicant Connection state is changed : true
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1032): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1961): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1961): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1032): SCAN_INTERVAL 120: returned true
W/Settings( 6099): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WfdsMonitor( 1961): WfdsMonitorThread create
D/WfdsMonitor( 1961): WFDS Monitor is created and started
D/WfdsService( 1961): WiFi: Supplicant connection re-established
D/WifiNative-HAL( 1032): Setting external_sim to 1
D/WifiNative-wlan0( 1032): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1032): SET external_sim 1: returned true
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989208dc
E/CtrlSupplicant( 1961): Access OK "@android:wpa_wlan0"
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501f82
I/WifiNative-HAL( 1032): Could not start hal
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9892085c
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501e2e
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1032): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1032): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1961): Succeed to open control connection
E/CtrlSupplicant( 1961): Succeed to open monitor connection
D/WfdsMonitor( 1961): Supplicant connection established
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WfdsService( 1961): Connected to the supplicant for wfds
,D/WifiHS20( 1032): hidePasspointNotification off =false
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6349): android_multicast_filter_startstop : multicast filter set
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1032): [299,218,207 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1032): doBoolean: RECONNECT
D/WifiNative-wlan0( 1032): RECONNECT: returned true
D/WifiNative-wlan0( 1032): doString: [STATUS]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0( 1032):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/LGWifiP2pService( 1032): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiScanningService( 1032): SCAN_AVAILABLE : 3
D/RttService( 1032): SCAN_AVAILABLE : 3
D/WifiScanningService( 1032): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x94e6c99c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601226
I/WifiNative-HAL( 1032): Could not start hal
,E/WifiScanningService( 1032): could not start HAL
D/RttService( 1032): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up p2p0
D/WifiMonitor( 1032): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1032): P2pEnablingState
D/LGWifiP2pService( 1032): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2p socket connection successful
D/LGWifiP2pService( 1032): P2pEnabledState
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1032): sending p2p connection changed broadcast
E/WifiStateMachine( 1032):  ConnectModeState CMD_START_DRIVER 0 0
D/WifiNative-p2p0( 1032): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1032):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1032):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1032):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1032): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6349): nWIFIDualbandAPConnection: 1
D/WiFiOffLoadUpdatePriority( 6340): remove : truetruetrue
E/WifiStateMachine( 1032):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1032):  ConnectModeState what:132096 -100 0
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1961): WifiP2pState is changed : true
E/WifiStateMachine( 1032):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1032): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6349): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1032): doBoolean: DRIVER COUNTRY CZ
D/WfdsService( 1961): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1961): Receive the WFDS_ENABLE Method
D/WfdsService( 1961): Set the WFDS Monitor: true
D/WfdsService( 1961): Connected to the supplicant for wfds
D/WfdsJNI ( 1961): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6349): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsService( 1961): isConnected: false
D/WfdsJNI ( 1961): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6349): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1961): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
,D/WfdsService( 1961): selectPreferredScanChannel [36]
D/WfdsService( 1961): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1032): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_name G3-1
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6349): [LGE_PATCH] driver_cmd() country:CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1032): DRIVER COUNTRY CZ: returned true
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETBAND 0
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1032): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1032): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SCAN
I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1032): SCAN: returned true
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=299242  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=299242  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1032):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,E/WifiStateMachine( 1032):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1032):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-p2p0( 1032): SET device_name G3-1: returned true
D/LGWifiP2pService( 1032): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1032): before postfix = G3-1
D/WifiServerServiceExt( 1032): postfix byte check : 4
D/LGWifiP2pService( 1032): after postfix = G3-1
D/WifiNative-p2p0( 1032): doBoolean: SET p2p_ssid_postfix -G3-1
I/rmt_storage(  306): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  306): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  306): wakelock acquired: 1, error no: 42
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1032): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiService( 1032): New client listening to asynchronous messages
D/WifiNative-p2p0( 1032): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1032): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1032): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1032): p2pGetDeviceAddress
E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
V/FormManager( 6369): Network unavailable.
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
W/FormManager( 6369): Network not available. Please check & try again.
V/FormManager( 6369): Network unavailable.
D/WifiNative-HAL( 1032): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1032): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1032): doBoolean: P2P_FLUSH
I/WfdStateTracker( 1961): handleP2pThisDeviceChanged
D/WfdsService( 1961): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1961): Update P2p Interface State: 3
,D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6340): remove1
V/WiFiOffLoadSharedPrefsUtils( 6340): save remove
,D/WifiNative-p2p0( 1032): P2P_FLUSH: returned true
,D/WifiNative-p2p0( 1032): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1032): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1032):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1032): doBoolean: SAVE_CONFIG
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  306): 
I/rmt_storage(  306): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  883): [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WiFiOffLoadBroadcast( 6340): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6340): S: false, R: false
E/WifiStateMachine( 1032):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6340): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6340): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6340): private wpa: "NG700" 300
D/WifiServiceImplEx( 1032): addOrUpdateNetwork pid=6340, uid=1000, packageName=android.uid.system:1000
,E/addOrUpdateNetwork( 1032):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1032):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1032):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1032):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1032): addOrUpdateNetwork: mThisIsFirstEnableing = false
,D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-p2p0( 1032): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1032): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1032): InactiveState
D/LGWifiP2pService( 1032): InactiveState{ when=-127ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-127ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1032): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-wlan0( 1032): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1032): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1032): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
,D/WifiNative-wlan0( 1032): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1032): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1032): will read network variables netId=0
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6349): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1032): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1032): InactiveState{ when=-69ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-69ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-17ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-17ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-17ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-18ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-18ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-18ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1961): DefaultState - msg [9441285] is not handled
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiServerServiceExt( 1032): No p2p device connected
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE ,init=DRIVER type=WORLD]
E/WifiConfigStore( 1032): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1032):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6340):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6340): configuration updated: 0
E/WifiStateMachine( 1032):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6340): configuration saved: true
D/BluetoothPermissionRequest( 6340): onReceive
D/LGBluetoothFeatureConfig( 6340):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d90f135:true
,I/ActivityManager( 1032): Killing 5565:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 6340): return without doing reset settings.
W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5565/cgroup.procs: No such file or directory
,D/LGBluetoothOppAdapter( 6302): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/BluetoothFtpReceiver( 6302): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/LGDMClient( 4013): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothSapReceiver( 6302): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6302): [BTUI] region:EU country:EU
,V/BluetoothSapReceiver( 6302): SapReceiver onReceive 
V/BluetoothSapReceiver( 6302): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6302):  Bluetooth Adapter state = 11
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/PCSuite ( 6392): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1032): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
,I/ActivityManager( 1032): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6491 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6474): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1032): Killing 5786:com.android.defcontainer/u0a4 (adj 15): empty #17
D/AuthorizationBluetoothService( 2205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1032): failed to open /acct/uid_10004/pid_5786/cgroup.procs: No such file or directory
W/ResourcesManager( 6491): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6491): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6491): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6491): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 6491): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6491): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6491): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6491): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6491): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6491): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,D/QRemote ( 6491): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5961): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5961): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5961): Boot Receiver Return
,D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6491): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6491): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6491): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6491): LgDataFeature() Constructor: none
D/LgDataFeature( 6491): LgDataFeature() Constructor Done, null
,V/SoundPool( 6491): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6491): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6491): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6491): doLoad: loading sample sampleID=1
I/QRemote ( 6491): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6491): Start decode
V/MediaPlayer[Native]( 6491): decode(31, 10857164, 17813)
D/UEI.SmartControl( 5979): QS Service created
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
,V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb5474840, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/QRemote ( 6491): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6491): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 6491): Create singleton instance
V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
I/UEI.SmartControl( 5979): Service initServices...
D/UEI.SmartControl( 5979): QS start get config
V/AwesomePlayer(  315): onPrepareAsyncEvent() 
V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb57bc060 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  3,15): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315): finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb5474840, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb5474840, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044786272
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb57bc470 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb5474840, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac202000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac203000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac204000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac205000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac206000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac207000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac208000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac209000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac20a000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac20b000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac20c000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac20d000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac20e000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac20f000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac210000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac211000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac212000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac213000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac214000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac215000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac216000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac217000, 0xb14ea000, 4096)
,V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac218000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac219000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac21a000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac21b000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac21c000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac21d000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac21e000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac21f000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac220000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac221000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac222000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac223000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac224000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac225000, 0xb14ea000, 4096)
E/QC-QMI  ( 6459): qmi_client [6459] 13: failed to locate client data
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac226000, 0xb14ea000, 4096)
E/QC-QMI  (  472): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  472): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac227000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac228000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac229000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac22a000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac22b000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac22c000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac22d000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac22e000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac22f000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac230000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac231000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac232000, 0xb14ea000, 4096)
V/AudioCache(  315): write(0xb14ea000, 4096)
V/AudioCache(  315): memcpy(0xac233000, 0xb14ea000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb14ea000, 280)
V/AudioCache(  315): memcpy(0xac234000, 0xb14ea000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb5474840, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb5474840, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb5474840, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb57bc470 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/SoundPool( 6491): close(31)
V/SoundPool( 6491): pointer = 0x9fe91000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7529
I/qcom-bluetooth( 6527): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6528): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6302): bluetooth satus is on
,D/bt_hci_bdroid( 6302): preload
D/bt_userial_mct( 6302): userial_open(port:0)
I/bt_vendor( 6302): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6302): Done intiailizing UART
I/bt_vendor( 6302): Done intiailizing UART
I/bt_userial_mct( 6302): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6302): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6302): btu_task received preload complete event
D/bt_userial_mct( 6302): Entering userial_read_thread()
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6302): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6302): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6302): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6302): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6302): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6302): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6302): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6302): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6302): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6302): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6302): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6302): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6302): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6302): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6302): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6302): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6302): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6302): BTM_SecRegister:p_cb_info->p_le_callback == 0xa019d061 
E/bt-btm  ( 6302): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa019d061 
,E/bt-btif ( 6302): Calling BTA_HhEnable
E/bt-btif ( 6302): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6302): Address is:58:3F:54:73:64:C0
,D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6302): Name is: G3-1
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x0019
D/BluetoothAdapterProperties( 6302): Scan Mode:20
W/sh      ( 6533): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x0017
D/BluetoothAdapterProperties( 6302): Discoverable Timeout:120
W/sh      ( 6533): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x001b
D/bt_hci_bdroid( 6302): postload
E/bt_mct  ( 6302): hci lib postload completed
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x0013
W/bt-l2cap( 6302): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bte_conf( 6302): Device ID record 1 : primary
D/bte_conf( 6302):   vendorId            = 00c4
D/bte_conf( 6302):   vendorIdSource      = 0001
D/bte_conf( 6302):   product             = 13a1
D/bte_conf( 6302):   version             = 1000
D/bte_conf( 6302):   clientExecutableURL = 
D/bte_conf( 6302):   serviceDescription  = 
D/bte_conf( 6302):   documentationURL    = 
D/bte_conf( 6302): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6302): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6302): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6302): ScanMode =  20
D/BluetoothAdapterProperties( 6302): State =  11
D/BluetoothAdapterProperties( 6302): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6302): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6302): Setting state to 12
I/BluetoothAdapterState( 6302): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1032): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp( 1032): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6302): Entering On State
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6302): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6302): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6302): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6302): [BTUI] autoConnect() : not allowed
D/btif_config_util( 6302): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1032): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1032): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 6302): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6302): Plain text(LSB ~ MSB) = 09 41 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6302): Encrypted text(LSB ~ MSB) = d9 fe 9d d8 73 f2 e8 0b 9d ee b0 26 13 1e 1c a8 
W/bt-btm  ( 6302): Stopping oneshot timer
,D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1467): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1961): Message: 1
D/LGBluetoothAPIService( 1961): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIService Binding Success
W/bt-smp  ( 6302): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6302): Plain text(LSB ~ MSB) = f7 b4 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6302): Encrypted text(LSB ~ MSB) = 62 cc a5 25 e5 a5 f2 5e 42 5a fc c6 bd 02 72 8e 
W/bt-btm  ( 6302): Stopping oneshot timer
I/BluetoothMapService( 6302): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6302): STATE_ON
W/bt-smp  ( 6302): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6302): Plain text(LSB ~ MSB) = d5 10 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6302): Encrypted text(LSB ~ MSB) = d5 61 b9 55 e6 aa 51 3c 10 60 97 ae 94 da 88 8d 
W/bt-btm  ( 6302): Stopping oneshot timer
,W/ContextImpl( 6340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6302): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6302): [BTUI] onBind()
D/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1961): Message: 100
D/LGBluetoothAPIService( 1961): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/bt-smp  ( 6302): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6302): Plain text(LSB ~ MSB) = b5 e7 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6302): Encrypted text(LSB ~ MSB) = 4c 03 58 a9 e9 57 ca 95 81 90 61 cb 5a df 0f b0 
W/bt-btm  ( 6302): Stopping oneshot timer
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
V/BluetoothPbapService( 6302): Pbap Service onCreate
V/BluetoothPbapService( 6302): Starting PBAP service
,D/LGBluetoothPbapAdapter( 6302): [BTUI] getInstance : create
V/BluetoothPbapService( 6302): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6302): state: 12
V/BluetoothMapService( 6302): Handler(): got msg=1
D/BluetoothMapMasInstance( 6302): Map Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6302): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6302): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6302): ***********state = 12
V/BluetoothPbapService( 6302): Handler(): got msg=1
W/bt-smp  ( 6302): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6302): Plain text(LSB ~ MSB) = f9 22 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6302): Encrypted text(LSB ~ MSB) = 51 40 8b 80 1d 0e 73 e0 10 de f5 88 69 9f 51 fb 
V/BluetoothPbapService( 6302): Pbap Service startRfcommSocketListener
W/bt-btm  ( 6302): Stopping oneshot timer
D/BluetoothMapMasInstance( 6302): MAS initSocket()
D/LGBluetoothDeviceModeControllManager( 6302): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothMapMasInstance( 6302):   masId = 00
D/BluetoothMapMasInstance( 6302):   msgTypes = 0e
D/BluetoothMapMasInstance( 6302):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6302):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 6302): Pbap Service initSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6302): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 6340): Adding local A2DP profile
I/qcom-bt-wlan-coex( 6541): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/BluetoothAdapter( 6302): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6302): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6302): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6302): Accepting socket connection...
D/LGBluetoothServiceAdapter( 6302): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6302): Succeed to create listening socket 
V/BluetoothPbapService( 6302): Accepting socket connection...
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6340): Adding local HEADSET profile
D/BluetoothManagerService( 1032): Message: 30
,D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6340): Adding local MAP profile
,D/BluetoothMap( 6340): Create BluetoothMap proxy object
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6340): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6302): Pbap Service onBind
D/LGBluetoothUserBindClient( 6340): [BTUI] initUserBindClient
W/ContextImpl( 6340): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6340): finishStartingService: stopping service
,D/BluetoothA2dp( 6340): Proxy object connected
D/A2dpProfile( 6340): Bluetooth service connected
D/BluetoothHeadset( 6340): Proxy object connected
,D/HeadsetProfile( 6340): Bluetooth service connected
D/BluetoothInputDevice( 6340): Proxy object connected
D/HidProfile( 6340): Bluetooth service connected
D/BluetoothPan( 6340): BluetoothPAN Proxy object connected
D/PanProfile( 6340): Bluetooth service connected
D/BluetoothMap( 6340): Proxy object connected
D/MapProfile( 6340): Bluetooth service connected
D/BluetoothMap( 6340): getConnectedDevices()
V/BluetoothMapService( 6302): getConnectedDevices()
D/BluetoothPbap( 6340): Proxy object connected
D/PbapServerProfile( 6340): Bluetooth service connected
D/LGBluetoothUserBindClient( 6340): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6340): onReceive
D/LGBluetoothFeatureConfig( 6340): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6340): [BTUI] FileNotFound: readProperty
,D/LGBluetoothResetSettingReceiver( 6340): return without doing reset settings.
V/BluetoothOppReceiver( 6302): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
D/BluetoothAdapterProperties( 6302): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6302): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
I/LGBluetoothOppAdapter( 6302): [BTUI] startOppService()
D/BluetoothAdapterProperties( 6302): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6302): getDeviceMode  deviceMode 0
V/BluetoothOppManager( 6302): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6302): isPrivacyLogsEnabled : true
V/BtOppService( 6302): onCreate
,V/BluetoothOppNotification( 6302): send message
I/UEI.SmartControl( 5979): Supports setup maps: true
V/BtOppService( 6302): Starting RfcommListener
,D/BluetoothOppPreference( 6302): Dumping Names:  
D/BluetoothOppPreference( 6302): {}
D/BluetoothOppPreference( 6302): Dumping Channels:  
D/BluetoothOppPreference( 6302): {}
D/UEI.SmartControl( 5979): QS start statue = true Error code = 0
I/UEI.SmartControl( 5979): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5979): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5979): ### init IR Blaster...
V/BtOppService( 6302): onStartCommand
V/BtOppService( 6302): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6302): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6302): BluetoothFtpReceiver Start Service
D/serial_port( 5979): Configuring serial port
V/BluetoothOppNotification( 6302): new notify threadi!
E/UEI.SmartControl( 5979): UEIBLaster setting for 616
I/UEI.SmartControl( 5979): Setting serial record hearder size = 2
I/UEI.SmartControl( 5979): configuring settings for MAXQ616
I/UEI.SmartControl( 5979): Get version...
V/BluetoothOppNotification( 6302): send delay message
V/BtOppService( 6302): start RfcommListener
,V/BtOppService( 6302): RfcommListener started
V/BtOppRfcommListener( 6302): Starting RFCOMM listener....
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtOppService( 6302): Deleted complete outbound shares, number =  0
W/BluetoothAdapter( 6302): getBluetoothService() called with no BluetoothManagerCallback
V/BtOppService( 6302): Deleted complete inbound failed shares, number = 0
D/LGBluetoothServiceAdapter( 6302): [BTUI] createSocketChannel FD=78 mFd=75
V/BluetoothOppProvider( 6302): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6302): Started RFCOMM listener....
I/BtOppRfcommListener( 6302): Accept thread started.
V/BtOppRfcommListener( 6302): Accepting connection...
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@1e63beb6 on behalf of 
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@b57d7b7 on behalf of 
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
V/BluetoothFtpService( 6302): Ftp Service onCreate
I/BluetoothFtpService( 6302): Ftp Service onCreate
V/BluetoothFtpService( 6302): Ftp Service onStartCommand
V/BluetoothFtpService( 6302): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6302): Starting Listening on sockets
V/BluetoothSapReceiver( 6302): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6302): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6302): SapReceiver onReceive 
V/BluetoothSapReceiver( 6302): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6302):  Bluetooth Adapter state = 12
V/BtOppService( 6302): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothSapReceiver( 6302): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@275a68d on behalf of 
V/BluetoothOppNotification( 6302): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@2e51042 on behalf of 
V/BtOppService( 6302): ContentObserver received notification
V/BtOppService( 6302): ContentObserver received notification
V/BluetoothFtpService( 6302): Handler(): got msg=1
V/BluetoothFtpService( 6302): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6302): Ftp Service initSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/AuthorizationBluetoothService( 2205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BluetoothAdapter( 6302): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6302): update too frequent, put in queue
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/UEI.SmartControl( 5979): serial port data available: 21
D/LGBluetoothServiceAdapter( 6302): [BTUI] createSocketChannel FD=81 mFd=78
V/BtOppService( 6302): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothFtpService( 6302): Succeed to create listening socket on channel 20
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@1b883853 on behalf of 
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@1d5b7590 on behalf of 
V/BluetoothFtpService:RfcommSocketAcceptThread( 6302): Run Accept thread
V/BluetoothOppNotification( 6302): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6302): update too frequent, put in queue
V/BtOppService( 6302): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6302): outbound notification was removed.
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
V/BluetoothSapService( 6302): Sap Service onCreate
V/BluetoothSapService( 6302): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6302): state: 12
V/BluetoothSapService( 6302): Starting SAP server process
V/BluetoothSapService( 6302): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6302): Sap Service initRfcommSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6302): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6302): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6302): Succeed to create listening socket 
V/BluetoothSapService( 6302): Accepting socket connection...
W/sapd    ( 6556): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6556): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/BT_SAP  ( 6556): Event pipe created
V/BT_SAP  ( 6556): create_server_socket qcom.sap.server
V/BT_SAP  ( 6556): created socket fd 6
D/UEI.SmartControl( 5979): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5979): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5979): QS saving settings...
,D/UEI.SmartControl( 5979): IR Blaster version: 25672567
D/UEI.SmartControl( 5979): serial port data available: 4
,W/ContextImpl( 5979): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/art     ( 1032): Explicit concurrent mark sweep GC freed 36686(1871KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.413ms total 69.232ms
,E/UEI.SmartControl( 5979): Services init done
D/UEI.SmartControl( 5979): QS Service init finished
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@a2a5abc on behalf of 
V/BluetoothOppNotification( 6302): inbound: succ-0  fail-0
D/UEI.SmartControl( 5979): QS Service version name: 2.1.91
D/UEI.SmartControl( 5979): QS Service version code: 201091
D/UEI.SmartControl( 5979): Service requested: Control
I/QRemote ( 6491): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 5979): Internal service binding...
I/UEI.SmartControl( 5979): Device manager: loading config....
D/UEI.SmartControl( 5979): ----------- loading internal config...
I/UEI.SmartControl( 5979): ------ IControl API: 11
D/UEI.SmartControl( 5979): File observer start...
V/BluetoothOppNotification( 6302): inbound notification was removed.
E/UEI.SmartControl( 5979): IR Port is disabled: false
D/UEI.SmartControl( 5979): Starting file observer...
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
I/UEI.SmartControl( 5979): Registering callback...
I/UEI.SmartControl( 5979): ------ IControl API: 19
I/UEI.SmartControl( 5979): Registering Services Ready callback...
,V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@25161a45 on behalf of 
E/UEI.SmartControl( 5979): Loading SETTINGS...
D/UEI.SmartControl( 5979): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5979): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5979): -----service ready thread exits
I/QRemote ( 6491): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6491): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6491): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6491): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6491): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5979): ------ IControl API: 8
,D/QRemote ( 6491): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6491): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6491): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6491): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6491): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6491): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6491): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6491): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6491): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 6491): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449683848962]
D/QRemote ( 6491): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1032): Killing 5588:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/QRemote ( 6491): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_5588/cgroup.procs: No such file or directory
,V/QRemote ( 6491): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6491): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6491): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/wpa_supplicant( 6349): USIM:  scard_init function
I/wpa_supplicant( 6349): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989208cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20220e
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=301389  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=301402  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATING
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6340): Not supported operator for automatic switch
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
,D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/wpa_supplicant( 6349): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1032): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=301475  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=301475  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=301476
E/WifiStateMachine( 1032):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=301476
E/WifiStateMachine( 1032):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=301476
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=301477
E/WifiStateMachine( 1032):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=301477
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=301477  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 6349): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1032): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1032): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=301496  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=301503  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=301504  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1032):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=301505
E/WifiStateMachine( 1032):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=301505
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6340): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1032):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsControl( 6340): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6340): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6340): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6340): [AUTORUN] setTetherStatus() : status=false
I/WifiServiceExtension( 1032): setVHTCapabilityType  : false
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt( 1032): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1032): setKeepAlivePacketInterval msec : 60
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1032): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1032): Got NetworkAgent Messenger
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1032): NetworkAgent connected
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/CommandListener(  310): Setting iface cfg
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine( 1032): StoppedState
E/WifiStateMachine( 1032): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1032): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): WaitBeforeStartState
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=301553  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=301554  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=301554  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=301556  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=301556  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=301556  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-2015096282] from screen [on:0 period:-2015096282]
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2015096281]
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x989208bc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x7021b6
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateGROUP_HANDSHAKE
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1032): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1032):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 0
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 0
D/WifiNative-wlan0( 1032): SET ps 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
V/BluetoothOppNotification( 6302): new notify threadi!
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 1: returned true
V/BluetoothOppNotification( 6302): send delay message
E/WifiStateMachine( 1032): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31631606 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31631606 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
D/DhcpStateMachine( 1032): DHCP Start wake lock is acquired.
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@1cc8659a on behalf of 
V/BluetoothOppNotification( 6302): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@3f645ecb on behalf of 
V/BluetoothOppNotification( 6302): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6302): outbound notification was removed.
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@2ea066a8 on behalf of 
V/BluetoothOppNotification( 6302): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6302): inbound notification was removed.
V/BluetoothOppProvider( 6302): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6302): created cursor android.database.sqlite.SQLiteCursor@78315c1 on behalf of 
D/DhcpStateMachine( 1032): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1032): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1032): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6584): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6584): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6584): version 5.5.6 starting
,E/dhcpcd  ( 6584): get_duid: m
D/dhcpcd  ( 6584): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6584): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6584): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6584): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6584): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6584): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 6584): wlan0: sending REQUEST (xid 0x9c028bf5), next in 4.23 seconds
I/dhcpcd  ( 6584): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,I/dhcpcd  ( 6584): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 6584): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 6584): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6584): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6584): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6584): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6584): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6584): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,W/ProcessCpuTracker( 1032): Skipping unknown process pid 6603
,D/DhcpStateMachine( 1032): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1032): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1032): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1032): Add DhcpResults: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1032): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1032): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1032):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1032): RunningState
E/WifiStateMachine( 1032):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 2: returned true
,D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1,
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
,D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1032): ignoring duplicate network state non-change
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine( 1032): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1032): Adding iface wlan0 to network 100
E/WifiStateMachine( 1032):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1961): handleWifiStateChangedEvent: 1
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService( 1032): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1032): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1032): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1032): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1032): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1032): Setting Dns servers for network 100 to [/192.168.1.1]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 3
,D/Nat464Xlat( 1032): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1032): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Checking http://clients3.google.com/generate_204 on "NG700"
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1032): currentScore = 0, newScore = 20
D/ConnectivityService( 1032):    accepting network in place of null
D/ConnectivityService( 1032): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1868): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1032): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1032): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1032): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1032): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1032): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1032): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LocSvc_java( 1032): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1032): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1032): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1032): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1032): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1032): validation of new default Network = false
D/ConnectivityService( 1032): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1032): enableDataServiceNotify 
D/DSQN    ( 1032): start dsqn bin
,D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
D/ConnectivityService( 1032): identical MTU - not setting
D/Nat464Xlat( 1032): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1032): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524295
W/dsqn    ( 6634): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
W/dsqn    ( 6634): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/DSQN    ( 6634): DSQN ssw
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  310): res_queryN name = 2.android.pool.ntp.org succeed
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
,D/LGDataListener(  310): argv[0]=dsqncommand
D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1032): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1032): start to monitor internet connection
,D/libc-netbsd(  310): res_queryN name = europe.pool.ntp.org succeed
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6491): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6491): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6491): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:57:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683851890], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683851872]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Validated
D/ConnectivityService( 1032): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1032): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524290
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WIFI    ( 1032): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1868): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1032): [LG_RESTRICTED] checkMobilePolicy_type()
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
,D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6491): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6491): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6491): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/LocSvc_java( 1032): NTP server : europe.pool.ntp.org
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1032): NTP server returned: 1449683851792 (Wed Dec 09 18:57:31 GMT+01:00 2015) reference: 303728 certainty: 29 system time offset: -145
D/LocSvc_java( 1032): Sending msg: 10 arg1:0 arg2:1
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1032): reportXtraServer 
D/LocSvc_java( 1032):  server1=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1032):  server2=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1032):  server3=
D/LocSvc_java( 1032): xtraDownloadRequest
D/LocSvc_java( 1032): Sending msg: 6 arg1:0 arg2:1
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = xtra2.gpsOneXTRA.net, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = xtra2.gpsOneXTRA.net succeed
,D/LocSvc_java( 1032): calling native_inject_xtra_data
,D/LocSvc_java( 1032): Sending msg: 11 arg1:0 arg2:1
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2015093271] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015093268] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6214): Test app app.js loaded
I/jxcore-log( 6214): 
,I/chromium( 6214): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6214): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6214): 
,I/chromium( 6214): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/QRemote ( 6491): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7529
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,D/UEI.SmartControl( 5979): Internal timer expired: 2
D/UEI.SmartControl( 5979): unbind internal service
,D/serial_port( 5979): close(fd = 24)
,I/UEI.SmartControl( 5979): Serial port is closed.
V/WifiInternetCheck( 1032): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1032): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1032): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1032): Setting time of day to sec=1449683854
W/AlarmManagerService( 1032): Unable to set rtc to 1449683854: Invalid argument
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,I/SecureClockService( 1961): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1467): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 3564): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 3564): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-09 18:57:34...... Request
I/LIA_Informant_Tips_LogTracer( 3564): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 108, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3564): DateInfo : SmartTips Total Working Day Count = 108
D/LIA_Informant_Tips_DateChangeManager( 3564): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 3564): DateInfo : Last Date Check Time = 2015-12-09 18:57:34
,D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/LgeClockWidgetControlView( 1467): time changed, timezoneChanged : false
W/ActivityManager( 1032): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 2083): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2083): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
I/[LGHome]LGCalendarIcon( 2083): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ContextImpl( 5216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5271): type=WIFI subType= reason=null isConnected=true
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6684 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1032): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6703 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppUp4:AppBoxCP( 6684): onCreate
,W/AppUp4:DB( 6684):  [AppBoxDatabaseHelper] construct
I/ActivityManager( 1032): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6721 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/AppUp4:DB( 6684):  setFingerPrint start
,I/AppUp4:DB( 6684):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6684):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6684):  SDK version = 21
I/AppUp4:DB( 6684):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6684): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6684): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6684): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6684): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6684): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6684): onReceive
,W/ResourcesManager( 6721): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6721): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6721): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6721): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6684): LgDataFeature() Constructor: none
,D/LgDataFeature( 6684): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6684): Context : android.app.ReceiverRestrictedContext@2b1a52ef
D/AppUp4:CustFacade( 6684): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6684): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6684): begin check event
I/AppUp4:CustModeStarterReceiver( 6684): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6684): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/AppConfig( 6721): Total System Memory = 2995761152
,D/SystemHelper( 6721): region [EU], country [EU], operator [OPEN], sub-operator []
D/AppUp4:CustModeStarterReceiver( 6684): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6684): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6684): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1032): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6741 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1032): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/GpsLocationProvider( 1032): No APN found to select.
,I/VacuumService( 2205): Vacuum at: now=1449683855288 tag=VacuumService
V/DownloadManager( 3357): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/GoogleURLConnFactory( 2205): Using platform SSLCertificateSocketFactory
V/DownloadManager( 3357): DownloadService onCreate
,D/LGDMClient( 4013): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/ReaderUtils( 6703): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/DownloadManager( 3357): in removeSpuriousFiles
V/DownloadManager( 3357): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3357): created cursor android.database.sqlite.SQLiteCursor@e560565 on behalf of 3357
W/Uploader( 2205): No account for auth token provided
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3357): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/LGDMClient( 4013): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3357): in trimDatabase
V/DownloadManager( 3357): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3357): created cursor android.database.sqlite.SQLiteCursor@284d0eeb on behalf of 3357
,I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6770 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3357): DownloadService onStartCommand
V/DownloadManager( 3357): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3357): created cursor android.database.sqlite.SQLiteCursor@3d2692e1 on behalf of 3357
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com, class = 1, type = 1
E/LGDMClient( 4013): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4013): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4013): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3357): processing inserted download 1
V/DownloadManager( 3357): processing inserted download 4
,V/DownloadManager( 3357): processing inserted download 7
V/DownloadManager( 3357): processing inserted download 8
V/DownloadManager( 3357): processing inserted download 9
V/DownloadManager( 3357): processing inserted download 10
V/DownloadManager( 3357): processing inserted download 16
V/DownloadManager( 3357): processing inserted download 17
,V/DownloadManager( 3357): processing inserted download 18
V/DownloadManager( 3357): processing inserted download 21
I/ActivityManager( 1032): Killing 5902:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/GAV2    ( 6703): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ResourcesManager( 6770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6770): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6770): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6770): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/libc-netbsd(  310): res_queryN name = play.googleapis.com succeed
V/DownloadManager( 3357): DownloadService onDestroy
,W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5902/cgroup.procs: No such file or directory
,I/LGEmail ( 6770): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/BooksApp( 6703): Created application version: 3.2.35 (30235)
D/LGEmail ( 6770): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2371): Background init thread started
E/Auth.Api.Credentials( 2371): [CredentialSyncAdapter] Unknown sync event.
W/ResourceType( 6770): No package identifier when getting value for resource number 0x00000000
,W/DriveInitializer( 2371): Awaiting to be initialized
I/BooksSync( 6703): Starting books sync
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
D/DelayedSyncController( 6741): Delaying sync.
W/ContextImpl( 2371): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,I/ActivityManager( 1032): Killing 5620:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/LgDataFeature( 6770): LgDataFeature() Constructor: none
D/LgDataFeature( 6770): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_5620/cgroup.procs: No such file or directory
,W/Uploader( 2205): No account for auth token provided
,W/DriveInitializer( 2371): Background init thread ended
,D/eas_req ( 6770): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=30.2, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:2857] from screen [on:0 period:-2015090395] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=30.2, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2015090394] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/HubEmail( 6770): JNI_OnLoad()
,I/HubEmail( 6770): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6770): registerNatives()
I/HubEmail( 6770): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6770): registerNativeMethods()
I/HubEmail( 6770): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6770): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/LgeMiscReceiver( 3319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3319): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3319): networkInfo.isConnected() = true
D/PhoneState( 3319): setPdpRejectCasuse : false
,W/Uploader( 2205): No account for auth token provided
I/art     ( 2205): Explicit concurrent mark sweep GC freed 25639(1381KB) AllocSpace objects, 1(39KB) LOS objects, 51% free, 30MB/62MB, paused 1.439ms total 37.883ms
,I/ActivityManager( 1032): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6825 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,W/Settings( 6770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BooksSync( 6703): started syncMyEbooks
,W/Uploader( 2205):  no longer exists, so no auth token.
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,D/DrmBroadcastReceiver( 6825): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6825): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6825): Service onCreate
D/DrmService( 6825): Received new request = 2
I/DrmSntpClient( 6825): Start Sync process
D/DrmSntpClient( 6825): Server : 0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6850 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  310): res_queryN name = pool.ntp.org succeed
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
I/LGDrmClient( 6825): _DRM_ServiceGet() : Bind lgdrm service
D/libc-netbsd(  310): res_queryN name = www.google.com succeed
,V/ILGDrmService(  325): eDRM_SetDRMTime +++
I/LGDRM   (  325): [DRM] SET TIME : YR=2015, MON=12, DAY=9
I/LGDRM   (  325): [DRM] SET TIME : HR=17, MIN=57, SEC=34
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
V/ILGDrmService(  325): eDRM_SetDRMTime ---
I/DrmSntpClient( 6825): Synched
V/FormManager( 6369): There are no updated forms. The schedule will be deleted.
D/DrmService( 6825): Completed !! request = 2
D/DrmService( 6825): Request count = 0
V/FormManager( 6369): Alarm would be updated, because LastCheckTime has been updated.
,V/WifiInternetCheck( 1032): isHttpConnectionAvailable - We got a valid response : 204
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 65398(3MB) AllocSpace objects, 5(121KB) LOS objects, 33% free, 44MB/66MB, paused 1.966ms total 105.761ms
,V/DrmService( 6825): Service onDestroy
I/ActivityManager( 1032): Killing 5944:com.lge.eula/1000 (adj 15): empty #17
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 6850): Almond Protected OAT
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5944/cgroup.procs: No such file or directory
,D/WeatherApplication( 6850): removeAccount
D/WeatherApplication( 6850): Account.length = 0
E/WeatherApplication( 6850): OPERATOR:OPEN
,I/ActivityManager( 1032): Killing 6003:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/WeatherAncestor( 6850): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:57:36
,D/Weather.Utils( 6850): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6850): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6850): 2 : This is isUpdating : false
,D/WeatherAncestor( 6850): connectivity changed - connection : true
D/WeatherService( 6850): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6850): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6850): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6850): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6850): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6850): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:57:36
,W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_6003/cgroup.procs: No such file or directory
I/ActivityManager( 1032): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6873 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6099:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10072/pid_6099/cgroup.procs: No such file or directory
,D/DelayedSyncController( 6741): Delaying sync.
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1032): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
E/BooksAccountManager( 6703): Authentication error
E/BooksAccountManager( 6703): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6703): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6703): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6703): null auth token
,W/ResourcesManager( 1467): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1467): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1413): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1413): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do add job
D/LgeQuickCoverNotificationData( 1413): add : 2
D/LgeQuickCoverNotificationData( 1413): do add job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
W/ContextImpl( 6873): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6873): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6873): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6873): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2205): innerSync failed
D/ContactsSyncAdapter( 2205): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2205): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2205): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2205): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2205): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2205): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2205): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2205): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2205): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2205): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2205): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 27028, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 340130, reason: 10019
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6703): Error response from books API: {
W/ApiaryClient( 6703):  "error": {
W/ApiaryClient( 6703):   "errors": [
W/ApiaryClient( 6703):    {
W/ApiaryClient( 6703):     "domain": "global",
W/ApiaryClient( 6703):     "reason": "required",
W/ApiaryClient( 6703):     "message": "Login Required",
W/ApiaryClient( 6703):     "locationType": "header",
W/ApiaryClient( 6703):     "location": "Authorization"
W/ApiaryClient( 6703):    }
W/ApiaryClient( 6703):   ],
W/ApiaryClient( 6703):   "code": 401,
W/ApiaryClient( 6703):   "message": "Login Required"
W/ApiaryClient( 6703):  }
W/ApiaryClient( 6703): }
,W/ApiaryClient( 6703): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6703): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5634856817399804302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6703): Headers:
W/ApiaryClient( 6703): accept-encoding: [gzip]
W/ApiaryClient( 6703): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6703): gdata-version: 2
I/WebViewFactory( 6873): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/ActivityManager( 1032): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6925 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.080ms
,I/LibraryLoader( 6873): Loading: webviewchromium
I/LibraryLoader( 6873): Time to load native libraries: 5 ms (timestamps 8733-8738)
I/LibraryLoader( 6873): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6873): Binding Chromium to main looper Looper (main, tid 1) {240add56}
I/LibraryLoader( 6873): Expected native library version number "",actual native library version number ""
I/chromium( 6873): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 18.445ms
I/BrowserStartupController( 6873): Initializing chromium process, renderers=0
,W/art     ( 6873): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 295us total 15.925ms
W/chromium( 6873): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6873): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6873): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb558a520, uid 10093
,W/AudioManagerAndroid( 6873): Requires BLUETOOTH permission
W/ResourcesManager( 6925): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Adreno-EGL( 6873): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6873): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6873): Build Date: 12/12/14 금
I/Adreno-EGL( 6873): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6873): Remote Branch: 
I/Adreno-EGL( 6873): Local Patches: 
I/Adreno-EGL( 6873): Reconstruct Branch: 
I/NSApplication( 6873): Starting up...
,I/ActivityManager( 1032): Killing 4954:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10044/pid_4954/cgroup.procs: No such file or directory
,I/GLSActivity( 2205): [ac] getting account id
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
I/GLSUser ( 2205): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/iu.SyncManager( 2371): SYNC; picasa accounts
,D/NetworkLogImpl( 2371): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2371): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
I/iu.UploadsManager( 2371): num queued entries: 0
I/iu.UploadsManager( 2371): num updated entries: 0
I/iu.SyncManager( 2371): NEXT; no task
,D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 5216): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ActivityManager( 1032): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6982 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/ALBootInit( 6982): ====action==>android.intent.action.TIME_SET
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
W/Kids    ( 2371): [AccountUtils] Account not ready
W/Kids    ( 2371): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2371): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2371): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2371): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2371): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2371): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/ALBootInit( 6982): Alarm ALBootInit: TIME_SET
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/Alarms  ( 6982): [setNextAlert] start
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 1032): Explicit concurrent mark sweep GC freed 26090(1139KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.309ms total 67.913ms
,D/Alarms  ( 6982): [setNextAlert] (1)
D/Alarms  ( 6982):  minTime  = 0
,D/Alarms  ( 6982):  -- OK multi -- 0
E/jeny.kim( 6982): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6982): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/CommonUtil( 6982): BUILD Country: EU
D/GCM     ( 2205): Connected
,D/Alarms  ( 6982): broadcastToWidgetProvider : false
D/Alarms  ( 6982): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/GCM     ( 2205): Message class com.google.f.a.a.p
V/SettingsProvider( 1032): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6982): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6982): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@335451fc
V/DigitalAppWidgetProvider( 6982): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@335451fc
D/QuickCoverProvider( 6982): onReceiver
I/indal   ( 1413): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1413): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6850): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:57:37
D/Weather.Utils( 6850): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6850): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6850): 2 : This is isUpdating : false
D/WeatherService( 6850): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30c9e085
D/ForecastDataCache( 6850): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6850): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6850): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6850): 2 : set auto-update time : 12/9 21:57
D/WeatherAncestor( 6850): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:57:37
I/ActivityManager( 1032): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7008 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 5961:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5961/cgroup.procs: No such file or directory
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/TimeService( 7008): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683857762
D/        ( 7008): TimeServiceNative: User Time to be set is 1449683857763
D/QC-time-services( 7008): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7008): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7008): Lib:time_genoff_operation: pargs->ts_val = 1449683857763
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services( 7008): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683857763
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1449683857763, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/18/70 11:10:20
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 9285020000
D/QC-time-services(  374): Daemon:new time 1449683857763 
D/QC-time-services(  374): Daemon: delta 1440398837763 genoff 1440398837763 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1440398837763 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QC-time-services(  374): Updating the TOD offset
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1440398837763 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1124434037763
E/QC-time-services( 7008): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1032): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7029 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1032): Killing 6418:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10037/pid_6418/cgroup.procs: No such file or directory
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6703): Authentication error
E/BooksAccountManager( 6703): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6703): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6703): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6703): null auth token
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/ResourcesManager( 7029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/CalendarApplication( 7029): CalendarApplication.onCreate()
D/PreferenceKeysParser( 7029): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 7029): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1fd64093, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1a9878d0, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@89b00c9, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@8b2c3ce, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2b1a52ef, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@335451fc, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@30c9e085, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@343b4eda, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@25e32f0b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@79291e8, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@234d0001, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3f8f7ea6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2313b0e7, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@28f2e494, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@f889b3d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@aa4df32, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@16e07483, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@163b600, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce8ae39, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@d3dbc7e, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3a2bd5df, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@294e322c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@239cf4f5, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@26f5228a, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@7a1f0fb, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@34824518, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1514eb71, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@240add56, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2e94a1d7, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@21e29ac4, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@303bcdad, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2ef78e2, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@17978473, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@19d09f30, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1d7497a9, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@690412e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@16dbf4cf, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@27587e5c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@e560565, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2163423a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@284d0eeb, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@181d2448,
D/GeneralPreferenceUtils( 7029): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
W/ApiaryClient( 6703): Error response from books API: {
W/ApiaryClient( 6703):  "error": {
W/ApiaryClient( 6703):   "errors": [
W/ApiaryClient( 6703):    {
W/ApiaryClient( 6703):     "domain": "global",
W/ApiaryClient( 6703):     "reason": "required",
W/ApiaryClient( 6703):     "message": "Login Required",
W/ApiaryClient( 6703):     "locationType": "header",
W/ApiaryClient( 6703):     "location": "Authorization"
W/ApiaryClient( 6703):    }
W/ApiaryClient( 6703):   ],
W/ApiaryClient( 6703):   "code": 401,
W/ApiaryClient( 6703):   "message": "Login Required"
W/ApiaryClient( 6703):  }
W/ApiaryClient( 6703): }
W/ApiaryClient( 6703): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6703): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5634856817399804302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6703): Headers:
W/ApiaryClient( 6703): accept-encoding: [gzip]
W/ApiaryClient( 6703): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6703): gdata-version: 2
D/Config  ( 7029): [init]
I/Config  ( 7029): LGCalendar ver.4.40.16
I/Config  ( 7029): start check model
I/Config  ( 7029): start check native_ca
I/Config  ( 7029): Config Operator=OPEN, Country=EU
D/Config  ( 7029): [setDefaultValuesToPref]
D/Config  ( 7029): [parseProfiles]
D/ProfilesParser( 7029): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7029): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7029): [updateProfiletoCountryInfo]
D/GeneralPreference( 7029): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 7029): [updateWidgets] 
I/InitNotificationRingtoneService( 7029): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7029): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 7029): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
W/HolidayIntentService( 7029): onHandleIntent
D/MonthWidgetProvider( 7029): [onReceive]
D/CalendarWidgetProvider( 7029): [onReceive]
D/CalendarWidgetProvider( 7029): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 7029): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 7029): readJsonAsset : holiday.json
D/WeekWidgetProvider( 7029): [onReceive]
D/CalendarWidgetProvider( 7029): [onReceive]
D/CalendarWidgetProvider( 7029): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7029): [onUpdateAndInitCalendarTime]
I/AlertUtils( 7029): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7029): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 7029): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 7029): End InitializeAlertRingtoneService.onHandleIntent
E/HolidayIntentService( 7029): onHandleIntent:holiday data empty
I/ActivityManager( 1032): Killing 6474:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6474/cgroup.procs: No such file or directory
I/DigitalAppWidgetProvider( 6982): onReceive: android.intent.action.ALARM_CHANGED
I/ActivityManager( 1032): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7062 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7062): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 7062): LgDataFeature() Constructor: none
D/LgDataFeature( 7062): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=25.1, 0.0, 0.0  rx=22.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-2015087384] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=25.1, 0.0, 0.0  rx=22.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-2015087370] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/Babel   ( 7062): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7062): MmsConfig.loadMmsSettings
I/Babel   ( 7062): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7062): MmsConfig.loadFromDatabase
,E/Babel   ( 7062): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7062): MmsConfig.loadFromResources
E/Babel   ( 7062): canonicalizeMccMnc: invalid mccmnc nullnull
,W/Settings( 7062): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 7062): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 7062): Unsupported mime audio/evrc
W/AudioCapabilities( 7062): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7062): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7062): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7062): Unsupported mime audio/qcelp
W/AudioCapabilities( 7062): Unsupported mime audio/evrc
W/VideoCapabilities( 7062): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7062): Unsupported mime video/divx
,W/VideoCapabilities( 7062): Unsupported mime video/divx311
D/WeatherAncestor( 6850): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:57:38
D/Weather.Utils( 6850): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6850): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6850): 2 : This is isUpdating : false
D/Weather_cast( 6850): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6850): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:57:38
W/VideoCapabilities( 7062): Unsupported mime video/divx4
,W/VideoCapabilities( 7062): Unsupported mime video/mp4v-esdp
W/ResourcesManager( 7062): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7062): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/VideoCapabilities( 7062): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 7062): Unsupported mime audio/eac3
,W/AudioCapabilities( 7062): Unsupported mime audio/ac3
W/AudioCapabilities( 7062): Unsupported mime audio/g726
W/AudioCapabilities( 7062): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7062): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7062): Unsupported mime audio/adpcm
W/VideoCapabilities( 7062): Unsupported mime video/theora
,W/VideoCapabilities( 7062): Unsupported mime video/mjpg
V/JNIHelp ( 7062): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/System  ( 7062): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7062): Installed default security provider GmsCore_OpenSSL
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6703): Authentication error
E/BooksAccountManager( 6703): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6703): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6703): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6703): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6703): null auth token
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6703): Error response from books API: {
W/ApiaryClient( 6703):  "error": {
W/ApiaryClient( 6703):   "errors": [
W/ApiaryClient( 6703):    {
W/ApiaryClient( 6703):     "domain": "global",
W/ApiaryClient( 6703):     "reason": "required",
W/ApiaryClient( 6703):     "message": "Login Required",
W/ApiaryClient( 6703):     "locationType": "header",
W/ApiaryClient( 6703):     "location": "Authorization"
W/ApiaryClient( 6703):    }
W/ApiaryClient( 6703):   ],
W/ApiaryClient( 6703):   "code": 401,
W/ApiaryClient( 6703):   "message": "Login Required"
W/ApiaryClient( 6703):  }
W/ApiaryClient( 6703): }
,W/ApiaryClient( 6703): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6703): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5634856817399804302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6703): Headers:
W/ApiaryClient( 6703): accept-encoding: [gzip]
W/ApiaryClient( 6703): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6703): gdata-version: 2
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 7062): UserRecoverableAuthException.
E/Babel   ( 7062): cfq: BadAuthentication
E/Babel   ( 7062): 	at cfn.a(Unknown Source)
E/Babel   ( 7062): 	at f.a(PG:191)
E/Babel   ( 7062): 	at ava.a(PG:88)
E/Babel   ( 7062): 	at ava.a(PG:128)
E/Babel   ( 7062): 	at bjs.a(PG:255)
E/Babel   ( 7062): 	at bep.a(PG:602)
E/Babel   ( 7062): 	at bep.a(PG:469)
E/Babel   ( 7062): 	at bpo.run(PG:1141)
E/Babel   ( 7062): Error getting auth token
E/Babel   ( 7062): bxl
E/Babel   ( 7062): 	at f.a(PG:201)
E/Babel   ( 7062): 	at ava.a(PG:88)
E/Babel   ( 7062): 	at ava.a(PG:128)
E/Babel   ( 7062): 	at bjs.a(PG:255)
E/Babel   ( 7062): 	at bep.a(PG:602)
E/Babel   ( 7062): 	at bep.a(PG:469)
E/Babel   ( 7062): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7062): error sending REQ[fc:8; creat:1449683142449; type:bev-62781669]; took 108 ms (error code == 100)
E/Babel   ( 7062): Account registration failedRedacted-21
,E/Babel   ( 7062): bph: null -- null
E/Babel   ( 7062): 	at ava.a(PG:120)
E/Babel   ( 7062): 	at ava.a(PG:128)
E/Babel   ( 7062): 	at bjs.a(PG:255)
E/Babel   ( 7062): 	at bep.a(PG:602)
E/Babel   ( 7062): 	at bep.a(PG:469)
E/Babel   ( 7062): 	at bpo.run(PG:1141)
I/Babel   ( 7062): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 7062): Account sign in complete with state 106account: Redacted-21
I/art     ( 7062): Note: end time exceeds epoch: 
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2205): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 7062): Unexpected exception while authenticating.
E/Babel   ( 7062): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7062): 	at cfn.b(Unknown Source)
E/Babel   ( 7062): 	at cfn.a(Unknown Source)
E/Babel   ( 7062): 	at f.a(PG:188)
E/Babel   ( 7062): 	at ava.b(PG:143)
E/Babel   ( 7062): 	at bnr.run(PG:5415)
E/Babel   ( 7062): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7062): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7062): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksSync( 6703): Soft error: 
E/BooksSync( 6703): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6703): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5634856817399804302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6703): Headers:
E/BooksSync( 6703): accept-encoding: [gzip]
E/BooksSync( 6703): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6703): gdata-version: 2
E/BooksSync( 6703): 
E/BooksSync( 6703): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6703): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6703): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6703): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6703): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6703): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6703): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6703): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6703): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6703): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6703): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6703): {
E/BooksSync( 6703):  "error": {
E/BooksSync( 6703):   "errors": [
E/BooksSync( 6703):    {
E/BooksSync( 6703):     "domain": "global",
E/BooksSync( 6703):     "reason": "required",
E/BooksSync( 6703):     "message": "Login Required",
E/BooksSync( 6703):     "locationType": "header",
E/BooksSync( 6703):     "location": "Authorization"
E/BooksSync( 6703):    }
E/BooksSync( 6703):   ],
E/BooksSync( 6703):   "code": 401,
E/BooksSync( 6703):   "message": "Login Required"
E/BooksSync( 6703):  }
E/BooksSync( 6703): }
E/BooksSync( 6703): 
E/BooksSync( 6703): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6703): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6703): 	... 8 more
,E/BooksSync( 6703): Sync error
E/BooksSync( 6703): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6703): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5634856817399804302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6703): Headers:
E/BooksSync( 6703): accept-encoding: [gzip]
E/BooksSync( 6703): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6703): gdata-version: 2
E/BooksSync( 6703): 
E/BooksSync( 6703): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6703): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6703): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6703): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6703): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6703): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6703): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6703): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6703): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6703): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6703): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6703): {
E/BooksSync( 6703):  "error": {
E/BooksSync( 6703):   "errors": [
E/BooksSync( 6703):    {
E/BooksSync( 6703):     "domain": "global",
E/BooksSync( 6703):     "reason": "required",
E/BooksSync( 6703):     "message": "Login Required",
E/BooksSync( 6703):     "locationType": "header",
E/BooksSync( 6703):     "location": "Authorization"
E/BooksSync( 6703):    }
E/BooksSync( 6703):   ],
E/BooksSync( 6703):   "code": 401,
E/BooksSync( 6703):   "message": "Login Required"
E/BooksSync( 6703):  }
E/BooksSync( 6703): }
E/BooksSync( 6703): 
E/BooksSync( 6703): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6703): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6703): 	... 8 more
I/BooksSync( 6703): Finished books sync
I/ActivityManager( 1032): Killing 5979:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 27010, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/QRemote ( 6491): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6491): android.os.DeadObjectException
W/System.err( 6491): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6491): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6491): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6491): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6491): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6491): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6491): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6491): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6491): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6491): android.os.DeadObjectException
W/System.err( 6491): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6491): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6491): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6491): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6491): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6491): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6491): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6491): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6491): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6491): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
I/ActivityManager( 1032): Killing 6392:com.lge.sync/1000 (adj 15): empty #18
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5979/cgroup.procs: No such file or directory
W/ActivityManager( 1032): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6491): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6491): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1032): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7120 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6392/cgroup.procs: No such file or directory
D/QRemote ( 6491): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/GAV2    ( 6703): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 7120): Quickset Services start...
,I/UEI.SmartControl( 7120): Manufacture = LGE
D/UEI.SmartControl( 7120): Id = LGNevo
D/UEI.SmartControl( 7120): File observer start...
,E/UEI.SmartControl( 7120): IR Port is disabled: false
D/UEI.SmartControl( 7120): Starting file observer...
D/UEI.SmartControl( 7120): Extracting JNI libs...
D/UEI.SmartControl( 7120): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7120): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7120): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7120): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2205): innerSync failed
D/ContactsSyncAdapter( 2205): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2205): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2205): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2205): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2205): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2205): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2205): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2205): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2205): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2205): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2205): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 340130, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
I/UEI.SmartControl( 7120): --- Selecting new region: 6
,I/UEI.SmartControl( 7120): Model = LG-D855
D/UEI.SmartControl( 7120): QS Service created
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/UEI.SmartControl( 7120): Service initServices...
D/UEI.SmartControl( 7120): QS start get config
D/UEI.SmartControl( 7120): Loading JNI Libs...
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 312831083895; DSPS: 10391701; Offset : -4312601895
,I/UEI.SmartControl( 7120): Supports setup maps: true
D/UEI.SmartControl( 7120): QS start statue = true Error code = 0
I/UEI.SmartControl( 7120): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7120): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7120): ### init IR Blaster...
D/serial_port( 7120): Configuring serial port
,E/UEI.SmartControl( 7120): UEIBLaster setting for 616
I/UEI.SmartControl( 7120): Setting serial record hearder size = 2
I/UEI.SmartControl( 7120): configuring settings for MAXQ616
I/UEI.SmartControl( 7120): Get version...
D/UEI.SmartControl( 7120): serial port data available: 21
,D/UEI.SmartControl( 7120): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7120): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7120): QS saving settings...
,D/UEI.SmartControl( 7120): IR Blaster version: 25672567
D/UEI.SmartControl( 7120): serial port data available: 4
,I/UEI.SmartControl( 7120): Device manager: loading config....
D/UEI.SmartControl( 7120): ----------- loading internal config...
,W/ContextImpl( 7120): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7120): Services init done
D/UEI.SmartControl( 7120): QS Service init finished
D/UEI.SmartControl( 7120): QS Service version name: 2.1.91
D/UEI.SmartControl( 7120): QS Service version code: 201091
D/UEI.SmartControl( 7120): Service requested: Control
E/UEI.SmartControl( 7120): Loading SETTINGS...
,D/UEI.SmartControl( 7120): Request IControl service: devices are loaded...
I/ActivityManager( 1032): Killing 6340:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 6491): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,D/UEI.SmartControl( 7120): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7120): ------ IControl API: 11
I/UEI.SmartControl( 7120): Registering callback...
I/UEI.SmartControl( 7120): ------ IControl API: 19
I/UEI.SmartControl( 7120): Registering Services Ready callback...
I/UEI.SmartControl( 7120): Notify client services are ready...
I/QRemote ( 6491): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6491): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6491): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6491): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6491): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7120): ------ IControl API: 8
D/QRemote ( 6491): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6491): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6491): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6491): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6491): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6491): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,I/UEI.SmartControl( 7120): Notify AllClients services are ready: 0
I/QRemote ( 6491): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6491): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6491): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 7120): -----service ready thread exits
D/WifiService( 1032): Client connection lost with reason: 4
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6340/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7120): Internal service binding...
D/QRemote ( 6491): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 6491): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
V/QRemote ( 6491): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6491): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,D/QRemote ( 6491): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6491): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449683861112]
D/QRemote ( 6491): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6491): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6491): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6491): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/GAV4    ( 6873): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=32.6, 0.0, 0.0  rx=27.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2015084354] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=32.6, 0.0, 0.0  rx=27.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-2015084341] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/ActivityManager( 1032): Killing 6684:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_6684/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Killing 6369:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10026/pid_6369/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=18.3, 0.0, 0.0  rx=14.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2015081325] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=18.3, 0.0, 0.0  rx=14.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-2015081324] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 7120): Internal timer expired: 1
D/UEI.SmartControl( 7120): unbind internal service
,D/serial_port( 7120): close(fd = 25)
I/UEI.SmartControl( 7120): Serial port is closed.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=10.1, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2015078289] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=10.1, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015078286] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2015075264] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=5.1, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-2015075253] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-2015072230] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015072227] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1467): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1885): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1885): split_name #11 / not available #0
I/SplitUIService( 1885): split app #11
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7178 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1467): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1467): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/administrator( 1032): Handling package changes for user 0
W/ResourcesManager( 2083): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7178): onCreate
W/AppUp4:DB( 7178):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7178):  setFingerPrint start
I/AppUp4:DB( 7178):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7178):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7178):  SDK version = 21
I/AppUp4:DB( 7178):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7178): AppBoxApplication onCreate()
I/NotificationService( 1032): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/AppUp4:CustModeStarterReceiver( 7178): onReceive
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7178): LgDataFeature() Constructor: none
D/LgDataFeature( 7178): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7178): Context : android.app.ReceiverRestrictedContext@1a9878d0
D/AppUp4:CustFacade( 7178): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7178): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7178): begin check event
I/AppUp4:CustModeStarterReceiver( 7178): Event For Nothing, skip.
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1032): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7215 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6825:com.lge.drmservice/u0a62 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10062/pid_6825/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 32814(1703KB) AllocSpace objects, 8(640KB) LOS objects, 33% free, 44MB/66MB, paused 2.411ms total 109.171ms
,W/ResourcesManager( 7215): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7215): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7215): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7215): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7215): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7215): BUILD Country: EU
I/SystemConfig( 7215): BUILD Operator: OPEN
,I/ActivityManager( 1032): Killing 6873:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10093/pid_6873/cgroup.procs: No such file or directory
,I/SystemConfig( 7215): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7215): existFile = false
I/SystemConfig( 7215): canReadFile = false
I/SystemConfig( 7215): systemFeature RCS result false
D/SystemConfig( 7215): refreshRcsSupport() :false
,I/UpdateIcingCorporaServi( 4314): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/ActivityManager( 1032): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7239 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 4314): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4314): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,I/LockScreenSettings( 7239): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7239): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7239): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7239): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7239): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7239): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7239): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1032): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7257 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6741:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10057/pid_6741/cgroup.procs: No such file or directory
,D/Finsky  ( 7257): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7257): LgDataFeature() Constructor: none
D/LgDataFeature( 7257): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7257): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1032): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7296 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7257): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7257): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7296): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7296): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3357): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3357): created cursor android.database.sqlite.SQLiteCursor@116baec7 on behalf of 7257
I/MultiDex( 7296): VM with version 2.1.0 has multidex support
I/MultiDex( 7296): install
,I/MultiDex( 7296): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7257): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7257): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7257): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 7296): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 7257): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 2371): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/ActivityManager( 1032): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7330 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityThread( 7296): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7296): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39862f78: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7296): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2205): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 294us total 14.184ms
I/PeopleContactsSync( 2371): CP2 sync disabled
D/AuthorizationBluetoothService( 2205): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 275us total 13.376ms
,V/GmsCoreStatsServiceLauncher( 2371): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 12.323ms
,I/ActivityManager( 1032): Killing 6770:com.lge.email/u0a23 (adj 15): empty #17
I/art     ( 2205): Explicit concurrent mark sweep GC freed 30279(1803KB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.014ms total 75.753ms
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_6770/cgroup.procs: No such file or directory
,W/ResourcesManager( 7330): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7330): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LocationInitializer( 2371): Restart initialization of location
,I/MultiDex( 7330): VM with version 2.1.0 has multidex support
I/MultiDex( 7330): install
I/MultiDex( 7330): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7330): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7330): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7330): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39862f78: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7330): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 7330): Install did not work
W/NativeLibraryUtils( 7330): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7330): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7330): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7330): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7330): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7330): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7330): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7330): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7330): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7330): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7330): 	... 4 more
,D/WearableService( 7330): callingUid 10005, callindPid: 7330
D/GCM     ( 2205): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2205): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1832): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/GmsCoreStatsServiceLauncher( 2371): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1832): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2371): Restart initialization of location
,V/Finsky  ( 7257): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2015069198] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015069195] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{237b2512 type 0 when 1449683877053 com.android.vending} when 1449683877053
D/Finsky  ( 7257): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7257): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7257): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7257): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7257): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7257): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7257): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2015066175] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015066172] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 332833044928; DSPS: 11047125; Offset : -4312594352
,I/ActivityManager( 1032): Killing 5216:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5216/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Killing 7008:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_7008/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-2015063144] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015063141] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{7c31fed type 2 when 337201 android} when 337201
D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2015060111] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-2015060107] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2015057078] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015057075] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-2015054054] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-43 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-2015054051] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/jxcore-log( 6214): Toggling radios to false
I/jxcore-log( 6214): 
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@201cfe22 mBinding = false
,D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
D/BluetoothManagerService( 1032): Message: 2
D/BluetoothManagerService( 1032): Sending off request.
D/LGBluetoothServiceAdapter( 6302): [BTUI] Precleanup
D/BluetoothAdapterState( 6302): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6302): Setting state to 13
I/BluetoothAdapterState( 6302): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6302): onBluetoothDisable()
I/BluetoothAdapterState( 6302): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 6302): Scan Mode:20
,D/BluetoothAdapterState( 6302): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 6302): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6302): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6302): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6302): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6302): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6302): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6302): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6302): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothPbapService( 6302): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6302): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6302): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 6302): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 6302): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x000f
,W/bt-btif ( 6302): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6302): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6302): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6302): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6302): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1032): Message: 60
,D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 12 -> 13
I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7380 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1467): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 6302): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6302): STATE_TURNING_OFF
V/BluetoothMapService( 6302): Handler(): got msg=4
D/BluetoothMapService( 6302): MAP Service closeService in
D/BluetoothMapMasInstance( 6302): MAP Service shutdown
D/LGBluetoothMapAdapter( 6302): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6302): MAP Service closeService out
,V/BtOppService( 6302): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6302): stopping Accept Thread
V/BtOppRfcommListener( 6302): close mBtServerSocket
V/BtOppRfcommListener( 6302): waiting for thread to terminate
I/BtOppRfcommListener( 6302): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 6302): done waiting for thread to terminate
I/ActivityManager( 1032): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7410 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiServiceImplEx( 1032): setWifiEnabled: false pid=6214, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1032): setWifiEnabled: false pid=6214, uid=10311
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
V/BtOppService( 6302): onDestroy
D/LGBluetoothOppAdapter( 6302): [BTUI] LGBluetoothOppAdapter cleanup
D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
E/WifiStateMachine( 1032):  ConnectedState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1032): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
I/jxcore-log( 6214): Radios toggled
I/jxcore-log( 6214): 
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
,D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1032): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2205): Read error: ssl=0xaa6f1800: I/O error during system call, Connection timed out
V/NativeCrypto( 2205): SSL shutdown failed: ssl=0xaa6f1800: I/O error during system call, Broken pipe
,D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1032): ignoring duplicate network state non-change
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1032): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1032):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGWifiP2pService( 1032): InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1032):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1032): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@11fd791d
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGWifiP2pService( 1032): P2pDisablingState
V/WfdStateTracker( 1961): handleWifiStateChangedEvent: 0
D/LGWifiP2pService( 1032): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGWifiP2pService( 1032): p2p socket connection lost
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService( 1032): P2pDisabledState
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent( 1032): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1032):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{624c670 type 0 when 1449683892386 com.android.vending} when 1449683892386
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1961): WifiP2pState is changed : false
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6349): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/LGWifiP2pService( 1032): P2pDisabledState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1961): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1961): Set the WFDS Monitor: false
D/WfdsMonitor( 1961): WFDS Monitor is stopped
D/CtrlSupplicant( 1961): Received on exit socket, terminate
D/WfdsService( 1961): STATE : WfdsDisabledState - enter
E/CtrlSupplicant( 1961): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1961): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1961): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1961): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1961): DefaultState - msg [9441355] is not handled
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1032): hidePasspointNotification off =false
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1032): SCAN_AVAILABLE : 1
D/RttService( 1032): SCAN_AVAILABLE : 1
D/WifiScanningService( 1032): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1032): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1032): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,W/ResourcesManager( 7410): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7410): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CommandListener(  310): Clearing all IP addresses on wlan0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/ConnectivityService( 1032): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1032): disableDataServiceNotify
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    ( 1032): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiNative-p2p0( 1032): doBoolean: TERMINATE
I/StatusBar.NetworkController( 1467): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1467): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1032): hidePasspointNotification off =false
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1032): TERMINATE: returned true
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [0]
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1032): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1032): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1467): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1032): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1032): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1032): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1032): Sending msg: 4 arg1:0 arg2:1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMo,nitor NetworkAgentInfo [WIFI () - null]( 1032): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java( 1032): getAGpsConnectionInfo connType - 4
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Disconnected - quitting
D/LocSvc_java( 1032): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1032): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1032): [LG_RESTRICTED] !!!isConnected  type  :1
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/ConnectivityService( 1032): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1032): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1032): Sending msg: 4 arg1:0 arg2:1
D/NetworkManagementService( 1032): Removing idletimer
D/LocSvc_java( 1032): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1032): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1032): ignore wifi update if we are not in OPENING or CLOSING
W/Settings( 1032): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1032): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/WIFI    ( 1032): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1868): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1032): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1467): null signal icon name: drawable/stat_sys_signal_null
E/ActivityThread( 7380): Failed to find provider info for com.lge.lgaccount.provider
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
W/LG Account v2.2( 7380): No ProfileInfo entries
I/LG Account v2.2( 7380): isEnabled: false
I/Feature ( 7380): [Lifetracker]ver: 4.21.112(40211120)
D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/Feature ( 7380): [Lifetracker]Country: EU
I/Feature ( 7380): [Lifetracker]Operator: OPEN
I/Feature ( 7380): [Lifetracker]Ranking support: false
I/Feature ( 7380): [Lifetracker]Comfort support: false
I/Feature ( 7380): [Lifetracker]Accessory: true
I/Feature ( 7380): [Lifetracker]Health device: true
I/Feature ( 7380): [Lifetracker]Extra Pedometer: false
I/Feature ( 7380): [Lifetracker]Blood glucose device: false
I/Feature ( 7380): [Lifetracker]Device Number: 3
W/ContextImpl( 7410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager( 1032): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7440 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothPbapReceiver( 6302): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6302): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6302): ***********state = 13
,V/BluetoothPbapReceiver( 6302): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6302): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6302): state: 13
V/BluetoothPbapService( 6302): Pbap Service closeService in
V/BluetoothPbapService( 6302): successfully stopped pbap service
D/BluetoothManagerService( 1032): Message: 20
V/BluetoothPbapService( 6302): Pbap Service closeService out
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@256eb50f:true
,V/BluetoothPbapService( 6302): Pbap Service onDestroy
V/BluetoothPbapService( 6302): Pbap Service closeService in
V/BluetoothPbapService( 6302): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6302): [BTUI] cleanup
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 7410): Adding local MAP profile
D/BluetoothMap( 7410): Create BluetoothMap proxy object
,I/wpa_supplicant( 6349): p2p0: CTRL-EVENT-TERMINATING 
D/BluetoothManagerService( 1032): Message: 30
I/wpa_supplicant( 6349): monitor socket send errors count : 1
I/wpa_supplicant( 6349): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1961-2\x00 that cannot receive messages
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1032): Dropping event because (p2p0) is stopped
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 7410): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7410):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 7410): [BTUI] initUserBindClient
,W/ContextImpl( 7410): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
W/ResourcesManager( 7440): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/DockEventReceiver( 7410): finishStartingService: stopping service
D/BluetoothInputDevice( 7410): Proxy object connected
D/HidProfile( 7410): Bluetooth service connected
D/BluetoothPan( 7410): BluetoothPAN Proxy object connected
D/PanProfile( 7410): Bluetooth service connected
D/BluetoothMap( 7410): Proxy object connected
,D/MapProfile( 7410): Bluetooth service connected
D/BluetoothMap( 7410): getConnectedDevices()
D/BluetoothMap( 7410): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7410): [BTUI] onServiceConnected
,D/LGBluetoothAuthorization( 7410): [BTUI] cancel All Notification
D/PluginManager( 7440): init()
D/BluetoothPermissionRequest( 7410): onReceive
D/DhcpStateMachine( 1032): StoppedState
D/DhcpStateMachine( 1032): StoppedState{ when=-188ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1032):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_ON_QUIT 0 0
D/LGBluetoothAuthorization( 7410): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 7410): return without doing reset settings.
,I/ActivityManager( 1032): Killing 7029:com.android.calendar/u0a13 (adj 15): empty #17
I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1032): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1032): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
W/wpa_supplicant( 6349): USIM:  scard_deinit function
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1032):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=344894
D/Tethering( 1032): InitialState.processMessage what=4
E/WifiStateMachine( 1032):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=344894
,E/WifiStateMachine( 1032):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=344895  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1032):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=344895  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
V/BluetoothOppReceiver( 6302): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/libprocessgroup( 1032): failed to open /acct/uid_10013/pid_7029/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 6302): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 6302): [BTUI] cancel opp active transfer file notification
D/Tethering( 1032): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1032):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/BluetoothFtpReceiver( 6302): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6302): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6302): Ftp Service onStartCommand
V/BluetoothFtpService( 6302): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6302): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6302): Shutdown
V/BluetoothFtpService( 6302): successfully stopped ftp service
V/BluetoothSapReceiver( 6302): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6302): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6302): SapReceiver onReceive 
V/BluetoothSapReceiver( 6302): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6302):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 6302): Calling SAP service start service with action = null
V/BluetoothFtpService( 6302): Ftp Service onDestroy
V/BluetoothFtpService( 6302): Ftp Service closeService
I/ActivityManager( 1032): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7464 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6302): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6302): state: 13
V/BluetoothSapService( 6302): Stopping SAP server process
V/BluetoothSapService( 6302): Sap Service closeSapService in
V/BluetoothSapService( 6302): Close listen Socket : 
V/BluetoothSapService( 6302): Close rfcomm Socket : 
V/BluetoothSapService( 6302): Close sapd  Socket : 
V/BluetoothSapService( 6302): Sap Service closeSapService out
V/BluetoothSapService( 6302): Sap Service onDestroy
V/BluetoothSapService( 6302): Sap Service closeSapService in
V/BluetoothSapService( 6302): Close listen Socket : 
V/BluetoothSapService( 6302): Close rfcomm Socket : 
V/BluetoothSapService( 6302): Close sapd  Socket : 
V/BluetoothSapService( 6302): Sap Service closeSapService out
,I/wpa_supplicant( 6349): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1032): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1032):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,W/ResourcesManager( 7464): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager( 1032): Killing 6982:com.lge.clock/u0a10 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1032): failed to open /acct/uid_10010/pid_6982/cgroup.procs: No such file or directory
D/WifiOffDelayIfNotUsed( 1032): stopMonitoring
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
W/Settings( 7062): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1467): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [1]
D/WfdsService( 1961): Supplicant Connection state is changed : false
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : this is not treated
D/WfdsService( 1961): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1961): Set the WFDS Monitor: false
D/WfdsMonitor( 1961): WFDS Monitor is stopped
W/Settings( 1832): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 55142(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.558ms total 100.841ms
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ExternalStrings( 7440): load override strings
W/ExternalStrings( 7440): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7440): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7440): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7440): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7440): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7440): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7440): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7440): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7440): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7440): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7440): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7440): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7440): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7440): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7440): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7440): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7440): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7440): onCreate
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7257): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7257): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7257): [1] 5.onFinished: Scheduling replication attempt 1.
I/ActivityManager( 1032): Killing 7062:com.google.android.talk/u0a72 (adj 15): empty #17
,V/Signer  ( 7440): override build config not found
D/Signer  ( 7440): value of property debug is false
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7440): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7440): Create singleton instance
W/bt-btif ( 6302): ag scb idx 1 not allocated
E/bt-btif ( 6302): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6302): L2CAP - PSM: 0x0019 not found for deregistration
D/bt_hci_bdroid( 6302): cleanup
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6302): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6302): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6302): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6302): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6302): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6302): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6302): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6302): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6302): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6302): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_lpm  ( 6302): LPM is already off!!!
I/bt_userial_mct( 6302): exiting userial_read_thread
D/bt_userial_mct( 6302): Leaving userial_evt_read_thread()
D/bt_userial_mct( 6302): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6302): hw_epilog_process
D/bt_hci_bdroid( 6302): cleanup Finalizing cleanup
D/bt_userial_mct( 6302): userial_close
E/bt_userial_mct( 6302): pthread_join() FAILED result:3
I/bt_vendor( 6302): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/LGMDMWrapper( 7440): LG MDM library v4.0.0 is available on this device.
,W/libprocessgroup( 1032): failed to open /acct/uid_10072/pid_7062/cgroup.procs: No such file or directory
D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7440): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/bt_hci_bdroid( 6302): set_power 0
I/bt_vendor( 6302): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6302): bluetooth satus is on
I/bt_vendor( 6302): bt-vendor : resetting BT status
I/bt_vendor( 6302): Starting hciattach daemon
I/bt_vendor( 6302): try to set false
I/bt_vendor( 6302): Starting hciattach daemon
I/bt_vendor( 6302): try to set false
I/bt_vendor( 6302): cleanup
I/GKI_LINUX( 6302): gki_task task_id=0 [BTU] terminating
,I/ActivityManager( 1032): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7490 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 6850:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/ActivityThread( 7440): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1032): failed to open /acct/uid_10085/pid_6850/cgroup.procs: No such file or directory
I/GKI_LINUX( 6302): GKI_exit_task 0 done
,I/GKI_LINUX( 6302): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6302): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6302): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 6302): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6302): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/HeadsetStateMachine( 6302): Exit Disconnected: -1
D/BluetoothHeadset( 1868): Proxy object disconnected
D/BluetoothHeadset( 1868): Proxy object disconnected
D/BluetoothHeadset( 1868): Proxy object disconnected
D/BluetoothHeadset( 1032): Proxy object disconnected
D/AudioService( 1032): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 6302): Received stop request...Stopping profile...
D/A2dpStateMachine( 6302): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 6302): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 6302): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6302): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/BluetoothAdapterState( 6302): Stopping profile services that were post enabled
D/BluetoothA2dp( 1032): Proxy object disconnected
D/AudioService( 1032): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 6302): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/BluetoothInputDevice( 7410): Proxy object disconnected
D/HidProfile( 7410): Bluetooth service disconnected
D/HeadsetStateMachine( 6302): Unbinding service...
,D/HeadsetPhoneState( 6302): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6302): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6302): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6302): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6302): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6302): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6302): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 6302): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/PanService( 6302): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/BtGatt.DebugUtils( 6302): handleDebugAction() action=null
D/BluetoothPan( 7410): BluetoothPAN Proxy object disconnected
D/PanProfile( 7410): Bluetooth service disconnected
D/BtGatt.GattService( 6302): Received stop request...Stopping profile...
D/BtGatt.GattService( 6302): stop()
D/BtGatt.AdvertiseManager( 6302): advertise clients cleared
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
D/BluetoothMapService( 6302): Received stop request...Stopping profile...
D/BluetoothMapService( 6302): stop()
D/BluetoothMapEmailAppObserver( 6302): deinitObservers()
D/BluetoothMapEmailAppObserver( 6302): removeReceiver()
D/BluetoothAdapterService( 6302): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@335451fc
I/BluetoothA2dpServiceJni( 6302): cleanupNative
I/GKI_LINUX( 6302): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6302): GKI_exit_task 2 done
,I/GKI_LINUX( 6302): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6302): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6302): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6302): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6302): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6302): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6302): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6302): Cleaning up Bluetooth PAN callback object
D/BluetoothMap( 7410): Proxy object disconnected
D/MapProfile( 7410): Bluetooth service disconnected
V/BluetoothMapService( 6302): Handler(): got msg=4
D/BluetoothMapService( 6302): MAP Service closeService in
D/LGBluetoothMapAdapter( 6302): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6302): MAP Service closeService out
D/BluetoothMapService( 6302): cleanup()
D/BluetoothMapService( 6302): MAP Service closeService in
D/LGBluetoothMapAdapter( 6302): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6302): MAP Service closeService out
D/BluetoothAdapterState( 6302): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6302): Setting state to 10
I/BluetoothAdapterState( 6302): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1032): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothA2dp( 1032): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 6302): Entering OffState
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=false
D/BluetoothMap( 7410): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1032): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7410): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=false
D/BluetoothPbap( 7410): onBluetoothStateChange: up=false
D/BluetoothPan( 7410): onBluetoothStateChange on: false
D/BluetoothManagerService( 1032): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1032): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1032): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1032): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1032): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@201cfe22 mBinding = false
,D/BluetoothManagerService( 1032): Sending unbind request.
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothFeatureConfig( 7410): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7410): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7410): [BTUI] clear device connection state
D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1961): Message: 2
D/LGBluetoothAPIService( 1961): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@5fb4f4c mBinding = false
D/LGBluetoothAPIService( 1961): Sending unbind request.
W/ContextImpl( 7410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/[SystemUI]BluetoothHandler( 1467): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/GKI_LINUX( 6302): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6302): GKI_exit_task 1 done
I/GKI_LINUX( 6302): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6302): cleanupNative: return from cleanup
I/art     ( 6302): --- WEIRD: removing null entry 246
W/art     ( 6302): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6302): Cleaning up Bluetooth Service callback object
D/DockEventReceiver( 7410): finishStartingService: stopping service
D/BluetoothAdapter( 1467): 452356372: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1467): 452356372: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothSettingsDBObserver( 6302): [BTUI] unregister observer for LG device name DB
I/art     ( 6302): System.exit called, status: 0
I/AndroidRuntime( 6302): VM exiting with result code 0, cleanup skipped.
,V/AudioFlinger(  315): 6302 died, releasing its sessions
V/AudioFlinger(  315):  pid 1868 @ 0
V/AudioFlinger(  315):  pid 3319 @ 1
V/AudioFlinger(  315):  pid 3319 @ 2
,D/LGBluetoothUserBindClient( 7410): [BTUI] onServiceDisconnected
I/PCSuite ( 7490): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7490): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7490): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1032): Process com.android.bluetooth (pid 6302) has died
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,V/WiFiOffLoadBroadcast( 7410): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7410): LgDataFeature() Constructor: none
,D/LgDataFeature( 7410): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7410): MCCMNC not supported: null
D/BluetoothPermissionRequest( 7410): onReceive
,D/LGBluetoothUtils( 7410): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7410): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7410): return without doing reset settings.
I/ActivityManager( 1032): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7526 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6703:com.google.android.apps.books/u0a54 (adj 15): empty #17
D/LgDataFeature( 7440): LgDataFeature() Constructor: none
D/LgDataFeature( 7440): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1032): failed to open /acct/uid_10054/pid_6703/cgroup.procs: No such file or directory
,D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7440): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7490): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7490): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7490): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/ResourcesManager( 7526): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7526): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7526): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
V/WiFiOffLoadBroadcast( 7410): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 7526): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/WiFiOffLoadBroadcast( 7410): MCCMNC not supported: null
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7440): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7490): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7490): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7490): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7410): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7410): MCCMNC not supported: null
D/BluetoothAdapterApp( 7526): Loading JNI Library
D/QRemote ( 6491): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6491): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6491): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ContextImpl( 7440): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,D/BluetoothAdapterApp( 7526): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e67e4cd Instance Count = 1
I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7545 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/BluetoothAdapterApp( 7526): onCreate
D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/ProfileConfigQcom( 7526): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7526): Adding HeadsetService
D/ProfileConfigQcom( 7526): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7526): Adding A2dpService
D/ProfileConfigQcom( 7526): [BTUI] HidService is supported
D/ProfileConfigQcom( 7526): Adding HidService
D/ProfileConfigQcom( 7526): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7526): Adding HealthService
D/LGBluetoothFeatureConfig( 7526): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7526): [BTUI] PanService is supported
D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/ProfileConfigQcom( 7526): Adding PanService
D/ProfileConfigQcom( 7526): [BTUI] GattService is supported
D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/ProfileConfigQcom( 7526): Adding GattService
D/ProfileConfigQcom( 7526): [BTUI] BluetoothMapService is supported
D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/ProfileConfigQcom( 7526): Adding BluetoothMapService
D/ProfileConfigQcom( 7526): [BTUI] HeadsetClientService is NOT supported
D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/LGBluetoothOppAdapter( 7526): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/LGBluetoothUserBindClient( 7410): [BTUI] onServiceConnected
,D/SiteAdvisor( 7440): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
V/LGMDMManagerInternal( 7526): Create singleton instance
,D/PCSuite ( 7490): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7410): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7410): MCCMNC not supported: null
V/BluetoothFtpReceiver( 7526): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7526): [BTUI] checkServiceStart
D/UsbSettingsReceiver( 7410): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7410): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7410): [AUTORUN] sys.usb.state = ptp_only,adb
V/BluetoothSapReceiver( 7526): [BTUI] region:EU country:EU
,D/UsbSettingsReceiver( 7410): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/BluetoothSapReceiver( 7526): SapReceiver onReceive 
D/UsbSettingsReceiver( 7410): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothSapReceiver( 7526): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7526):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7464): [BTUI] STATE_OFF : reset connected device information EasySettings
D/AuthorizationBluetoothService( 2205): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/UsbSettingsControl( 7410): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7410): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7410): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7410): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7410): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7410): [AUTORUN] setTetherStatus() : status=false
W/FormManager( 7545): Network not available. Please check & try again.
,I/ActivityManager( 1032): Killing 7178:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_7178/cgroup.procs: No such file or directory
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4013): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/FormManager( 7545): Network unavailable.
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 7490): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7490): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7490): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/FormManager( 7545): Network unavailable.
V/WiFiOffLoadBroadcast( 7410): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7410): MCCMNC not supported: null
D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
W/FormManager( 7545): Network not available. Please check & try again.
V/FormManager( 7545): Network unavailable.
V/FormManager( 7545): Network unavailable.
,D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1032): Killing 7215:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_7215/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-2015051022] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-2015051012] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1032): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1032): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/Tethering( 1032): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5271): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7588 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NetworkMonitor( 5271): type=WIFI subType= reason=null isConnected=false
,W/ContextImpl( 7440): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1032): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1032): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1032): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7588): onCreate
W/AppUp4:DB( 7588):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7588):  setFingerPrint start
I/AppUp4:DB( 7588):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7588):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7588):  SDK version = 21
I/AppUp4:DB( 7588):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7588): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7588): onReceive
D/LgDataFeature( 7588): LgDataFeature() Constructor: none
D/LgDataFeature( 7588): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7588): Context : android.app.ReceiverRestrictedContext@2b1a52ef
D/AppUp4:CustFacade( 7588): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7588): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7588): begin check event
I/AppUp4:CustModeStarterReceiver( 7588): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7588): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7588): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7588): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7588): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1032): Killing 6721:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_6721/cgroup.procs: No such file or directory
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4013): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7626 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7626): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7626): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7626): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7626): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7626): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7626): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7626): LgDataFeature() Constructor: none
D/LgDataFeature( 7626): LgDataFeature() Constructor Done, null
,D/eas_req ( 7626): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 7626): JNI_OnLoad()
I/HubEmail( 7626): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7626): registerNatives()
I/HubEmail( 7626): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7626): registerNativeMethods()
I/HubEmail( 7626): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7626): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7545): Network unavailable.
V/FormManager( 7545): Network unavailable.
W/FormManager( 7545): Network not available. Please check & try again.
I/ActivityManager( 1032): Killing 7239:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/LgeMiscReceiver( 3319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3319): action = android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_7239/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3319): networkInfo.isConnected() = false
I/ActivityManager( 1032): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7664 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7682 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 6925:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/art     (  349): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 38.075ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 21.735ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 21.184ms
,W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_6925/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7700 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 7296:com.google.android.gms:car/u0a5 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_7296/cgroup.procs: No such file or directory
,I/art     ( 7700): Almond Protected OAT
,D/WeatherApplication( 7700): removeAccount
,D/WeatherApplication( 7700): Account.length = 0
,E/WeatherApplication( 7700): OPERATOR:OPEN
D/WeatherAncestor( 7700): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:17
,D/Weather.Utils( 7700): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7700): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7700): 2 : This is isUpdating : false
D/WeatherAncestor( 7700): connectivity changed - connection : true
,D/WeatherService( 7700): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7700): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7700): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7700): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7700): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7700): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:17
I/ActivityManager( 1032): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7718 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 7330:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/LGWifiP2pService( 1032): P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1032):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1032):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_7330/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7718): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7718): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7718): Loading: webviewchromium
,I/LibraryLoader( 7718): Time to load native libraries: 5 ms (timestamps 194-199)
I/LibraryLoader( 7718): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7718): Binding Chromium to main looper Looper (main, tid 1) {34824518}
,I/LibraryLoader( 7718): Expected native library version number "",actual native library version number ""
,I/chromium( 7718): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7718): Initializing chromium process, renderers=0
W/art     ( 7718): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7718): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7718): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7718): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  315): registerClient() client 0xb558a560, uid 10093
,W/AudioManagerAndroid( 7718): Requires BLUETOOTH permission
I/Adreno-EGL( 7718): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7718): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7718): Build Date: 12/12/14 금
I/Adreno-EGL( 7718): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7718): Remote Branch: 
I/Adreno-EGL( 7718): Local Patches: 
I/Adreno-EGL( 7718): Reconstruct Branch: 
,I/NSApplication( 7718): Starting up...
,I/ActivityManager( 1032): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7783 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 7257:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10044/pid_7257/cgroup.procs: No such file or directory
,W/ResourcesManager( 7783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2371): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2371): num queued entries: 0
I/iu.UploadsManager( 2371): num updated entries: 0
I/iu.SyncManager( 2371): NEXT; no task
D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7440): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7440): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7588): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7588): onReceive
,I/GLSActivity( 2205): [ac] getting account id
D/AppUp4:CustFacade( 7588): Context : android.app.ReceiverRestrictedContext@2b1a52ef
D/AppUp4:CustFacade( 7588): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7588): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7588): begin check event
I/AppUp4:CustModeStarterReceiver( 7588): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2205): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4013): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7626): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4013): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3319): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3319): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3319): networkInfo.isConnected() = false
W/Settings( 7626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherAncestor( 7700): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:19
D/Weather.Utils( 7700): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7700): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7700): 2 : This is isUpdating : false
D/WeatherAncestor( 7700): connectivity changed - connection : true
D/WeatherService( 7700): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30c9e085
,D/ForecastDataCache( 7700): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7700): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7700): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7700): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7700): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:58:19
W/FormManager( 7545): Network not available. Please check & try again.
V/FormManager( 7545): Network unavailable.
,V/FormManager( 7545): Network unavailable.
D/ChimeraCfgMgr( 2371): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 35771(1663KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.641ms total 113.870ms
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{3a19e531 type 2 when 351451 com.google.android.gms} when 351451
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 352834844712; DSPS: 11702544; Offset : -4312595130
,I/GAV4    ( 7718): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1032): Killing 7380:com.lge.lifetracker/u0a37 (adj 15): empty #17,
,W/libprocessgroup( 1032): failed to open /acct/uid_10037/pid_7380/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7847 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{37f6a36d type 0 when 1449683913411 com.android.vending} when 1449683913411
V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{d1cfba2 type 2 when 367287 android} when 367287
,D/Finsky  ( 7847): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7847): LgDataFeature() Constructor: none
D/LgDataFeature( 7847): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7847): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1032): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7896 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7847): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7847): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7896): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
V/DownloadManager( 3357): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
W/ResourcesManager( 7896): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3357): created cursor android.database.sqlite.SQLiteCursor@2f043cf4 on behalf of 7847
D/Finsky  ( 7847): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7847): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7847): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7847): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7896): VM with version 2.1.0 has multidex support
I/MultiDex( 7896): install
I/MultiDex( 7896): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7896): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,W/ActivityThread( 7896): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7896): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39862f78: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7896): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2205): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2205): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2371): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1032): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7935 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2371): Restart initialization of location
,W/ResourcesManager( 7935): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7935): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7935): VM with version 2.1.0 has multidex support
I/MultiDex( 7935): install
I/MultiDex( 7935): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 2205): Explicit concurrent mark sweep GC freed 17360(958KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 942us total 35.142ms
,V/JNIHelp ( 7935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/Finsky  ( 7847): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/ActivityThread( 7935): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7935): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39862f78: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7935): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2205): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2205): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2371): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 7935): callingUid 10005, callindPid: 7935
D/LocationInitializer( 2371): Restart initialization of location
,E/MDM     ( 1832): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1832): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1032): Killing 7120:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6491): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6491): android.os.DeadObjectException
W/System.err( 6491): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6491): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6491): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6491): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6491): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6491): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6491): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6491): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6491): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6491): android.os.DeadObjectException
W/System.err( 6491): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6491): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6491): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6491): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,W/System.err( 6491): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6491): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6491): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6491): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6491): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6491): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6491): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6491): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_7120/cgroup.procs: No such file or directory
W/ActivityManager( 1032): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6491): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6491): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1032): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7963 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6491): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{19065c67 type 0 when 1449683916801 com.android.vending} when 1449683916801
D/Finsky  ( 7847): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7847): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/UEI.SmartControl( 7963): Quickset Services start...
I/UEI.SmartControl( 7963): Manufacture = LGE
D/UEI.SmartControl( 7963): Id = LGNevo
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7963): File observer start...
E/UEI.SmartControl( 7963): IR Port is disabled: false
D/UEI.SmartControl( 7963): Starting file observer...
D/UEI.SmartControl( 7963): Extracting JNI libs...
D/UEI.SmartControl( 7963): --- this system supports 32-bit or 64-bit only
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7963): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7963): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7963): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/Finsky  ( 7847): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/UEI.SmartControl( 7963): --- Selecting new region: 6
,I/UEI.SmartControl( 7963): Model = LG-D855
D/UEI.SmartControl( 7963): QS Service created
I/UEI.SmartControl( 7963): Service initServices...
,D/UEI.SmartControl( 7963): QS start get config
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
D/UEI.SmartControl( 7963): Loading JNI Libs...
,I/UEI.SmartControl( 7963): Supports setup maps: true
,D/UEI.SmartControl( 7963): QS start statue = true Error code = 0
I/UEI.SmartControl( 7963): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7963): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7963): ### init IR Blaster...
D/serial_port( 7963): Configuring serial port
E/UEI.SmartControl( 7963): UEIBLaster setting for 616
I/UEI.SmartControl( 7963): Setting serial record hearder size = 2
I/UEI.SmartControl( 7963): configuring settings for MAXQ616
I/UEI.SmartControl( 7963): Get version...
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7963): serial port data available: 21
I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7963): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7963): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7963): QS saving settings...
D/UEI.SmartControl( 7963): IR Blaster version: 25672567
W/Finsky  ( 7847): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7847): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/UEI.SmartControl( 7963): serial port data available: 4
D/Finsky  ( 7847): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7847): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,W/ContextImpl( 7963): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7963): Services init done
D/UEI.SmartControl( 7963): QS Service init finished
D/UEI.SmartControl( 7963): QS Service version name: 2.1.91
D/UEI.SmartControl( 7963): QS Service version code: 201091
,I/UEI.SmartControl( 7963): Device manager: loading config....
D/UEI.SmartControl( 7963): ----------- loading internal config...
D/UEI.SmartControl( 7963): Service requested: Control
E/UEI.SmartControl( 7963): Loading SETTINGS...
D/UEI.SmartControl( 7963): Request IControl service: devices are loaded...
I/ActivityManager( 1032): Killing 6491:com.lge.qremote/u0a112 (adj 15): empty #17
,D/UEI.SmartControl( 7963): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7963): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7963): -----service ready thread exits
,W/libprocessgroup( 1032): failed to open /acct/uid_10112/pid_6491/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7963): Internal service binding...
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 372836796163; DSPS: 12357968; Offset : -4312596726
,I/ActivityManager( 1032): Killing 7464:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_7464/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Killing 7526:com.android.bluetooth/1002 (adj 15): empty #17
,D/LGBluetoothUserBindClient( 7410): [BTUI] onServiceDisconnected
,W/libprocessgroup( 1032): failed to open /acct/uid_1002/pid_7526/cgroup.procs: No such file or directory
W/ActivityManager( 1032): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
D/UEI.SmartControl( 7963): Internal timer expired: 1
,D/UEI.SmartControl( 7963): unbind internal service
D/UEI.SmartControl( 7963): Service.onUnbind: IControl
,D/UEI.SmartControl( 7963): Service.onDestroy
D/UEI.SmartControl( 7963): Lock is in USE false
D/UEI.SmartControl( 7963): unbind internal service
W/System.err( 7963): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@25e32f0b
W/System.err( 7963): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 7963): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 7963): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7963): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7963): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7963): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 7963): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 7963): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 7963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7963): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7963): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7963): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7963): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7963): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7963): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 7963): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@25e32f0b
D/serial_port( 7963): close(fd = 25)
I/UEI.SmartControl( 7963): Serial port is closed.
I/UEI.SmartControl( 7963): Serial port is closed.
D/UEI.SmartControl( 7963): Blaster closed
D/UEI.SmartControl( 7963): Shut down QS...
D/UEI.SmartControl( 7963): Stopping QS lib
D/UEI.SmartControl( 7963): QS lib stop result = true
D/UEI.SmartControl( 7963): Stopped QS lib
,D/UEI.SmartControl( 7963): Stopped file observer...
D/UEI.SmartControl( 7963): QS shutdown complete
I/ActivityManager( 1032): Start proc com.android.bluetooth for service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer: pid=8000 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,W/ResourcesManager( 8000): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 8000): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8000): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 8000): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 8000): Loading JNI Library
,D/BluetoothAdapterApp( 8000): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e67e4cd Instance Count = 1
,D/BluetoothAdapterApp( 8000): onCreate
D/ProfileConfigQcom( 8000): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 8000): Adding HeadsetService
,D/ProfileConfigQcom( 8000): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 8000): Adding A2dpService
,D/ProfileConfigQcom( 8000): [BTUI] HidService is supported
D/ProfileConfigQcom( 8000): Adding HidService
D/ProfileConfigQcom( 8000): [BTUI] HealthService is supported
D/ProfileConfigQcom( 8000): Adding HealthService
D/LGBluetoothFeatureConfig( 8000): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 8000): [BTUI] PanService is supported
D/ProfileConfigQcom( 8000): Adding PanService
D/ProfileConfigQcom( 8000): [BTUI] GattService is supported
D/ProfileConfigQcom( 8000): Adding GattService
D/ProfileConfigQcom( 8000): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 8000): Adding BluetoothMapService
D/ProfileConfigQcom( 8000): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothUserBindClient( 7410): [BTUI] onServiceConnected
I/ActivityManager( 1032): Killing 7490:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_7490/cgroup.procs: No such file or directory
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{372bf0a4 type 0 when 1449683937065 com.android.vending} when 1449683937065
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1032): Explicit concurrent mark sweep GC freed 25393(1079KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.875ms total 93.276ms
,D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 3.
I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 392839213655; DSPS: 13013407; Offset : -4312590227
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 412841153595; DSPS: 13668830; Offset : -4312572868
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{8224827 type 0 when 1449683957979 com.android.vending} when 1449683957979
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 4.
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 432843515098; DSPS: 14324268; Offset : -4312591736
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{2137d996 type 0 when 1449683992724 com.android.vending} when 1449683992724
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 452845541913; DSPS: 14979694; Offset : -4312579055
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,I/ActivityManager( 1032): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8097 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8097): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8097): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1a9878d0
D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
I/ActivityManager( 1032): Killing 7410:com.android.settings/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_7410/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 472847401540; DSPS: 15635115; Offset : -4312581156
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{32b7d446 type 0 when 1449684019882 com.android.vending} when 1449684019882
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7847): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
D/WifiController( 1032): battery changed pluggedType: 2
,D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 492849065440; DSPS: 16290530; Offset : -4312595593
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 512851162099; DSPS: 16945958; Offset : -4312574130
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 532853739904; DSPS: 17601403; Offset : -4312590371
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 552856182240; DSPS: 18256843; Offset : -4312589468
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 572858342075; DSPS: 18912274; Offset : -4312596250
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 592861888163; DSPS: 19567750; Offset : -4312590331
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 612865412634; DSPS: 20223225; Offset : -4312575225
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 632867314448; DSPS: 20878648; Offset : -4312596149
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 652869276056; DSPS: 21534072; Offset : -4312587588
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7847): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7847): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7847): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1413): Notification difference=198
,D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 7847): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 672871054121; DSPS: 22189490; Offset : -4312579568
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 692872885312; DSPS: 22844910; Offset : -4312579432
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 712874805616; DSPS: 23500333; Offset : -4312581840
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 732877254619; DSPS: 24155773; Offset : -4312574165
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 752881293414; DSPS: 24811266; Offset : -4312594234
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 772882984239; DSPS: 25466681; Offset : -4312581745
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 792884814908; DSPS: 26122101; Offset : -4312582235
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 812887266255; DSPS: 26777541; Offset : -4312572190
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 832889486664; DSPS: 27432974; Offset : -4312579591
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 852892218427; DSPS: 28088424; Offset : -4312594567
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 872894511232; DSPS: 28743859; Offset : -4312590450
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 892896464714; DSPS: 29399283; Offset : -4312590066
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 912897942519; DSPS: 30054691; Offset : -4312577053
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 932903757355; DSPS: 30710242; Offset : -4312591100
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 952905184535; DSPS: 31365649; Offset : -4312598194
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7847): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7847): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7847): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 7847): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 972907444996; DSPS: 32021083; Offset : -4312596138
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 992909686447; DSPS: 32676516; Offset : -4312582548
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1012911146648; DSPS: 33331924; Offset : -4312587192
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1032913403515; DSPS: 33987358; Offset : -4312588547
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1052915541059; DSPS: 34642788; Offset : -4312587363
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1072917420010; DSPS: 35298209; Offset : -4312569803
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1092919314325; DSPS: 35953632; Offset : -4312598147
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1112921360776; DSPS: 36609059; Offset : -4312596374
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1132922813373; DSPS: 37264466; Offset : -4312577999
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1152924759771; DSPS: 37919890; Offset : -4312584883
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,D/Finsky  ( 7847): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{32ed78df type 0 when 1449684529527 com.android.vending} when 1449684529527
D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7847): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2205): Explicit concurrent mark sweep GC freed 32002(1890KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 1.031ms total 38.647ms
,W/Finsky  ( 7847): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7847): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 7847): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7847): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7847): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1172926488409; DSPS: 38575307; Offset : -4312595720
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{2b578989 type 0 when 1449684725921 com.android.vending} when 1449684725921
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 1.
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1192928673089; DSPS: 39230738; Offset : -4312577919
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1212931126832; DSPS: 39886179; Offset : -4312596074
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{25e259c0 type 0 when 1449684755957 com.android.vending} when 1449684755957
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 26709(1126KB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 2.472ms total 97.814ms
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 2.
,I/UsageStatsService( 1032): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1232933179533; DSPS: 40541606; Offset : -4312587971
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{31ab8f33 type 0 when 1449684782026 com.android.vending} when 1449684782026
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 3.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1252935450202; DSPS: 41197040; Offset : -4312575577
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 7847): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7847): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7847): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 7847): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{20731677 type 0 when 1449684807071 com.android.vending} when 1449684807071
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 4.
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1272936886965; DSPS: 41852448; Offset : -4312602408
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1292939468884; DSPS: 42507892; Offset : -4312585190
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{259f618b type 0 when 1449684840942 com.android.vending} when 1449684840942
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1312941705179; DSPS: 43163325; Offset : -4312576756
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{2b04af0a type 0 when 1449684864778 com.android.vending} when 1449684864778
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7847): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7847): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7847): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1332943569807; DSPS: 43818747; Offset : -4312602344
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1352945659331; DSPS: 44474175; Offset : -4312589967
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=324515891, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,I/DigitalAppWidgetProvider( 8097): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2578): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 8097): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1a9878d0
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=324515891 [*alarm*], flags=0x0
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1372947900729; DSPS: 45129608; Offset : -4312576170
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1392949948636; DSPS: 45785035; Offset : -4312573071
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1412951937485; DSPS: 46440461; Offset : -4312598330
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1432954333519; DSPS: 47095899; Offset : -4312582537
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1452956544449; DSPS: 47751332; Offset : -4312599390
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1472958783347; DSPS: 48406765; Offset : -4312588458
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1492961079485; DSPS: 49062200; Offset : -4312580956
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1512963054791; DSPS: 49717625; Offset : -4312589449
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1532964967074; DSPS: 50373048; Offset : -4312599722
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1552967519670; DSPS: 51028491; Offset : -4312580137
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 7847): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7847): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7847): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 7847): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1572969471955; DSPS: 51683915; Offset : -4312581055
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1592972065541; DSPS: 52339360; Offset : -4312581332
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1612973980273; DSPS: 52994783; Offset : -4312589208
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1632975919224; DSPS: 53650206; Offset : -4312573047
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1652978189216; DSPS: 54305641; Offset : -4312591638
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1672980436136; DSPS: 54961074; Offset : -4312572449
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1692982898576; DSPS: 55616515; Offset : -4312582011
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1712985249193; DSPS: 56271952; Offset : -4312581249
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1732987182988; DSPS: 56927375; Offset : -4312570190
,I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1467): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
D/WifiController( 1032): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1467): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1467): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4013): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1752989771782; DSPS: 57582820; Offset : -4312575260
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1772991975994; DSPS: 58238253; Offset : -4312599040
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1792993929736; DSPS: 58893677; Offset : -4312598268
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1812996066342; DSPS: 59549107; Offset : -4312597866
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1467): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1467): On Skip Timer : true
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1832997817689; DSPS: 60204524; Offset : -4312586072
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1852999843566; DSPS: 60859950; Offset : -4312574303
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1032): Prepared write state in 11ms
,I/GLSUser ( 2205): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2205): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2205): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2205): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2205): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,W/GLSActivity( 2205): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2205): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2205): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2205): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2205): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1413): Notification difference=198
,D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{b57d7b7 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/PlayEventLogger( 7847): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 7847): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 7847): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 7847): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 7847): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ProcessStatsService( 1032): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-35-30.bin
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1873001709080; DSPS: 61515372; Offset : -4312600879
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1893003281416; DSPS: 62170783; Offset : -4312584939
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1913005231981; DSPS: 62826207; Offset : -4312587395
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1933007604629; DSPS: 63481645; Offset : -4312595171
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
,I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1953009472278; DSPS: 64137066; Offset : -4312589198
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1973011915344; DSPS: 64792506; Offset : -4312587564
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 1993014207160; DSPS: 65447941; Offset : -4312584436
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2013015950381; DSPS: 66103358; Offset : -4312580743
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2033017713966; DSPS: 66758776; Offset : -4312587256
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2053019766824; DSPS: 67414203; Offset : -4312579102
,I/[SystemUI]TimeTickManager( 1467): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1467): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1467): called onTimeUpdated()
I/[SystemUI]Clock( 1467): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
I/[SystemUI]DateView( 1467): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1467): handleTimeUpdate
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2073022180983; DSPS: 68069642; Offset : -4312575675
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2093024166235; DSPS: 68725067; Offset : -4312574144
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 2113026892061; DSPS: 69380517; Offset : -4312595057
,TIME-OUT KILL (timeout was 1800000ms)
```
