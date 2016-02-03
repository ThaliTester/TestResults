#### Test 57924002a578a80_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 107764725782; DSPS: 3671918; Offset : -4303763623
D/AndroidRuntime( 5997): 
D/AndroidRuntime( 5997): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5997): CheckJNI is OFF
D/AndroidRuntime( 5997): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1034): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1916): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1034): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{267dd7e0 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1034): setTaskToReturnTo : TaskRecord{267dd7e0 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1034): AppWindowTokenEx init.. 
E/GBMv2   (  332): DFP En is all cleared set to be enabled
I/ActivityManager( 1034): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6016 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5997): Shutting down VM
V/ActivityManager( 1034): Display changed displayId=0
D/DSDPConnection( 1827): Display #0 changed.
D/SplitWindowPolicy( 1916): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1916): topRunningActivity=ActivityInfo{1ec35d07 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1916): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1916): topRunningActivity=ActivityInfo{19f0ee34 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6016): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6016): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6016): Loading: webviewchromium
I/LibraryLoader( 6016): Time to load native libraries: 5 ms (timestamps 8527-8532)
I/LibraryLoader( 6016): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6016): Binding Chromium to main looper Looper (main, tid 1) {22041150}
I/LibraryLoader( 6016): Expected native library version number "",actual native library version number ""
I/chromium( 6016): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6016): Initializing chromium process, renderers=0
W/art     ( 6016): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6016): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6016): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6016): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6016): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  314): registerClient() client 0xb1427f60, uid 10311
I/Adreno-EGL( 6016): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6016): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6016): Build Date: 12/12/14 금
I/Adreno-EGL( 6016): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6016): Remote Branch: 
I/Adreno-EGL( 6016): Local Patches: 
I/Adreno-EGL( 6016): Reconstruct Branch: 
,D/BluetoothManagerService( 1034): Message: 20
D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b63356a:true
D/BluetoothAdapter( 6016): 753004361: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6016): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6016): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6016): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6016): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6016): CordovaWebView is running on device made by: LGE
,W/art     ( 6016): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6016): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6016): Render dirty regions requested: true
I/OpenGLRenderer( 6016): Initialized EGL, version 1.4
D/OpenGLRenderer( 6016): Enabling debug mode 0
,D/Atlas   ( 6016): Validating map...
,W/ActivityManager( 1034): Activity pause timeout for ActivityRecord{129b5a99 u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1034): check instance of lgWin Window{220570d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6016): LgDataFeature() Constructor: none
,D/LgDataFeature( 6016): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1034): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1458): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1034): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1034): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1034): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3b80ea1f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1034): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6016): Timeline: Activity_idle id: android.os.BinderProxy@a083cb9 time:108954
,I/ActivityManager( 1034): Displayed com.test.thalitest/.MainActivity: +625ms (total +729ms)
I/Timeline( 1034): Timeline: Activity_windows_visible id: ActivityRecord{129b5a99 u0 com.test.thalitest/.MainActivity t4} time:108958
D/JsMessageQueue( 6016): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6016): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6016): 
,I/chromium( 6016): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6016): 
,D/jxcore_app_log( 6016): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435212672
,I/chromium( 6016): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  332): DFP En is all cleared set to be enabled
E/GBMv2   (  332): Set value is all cleared set the max
I/GBMv2   (  332): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6016): Initializing JXcore engine
W/jxcore-log( 6016): JXcore engine is ready
,W/Thread-683( 6084): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[6144]" dev="sockfs" ino=6144 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-683( 6084): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-683( 6084): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10405]" dev="sockfs" ino=10405 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-683( 6084): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-683( 6084): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[29902]" dev="sockfs" ino=29902 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6016): Starting JXcore engine
,W/jxcore-log( 6016): Platform android
W/jxcore-log( 6016): 
W/jxcore-log( 6016): Process ARCH arm
W/jxcore-log( 6016): 
,I/jxcore-log( 6016): JXcore Cordova bridge is ready!
I/jxcore-log( 6016): 
,W/jxcore-log( 6016): JXcore engine is started
I/jxcore-log( 6016): Toggling radios to true
I/jxcore-log( 6016): 
,D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1034): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1034): Message: 1
D/BluetoothManagerService( 1034): MESSAGE_ENABLE: mBluetooth = null
,D/LocationManagerService( 1034): getAllProviders()=[passive, gps, network]
D/WifiService( 1034): New client listening to asynchronous messages
D/Ulp_jni ( 1034): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1034): JNI:system_update. Event-4
I/ActivityManager( 1034): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6087 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1034): setWifiEnabled: true pid=6016, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1034): setWifiEnabled: true pid=6016, uid=10311
E/WifiService( 1034): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine( 1034):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1034): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1034): disconnect pid=6016, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1034): reconnect pid=6016, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6016): Radios toggled
I/jxcore-log( 6016): 
I/jxcore-log( 6016): My device name is: LGE-LG-D855
I/jxcore-log( 6016): 
E/WifiUtil( 1034): wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1034): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1034): wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1034): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1034): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1034): unknown target_country: EU , set to default
E/WifiHW  ( 1034): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1034): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1034): gEnableBmps=1
,D/LocationManagerService( 1034): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1034): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1034): JNI:system_update. Event-4
,W/ResourcesManager( 6087): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6087): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6087): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 6087): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6087): Loading JNI Library
,D/BluetoothAdapterApp( 6087): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@372d2ae4 Instance Count = 1
,D/BluetoothAdapterApp( 6087): onCreate
D/SoftapController(  310): Softap fwReload - Ok
,D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring down wlan0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/Tethering( 1034): sendTetherStateChangedBroadcast 1, 0, 0
D/CommandListener(  310): Clearing all IP addresses on wlan0
D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Tethering( 1034): InitialState.processMessage what=4
D/ProfileConfigQcom( 6087): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6087): Adding HeadsetService
D/ProfileConfigQcom( 6087): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6087): Adding A2dpService
D/ProfileConfigQcom( 6087): [BTUI] HidService is supported
D/ProfileConfigQcom( 6087): Adding HidService
D/ProfileConfigQcom( 6087): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6087): Adding HealthService
D/LGBluetoothFeatureConfig( 6087): isSupportPan() :  mTargetOp=OPEN
E/WifiHW  ( 1034): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,D/ProfileConfigQcom( 6087): [BTUI] PanService is supported
D/ProfileConfigQcom( 6087): Adding PanService
D/ProfileConfigQcom( 6087): [BTUI] GattService is supported
D/ProfileConfigQcom( 6087): Adding GattService
D/ProfileConfigQcom( 6087): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6087): Adding BluetoothMapService
D/ProfileConfigQcom( 6087): [BTUI] HeadsetClientService is NOT supported
E/WifiStateMachine( 1034): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1034): useWiFiOffloading() : false
E/WifiStateMachine( 1034): CONFIG_LGE_WLAN_PATH : true
I/ActivityManager( 1034): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6121 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1034): sendTetherStateChangedBroadcast 0, 0, 0
W/wpa_supplicant( 6120): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6120): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WfdStateTracker( 1916): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServerServiceExt( 1034): WIFI_STATE_CHANGED_ACTION [2]
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1034): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1034): connecting to supplicant
,I/wpa_supplicant( 6120): Successfully initialized wpa_supplicant
D/BluetoothManagerService( 1034): Message: 20
D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33b48717:true
,D/BluetoothAdapterState( 6087): make
I/wpa_supplicant( 6120): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6120): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
I/LGFMServiceAdapter( 6087): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6087): init
I/BluetoothAdapterState( 6087): Entering OffState
I/bte_conf( 6087): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6087): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6087): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6087): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6087): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6087): get_profile_interface socket
I/bluedroid-qcom( 6087): get_profile_interface map_client
I/GKI_LINUX( 6087): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6145): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6145): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/lge_bdaddr_loader( 6145): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6145): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6145): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1034): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/lge_bdaddr_loader( 6145): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): Message: 40
D/BluetoothManagerService( 1034): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6087): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6087): Name is: G3-1
D/BluetoothManagerService( 1034): Bluetooth Adapter name changed to G3-1
I/bluedroid-qcom( 6087): config_hci_snoop_log
D/BluetoothManagerService( 1034): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1034): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1034): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6145): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6145): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6087): Create singleton instance
W/ResourcesManager( 6121): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/wpa_supplicant( 6120): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterState( 6087): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 6087): Setting state to 11
I/BluetoothAdapterState( 6087): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1034): Message: 60
D/BluetoothManagerService( 1034): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1034): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6087): classInitNative: succeeds
D/LGBluetoothAPIService( 1916): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1458): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6087): make
I/BluetoothBondStateMachine( 6087): StableState(): Entering Off State
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/LGBluetoothServiceAdapter( 6087): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/LGBluetoothServiceAdapter( 6087): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6087): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6087): File transfer profiles supported!!
,D/BluetoothHeadset( 1034): Proxy object connected
E/BluetoothAdapterService( 6087): File transfer profiles supported!!
D/BluetoothHeadset( 1827): Proxy object connected
D/HeadsetService( 6087): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6087): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6087): Version 1.6
D/BluetoothHeadset( 1827): Proxy object connected
D/BluetoothHeadset( 1827): Proxy object connected
D/LGBluetoothFeatureConfig( 6087): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6087): classInitNative: succeeds
D/HeadsetStateMachine( 6087): make
E/BluetoothAdapterService( 6087): File transfer profiles supported!!
E/BluetoothAdapterService( 6087): File transfer profiles supported!!
,E/BluetoothAdapterService( 6087): File transfer profiles supported!!
E/BluetoothAdapterService( 6087): File transfer profiles supported!!
E/BluetoothAdapterService( 6087): File transfer profiles supported!!
,D/LgDataFeature( 6087): LgDataFeature() Constructor: none
D/LgDataFeature( 6087): LgDataFeature() Constructor Done, null
D/HeadsetStateMachine( 6087): max_hf_connections = 1
I/bluedroid-qcom( 6087): get_profile_interface handsfree
V/ToneGenerator( 6087): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  314): registerClient() client 0xb57c2220, uid 1002
V/AudioPolicyManager(  314): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  314): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  314): getOutput() returns output 2
V/AudioSystem( 6087): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  314): registerClient() client 0xb1433c70, pid 6087
V/AudioSystem(  314): ioConfigChanged() event 0, ioHandle 2
V/ToneGenerator( 6087): Create Track: 0xb4928a80
V/AudioSystem(  314): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 6087): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6087): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  314): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  314): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  314): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  314): getOutput() returns output 2
V/AudioSystem( 1034): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6087): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 1034): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6087): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6087): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1458): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1458): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1827): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1827): ioConfigChanged() opening already existing output! 2
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AudioSystem( 2152): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2152): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManager(  314): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioSystem( 3303): ioConfigChanged() event 0, ioHandle 2
V/AudioPolicyManager(  314): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  314): AudioPolicyManagerEx: getOutputForDevice
V/AudioSystem( 3303): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManagerEx(  314): getOutput() returns output 2
V/AudioSystem( 6087): getLatency() output 2, latency 50
V/AudioSystem(  314): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6087): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6087): createTrack_l() output 2 afLatency 50
V/AudioSystem(  314): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1034): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1034): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1458): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1827): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1458): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioSystem( 1827): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  314): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  314): createTrack() lSessionId: 16
V/AudioSystem( 2152): ioConfigCh,anged() event 0, ioHandle 4
V/AudioSystem( 2152): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3303): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3303): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6087): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6087): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioTrack( 6087): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  314): acquiring 16 from 6087, for 6087
V/AudioFlinger(  314):  added new entry for 16
V/ToneGenerator( 6087): ToneGenerator INIT OK, time: 111918
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/HeadsetStateMachine( 6087): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6087): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6087): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6087): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  314): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6087
D/audio_hw_primary(  314): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  314): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: exit
V/voice   (  314): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  314): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  314): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  314): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  314): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  314): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  314): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6087): ToneGenerator destructor
V/ToneGenerator( 6087): stopTone
V/ToneGenerator( 6087): Delete Track: 0xb4928a80
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
V/AudioTrack( 6087): ~AudioTrack, releasing session id from 6087 on behalf of 6087
V/AudioPolicyService(  314): AudioCommandThread() adding release output 2
V/AudioPolicyService(  314): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  314): releasing 16 from 6087 for 6087
V/AudioFlinger(  314):  decremented refcount to 0
V/AudioPolicyService(  314): AudioCommandThread() waking up
V/AudioFlinger(  314): purging stale effects
V/AudioPolicyService(  314): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  314): releaseOutput() 2
V/AudioPolicyService(  314): AudioCommandThread() going to sleep
V/AudioFlinger(  314): PlaybackThread::Track destructor
V/AudioFlinger(  314): removeClient_l() pid 6087, calling pid 314
,D/BluetoothA2dp( 1034): Proxy object connected
D/A2dpService( 6087): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6087): classInitNative: succeeds
V/Avrcp   ( 6087): make
D/Avrcp   ( 6087): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6087): get_profile_interface avrcp
W/Process ( 1034): Unable to open /proc/6151/status
V/LGMDMManager( 6087): Create singleton instance
V/AudioManager( 6087): registerRemoteController: size of Media player list: 0
I/BluetoothAdapterState( 6087): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/AudioManager( 6087): No RCC entry present to update
E/RemoteController( 6087): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothAvrcpQcomServiceJni( 6087): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6087): initQcomNative: succeeds
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6121): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] sys.usb.state = ptp_only,adb
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] [+] updateMediaPlayerInfo
D/UsbSettingsReceiver( 6121): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/wpa_supplicant( 6120): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1034):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
E/WifiStateMachine( 1034):  SupplicantStartingState CMD_START_DRIVER 0 0
,E/WifiStateMachine( 1034):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1034):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1034):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1034):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1034): doString: [DRIVER MACADDR]
D/WifiMonitor( 1034): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1034):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1034): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1034): setPowerSaveActivated(false)
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1034): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1034): useWiFiOffloading() : false
E/WifiStateMachine( 1034): CONFIG_LGE_WLAN_PATH : true
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/UsbSettingsControl( 6121): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6121): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6121): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1034): doBoolean: SET update_config 1
,D/WifiNative-wlan0( 1034): SET update_config 1: returned true
D/WifiConfigStore( 1034): Loading config and enabling all networks 
D/WifiNative-wlan0( 1034): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1034):    returned network id / ssid / bssid / flags 0	NG700	any	
I/ActivityManager( 1034): Killing 5663:com.android.defcontainer/u0a4 (adj 15): empty #17
E/WifiConfigStore( 1034): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore( 1034): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1034): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/libprocessgroup( 1034): failed to open /acct/uid_10004/pid_5663/cgroup.procs: No such file or directory
D/WfdService( 1916): Waiting for WifiP2p enabling
I/WifiServerServiceExt( 1034): WIFI_STATE_CHANGED_ACTION [3]
W/ActivityManager( 1034): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6121): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6121): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6121): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6121): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1034): batteryPsActivateMsgHandler : state:0 event:3
D/WifiStateMachine( 1034): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1034): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1034): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1034): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1034): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1034): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1034): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1034): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1034): SET device_type 10-0050F204-5: returned true
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6087): classInitNative
I/BluetoothA2dpServiceJni( 6087): classInitNative: succeeds
D/A2dpStateMachine( 6087): make
I/bluedroid-qcom( 6087): get_profile_interface a2dp
I/GKI_LINUX( 6087): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6087): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6087): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/A2dpStateMachine( 6087): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6087): classInitNative: succeeds
D/HidService( 6087): Received start request. Starting profile...
I/bluedroid-qcom( 6087): get_profile_interface hidhost
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
I/BluetoothHealthServiceJni( 6087): classInitNative: succeeds
D/HealthService( 6087): Received start request. Starting profile...
I/ActivityManager( 1034): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6159 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/WifiStateMachine( 1034): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1034): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1034): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1034): Setting external_sim to 1
D/WifiNative-wlan0( 1034): doBoolean: SET external_sim 1
I/bluedroid-qcom( 6087): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6087): classInitNative: succeeds
D/WifiNative-wlan0( 1034): SET external_sim 1: returned true
I/WifiNative-HAL( 1034): startHal
E/wifi    ( 1034): getStaticLongField sWifiHalHandle 0x988f08dc
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
E/WifiHAL ( 1034): Could not connect handle
D/WfdsService( 1916): Supplicant Connection state is changed : true
D/wifi    ( 1034): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x3021b6
I/WifiNative-HAL( 1034): Could not start hal
D/WifiStateMachine( 1034): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1034): startHal
E/wifi    ( 1034): getStaticLongField sWifiHalHandle 0x988f085c
D/WfdsService( 1916): DefaultState - WIFI_SUPPLICANT_CONNECTED
E/WifiHAL ( 1034): Could not connect handle
D/wifi    ( 1034): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601fce
D/WfdsService( 1916): Set the WFDS Monitor: true
I/WifiNative-HAL( 1034): Could not start hal
D/WifiNative-wlan0( 1034): doBoolean: STA_AUTOCONNECT 1
I/BluetoothPanServiceJni( 6087): classInitNative(L105): succeeds
D/WfdsMonitor( 1916): WfdsMonitorThread create
D/WfdsMonitor( 1916): WFDS Monitor is created and started
D/WfdsService( 1916): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1034): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1034): DRIVER BTCOEXSCAN-STOP: returned true
D/PanService( 6087): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6087): initializeNative(L110): pan
I/bluedroid-qcom( 6087): get_profile_interface pan
E/CtrlSupplicant( 1916): Access OK "@android:wpa_wlan0"
D/WifiHS20( 1034): hidePasspointNotification off =false
D/WifiNative-wlan0( 1034): doBoolean: DRIVER RXFILTER-STOP
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1034): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1034): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1034): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1034): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6120): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1034): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1034): DRIVER RXFILTER-START: returned true
I/LGBluetoothPanAdapter( 6087): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
E/WifiNative: ( 1034): [112,143,101 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1034): doBoolean: RECONNECT
I/BtGatt.JNI( 6087): classInitNative(L901): classInitNative: Success!
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1034): RECONNECT: returned true
D/WifiNative-wlan0( 1034): doString: [STATUS]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1034):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/WifiNative-wlan0( 1034): SET ps 1: returned true
D/LGWifiP2pService( 1034): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  310): Setting iface cfg
D/CommandListener(  310): Trying to bring up p2p0
D/WifiScanningService( 1034): SCAN_AVAILABLE : 3
D/BtGatt.DebugUtils( 6087): handleDebugAction() action=null
D/RttService( 1034): SCAN_AVAILABLE : 3
D/RttService( 1034): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1034): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1034): P2pEnablingState
D/BtGatt.GattService( 6087): Received start request. Starting profile...
D/LGWifiP2pService( 1034): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.GattService( 6087): start()
I/bluedroid-qcom( 6087): get_profile_interface gatt
D/WifiScanningService( 1034): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2p socket connection successful
I/WifiNative-HAL( 1034): startHal
D/LGWifiP2pService( 1034): P2pEnabledState
E/wifi    ( 1034): getStaticLongField sWifiHalHandle 0x94e6799c
E/WifiHAL ( 1034): Could not connect handle
D/wifi    ( 1034): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x2022be
D/BtGatt.AdvertiseManager( 6087): advertise manager created
I/WifiNative-HAL( 1034): Could not start hal
D/LGWifiP2pService( 1034): sending p2p connection changed broadcast
E/WifiScanningService( 1034): could not start HAL
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1034): doBoolean: SET persistent_reconnect 1
E/CtrlSupplicant( 1916): Succeed to open control connection
D/WifiNative-p2p0( 1034): SET persistent_reconnect 1: returned true
D/WifiService( 1034): New client listening to asynchronous messages
D/WifiNative-p2p0( 1034): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1034): SET device_name G3-1: returned true
D/LGWifiP2pService( 1034): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1034): before postfix = G3-1
V/WfdStateTracker( 1916): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiServerServiceExt( 1034): postfix byte check : 4
D/LGWifiP2pService( 1034): after postfix = G3-1
D/WifiNative-p2p0( 1034): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1034): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1034): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1034): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1034): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1034): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1034): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1034): p2pGetDeviceAddress
D/WifiNative-HAL( 1034): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/WfdsService( 1916): WifiP2pState is changed : true
E/WifiStateMachine( 1034):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WfdsService( 1916): Receive the WFDS_ENABLE Method
D/WfdsService( 1916): Set the WFDS Monitor: true
D/WfdsService( 1916): Connected to the supplicant for wfds
D/WfdsJNI ( 1916): doCommand: WFDS_SET TRUE
E/WifiStateMachine( 1034):  DisconnectedState CMD_START_DRIVER 0 0
I/wpa_supplicant( 6120): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/WifiStateMachine( 1034):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1034):  DisconnectedState what:132106 1 0
D/WfdsJNI ( 1916): doCommand: WFDS_GET_MAC_ADDRESS
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
I/wpa_supplicant( 6120): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
E/WifiStateMachine( 1034):  ConnectModeState what:132106 1 0
D/WfdsJNI ( 1916): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/WifiStateMachine( 1034):  DriverStartedState what:132106 1 0
D/WfdsService( 1916): selectPreferredScanChannel [36]
I/WifiServerServiceExt( 1034): setWifiDualbandAPConnection band : 1
D/WfdsService( 1916): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/wpa_supplicant( 6120): nWIFIDualbandAPConnection: 1
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
I/LGBluetoothMapAdapter( 6087): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6087): BluetoothMapBinder()
D/BluetoothMapService( 6087): Received start request. Starting profile...
D/BluetoothMapService( 6087): start()
E/CtrlSupplicant( 1916): Succeed to open monitor connection
D/WfdsMonitor( 1916): Supplicant connection established
D/WfdsService( 1916): Received the Event that WfdsMonitor is connected to supplicant
D/BluetoothMapEmailSettingsLoader( 6087): Found 0 applications
D/BluetoothMapEmailAppObserver( 6087): createReceiver()
D/WfdsService( 1916): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/LGWifiP2pService( 1034): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1034): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1034): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1034): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1034): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1034): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1034):    returned OK
D/WifiNative-p2p0( 1034): doBoolean: SAVE_CONFIG
D/BluetoothMapEmailAppObserver( 6087): initObservers()
D/BluetoothMapEmailAppObserver( 6087): getEnabledAccountItems()
D/WifiNative-p2p0( 1034): SAVE_CONFIG: returned false
D/LGWifiP2pService( 1034): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1034): InactiveState
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1034): doBoolean: DRIVER COUNTRY CZ
D/WfdsService( 1916): isConnected: false
I/WfdStateTracker( 1916): handleP2pThisDeviceChanged
D/WfdsService( 1916): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1916): Update P2p Interface State: 3
D/WifiNative-p2p0( 1034): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1034): InactiveState{ when=-9ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-9ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/LGWifiP2pService( 1034): DefaultState{ when=-9ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): InactiveState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
I/wpa_supplicant( 6120): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/HeadsetStateMachine( 6087): Proxy object connected
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1916): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1916): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1916): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1034): DefaultState{ when=-9ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1034):  DisconnectedState what:132096 -100 0
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1034): No p2p device connected
D/LGWifiP2pService( 1034): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothHfpAdapter( 6087): [BTUI] queryPhoneState
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothHfpAdapter( 6087): Try to query the phonestate on bind
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1034):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1034):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1034): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6120): disconnect_rssi_lvl: -100
D/BluetoothPhoneService.BluetoothLTECall( 1827):  call mBluetoothHeadset.phoneStateChanged()
E/WifiStateMachine( 1034):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1034):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
W/WfdsService( 1916): DefaultState - msg [9441285] is not handled
E/WifiStateMachine( 1034):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1034): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
W/BluetoothHeadset( 1827): Proxy not attached to service
I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/BluetoothHeadset( 1827): java.lang.Throwable
D/BluetoothHeadset( 1827): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1827): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1827): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1827): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1827): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1827): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1827): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1827): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/wpa_supplicant( 6120): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1034): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1034):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiStateMachine( 1034):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1034): InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1034): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1034):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETBAND 0
D/WfdsMonitor( 1916): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1916): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/BluetoothAdapterService( 6087): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6087): Disconnected process message: 10, size: 0
V/BluetoothPbapReceiver( 6087): PbapReceiver onReceive 
D/WifiNative-wlan0( 1034): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1034): BSS_FLUSH 0: returned true
V/BluetoothPbapReceiver( 6087): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/WifiNative-wlan0( 1034): doBoolean: SCAN
V/BluetoothPbapReceiver( 6087): ***********state = 11
D/WifiNative-wlan0( 1034): SCAN: returned false
D/HeadsetPhoneState( 6087): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6087): Disconnected process message: 11, size: 0
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=112184  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/BluetoothAdapterService( 6087): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6087): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6087): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6087): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6087): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6087): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6087): Handler(): got msg=1
I/ActivityManager( 1034): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6183 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/BluetoothAdapterState( 6087): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6087): enable
I/bt_hci_bdroid( 6087): init
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=112209  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/GKI_LINUX( 6087): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6087): btu_task pending for preload complete event
E/WifiStateMachine( 1034):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1034):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1034):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1034):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1034):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/bt_vendor( 6087): bt-vendor : init
I/bt_vendor( 6087): bt-vendor : get_bt_soc_type
E/bt_vendor( 6087): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6087): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6087): userial_init
D/bt_hci_bdroid( 6087): set_power 1
I/bt_vendor( 6087): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6087): Starting hciattach daemon
I/bt_vendor( 6087): try to set true
W/sh      ( 6195): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6195): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateSCANNING
I/qcom-bluetooth( 6199): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
I/ActivityManager( 1034): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/FormManager( 6159): Network not available. Please check & try again.
I/qcom-bluetooth( 6228): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6230): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
V/FormManager( 6159): Network unavailable.
I/qcom-bluetooth( 6235): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
V/FormManager( 6159): Network unavailable.
I/ActivityManager( 1034): Killing 5784:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/qcom-bluetooth( 6236): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6239): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6240): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/PCSuite ( 6209): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/libmdmdetect( 6242): ESOC framework not supported
E/Diag_Lib( 6242):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/bthci_qcomm_linux( 6242): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6242): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6242): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6242): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6242): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6242): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6242): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1034): failed to open /acct/uid_10008/pid_5784/cgroup.procs: No such file or directory
E/ActivityThread( 6183): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6183): No ProfileInfo entries
I/LG Account v2.2( 6183): isEnabled: false
I/Feature ( 6183): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6183): [Lifetracker]Country: EU
I/Feature ( 6183): [Lifetracker]Operator: OPEN
I/Feature ( 6183): [Lifetracker]Ranking support: false
I/Feature ( 6183): [Lifetracker]Comfort support: false
I/Feature ( 6183): [Lifetracker]Accessory: true
I/Feature ( 6183): [Lifetracker]Health device: true
I/Feature ( 6183): [Lifetracker]Extra Pedometer: false
I/Feature ( 6183): [Lifetracker]Blood glucose device: false
I/Feature ( 6183): [Lifetracker]Device Number: 3
I/ActivityManager( 1034): Killing 5459:com.lge.appbox.client/u0a11 (adj 15): empty #17
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1034): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1034): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
E/wpa_supplicant( 6120): USIM:  scard_init function
W/WifiMonitor( 1034): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6120): Trying to associate with SSID 'NG700'
I/rmt_storage(  307): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  307): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  307): wakelock acquired: 1, error no: 42
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1034):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1034):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1034):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1034):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1034): startHal
E/wifi    ( 1034): getStaticLongField sWifiHalHandle 0x988f08cc
E/WifiHAL ( 1034): Could not connect handle
D/wifi    ( 1034): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x60206a
I/WifiNative-HAL( 1034): Could not start hal
D/WifiNative-wlan0( 1034): doString: [BSS RANGE=0- MASK=0x21987]
W/libprocessgroup( 1034): failed to open /acct/uid_10011/pid_5459/cgroup.procs: No such file or directory
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=112474  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiService( 1034): New client listening to asynchronous messages
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=112486  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateASSOCIATING
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  307): 
D/LgDataFeature( 6121): LgDataFeature() Constructor: none
D/LgDataFeature( 6121): LgDataFeature() Constructor Done, null
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/rmt_storage(  307): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  891): [IMS_FATAL]| 3347 | 910 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WiFiOffLoadUpdatePriority( 6121): remove : truetruetrue
E/WifiStateMachine( 1034):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1034):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1034):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6121): remove1
V/WiFiOffLoadSharedPrefsUtils( 6121): save remove
D/WiFiOffLoadBroadcast( 6121): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6121): S: false, R: false
E/WifiStateMachine( 1034):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1034):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6121): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6121): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6121): private wpa: "NG700" 300
D/WifiServiceImplEx( 1034): addOrUpdateNetwork pid=6121, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1034):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1034):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1034):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1034):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1034): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1034): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1034): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1034): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1034): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1034): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1034): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1034): will read network variables netId=0
E/WifiConfigStore( 1034): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1034):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6121):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6121): configuration updated: 0
E/WifiStateMachine( 1034):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6121): configuration saved: true
D/BluetoothPermissionRequest( 6121): onReceive
D/LGBluetoothFeatureConfig( 6121):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1034): Message: 20
D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b34c43d:true
I/ActivityManager( 1034): Killing 5487:com.android.contacts/u0a19 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6121): return without doing reset settings.
D/LGBluetoothOppAdapter( 6087): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/libprocessgroup( 1034): failed to open /acct/uid_10019/pid_5487/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6087): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6087): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6087): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6087): SapReceiver onReceive 
V/BluetoothSapReceiver( 6087): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6087):  Bluetooth Adapter state = 11
I/wpa_supplicant( 6120): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1034): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=112819  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=112821  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1034):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112822
E/WifiStateMachine( 1034):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112823
E/WifiStateMachine( 1034):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112823
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112823
E/WifiStateMachine( 1034):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=112824
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=112824  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6120): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/ActivityManager( 1034): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1034): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiMonitor( 1034): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1034): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1034): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=112842  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=112843  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=112844  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateASSOCIATED
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1034):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112856
E/WifiStateMachine( 1034):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=112856
D/WifiNative-wlan0( 1034): doString: [STATUS]
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1034):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1034): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PCSuite ( 6209): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/WifiServerServiceExt( 1034): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1034): setKeepAlivePacketInterval msec : 60
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{1f1a378a type 0 when 1454460157728 com.android.vending} when 1454460157728
W/ResourcesManager( 6254): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/FormManager( 6159): Network not available. Please check & try again.
D/ConnectivityService( 1034): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1034): Got NetworkAgent Messenger
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1034): NetworkAgent connected
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2051): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
V/FormManager( 6159): Network unavailable.
V/FormManager( 6159): Network unavailable.
D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/CommandListener(  310): Setting iface cfg
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
E/WifiStateMachine( 1034): Start Dhcp Watchdog 1
E/WifiStateMachine( 1034):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=112952  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=112952  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=112953  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/WifiStateMachine( 1034):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1034): StoppedState
E/WifiStateMachine( 1034):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1034): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): WaitBeforeStartState
E/WifiStateMachine( 1034):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1034):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=112959  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1034):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=112960  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=112960  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1034):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1533749575] from screen [on:0 period:-1533749575]
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533749574]
I/WifiNative-HAL( 1034): startHal
E/wifi    ( 1034): getStaticLongField sWifiHalHandle 0x988f08bc
E/WifiHAL ( 1034): Could not connect handle
D/wifi    ( 1034): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x10233a
I/WifiNative-HAL( 1034): Could not start hal
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
I/PCSuite ( 6209): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 3975): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/ConnectivityService( 1034): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/PCSuite ( 6209): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6209): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1034):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
I/ActivityManager( 1034): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6285 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6285): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 0
,D/WifiNative-wlan0( 1034): SET ps 0: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1034): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1034): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateCOMPLETED
D/LGWifiP2pService( 1034): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@aedc163 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@aedc163 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1034): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
I/art     ( 1034): Explicit concurrent mark sweep GC freed 62337(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.281ms total 110.291ms
D/DhcpStateMachine( 1034): DHCP Start wake lock is acquired.
D/QRemote ( 6285): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 6285): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6285): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6285): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6285): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6285): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6285): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6285): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6285): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5916): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5916): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5916): Boot Receiver Return
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6285): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6121): Not supported operator for automatic switch
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
,D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6121): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6121): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6121): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6121): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6121): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6285): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/DhcpStateMachine( 1034): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1034): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1034): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6309): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6309): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/ContextImpl( 4205): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/dhcpcd  ( 6309): version 5.5.6 starting
,E/dhcpcd  ( 6309): get_duid: m
D/dhcpcd  ( 6309): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6309): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/LgDataFeature( 6285): LgDataFeature() Constructor: none
D/LgDataFeature( 6285): LgDataFeature() Constructor Done, null
,V/SoundPool( 6285): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6285): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6285): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6285): doLoad: loading sample sampleID=1
V/SoundPool( 6285): Start decode
V/MediaPlayer[Native]( 6285): decode(31, 10857164, 17813)
V/MediaPlayerService(  314): decode(24, 10857164, 17813)
,W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
,V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb1432680, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
I/QRemote ( 6285): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
V/AwesomePlayer(  314): onPrepareAsyncEvent() 
V/AwesomePlayer(  314): initAudioDecoder() 
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AwesomePlayer(  314): getUseOffload() = 0 
V/OMXCodec(  314): OMXCodec::Create
V/OMXCodec(  314): findMatchingCodecs()
V/OMXCodec(  314): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  314): matchingCodecs.size()=1
V/OMXCodec(  314): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  314): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  314): LG Codec Adapter start
V/OMXCodec(  314): OMXCodec Createtor
V/OMXCodec(  314): setComponentRole
V/OMXCodec(  314): configureCodec protected=0
V/LGCodecAdapter(  314): called getLGCodecSpecificData
V/LGCodecOSAL(  314): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMSG
V/LGCodecOSAL(  314): Not support LGCodec
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  314): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  314): Could not offload audio decode, try pcm offload
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  314): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  314): init()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  314): allocateBuffers
V/OMXCodec(  314): allocateBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434a10 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434b50 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ec0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f60 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb15200b0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated, buffer 0xb1520100 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb1432680, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb1432680, 1, 0, 0)
V/AudioCache(  314): prepared
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): start
V/AwesomePlayer(  314): play_l() 
V/AwesomePlayer(  314): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  314): createAudioPlayer_l
V/AwesomePlayer(  314): seekAudioIfNecessary_l() 
V/AwesomePlayer(  314): startAudioPlayer_l() 
D/AudioPlayer(  314): start of Playback, useOffload 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  314): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978304
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978464
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974941360
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974941440
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb15200b0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f60 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ec0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb1003f10 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb1432680, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb1247000, 4096)
,V/AudioCache(  314): memcpy(0xaf406000, 0xb1247000, 4096)
,D/QRemote ( 6285): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf407000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf408000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf409000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf40a000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf40b000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf40c000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf40d000, 0xb1247000, 4096)
D/UEI.SmartControl( 5896): QS Service created
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf40e000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf40f000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf410000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf411000, 0xb1247000, 4096)
E/QC-QMI  ( 6242): qmi_client [6242] 13: failed to locate client data
E/QC-QMI  (  466): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  466): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf412000, 0xb1247000, 4096)
,V/LGMDMManager( 6285): Create singleton instance
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf413000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf414000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf415000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf416000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf417000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf418000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf419000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf41a000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf41b000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf41c000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf41d000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf41e000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf41f000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf420000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf421000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf422000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf423000, 0xb1247000, 4096)
D/dhcpcd  ( 6309): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6309): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6309): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf424000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf425000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf426000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf427000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf428000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf429000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf42a000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf42b000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf42c000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf42d000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf42e000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf42f000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf430000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf431000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf432000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf433000, 0xb1247000, 4096)
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf434000, 0xb1247000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf435000, 0xb1247000, 4096)
V/OMXCodec(  314):, [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf436000, 0xb1247000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  314): write(0xb1247000, 4096)
V/AudioCache(  314): memcpy(0xaf437000, 0xb1247000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb1247000, 280)
V/AudioCache(  314): memcpy(0xaf438000, 0xb1247000, 280)
,I/dhcpcd  ( 6309): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 6309): wlan0: sending REQUEST (xid 0x46b6a883), next in 4.90 seconds
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb1432680, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): wait - success
V/AudioCache(  314): notify(0xb1432680, 7, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb1432680, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434b50 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434a10 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1003f10 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434ec0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f60 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb15200b0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  314): AudioPlayer releasing audio source
D/AudioPlayer(  314): AudioPlayer done releasing audio source
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): ~AwesomePlayer call
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/SoundPool( 6285): close(31)
V/SoundPool( 6285): pointer = 0x9fe5d000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 5896): Service initServices...
D/UEI.SmartControl( 5896): QS start get config
D/QRemote ( 6285): [Re,moteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1237
,I/qcom-bluetooth( 6327): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6328): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/bt_vendor( 6087): bluetooth satus is on
D/bt_hci_bdroid( 6087): preload
D/bt_userial_mct( 6087): userial_open(port:0)
I/bt_vendor( 6087): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 6087): Done intiailizing UART
,I/bt_vendor( 6087): Done intiailizing UART
I/bt_userial_mct( 6087): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6087): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6087): btu_task received preload complete event
D/bt_userial_mct( 6087): Entering userial_read_thread()
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x0003
I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/        ( 6087): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6087): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6087): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6087): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6087): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6087): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6087): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6087): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6087): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6087): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6087): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6087): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6087): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6087): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6087): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6087): BTE_InitTraceLevels -- TRC_BTIF
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4868): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4868): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4868): [1] 5.onFinished: Scheduling replication attempt 1.
,W/bt-btm  ( 6087): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6087): BTM_SecRegister:p_cb_info->p_le_callback == 0xa0169061 
E/bt-btm  ( 6087): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0169061 
E/bt-btif ( 6087): Calling BTA_HhEnable
,W/bt-l2cap( 6087): btif_storage_get_adapter_property service_mask
E/bt-btif ( 6087): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6087): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1034): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1034): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6087): Name is: G3-1
D/BluetoothAdapterProperties( 6087): Scan Mode:20
D/BluetoothAdapterProperties( 6087): Discoverable Timeout:120
D/bt_hci_bdroid( 6087): postload
D/bt_hci_bdroid( 6087): Used up Tx Cmd credits
W/bt-l2cap( 6087): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bte_conf( 6087): Device ID record 1 : primary
D/bte_conf( 6087):   vendorId            = 00c4
D/bte_conf( 6087):   vendorIdSource      = 0001
D/bte_conf( 6087):   product             = 13a1
,D/bte_conf( 6087):   version             = 1000
D/bte_conf( 6087):   clientExecutableURL = 
D/bte_conf( 6087):   serviceDescription  = 
D/bte_conf( 6087):   documentationURL    = 
D/bte_conf( 6087): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6087): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6087): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6087): ScanMode =  20
D/BluetoothAdapterProperties( 6087): State =  11
D/BluetoothAdapterProperties( 6087): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6087): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6087): Setting state to 12
I/BluetoothAdapterState( 6087): Bluetooth adapter state changed: 11-> 12
W/sh      ( 6332): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1034): Message: 60
D/BluetoothManagerService( 1034): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1034): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/btif_config_util( 6087): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/BluetoothAdapterState( 6087): Entering On State
W/sh      ( 6332): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothHeadset( 1827): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6087): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6087): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6087): [BTUI]         local_name: G3-1
D/BluetoothHeadset( 1034): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1034): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1827): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 6087): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1827): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1034): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1034): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1916): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
W/bt-smp  ( 6087): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6087): Plain text(LSB ~ MSB) = 48 53 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6087): Encrypted text(LSB ~ MSB) = e9 bd f0 65 b9 74 34 e9 6f e7 73 ce 50 17 91 a1 
W/bt-btm  ( 6087): Stopping oneshot timer
D/bt_hci_bdroid( 6087): Used up Tx Cmd credits
D/LGBluetoothAPIService( 1916): Message: 1
D/bt_hci_bdroid( 6087): Used up Tx Cmd credits
D/LGBluetoothAPIService( 1916): MESSAGE_BOOT_COMPLETED
D/bt_hci_bdroid( 6087): Used up Tx Cmd credits
D/bt_hci_bdroid( 6087): Used up Tx Cmd credits
E/bt_mct  ( 6087): hci lib postload completed
,I/[SystemUI]BluetoothHandler( 1458): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothManagerService( 1034): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1034): Message: 40
D/BluetoothManagerService( 1034): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/LGBluetoothAPIService( 1916): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6087): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6087): STATE_ON
W/bt-smp  ( 6087): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6087): Plain text(LSB ~ MSB) = 97 a0 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6087): Encrypted text(LSB ~ MSB) = b0 54 19 ed 6b 6a cd a5 1d 1a 00 66 2a 35 2a 67 
W/bt-btm  ( 6087): Stopping oneshot timer
,W/ContextImpl( 6121): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,W/bt-smp  ( 6087): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6087): Plain text(LSB ~ MSB) = 28 30 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6087): Encrypted text(LSB ~ MSB) = 5c f7 f4 3f fc a3 c6 17 49 33 f9 f4 62 d4 80 24 
W/bt-btm  ( 6087): Stopping oneshot timer
D/LGBluetoothAPIServer( 6087): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6087): [BTUI] onBind()
D/LGBluetoothAPIService( 1916): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1916): Message: 100
D/LGBluetoothAPIService( 1916): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/bt-smp  ( 6087): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6087): Plain text(LSB ~ MSB) = a5 37 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6087): Encrypted text(LSB ~ MSB) = f7 76 07 f9 d2 65 8c 37 ed fa 5d 6b 46 68 47 97 
W/bt-btm  ( 6087): Stopping oneshot timer
I/qcom-bt-wlan-coex( 6339): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
V/BluetoothPbapService( 6087): Pbap Service onCreate
V/BluetoothPbapService( 6087): Starting PBAP service
W/bt-smp  ( 6087): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6087): Plain text(LSB ~ MSB) = 45 4f 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6087): Encrypted text(LSB ~ MSB) = fd 33 c4 d0 55 60 59 ff 06 85 b0 8f 42 98 c3 cb 
W/bt-btm  ( 6087): Stopping oneshot timer
D/LGBluetoothPbapAdapter( 6087): [BTUI] getInstance : create
V/BluetoothPbapService( 6087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6087): state: 12
V/BluetoothMapService( 6087): Handler(): got msg=1
D/BluetoothMapMasInstance( 6087): Map Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6087): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6087): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6087): ***********state = 12
,D/BluetoothMapMasInstance( 6087): MAS initSocket()
D/BluetoothMapMasInstance( 6087):   masId = 00
D/BluetoothMapMasInstance( 6087):   msgTypes = 0e
D/BluetoothMapMasInstance( 6087):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6087):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 6087): Handler(): got msg=1
V/BluetoothPbapService( 6087): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6087): Pbap Service initSocket
D/LGBluetoothDeviceModeControllManager( 6087): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6087): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 6087): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6087): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothPbapService( 6087): Succeed to create listening socket 
V/BluetoothPbapService( 6087): Accepting socket connection...
D/LGBluetoothServiceAdapter( 6087): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothMapMasInstance( 6087): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6087): Accepting socket connection...
D/LocalBluetoothProfileManager( 6121): Adding local A2DP profile
D/BluetoothManagerService( 1034): Message: 30
D/LocalBluetoothProfileManager( 6121): Adding local HEADSET profile
,D/BluetoothManagerService( 1034): Message: 30
D/BluetoothManagerService( 1034): Message: 30
D/BluetoothManagerService( 1034): Message: 30
D/LocalBluetoothProfileManager( 6121): Adding local MAP profile
D/BluetoothMap( 6121): Create BluetoothMap proxy object
D/BluetoothManagerService( 1034): Message: 30
D/BluetoothManagerService( 1034): Message: 30
,D/LocalBluetoothProfileManager( 6121): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6087): Pbap Service onBind
D/LGBluetoothUserBindClient( 6121): [BTUI] initUserBindClient
W/ContextImpl( 6121): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6121): finishStartingService: stopping service
D/BluetoothA2dp( 6121): Proxy object connected
D/A2dpProfile( 6121): Bluetooth service connected
,D/BluetoothHeadset( 6121): Proxy object connected
D/HeadsetProfile( 6121): Bluetooth service connected
,D/BluetoothInputDevice( 6121): Proxy object connected
D/HidProfile( 6121): Bluetooth service connected
D/BluetoothPan( 6121): BluetoothPAN Proxy object connected
D/PanProfile( 6121): Bluetooth service connected
D/BluetoothMap( 6121): Proxy object connected
D/MapProfile( 6121): Bluetooth service connected
D/BluetoothMap( 6121): getConnectedDevices()
V/BluetoothMapService( 6087): getConnectedDevices()
D/BluetoothPbap( 6121): Proxy object connected
D/PbapServerProfile( 6121): Bluetooth service connected
D/LGBluetoothUserBindClient( 6121): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6121): onReceive
D/LGBluetoothFeatureConfig( 6121): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6121): [BTUI] FileNotFound: readProperty
,D/LGBluetoothResetSettingReceiver( 6121): return without doing reset settings.
V/BluetoothOppReceiver( 6087): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
D/BluetoothAdapterProperties( 6087): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6087): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
I/LGBluetoothOppAdapter( 6087): [BTUI] startOppService()
D/BluetoothAdapterProperties( 6087): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6087): getDeviceMode  deviceMode 0
V/BluetoothOppManager( 6087): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6087): isPrivacyLogsEnabled : true
V/BtOppService( 6087): onCreate
,V/BluetoothOppNotification( 6087): send message
V/BtOppService( 6087): Starting RfcommListener
D/BluetoothOppPreference( 6087): Dumping Names:  
D/BluetoothOppPreference( 6087): {}
D/BluetoothOppPreference( 6087): Dumping Channels:  
D/BluetoothOppPreference( 6087): {}
V/BtOppService( 6087): onStartCommand
V/BtOppService( 6087): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6087): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6087): BluetoothFtpReceiver Start Service
V/BtOppService( 6087): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 6087): new notify threadi!
,V/BtOppService( 6087): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6087): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@fed14d1 on behalf of 
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@2eefbb36 on behalf of 
V/BluetoothOppNotification( 6087): send delay message
V/BtOppService( 6087): start RfcommListener
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@8e15a37 on behalf of 
V/BluetoothOppNotification( 6087): mUpdateCompleteNotification = true
V/BtOppService( 6087): RfcommListener started
V/BtOppRfcommListener( 6087): Starting RFCOMM listener....
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6087): getBluetoothService() called with no BluetoothManagerCallback
,D/LGBluetoothServiceAdapter( 6087): [BTUI] createSocketChannel FD=80 mFd=75
V/BtOppRfcommListener( 6087): Started RFCOMM listener....
I/BtOppRfcommListener( 6087): Accept thread started.
V/BtOppRfcommListener( 6087): Accepting connection...
V/BtOppService( 6087): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@2efa5ba4 on behalf of 
V/BluetoothOppNotification( 6087): update too frequent, put in queue
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
V/BluetoothFtpService( 6087): Ftp Service onCreate
I/BluetoothFtpService( 6087): Ftp Service onCreate
V/BluetoothFtpService( 6087): Ftp Service onStartCommand
V/BluetoothFtpService( 6087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6087): Starting Listening on sockets
V/BtOppService( 6087): ContentObserver received notification
V/BluetoothSapReceiver( 6087): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6087): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6087): SapReceiver onReceive 
V/BluetoothSapReceiver( 6087): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BtOppService( 6087): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothSapReceiver( 6087):  Bluetooth Adapter state = 12
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothSapReceiver( 6087): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6087): ContentObserver received notification
V/BluetoothFtpService( 6087): Handler(): got msg=1
V/BluetoothFtpService( 6087): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6087): Ftp Service initSocket
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@397454c2 on behalf of 
V/BluetoothOppNotification( 6087): update too frequent, put in queue
V/BtOppService( 6087): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@386762d3 on behalf of 
W/BluetoothAdapter( 6087): getBluetoothService() called with no BluetoothManagerCallback
D/AuthorizationBluetoothService( 2051): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGBluetoothServiceAdapter( 6087): [BTUI] createSocketChannel FD=81 mFd=80
V/BluetoothFtpService( 6087): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6087): Run Accept thread
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@6538e10 on behalf of 
V/BluetoothOppNotification( 6087): update too frequent, put in queue
,V/BtOppService( 6087): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6087): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6087): outbound notification was removed.
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@173c8d09 on behalf of 
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
V/BluetoothSapService( 6087): Sap Service onCreate
V/BluetoothOppNotification( 6087): inbound: succ-0  fail-0
V/BluetoothSapService( 6087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6087): state: 12
V/BluetoothSapService( 6087): Starting SAP server process
V/BluetoothSapService( 6087): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6087): Sap Service initRfcommSocket
V/BluetoothOppNotification( 6087): inbound notification was removed.
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
W/BluetoothAdapter( 6087): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@1797f0c5 on behalf of 
D/LGBluetoothServiceAdapter( 6087): [BTUI] createSocketChannel FD=83 mFd=81
V/BluetoothSapService( 6087): Succeed to create listening socket 
,W/sapd    ( 6355): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6355): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapService( 6087): Accepting socket connection...
V/BT_SAP  ( 6355): Event pipe created
V/BT_SAP  ( 6355): create_server_socket qcom.sap.server
V/BT_SAP  ( 6355): created socket fd 6
I/UEI.SmartControl( 5896): Supports setup maps: true
,D/UEI.SmartControl( 5896): QS start statue = true Error code = 0
I/UEI.SmartControl( 5896): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5896): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5896): ### init IR Blaster...
D/serial_port( 5896): Configuring serial port
E/UEI.SmartControl( 5896): UEIBLaster setting for 616
I/UEI.SmartControl( 5896): Setting serial record hearder size = 2
I/UEI.SmartControl( 5896): configuring settings for MAXQ616
I/UEI.SmartControl( 5896): Get version...
D/UEI.SmartControl( 5896): serial port data available: 21
,D/UEI.SmartControl( 5896): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5896): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 5896): QS saving settings...
D/UEI.SmartControl( 5896): IR Blaster version: 25672567
,D/UEI.SmartControl( 5896): serial port data available: 4
,I/UEI.SmartControl( 5896): Device manager: loading config....
,D/UEI.SmartControl( 5896): ----------- loading internal config...
W/ContextImpl( 5896): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5896): Services init done
D/UEI.SmartControl( 5896): QS Service init finished
E/UEI.SmartControl( 5896): Loading SETTINGS...
D/UEI.SmartControl( 5896): QS Service version name: 2.1.91
D/UEI.SmartControl( 5896): QS Service version code: 201091
D/UEI.SmartControl( 5896): Service requested: Control
D/UEI.SmartControl( 5896): Internal service binding...
I/QRemote ( 6285): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5896): ------ IControl API: 11
D/UEI.SmartControl( 5896): File observer start...
,E/UEI.SmartControl( 5896): IR Port is disabled: false
D/UEI.SmartControl( 5896): Starting file observer...
I/UEI.SmartControl( 5896): Registering callback...
I/UEI.SmartControl( 5896): ------ IControl API: 19
D/UEI.SmartControl( 5896): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5896): Registering Services Ready callback...
I/UEI.SmartControl( 5896): Notify AllClients services are ready: 0
,I/QRemote ( 6285): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6285): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6285): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 5896): -----service ready thread exits
D/QRemote ( 6285): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6285): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5896): ------ IControl API: 8
D/QRemote ( 6285): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6285): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6285): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6285): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6285): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6285): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6285): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6285): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454460164716]
D/QRemote ( 6285): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1034): Killing 5511:com.android.gallery3d/u0a27 (adj 15): empty #17
D/QRemote ( 6285): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1034): Killing 5813:com.lge.email/u0a23 (adj 15): empty #18
,W/libprocessgroup( 1034): failed to open /acct/uid_10027/pid_5511/cgroup.procs: No such file or directory
,W/libprocessgroup( 1034): failed to open /acct/uid_10023/pid_5813/cgroup.procs: No such file or directory
,V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,V/BluetoothOppNotification( 6087): new notify threadi!
V/BluetoothOppNotification( 6087): send delay message
,V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,I/dhcpcd  ( 6309): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@146bba1a on behalf of 
V/BluetoothOppNotification( 6087): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@eae594b on behalf of 
V/BluetoothOppNotification( 6087): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6087): outbound notification was removed.
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@3a730f28 on behalf of 
V/BluetoothOppNotification( 6087): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6087): inbound notification was removed.
V/BluetoothOppProvider( 6087): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6087): created cursor android.database.sqlite.SQLiteCursor@128bd441 on behalf of 
I/dhcpcd  ( 6309): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6309): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6309): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6309): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6309): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6309): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6309): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6309): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1034):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/CloudHub( 2152): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19978
,D/DhcpStateMachine( 1034): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1034): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1034): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1034): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1034): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1034): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper( 1034): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1034):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1034):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1034): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/DhcpStateMachine( 1034): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1034): RunningState
D/WifiNative-wlan0( 1034): SET ps 1: returned true
,D/ConnectivityService( 1034): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1034):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1034): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1034): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1034): Adding iface wlan0 to network 100
D/WifiHS20( 1034): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1916): handleWifiStateChangedEvent: 1
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1034): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1034): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = true, mWifiLevel = 2
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1034): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1034): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1034): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService( 1034): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1034): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1034): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1034): Setting Dns servers for network 100 to [/192.168.1.1]
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1034): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1034): currentScore = 0, newScore = 20
D/ConnectivityService( 1034):    accepting network in place of null
D/ConnectivityService( 1034): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1827): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1827):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1034): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1034): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1034): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1034): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1034): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1034): Sending msg: 5 arg1:0 arg2:1
D/ConnectivityService( 1034): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/ConnectivityService( 1034): validation of new default Network = false
D/ConnectivityService( 1034): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1034): enableDataServiceNotify 
D/DSQN    ( 1034): start dsqn bin
D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,W/dsqn    ( 6406): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6406): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6842 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524290
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
E/DSQN    ( 6406): DSQN ssw
V/NetworkPolicy( 1034): [LG_RESTRICTED] checkMobilePolicy_type()
,D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  310): res_queryN name = europe.pool.ntp.org succeed
D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6209): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6209): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/LocSvc_java( 1034): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1034): NTP server returned: 1454460165963 (Wed Feb 03 01:42:45 GMT+01:00 2016) reference: 115263 certainty: 15 system time offset: -108
D/LocSvc_java( 1034): Sending msg: 10 arg1:0 arg2:1
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6285): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6285): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6285): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6209): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/LGDataListener(  310): argv[0]=dsqncommand
D/LGDataListener(  310): argv[1]=wlan0
D/LGDataListener(  310): argv[2]=1
D/LGDataListener(  310): notifyDSQN DSQN STARTMONITOR wlan0 1
D/PCSuite ( 6209): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/DSQN    ( 1034): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1034): start to monitor internet connection
V/WiFiOffLoadBroadcast( 6121): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6121): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6285): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6285): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 00:42:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454460166102], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454460166081]}
I/QRemote ( 6285): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Validated
D/ConnectivityService( 1034): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1034): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1827): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1827):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533746568] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1533746568] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6016): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6016): 
,I/jxcore-log( 6016): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6016): 
,I/jxcore-log( 6016): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6016): 
,I/jxcore-log( 6016): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6016): 
I/jxcore-log( 6016): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6016): 
,V/WifiInternetCheck( 1034): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1034): MasterInitialState.processMessage what=3
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5086): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/libc-netbsd(  310): res_queryN name = 2.android.pool.ntp.org succeed
,D/AlarmManagerService( 1034): Setting time of day to sec=1454460168
,W/AlarmManagerService( 1034): Unable to set rtc to 1454460168: Invalid argument
I/NetworkMonitor( 5235): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LIA_Informant_Tips_DateChangeManager( 2681): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2681): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-03 01:42:48...... Request
I/LIA_Informant_Tips_LogTracer( 2681): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 164, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2681): DateInfo : SmartTips Total Working Day Count = 164
D/LIA_Informant_Tips_DateChangeManager( 2681): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 2681): DateInfo : Last Date Check Time = 2016-02-03 01:42:48
,I/[SystemUI]Clock( 1458): onReceive = android.intent.action.TIME_SET
I/SecureClockService( 1916): Intent.ACTION_TIME_CHANGED 
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/LgeClockWidgetControlView( 1458): time changed, timezoneChanged : false
,W/ActivityManager( 1034): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 2008): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=3 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2008): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
I/[LGHome]LGCalendarIcon( 2008): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1034): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6437 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/GoogleURLConnFactory( 2051): Using platform SSLCertificateSocketFactory
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,I/ActivityManager( 1034): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6459 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AppUp4:AppBoxCP( 6437): onCreate
W/AppUp4:DB( 6437):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6437):  setFingerPrint start
I/AppUp4:DB( 6437):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6437):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6437):  SDK version = 21
I/AppUp4:DB( 6437):  beforefinger == newfinger no write in DB
I/ActivityManager( 1034): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6476 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AppUp4:AppBoxApplication( 6437): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6437): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6437): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6437): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6437): [onReceive] request level :IDLE....
I/art     (  336): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 208us total 10.162ms
I/AppUp4:CustModeStarterReceiver( 6437): onReceive
I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.992ms
I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 9.024ms
,W/ResourcesManager( 6476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6437): LgDataFeature() Constructor: none
D/LgDataFeature( 6437): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6437): Context : android.app.ReceiverRestrictedContext@e91504e
D/AppUp4:CustFacade( 6437): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6437): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 6437): begin check event
I/AppUp4:CustModeStarterReceiver( 6437): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6437): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6437): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6437): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6437): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1034): Killing 5534:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10080/pid_5534/cgroup.procs: No such file or directory
,D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ReaderUtils( 6459): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,I/ActivityManager( 1034): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6500 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppConfig( 6476): Total System Memory = 2995761152
D/LGDMClient( 3975): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/SystemHelper( 6476): region [EU], country [EU], operator [OPEN], sub-operator []
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3975): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3325): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3325): DownloadService onCreate
I/DownloadManager( 3325): in removeSpuriousFiles
V/DownloadManager( 3325): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3325): created cursor android.database.sqlite.SQLiteCursor@3c48074f on behalf of 3325
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3325): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3325): in trimDatabase
V/DownloadManager( 3325): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3325): created cursor android.database.sqlite.SQLiteCursor@1fca9be5 on behalf of 3325
I/art     ( 2051): Explicit concurrent mark sweep GC freed 21452(1234KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 996us total 44.477ms
,I/ActivityManager( 1034): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6526 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3325): DownloadService onStartCommand
V/DownloadManager( 3325): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3325): created cursor android.database.sqlite.SQLiteCursor@30a7c96b on behalf of 3325
V/DownloadManager( 3325): processing inserted download 1
V/DownloadManager( 3325): processing inserted download 4
,E/GpsLocationProvider( 1034): No APN found to select.
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 3975): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3325): processing inserted download 7
W/GAV2    ( 6459): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LGDMClient( 3975): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 3975): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3325): processing inserted download 8
I/BooksApp( 6459): Created application version: 3.2.35 (30235)
W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6526): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/DownloadManager( 3325): processing inserted download 9
V/DownloadManager( 3325): processing inserted download 10
V/DownloadManager( 3325): processing inserted download 16
V/DownloadManager( 3325): processing inserted download 17
V/DownloadManager( 3325): processing inserted download 18
V/DownloadManager( 3325): processing inserted download 21
V/DownloadManager( 3325): processing inserted download 22
W/DriveInitializer( 2321): Background init thread started
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2321): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,D/UEI.SmartControl( 5896): Internal timer expired: 4
D/UEI.SmartControl( 5896): unbind internal service
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 43391(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.499ms total 74.480ms
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2888] from screen [on:0 period:-1533743672] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533743671] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/serial_port( 5896): close(fd = 24)
,V/DownloadManager( 3325): DownloadService onDestroy
,I/LGEmail ( 6526): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/UEI.SmartControl( 5896): Serial port is closed.
,D/LGEmail ( 6526): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2321): Background init thread ended
I/BooksSync( 6459): Starting books sync
,D/DelayedSyncController( 6500): Delaying sync.
I/ActivityManager( 1034): Killing 5844:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/ResourceType( 6526): No package identifier when getting value for resource number 0x00000000
W/libprocessgroup( 1034): failed to open /acct/uid_10061/pid_5844/cgroup.procs: No such file or directory
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2051): Vacuum at: now=1454460169902 tag=VacuumService
D/LgDataFeature( 6526): LgDataFeature() Constructor: none
D/LgDataFeature( 6526): LgDataFeature() Constructor Done, null
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1034): Killing 5563:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  310): res_queryN name = www.google.com succeed
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1034): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup( 1034): failed to open /acct/uid_10097/pid_5563/cgroup.procs: No such file or directory
E/Ads     ( 2321): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 2321): [CredentialSyncAdapter] Unknown sync event.
,D/eas_req ( 6526): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = true
D/PhoneState( 3303): setPdpRejectCasuse : false
,I/HubEmail( 6526): JNI_OnLoad()
I/HubEmail( 6526): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6526): registerNatives()
I/HubEmail( 6526): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6526): registerNativeMethods()
,I/HubEmail( 6526): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6526): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1034): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6584 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/Settings( 6526): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GoogleURLConnFactory( 2051): Using platform SSLCertificateSocketFactory
,W/Settings( 6526): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Uploader( 2051): No account for auth token provided
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/DrmBroadcastReceiver( 6584): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6584): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6584): Service onCreate
D/DrmService( 6584): Received new request = 2
I/DrmSntpClient( 6584): Start Sync process
D/DrmSntpClient( 6584): Server : 0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = pool.ntp.org, class = 1, type = 1
,D/BooksSync( 6459): started syncMyEbooks
I/ActivityManager( 1034): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6611 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  310): res_queryN name = play.googleapis.com succeed
,I/art     ( 6611): Almond Protected OAT
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WeatherApplication( 6611): removeAccount
,D/WeatherApplication( 6611): Account.length = 0
E/WeatherApplication( 6611): OPERATOR:OPEN
D/libc-netbsd(  310): res_queryN name = pool.ntp.org succeed
D/WeatherAncestor( 6611): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:42:50
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6459): null auth token
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/Weather.Utils( 6611): 2 : the weather widgets(using time tick) are gone.
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/Weather.Utils( 6611): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6611): 2 : This is isUpdating : false
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
,D/WeatherAncestor( 6611): connectivity changed - connection : true
D/WeatherService( 6611): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6611): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6611): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6611): 2 : Cache is not up-to-date, count: 0
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/LGDrmClient( 6584): _DRM_ServiceGet() : Bind lgdrm service
,I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/ILGDrmService(  321): eDRM_SetDRMTime +++
I/LGDRM   (  321): [DRM] SET TIME : YR=2016, MON=2, DAY=3
I/LGDRM   (  321): [DRM] SET TIME : HR=0, MIN=42, SEC=50
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather_cast( 6611): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6611): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:42:50
V/ILGDrmService(  321): eDRM_SetDRMTime ---
I/DrmSntpClient( 6584): Synched
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DrmService( 6584): Completed !! request = 2
D/DrmService( 6584): Request count = 0
I/ActivityManager( 1034): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6633 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 5878:com.lge.eula/1000 (adj 15): empty #17
D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
D/libc-netbsd(  310): res_queryN name = static-avc.lglime.com succeed
,V/DrmService( 6584): Service onDestroy
,I/ActivityManager( 1034): Killing 5384:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_5878/cgroup.procs: No such file or directory
W/libprocessgroup( 1034): failed to open /acct/uid_10005/pid_5384/cgroup.procs: No such file or directory
,V/FormManager( 6159): There are no updated forms. The schedule will be deleted.
V/FormManager( 6159): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/ContactsSyncAdapter( 2051): innerSync failed
D/ContactsSyncAdapter( 2051): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2051): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2051): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2051): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 205,1): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager( 1034): Killing 2152:com.lge.music/u0a34 (adj 15): empty #17
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/AudioFlinger(  314): 2152 died, releasing its sessions
V/AudioFlinger(  314):  pid 1827 @ 0
V/AudioFlinger(  314):  pid 3303 @ 1
V/AudioFlinger(  314):  pid 3303 @ 2
,W/libprocessgroup( 1034): failed to open /acct/uid_10034/pid_2152/cgroup.procs: No such file or directory
,D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26893, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1034): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 151347, reason: 10019
,W/Uploader( 2051): No account for auth token provided
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
W/ApiaryClient( 6459): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1205359777851979599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6633): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6633): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/Uploader( 2051):  no longer exists, so no auth token.
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6633): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6633): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/DelayedSyncController( 6500): Delaying sync.
,W/Uploader( 2051): No account for auth token provided
,W/Uploader( 2051): No account for auth token provided
I/ActivityManager( 1034): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6680 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6633): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 33121(1464KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.548ms total 94.627ms
,I/LibraryLoader( 6633): Loading: webviewchromium
,I/LibraryLoader( 6633): Time to load native libraries: 6 ms (timestamps 706-712)
I/LibraryLoader( 6633): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6633): Binding Chromium to main looper Looper (main, tid 1) {7c7c9f1}
I/LibraryLoader( 6633): Expected native library version number "",actual native library version number ""
I/chromium( 6633): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6633): Initializing chromium process, renderers=0
W/art     ( 6633): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6633): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6633): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
I/chromium( 6633): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
V/AudioPolicyService(  314): registerClient() client 0xb15242a0, uid 10093
,I/Adreno-EGL( 6633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6633): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6633): Build Date: 12/12/14 금
I/Adreno-EGL( 6633): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6633): Remote Branch: 
I/Adreno-EGL( 6633): Local Patches: 
I/Adreno-EGL( 6633): Reconstruct Branch: 
W/AudioManagerAndroid( 6633): Requires BLUETOOTH permission
,I/NSApplication( 6633): Starting up...
,I/ActivityManager( 1034): Killing 4868:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10044/pid_4868/cgroup.procs: No such file or directory
,I/GLSActivity( 2051): [ac] getting account id
,I/GLSUser ( 2051): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = mtalk.google.com, class = 1, type = 1
I/iu.SyncManager( 2321): SYNC; picasa accounts
,D/NetworkLogImpl( 2321): Loaded NetworkSpeedPredictor
,D/libc-netbsd(  310): res_queryN name = mtalk.google.com succeed
I/iu.Environment( 2321): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2321): num queued entries: 0
I/art     ( 2051): Explicit concurrent mark sweep GC freed 29491(1632KB) AllocSpace objects, 8(919KB) LOS objects, 51% free, 30MB/62MB, paused 1.479ms total 82.822ms
,I/iu.UploadsManager( 2321): num updated entries: 0
I/iu.SyncManager( 2321): NEXT; no task
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5086): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1034): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6744 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
W/Kids    ( 2321): [AccountUtils] Account not ready
W/Kids    ( 2321): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2321): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2321): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2321): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2321): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2321): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2321): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2321): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2321): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2321): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2321): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2321): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ALBootInit( 6744): ====action==>android.intent.action.TIME_SET
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
D/ALBootInit( 6744): Alarm ALBootInit: TIME_SET
D/LgeQuickCoverNLService( 1399): onNotificationPosted
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/Alarms  ( 6744): [setNextAlert] start
D/Alarms  ( 6744): [setNextAlert] (1)
D/Alarms  ( 6744):  minTime  = 0
,D/Alarms  ( 6744):  -- OK multi -- 0
,E/jeny.kim( 6744): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6744): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/CommonUtil( 6744): BUILD Country: EU
,D/Alarms  ( 6744): broadcastToWidgetProvider : false
D/Alarms  ( 6744): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1034): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6744): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6744): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@24ab256f
V/DigitalAppWidgetProvider( 6744): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@24ab256f
D/QuickCoverProvider( 6744): onReceiver
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
W/ApiaryClient( 6459): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1205359777851979599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
I/indal   ( 1399): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1399): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6611): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:42:52
,D/Weather.Utils( 6611): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6611): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6611): 2 : This is isUpdating : false
D/WeatherService( 6611): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2520f27c
D/ForecastDataCache( 6611): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6611): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6611): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6611): 2 : set auto-update time : 2/3 4:42
D/WeatherAncestor( 6611): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 1:42:52
,I/ActivityManager( 1034): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6770 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 5916:com.lge.bnr/1000 (adj 15): empty #17
D/GCM     ( 2051): Connected
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_5916/cgroup.procs: No such file or directory
,D/GCM     ( 2051): Message class com.google.f.a.a.p
D/TimeService( 6770): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454460172430
D/        ( 6770): TimeServiceNative: User Time to be set is 1454460172430
D/QC-time-services( 6770): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6770): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6770): Lib:time_genoff_operation: pargs->ts_val = 1454460172430
D/QC-time-services( 6770): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  368): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  368): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454460172430
D/QC-time-services(  368): Daemon:genoff_opr: Base = 2, val = 1454460172430, operation = 0
D/QC-time-services(  368): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 17:54:59
D/QC-time-services(  368): Daemon:Value read from RTC seconds = 14061299000
,D/QC-time-services(  368): Daemon:new time 1454460172430 
D/QC-time-services(  368): Daemon: delta 1440398873430 genoff 1440398873430 
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440398873430 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  368): Updating the TOD offset
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440398873430 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  368): Daemon:Update to modem bit set
D/QC-time-services(  368): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  368): Daemon: Base = 2, Value being sent to MODEM = 1124434073430
E/QC-time-services( 6770): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  368): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  368): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1034): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6788 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1034): Killing 6183:com.lge.lifetracker/u0a37 (adj 15): empty #17
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1533740656] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533740653] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
W/libprocessgroup( 1034): failed to open /acct/uid_10037/pid_6183/cgroup.procs: No such file or directory
,W/ResourcesManager( 6788): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6788): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6788): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6788): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@d77d602, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@6c6eb13, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@22041150, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2ce1ef49, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@e91504e, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@24ab256f, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2520f27c, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@20d13705, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@ab6235a, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3feea98b, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc8ba68, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3eb33e81, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@28231b26, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2e9c5367, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@22a31514, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@115441bd, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2215c3b2, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3290bf03, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@21266e80, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@a083cb9, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@381868fe, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@4d6485f, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@31c3f2ac, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@166eb75, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@60e170a, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3ac10b7b, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@31d38d98, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@7c7c9f1, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@10fe99d6, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20cae457, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3feb44, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@17e142d, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@14a27d62, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@272f6ef3, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@25f277b0, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@ad4c629, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1daf0dae, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3c48074f, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@12ff5edc, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1fca9be5, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce256ba, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@30a7c96b,
,D/GeneralPreferenceUtils( 6788): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6788): [init]
,I/Config  ( 6788): LGCalendar ver.4.40.16
I/Config  ( 6788): start check model
I/Config  ( 6788): start check native_ca
I/Config  ( 6788): Config Operator=OPEN, Country=EU
D/Config  ( 6788): [setDefaultValuesToPref]
D/Config  ( 6788): [parseProfiles]
D/ProfilesParser( 6788): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6788): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6788): [updateProfiletoCountryInfo]
D/GeneralPreference( 6788): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6788): [updateWidgets] 
,I/InitNotificationRingtoneService( 6788): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6788): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6788): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6788): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6788): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6788): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6788): End InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6788): [onReceive]
D/CalendarWidgetProvider( 6788): [onReceive]
,D/CalendarWidgetProvider( 6788): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6788): onHandleIntent
D/CalendarTypeController( 6788): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 6788): readJsonAsset : holiday.json
D/WeekWidgetProvider( 6788): [onReceive]
D/CalendarWidgetProvider( 6788): [onReceive]
D/CalendarWidgetProvider( 6788): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6788): [onUpdateAndInitCalendarTime]
E/HolidayIntentService( 6788): onHandleIntent:holiday data empty
,I/ActivityManager( 1034): Killing 6254:com.lge.settings.easy/1000 (adj 15): empty #17
I/jxcore-log( 6016): Test app app.js loaded
I/jxcore-log( 6016): 
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6254/cgroup.procs: No such file or directory
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6016): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc81d05 added. We now have 1 listener(s)
I/chromium( 6016): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 6016): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6016): 
I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/LgeQuickCoverNLService( 1399): onNotificationPosted
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
I/art     ( 2321): Explicit concurrent mark sweep GC freed 17239(1269KB) AllocSpace objects, 20(320KB) LOS objects, 49% free, 32MB/64MB, paused 2.267ms total 93.178ms
,D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/DigitalAppWidgetProvider( 6744): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6611): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:42:53
D/Weather.Utils( 6611): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6611): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6611): 2 : This is isUpdating : false
D/Weather_cast( 6611): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
,D/WeatherAncestor( 6611): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:42:53
,W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
W/ApiaryClient( 6459): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1205359777851979599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
I/ActivityManager( 1034): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6825 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6825): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6825): LgDataFeature() Constructor: none
,D/LgDataFeature( 6825): LgDataFeature() Constructor Done, null
,I/Babel   ( 6825): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6825): MmsConfig.loadMmsSettings
,W/AudioCapabilities( 6825): Unsupported mime audio/evrc
,W/AudioCapabilities( 6825): Unsupported mime audio/qcelp
W/VideoCapabilities( 6825): Unrecognized profile 2130706433 for video/avc
I/art     ( 1034): Explicit concurrent mark sweep GC freed 16803(771KB) AllocSpace objects, 3(432KB) LOS objects, 33% free, 44MB/66MB, paused 3.054ms total 153.735ms
,I/Babel   ( 6825): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6825): MmsConfig.loadFromDatabase
W/AudioCapabilities( 6825): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6825): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6825): Unsupported mime audio/evrc
E/Babel   ( 6825): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6825): MmsConfig.loadFromResources
E/Babel   ( 6825): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6825): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 6825): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/VideoCapabilities( 6825): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6825): Unsupported mime video/divx
W/VideoCapabilities( 6825): Unsupported mime video/divx311
,W/VideoCapabilities( 6825): Unsupported mime video/divx4
W/VideoCapabilities( 6825): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6825): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6825): Unsupported mime audio/eac3
W/AudioCapabilities( 6825): Unsupported mime audio/ac3
W/AudioCapabilities( 6825): Unsupported mime audio/g726
W/AudioCapabilities( 6825): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6825): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6825): Unsupported mime audio/adpcm
W/VideoCapabilities( 6825): Unsupported mime video/theora
,W/VideoCapabilities( 6825): Unsupported mime video/mjpg
W/ResourcesManager( 6825): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6825): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6825): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6825): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6825): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6825): UserRecoverableAuthException.
E/Babel   ( 6825): cfq: BadAuthentication
E/Babel   ( 6825): 	at cfn.a(Unknown Source)
E/Babel   ( 6825): 	at f.a(PG:191)
E/Babel   ( 6825): 	at ava.a(PG:88)
E/Babel   ( 6825): 	at ava.a(PG:128)
E/Babel   ( 6825): 	at bjs.a(PG:255)
E/Babel   ( 6825): 	at bep.a(PG:602)
E/Babel   ( 6825): 	at bep.a(PG:469)
E/Babel   ( 6825): 	at bpo.run(PG:1141)
E/Babel   ( 6825): Error getting auth token
E/Babel   ( 6825): bxl
E/Babel   ( 6825): 	at f.a(PG:201)
E/Babel   ( 6825): 	at ava.a(PG:88)
E/Babel   ( 6825): 	at ava.a(PG:128)
E/Babel   ( 6825): 	at bjs.a(PG:255)
E/Babel   ( 6825): 	at bep.a(PG:602)
E/Babel   ( 6825): 	at bep.a(PG:469)
E/Babel   ( 6825): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6825): error sending REQ[fc:8; creat:1454442015548; type:bev-363982940]; took 114 ms (error code == 100)
,E/Babel   ( 6825): Account registration failedRedacted-21
E/Babel   ( 6825): bph: null -- null
E/Babel   ( 6825): 	at ava.a(PG:120)
E/Babel   ( 6825): 	at ava.a(PG:128)
E/Babel   ( 6825): 	at bjs.a(PG:255)
E/Babel   ( 6825): 	at bep.a(PG:602)
E/Babel   ( 6825): 	at bep.a(PG:469)
E/Babel   ( 6825): 	at bpo.run(PG:1141)
I/Babel   ( 6825): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6825): Account sign in complete with state 106account: Redacted-21
I/art     ( 6825): Note: end time exceeds epoch: 
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2051): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
E/Babel   ( 6825): Unexpected exception while authenticating.
E/Babel   ( 6825): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6825): 	at cfn.b(Unknown Source)
E/Babel   ( 6825): 	at cfn.a(Unknown Source)
E/Babel   ( 6825): 	at f.a(PG:188)
E/Babel   ( 6825): 	at ava.b(PG:143)
E/Babel   ( 6825): 	at bnr.run(PG:5415)
E/Babel   ( 6825): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6825): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6825): 	at java.lang.Thread.run(Thread.java:818)
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksSync( 6459): Soft error: 
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1205359777851979599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
,E/BooksSync( 6459): Sync error
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1205359777851979599&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
,E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
I/BooksSync( 6459): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26864, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1034): Killing 6209:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6209/cgroup.procs: No such file or directory
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 6459): Thread[GAThread,5,main]: No campaign data found.
,V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2051): innerSync failed
D/ContactsSyncAdapter( 2051): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2051): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2051): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2051): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2051): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 151347, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefb,b36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=24.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533737636] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=29.8, 0.0, 0.0  rx=24.6 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1533737628] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
I/GAV4    ( 6633): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1034): Killing 5896:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6285): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6285): android.os.DeadObjectException
,W/System.err( 6285): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6285): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6285): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6285): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6285): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6285): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6285): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6285): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6285): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6285): android.os.DeadObjectException
W/System.err( 6285): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6285): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6285): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6285): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6285): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6285): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6285): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6285): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6285): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6285): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_5896/cgroup.procs: No such file or directory
W/ActivityManager( 1034): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6285): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6285): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1034): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6877 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/art     (  336): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 34.956ms
,D/QRemote ( 6285): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/art     (  336): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 29.842ms
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 24.230ms
,D/UEI.SmartControl( 6877): Quickset Services start...
,I/UEI.SmartControl( 6877): Manufacture = LGE
D/UEI.SmartControl( 6877): Id = LGNevo
D/UEI.SmartControl( 6877): File observer start...
E/UEI.SmartControl( 6877): IR Port is disabled: false
D/UEI.SmartControl( 6877): Starting file observer...
D/UEI.SmartControl( 6877): Extracting JNI libs...
D/UEI.SmartControl( 6877): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6877): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6877): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6877): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6877): --- Selecting new region: 6
,I/UEI.SmartControl( 6877): Model = LG-D855
D/UEI.SmartControl( 6877): QS Service created
I/UEI.SmartControl( 6877): Service initServices...
,D/UEI.SmartControl( 6877): QS start get config
D/UEI.SmartControl( 6877): Loading JNI Libs...
,I/UEI.SmartControl( 6877): Supports setup maps: true
,D/UEI.SmartControl( 6877): QS start statue = true Error code = 0
I/UEI.SmartControl( 6877): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6877): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6877): ### init IR Blaster...
D/serial_port( 6877): Configuring serial port
E/UEI.SmartControl( 6877): UEIBLaster setting for 616
I/UEI.SmartControl( 6877): Setting serial record hearder size = 2
I/UEI.SmartControl( 6877): configuring settings for MAXQ616
I/UEI.SmartControl( 6877): Get version...
,D/UEI.SmartControl( 6877): serial port data available: 21
,D/UEI.SmartControl( 6877): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6877): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6877): QS saving settings...
,D/UEI.SmartControl( 6877): IR Blaster version: 25672567
D/UEI.SmartControl( 6877): serial port data available: 4
,W/ContextImpl( 6877): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6877): Services init done
D/UEI.SmartControl( 6877): QS Service init finished
I/UEI.SmartControl( 6877): Device manager: loading config....
D/UEI.SmartControl( 6877): ----------- loading internal config...
D/UEI.SmartControl( 6877): QS Service version name: 2.1.91
D/UEI.SmartControl( 6877): QS Service version code: 201091
D/UEI.SmartControl( 6877): Service requested: Control
,D/UEI.SmartControl( 6877): Request IControl service: devices are loaded...
,I/ActivityManager( 1034): Killing 6121:com.android.settings/1000 (adj 15): empty #17
I/QRemote ( 6285): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6877): ------ IControl API: 11
I/UEI.SmartControl( 6877): Registering callback...
,I/UEI.SmartControl( 6877): ------ IControl API: 19
,I/UEI.SmartControl( 6877): Registering Services Ready callback...
E/UEI.SmartControl( 6877): Loading SETTINGS...
D/UEI.SmartControl( 6877): -- Open brand translation xml: brands_translations_ko
,D/WifiService( 1034): Client connection lost with reason: 4
,I/UEI.SmartControl( 6877): Notify AllClients services are ready: 0
I/QRemote ( 6285): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6285): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6285): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6285): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6285): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6877): ------ IControl API: 8
D/UEI.SmartControl( 6877): -----service ready thread exits
D/QRemote ( 6285): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6285): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6285): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6285): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6285): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6285): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6121/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6877): Internal service binding...
D/QRemote ( 6285): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6285): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454460177535]
D/QRemote ( 6285): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 127767212299; DSPS: 4327358; Offset : -4303722888
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=17.9, 0.0, 0.0  rx=14.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533734615] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=17.9, 0.0, 0.0  rx=14.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533734605] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,I/ActivityManager( 1034): Killing 6437:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10011/pid_6437/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1237
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=9.0, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533731579] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=9.0, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533731576] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 6877): Internal timer expired: 1
,D/UEI.SmartControl( 6877): unbind internal service
,D/serial_port( 6877): close(fd = 25)
,I/UEI.SmartControl( 6877): Serial port is closed.
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533728554] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1533728542] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533725526] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533725515] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
I/[SystemUI]QPairHandler( 1458): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1844): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1034): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1034): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6930 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/SplitUIManager( 1844): split_name #11 / not available #0
I/SplitUIService( 1844): split app #11
,I/[LGHome]EVENT( 2008): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 2008): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1034): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6953 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{734ec5a type 0 when 1454460184288 com.android.vending} when 1454460184288
I/[SystemUI]QSlideListController( 1458): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1458): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/administrator( 1034): Handling package changes for user 0
,I/[LGHome]Launcher( 2008): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 6930): onCreate
,W/AppUp4:DB( 6930):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6930):  setFingerPrint start
I/AppUp4:DB( 6930):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6930):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6930):  SDK version = 21
I/AppUp4:DB( 6930):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6930): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6930): onReceive
I/NotificationService( 1034): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1034): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
W/ResourcesManager( 1034): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6930): LgDataFeature() Constructor: none
,D/LgDataFeature( 6930): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6930): Context : android.app.ReceiverRestrictedContext@6c6eb13
D/AppUp4:CustFacade( 6930): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6930): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6930): begin check event
I/AppUp4:CustModeStarterReceiver( 6930): Event For Nothing, skip.
D/Finsky  ( 6953): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 1034): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1034): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1034): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6987 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6159:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10026/pid_6159/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2008): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 6987): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6987): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6987): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6987): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6987): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LgDataFeature( 6953): LgDataFeature() Constructor: none
D/LgDataFeature( 6953): LgDataFeature() Constructor Done, null
,I/SystemConfig( 6987): BUILD Country: EU
,I/SystemConfig( 6987): BUILD Operator: OPEN
,D/Finsky  ( 6953): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1034): Killing 6584:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10062/pid_6584/cgroup.procs: No such file or directory
,I/SystemConfig( 6987): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6987): existFile = false
I/SystemConfig( 6987): canReadFile = false
I/SystemConfig( 6987): systemFeature RCS result false
D/SystemConfig( 6987): refreshRcsSupport() :false
,I/UpdateIcingCorporaServi( 4253): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,I/ActivityManager( 1034): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7024 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4253): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4253): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
,I/ActivityManager( 1034): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7041 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 6953): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6953): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/LockScreenSettings( 7024): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/ResourcesManager( 7041): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7041): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LockScreenSettings( 7024): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7024): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7024): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7024): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7024): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7024): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,V/DownloadManager( 3325): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3325): created cursor android.database.sqlite.SQLiteCursor@38e1161 on behalf of 6953
I/ActivityManager( 1034): Killing 6633:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,I/MultiDex( 7041): VM with version 2.1.0 has multidex support
I/MultiDex( 7041): install
I/MultiDex( 7041): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup( 1034): failed to open /acct/uid_10093/pid_6633/cgroup.procs: No such file or directory
,D/Finsky  ( 6953): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6953): [1] 2.run: Finished loading 1 libraries.
V/JNIHelp ( 7041): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 6953): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2321): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 6953): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ActivityThread( 7041): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7041): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d71e35b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7041): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1034): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7069 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/GCM     ( 2051): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/PeopleContactsSync( 2321): CP2 sync disabled
V/SIM_STK ( 1034): Menu title from STK is T-Mobile
D/AuthorizationBluetoothService( 2051): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2321): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ResourcesManager( 7069): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7069): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LocationInitializer( 2321): Restart initialization of location
I/MultiDex( 7069): VM with version 2.1.0 has multidex support
I/MultiDex( 7069): install
I/MultiDex( 7069): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7069): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7069): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7069): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d71e35b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7069): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 7069): Install did not work
W/NativeLibraryUtils( 7069): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7069): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7069): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7069): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7069): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7069): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7069): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7069): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7069): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7069): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7069): 	... 4 more
,D/GCM     ( 2051): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/WearableService( 7069): callingUid 10005, callindPid: 7069
D/AuthorizationBluetoothService( 2051): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2321): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 2321): Restart initialization of location
,E/MDM     ( 1792): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/MDM     ( 1792): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/Finsky  ( 6953): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{fe0721e type 0 when 1454460190599 com.android.vending} when 1454460190599
,D/Finsky  ( 6953): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2051): Explicit concurrent mark sweep GC freed 31359(1751KB) AllocSpace objects, 16(2MB) LOS objects, 50% free, 30MB/62MB, paused 1.656ms total 63.006ms
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533722493] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533722483] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
W/Finsky  ( 6953): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6953): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6953): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6953): [1] 5.onFinished: Scheduling replication attempt 2.
I/art     ( 1034): Explicit concurrent mark sweep GC freed 39267(1878KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.026ms total 130.958ms
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6953): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6953): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6953): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6953): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6953): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1792): client connected with version: 7571000
I/ActivityManager( 1034): Killing 6526:com.lge.email/u0a23 (adj 15): empty #17
,I/ActivityManager( 1034): Killing 6500:com.android.chrome/u0a57 (adj 15): empty #18
,W/libprocessgroup( 1034): failed to open /acct/uid_10023/pid_6526/cgroup.procs: No such file or directory
,W/libprocessgroup( 1034): failed to open /acct/uid_10057/pid_6500/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533719475] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533719465] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
I/ActivityManager( 1034): Killing 5086:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_5086/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533716445] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533716435] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 147769075520; DSPS: 4982779; Offset : -4303720953
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{15360306 type 2 when 148719 android} when 148719
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533713413] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533713410] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533710384] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533710374] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1034):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533707354] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1533707342] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533704327] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533704324] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533701300] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533701297] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533698270] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1533698266] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{3aa0eff4 type 0 when 1454460211184 com.android.vending} when 1454460211184
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6953): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6953): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6953): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533695240] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533695237] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 167771818690; DSPS: 5638229; Offset : -4303724600
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533692210] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533692207] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533689188] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533689185] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533686160] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533686157] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{e0b39b6 type 2 when 178743 android} when 178743
,I/BooksSync( 6459): Starting books sync
,D/BooksSync( 6459): started syncMyEbooks
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2051): innerSync failed
D/ContactsSyncAdapter( 2051): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2051): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2051): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2051): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2051): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2051): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2051): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 151347, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1034): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 241256, reason: 10019
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6459): null auth token
,D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5744851093865761583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533683134] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533683124] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
,W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5744851093865761583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
,W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5744851093865761583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533680110] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533680107] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/BooksSync( 6459): Soft error: 
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5744851093865761583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
,E/BooksSync( 6459): Sync error
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5744851093865761583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
I/BooksSync( 6459): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153766, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533677078] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533677075] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{2b01d852 type 0 when 1454460235483 com.android.vending} when 1454460235483
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6953): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6953): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6953): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 187773864516; DSPS: 6293656; Offset : -4303723476
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533674057] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533674054] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533671030] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533671027] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533668005] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533667996] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533664975] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533664964] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533661944] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1533661932] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533658919] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533658916] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533655892] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533655889] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{25ec8c76 type 0 when 1454460257008 com.android.vending} when 1454460257008
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 207775242424; DSPS: 6949061; Offset : -4303718469
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6953): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6953): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6953): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{3150fe68 type 2 when 208820 android} when 208820
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533652865] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533652856] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533649835] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1533649822] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533646802] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533646799] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533643777] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533643774] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533640746] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533640736] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533637724] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533637713] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 227776838197; DSPS: 7604473; Offset : -4303709948
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533634695] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1533634687] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1533631666] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1533631654] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533628632] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533628629] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533625605] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533625595] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533622582] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533622579] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{19703281 type 2 when 211890 android} when 211890
,V/AlarmManager( 1034): RTC_WAKEUP set : Alarm{38e46767 type 0 when 1454460278500 com.android.vending} when 1454460278500
,V/SIM_STK ( 1034): Menu title from STK is T-Mobile
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1034): Explicit concurrent mark sweep GC freed 55949(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 1.570ms total 86.825ms
,D/Finsky  ( 6953): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6953): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6953): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1034): battery changed pluggedType: 2
,D/LEDHandler( 1916): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1916): Battery Level Remaining: 100%
D/LEDHandler( 1916): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6087): Disconnected process message: 10, size: 0
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{15a9bdf1 type 2 when 242925 android} when 242925
,I/BooksSync( 6459): Starting books sync
,D/BooksSync( 6459): started syncMyEbooks
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2981] from screen [on:0 period:-1533619558] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533619557] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1438268656207554335&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
,W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1438268656207554335&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
,D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1438268656207554335&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533616538] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533616535] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/BooksSync( 6459): Soft error: 
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1438268656207554335&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
,E/BooksSync( 6459): Sync error
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1438268656207554335&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
I/BooksSync( 6459): Finished books sync
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 242925, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 247778907721; DSPS: 8259901; Offset : -4303715698
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=4.9, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533613511] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=4.9, 0.0, 0.0  rx=3.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533613508] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6744): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 6744): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@24ab256f
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533610482] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533610479] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533607460] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533607457] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533604432] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533604429] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1533601408] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1533601404] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533598378] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533598375] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533595353] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533595344] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 267781067454; DSPS: 8915332; Offset : -4303722505
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533592330] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533592327] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{21fddfa4 type 2 when 272968 android} when 272968
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1533589304] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533589303] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533586284] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533586274] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533583254] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1533583239] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533580219] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533580216] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533577194] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533577185] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 287783224998; DSPS: 9570762; Offset : -4303701374
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533574168] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533574165] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533571139] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533571136] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533568115] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533568105] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533565085] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533565074] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533562053] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1533562049] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533559024] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533559014] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533555993] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533555982] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 307785248688; DSPS: 10226189; Offset : -4303722257
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533552961] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533552958] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533549934] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533549925] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533546904] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533546893] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533543871] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533543868] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533540843] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1533540839] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533537806] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533537797] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 327787317430; DSPS: 10881616; Offset : -4303698115
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533534776] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533534767] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533531746] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533531743] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533528718] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533528715] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533525690] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533525687] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1533522665] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533522656] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533519635] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533519625] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1533516605] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533516604] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 347789235912; DSPS: 11537039; Offset : -4303702605
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533513585] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1533513575] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533510555] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533510544] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533507525] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533507514] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533504494] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1533504483] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533501462] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533501459] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533498433] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1533498424] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{3014610d type 2 when 367088 android} when 367088
,E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.6, 0.0, 0.0  rx=6.6 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1533495406] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=5.6, 0.0, 0.0  rx=6.6 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1533495406] gl rssi=-65 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,I/BooksSync( 6459): Starting books sync
D/BooksSync( 6459): started syncMyEbooks
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2051): Explicit concurrent mark sweep GC freed 37002(2MB) AllocSpace objects, 16(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.345ms total 46.026ms
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
W/ApiaryClient( 6459): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7225721272343027547&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 367791333249; DSPS: 12192468; Offset : -4303710668
,V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1399): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1399): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1399): onNotificationPosted
D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
,W/ResourcesManager( 1399): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1399): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
,D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
D/QuickStatusbarLayout( 1399): Notification difference=198
,D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7225721272343027547&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2051): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2051): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2051): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2051): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2051): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1034): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1034): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1034): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1034): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1034): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1399): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1399): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1399): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1399): handleNotificationPosted(true)
D/QuickCircle( 1399): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1399): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): post do just update job
D/LgeQuickCoverNotificationData( 1399): showAll3
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1399): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1399): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1399): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1399): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1399): updateNotificationData: count=3
W/GLSActivity( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2051): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2051): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2051): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2051): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1399): Notification difference=198
D/QuickStatusbarLayout( 1399): child = android.widget.LinearLayout{2eefbb36 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 6459): Authentication error
E/BooksAccountManager( 6459): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6459): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6459): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6459): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6459): null auth token
W/ApiaryClient( 6459): Error response from books API: {
W/ApiaryClient( 6459):  "error": {
W/ApiaryClient( 6459):   "errors": [
W/ApiaryClient( 6459):    {
W/ApiaryClient( 6459):     "domain": "global",
W/ApiaryClient( 6459):     "reason": "required",
W/ApiaryClient( 6459):     "message": "Login Required",
W/ApiaryClient( 6459):     "locationType": "header",
W/ApiaryClient( 6459):     "location": "Authorization"
W/ApiaryClient( 6459):    }
W/ApiaryClient( 6459):   ],
W/ApiaryClient( 6459):   "code": 401,
W/ApiaryClient( 6459):   "message": "Login Required"
W/ApiaryClient( 6459):  }
W/ApiaryClient( 6459): }
,W/ApiaryClient( 6459): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7225721272343027547&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6459): Headers:
W/ApiaryClient( 6459): accept-encoding: [gzip]
W/ApiaryClient( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6459): gdata-version: 2
I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1034): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiStateMachine( 1034):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1533492387] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1034):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-65 f=2412 sc=60 link=65 tx=2.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533492386] gl rssi=-65 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1034): doString: [SIGNAL_POLL]
,D/Tethering( 1034): InitialState.processMessage what=4
D/WifiMonitor( 1034): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1034): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1034): sendTetherStateChangedBroadcast 0, 0, 0
,D/ConnectivityService( 1034): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 50
D/ConnectivityService( 1034): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1034):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1034): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1034): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1034): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524290
,D/ConnectivityService( 1034): sending new Min Network Score(50): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1827): new score 50 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1827):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/WifiStateMachine( 1034):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-127 rt=370317
E/WifiStateMachine( 1034):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-127 rt=370317
E/WifiStateMachine( 1034):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-127 rt=370317
E/WifiConfigStore( 1034): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1034): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1034): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1034): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1034): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/WifiNative-wlan0( 1034): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1034): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/jxcore-log( 6016): Toggling radios to false
I/jxcore-log( 6016): 
,I/ActivityManager( 1034): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7264 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1034): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1034): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1034): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@17b4af0f mBinding = false
V/NativeCrypto( 2051): Read error: ssl=0xaf4d9600: I/O error during system call, Connection timed out
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1034): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 2051): SSL shutdown failed: ssl=0xaf4d9600: I/O error during system call, Broken pipe
E/WifiStateMachine( 1034): WifiStateMachine: Leaving Connected state
,D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=370461  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
V/WfdStateTracker( 1916): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=370462  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1034):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1034):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WIFI    ( 1034): new score 50 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 1034):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=370470  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocationManagerService( 1034): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1034): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1034): JNI:system_update. Event-4
,W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1034):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=370481  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServiceImplEx( 1034): setWifiEnabled: false pid=6016, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1034): setWifiEnabled: false pid=6016, uid=10311
E/WifiService( 1034): Invoking mWifiStateMachine.setWifiEnabled
E/WifiStateMachine( 1034):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1034): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
E/WifiStateMachine( 1034):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1034):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1034):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1034): NetworkAgent: NetworkAgent channel lost
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateDISCONNECTED
,D/BluetoothManagerService( 1034): Message: 2
D/WifiServerServiceExt( 1034): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1034): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/BluetoothManagerService( 1034): Sending off request.
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothServiceAdapter( 6087): [BTUI] Precleanup
D/BluetoothAdapterState( 6087): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6087): Setting state to 13
I/BluetoothAdapterState( 6087): Bluetooth adapter state changed: 12-> 13
D/LocationManagerService( 1034): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1034): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1034): JNI:system_update. Event-4
D/BluetoothAdapterProperties( 6087): onBluetoothDisable()
I/BluetoothAdapterState( 6087): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1034): Message: 60
D/BluetoothManagerService( 1034): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1034): Bluetooth State Change Intent: 12 -> 13
E/WifiStateMachine( 1034):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1034):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1034):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine( 1034):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
I/BluetoothMapService( 6087): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6087): STATE_TURNING_OFF
V/BluetoothMapService( 6087): Handler(): got msg=4
D/BluetoothMapService( 6087): MAP Service closeService in
D/BluetoothMapMasInstance( 6087): MAP Service shutdown
D/LGBluetoothAPIService( 1916): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/ConnectivityService( 1034): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1034): disableDataServiceNotify
D/DSQN    ( 1034): stop dsqn bin
V/BluetoothMapMasInstance( 6087): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6087): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6087): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6087): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6087): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6087): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6087): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6087): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
I/jxcore-log( 6016): Radios toggled
I/jxcore-log( 6016): 
D/WifiScanningService( 1034): SCAN_AVAILABLE : 1
D/RttService( 1034): SCAN_AVAILABLE : 1
D/WifiScanningService( 1034): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1034): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]BluetoothHandler( 1458): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGWifiP2pService( 1034): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1034): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@350c5f9d
D/LGBluetoothMapAdapter( 6087): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6087): MAP Service closeService out
V/BtOppService( 6087): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6087): stopping Accept Thread
V/BtOppRfcommListener( 6087): close mBtServerSocket
V/BtOppRfcommListener( 6087): waiting for thread to terminate
E/BtOppRfcommListener( 6087): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 6087): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 6087): done waiting for thread to terminate
D/LGWifiP2pService( 1034): P2pDisablingState
,D/BluetoothAdapterProperties( 6087): Scan Mode:20
D/LGWifiP2pService( 1034): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): p2p socket connection lost
D/LGWifiP2pService( 1034): P2pDisabledState
D/BluetoothAdapterState( 6087): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/WifiStateMachine( 1034):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1034): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapService( 6087): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 6087): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x000f
V/WfdStateTracker( 1916): WfdStateTracker handleDirectStateChangedEvent: 0
W/bt-btif ( 6087): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/WfdsService( 1916): WifiP2pState is changed : false
D/WfdsService( 1916): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1916): Set the WFDS Monitor: false
D/WfdsMonitor( 1916): WFDS Monitor is stopped
D/WfdsService( 1916): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1916): Received on exit socket, terminate
E/CtrlSupplicant( 1916): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1916): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1916): WfdsMonitorThread is received the interrupt - closing
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/WfdsService( 1916): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1916): DefaultState - msg [9441355] is not handled
V/BluetoothSapService( 6087): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6087): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6087): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6087): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6087): bta_gattc_deregister Deregister Failedm unknown client cif
D/ConnectivityService( 1034): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/BluetoothFtpService:RfcommSocketAcceptThread( 6087): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/ConnectivityService( 1034): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LGWifiP2pService( 1034): DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat( 1034): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1034): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isC,onnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{50} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1034): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1458): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1034): Disconnected - quitting
D/WifiNative-wlan0( 1034): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6120): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1034): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1034): doBoolean: SET ps 1
D/WifiNative-wlan0( 1034): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
D/ConnectivityService( 1034): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1034): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1034): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/BtOppService( 6087): onDestroy
,D/NetworkManagementService( 1034): Removing idletimer
W/Settings( 1034): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1034): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1034): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1034): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1827): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1827):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1034): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1034): [LG_RESTRICTED] !!!isConnected  type  :1
D/LGBluetoothOppAdapter( 6087): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiNative-p2p0( 1034): doBoolean: TERMINATE
D/LocSvc_java( 1034): Sending msg: 4 arg1:0 arg2:1
D/WifiNative-p2p0( 1034): TERMINATE: returned true
D/LocSvc_java( 1034): getAGpsConnectionInfo connType - 4
E/WifiStateMachine( 1034): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1034): useWiFiOffloading() : false
E/WifiStateMachine( 1034): CONFIG_LGE_WLAN_PATH : true
D/LocSvc_java( 1034): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1034): ignore wifi update if we are not in OPENING or CLOSING
,D/WIFI    ( 1034): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1034):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1034): hidePasspointNotification off =false
W/Settings( 1034): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1034): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1034): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1916): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1034): WIFI_STATE_CHANGED_ACTION [0]
,D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7264): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7264): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7264): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7264): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7264): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1458): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1458): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1458): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1034): StoppedState
,D/DhcpStateMachine( 1034): StoppedState{ when=-101ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1034):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1034):  DefaultState CMD_ON_QUIT 0 0
W/ContextImpl( 7264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/UsbSettingsReceiver( 7264): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7264): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7264): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7264): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/BluetoothPbapReceiver( 6087): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6087): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6087): ***********state = 13
V/BluetoothPbapReceiver( 6087): ***********Calling start service!!!! with action = null
D/UsbSettingsReceiver( 7264): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapService( 6087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6087): state: 13
V/BluetoothPbapService( 6087): Pbap Service closeService in
I/ActivityManager( 1034): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7307 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 6087): successfully stopped pbap service
,V/BluetoothPbapService( 6087): Pbap Service closeService out
V/BluetoothPbapService( 6087): Pbap Service onDestroy
V/BluetoothPbapService( 6087): Pbap Service closeService in
V/BluetoothPbapService( 6087): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6087): [BTUI] cleanup
D/UsbSettingsControl( 7264): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7264): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7264): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7264): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7264): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7264): [AUTORUN] setTetherStatus() : status=false
D/BluetoothManagerService( 1034): Message: 20
D/BluetoothManagerService( 1034): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18972d2b:true
,I/ActivityManager( 1034): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7325 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1034): Message: 30
,D/BluetoothManagerService( 1034): Message: 30
D/LocalBluetoothProfileManager( 7264): Adding local MAP profile
,D/BluetoothMap( 7264): Create BluetoothMap proxy object
D/BluetoothManagerService( 1034): Message: 30
D/BluetoothManagerService( 1034): Message: 30
D/LocalBluetoothProfileManager( 7264): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 7264):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 7264): [BTUI] initUserBindClient
W/ContextImpl( 7264): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,W/ResourcesManager( 7325): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/DockEventReceiver( 7264): finishStartingService: stopping service
,D/BluetoothInputDevice( 7264): Proxy object connected
D/HidProfile( 7264): Bluetooth service connected
D/BluetoothPan( 7264): BluetoothPAN Proxy object connected
D/PanProfile( 7264): Bluetooth service connected
E/ActivityThread( 7307): Failed to find provider info for com.lge.lgaccount.provider
D/BluetoothMap( 7264): Proxy object connected
W/LG Account v2.2( 7307): No ProfileInfo entries
I/LG Account v2.2( 7307): isEnabled: false
I/Feature ( 7307): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7307): [Lifetracker]Country: EU
I/Feature ( 7307): [Lifetracker]Operator: OPEN
I/Feature ( 7307): [Lifetracker]Ranking support: false
I/Feature ( 7307): [Lifetracker]Comfort support: false
I/Feature ( 7307): [Lifetracker]Accessory: true
D/MapProfile( 7264): Bluetooth service connected
I/Feature ( 7307): [Lifetracker]Health device: true
D/BluetoothMap( 7264): getConnectedDevices()
D/BluetoothMap( 7264): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7264): [BTUI] onServiceConnected
I/Feature ( 7307): [Lifetracker]Extra Pedometer: false
I/Feature ( 7307): [Lifetracker]Blood glucose device: false
I/Feature ( 7307): [Lifetracker]Device Number: 3
D/PluginManager( 7325): init()
,D/LGBluetoothAuthorization( 7264): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 7264): onReceive
D/LGBluetoothAuthorization( 7264): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 7264): return without doing reset settings.
I/ActivityManager( 1034): Killing 6770:com.qualcomm.timeservice/1000 (adj 15): empty #17
V/BluetoothOppReceiver( 6087): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,D/BluetoothOppNotification( 6087): [BTUI] cancel opp incoming file confirm notification
,D/BluetoothOppNotification( 6087): [BTUI] cancel opp active transfer file notification
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6770/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6087): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6087): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6087): Ftp Service onStartCommand
V/BluetoothFtpService( 6087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6087): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6087): Shutdown
,V/BluetoothFtpService( 6087): successfully stopped ftp service
V/BluetoothSapReceiver( 6087): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6087): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6087): SapReceiver onReceive 
V/BluetoothSapReceiver( 6087): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6087):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6087): Calling SAP service start service with action = null
V/BluetoothFtpService( 6087): Ftp Service onDestroy
V/BluetoothFtpService( 6087): Ftp Service closeService
E/BooksSync( 6459): Soft error: 
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7225721272343027547&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
,E/BooksSync( 6459): Sync error
E/BooksSync( 6459): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6459): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7225721272343027547&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6459): Headers:
E/BooksSync( 6459): accept-encoding: [gzip]
E/BooksSync( 6459): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6459): gdata-version: 2
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6459): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6459): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6459): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6459): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6459): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6459): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6459): {
E/BooksSync( 6459):  "error": {
E/BooksSync( 6459):   "errors": [
E/BooksSync( 6459):    {
E/BooksSync( 6459):     "domain": "global",
E/BooksSync( 6459):     "reason": "required",
E/BooksSync( 6459):     "message": "Login Required",
E/BooksSync( 6459):     "locationType": "header",
E/BooksSync( 6459):     "location": "Authorization"
E/BooksSync( 6459):    }
E/BooksSync( 6459):   ],
E/BooksSync( 6459):   "code": 401,
E/BooksSync( 6459):   "message": "Login Required"
E/BooksSync( 6459):  }
E/BooksSync( 6459): }
E/BooksSync( 6459): 
E/BooksSync( 6459): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6459): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6459): 	... 8 more
I/BooksSync( 6459): Finished books sync
I/ActivityManager( 1034): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7354 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6087): state: 13
V/BluetoothSapService( 6087): Stopping SAP server process
V/BluetoothSapService( 6087): Sap Service closeSapService in
V/BluetoothSapService( 6087): Close listen Socket : 
V/BluetoothSapService( 6087): Close rfcomm Socket : 
V/BluetoothSapService( 6087): Close sapd  Socket : 
V/BluetoothSapService( 6087): Sap Service closeSapService out
V/BluetoothSapService( 6087): Sap Service onDestroy
V/BluetoothSapService( 6087): Sap Service closeSapService in
V/BluetoothSapService( 6087): Close listen Socket : 
V/BluetoothSapService( 6087): Close rfcomm Socket : 
V/BluetoothSapService( 6087): Close sapd  Socket : 
V/BluetoothSapService( 6087): Sap Service closeSapService out
I/ActivityManager( 1034): Killing 6788:com.android.calendar/u0a13 (adj 15): empty #17
D/SyncManager( 1034): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 367088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1034): failed to open /acct/uid_10013/pid_6788/cgroup.procs: No such file or directory
,W/ResourcesManager( 7354): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1034): Killing 6611:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2051): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1034): failed to open /acct/uid_10085/pid_6611/cgroup.procs: No such file or directory
W/ExternalStrings( 7325): load override strings
W/ExternalStrings( 7325): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7325): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7325): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7325): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7325): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7325): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7325): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7325): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7325): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7325): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7325): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7325): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7325): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7325): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7325): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7325): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7325): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7325): onCreate
V/Signer  ( 7325): override build config not found
,D/Signer  ( 7325): value of property debug is false
,D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7325): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7325): Create singleton instance
D/LGMDMWrapper( 7325): LG MDM library v4.0.0 is available on this device.
,D/bt_hci_bdroid( 6087): cleanup
,I/bt_lpm  ( 6087): LPM is already off!!!
W/bt-btif ( 6087): ag scb idx 1 not allocated
I/bt_userial_mct( 6087): exiting userial_read_thread
E/bt-btif ( 6087): BTA AG is already disabled, ignoring ...
D/bt_userial_mct( 6087): Leaving userial_evt_read_thread()
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6087): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6087): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6087): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6087): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6087): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 6087): userial_close_reader Joined userial reader thread: 0
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6087): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6087): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x0017
I/bt_vendor( 6087): hw_epilog_process
W/bt-l2cap( 6087): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6087): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6087): L2CAP - PSM: 0x001b not found for deregistration
D/bt_hci_bdroid( 6087): cleanup Finalizing cleanup
D/bt_userial_mct( 6087): userial_close
E/bt_userial_mct( 6087): pthread_join() FAILED result:3
I/bt_vendor( 6087): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
E/bt-btif ( 6087): bta_gattc_deregister Deregister Failedm unknown client cif
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/ActivityManager( 1034): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7377 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6825:com.google.android.talk/u0a72 (adj 15): empty #17
I/art     (  336): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 23.854ms
,D/bt_hci_bdroid( 6087): set_power 0
I/bt_vendor( 6087): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6087): bluetooth satus is on
I/bt_vendor( 6087): bt-vendor : resetting BT status
I/bt_vendor( 6087): Starting hciattach daemon
I/bt_vendor( 6087): try to set false
I/bt_vendor( 6087): Starting hciattach daemon
I/bt_vendor( 6087): try to set false
I/bt_vendor( 6087): cleanup
I/GKI_LINUX( 6087): gki_task task_id=0 [BTU] terminating
I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 19.185ms
I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 17.227ms
,W/ActivityThread( 7325): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1034): failed to open /acct/uid_10072/pid_6825/cgroup.procs: No such file or directory
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 83800(3MB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.744ms total 168.248ms
I/GKI_LINUX( 6087): GKI_exit_task 0 done
I/GKI_LINUX( 6087): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6087): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 6087): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 6087): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6087): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/HeadsetStateMachine( 6087): Exit Disconnected: -1
D/BluetoothHeadset( 1827): Proxy object disconnected
D/BluetoothHeadset( 1827): Proxy object disconnected
D/BluetoothHeadset( 1827): Proxy object disconnected
D/A2dpService( 6087): Received stop request...Stopping profile...
D/A2dpStateMachine( 6087): Exit Disconnected: -1
D/BluetoothHeadset( 1034): Proxy object disconnected
D/AudioService( 1034): onServiceDisconnected: Bluetooth profile: 1
D/LGBluetoothAvrcpQcomAdapter( 6087): [BTUI] cleanup
D/BluetoothAdapterState( 6087): Stopping profile services that were post enabled
D/LGBluetoothA2dpAdapter( 6087): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6087): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/BluetoothA2dp( 1034): Proxy object disconnected
D/AudioService( 1034): onServiceDisconnected: Bluetooth profile: 2
D/HeadsetStateMachine( 6087): Unbinding service...
D/HeadsetPhoneState( 6087): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6087): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6087): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6087): [BTUI] listenForMultiSimPhoneState : start = false
,W/BluetoothHeadsetServiceJni( 6087): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6087): Cleaning up Bluetooth Handsfree callback object
,I/LGBluetoothHfpAdapter( 6087): [BTUI] LGBluetoothHfpAdapter cleanup
D/HidService( 6087): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/HealthService( 6087): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/PanService( 6087): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/BtGatt.DebugUtils( 6087): handleDebugAction() action=null
D/BluetoothInputDevice( 7264): Proxy object disconnected
D/HidProfile( 7264): Bluetooth service disconnected
D/BluetoothPan( 7264): BluetoothPAN Proxy object disconnected
D/PanProfile( 7264): Bluetooth service disconnected
D/BtGatt.GattService( 6087): Received stop request...Stopping profile...
D/BtGatt.GattService( 6087): stop()
D/BtGatt.AdvertiseManager( 6087): advertise clients cleared
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
D/BluetoothMapService( 6087): Received stop request...Stopping profile...
D/BluetoothMapService( 6087): stop()
D/BluetoothMapEmailAppObserver( 6087): deinitObservers()
D/BluetoothMapEmailAppObserver( 6087): removeReceiver()
D/BluetoothAdapterService( 6087): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24ab256f
I/BluetoothA2dpServiceJni( 6087): cleanupNative
I/GKI_LINUX( 6087): gki_task task_id=2 [A2DP-MEDIA] terminating
D/BluetoothMap( 7264): Proxy object disconnected
D/MapProfile( 7264): Bluetooth service disconnected
I/GKI_LINUX( 6087): GKI_exit_task 2 done
I/GKI_LINUX( 6087): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6087): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6087): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6087): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6087): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6087): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6087): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6087): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6087): Handler(): got msg=4
D/BluetoothMapService( 6087): MAP Service closeService in
D/LGBluetoothMapAdapter( 6087): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6087): MAP Service closeService out
D/BluetoothMapService( 6087): cleanup()
D/BluetoothMapService( 6087): MAP Service closeService in
D/LGBluetoothMapAdapter( 6087): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6087): MAP Service closeService out
D/BluetoothAdapterState( 6087): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6087): Setting state to 10
I/BluetoothAdapterState( 6087): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1034): Message: 60
D/BluetoothManagerService( 1034): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1034): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 6087): Entering OffState
D/BluetoothInputDevice( 7264): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1827): onBluetoothStateChange: up=false
D/BluetoothPbap( 7264): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1034): onBluetoothStateChange: up=false
D/BluetoothMap( 7264): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1034): onBluetoothStateChange: up=false
D/BluetoothPan( 7264): onBluetoothStateChange on: false
D/BluetoothHeadset( 1827): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1827): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1034): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1034): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1034): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1034): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1034): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@17b4af0f mBinding = false
D/BluetoothManagerService( 1034): Sending unbind request.
D/BluetoothManagerService( 1034): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1916): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1916): Message: 2
D/LGBluetoothAPIService( 1916): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2a60e5ff mBinding = false
D/LGBluetoothAPIService( 1916): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1458): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/GKI_LINUX( 6087): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6087): GKI_exit_task 1 done
I/GKI_LINUX( 6087): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6087): cleanupNative: return from cleanup
I/art     ( 6087): --- WEIRD: removing null entry 246
D/LGBluetoothFeatureConfig( 7264): isPrivacyLogsEnabled : true
W/art     ( 6087): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6087): Cleaning up Bluetooth Service callback object
E/LGBluetoothEventManager( 7264): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7264): [BTUI] clear device connection state
,D/LGBluetoothSettingsDBObserver( 6087): [BTUI] unregister observer for LG device name DB
W/ContextImpl( 7264): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/art     ( 6087): System.exit called, status: 0
I/AndroidRuntime( 6087): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1458): 42473959: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1458): 42473959: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 7264): finishStartingService: stopping service
V/AudioFlinger(  314): 6087 died, releasing its sessions
,V/AudioFlinger(  314):  pid 1827 @ 0
V/AudioFlinger(  314):  pid 3303 @ 1
V/AudioFlinger(  314):  pid 3303 @ 2
D/LGBluetoothUserBindClient( 7264): [BTUI] onServiceDisconnected
I/PCSuite ( 7377): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7377): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager( 1034): Process com.android.bluetooth (pid 6087) has died
W/ActivityManager( 1034): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7264): LgDataFeature() Constructor: none
,D/LgDataFeature( 7264): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
D/BluetoothPermissionRequest( 7264): onReceive
D/LGBluetoothUtils( 7264): [BTUI] FileNotFound: readProperty
,D/BluetoothDiscoverableTimeoutReceiver( 7264): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7264): return without doing reset settings.
D/LgDataFeature( 7325): LgDataFeature() Constructor: none
D/LgDataFeature( 7325): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1034): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7416 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6877:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6285): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 6285): android.os.DeadObjectException
W/System.err( 6285): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6285): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6285): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6285): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6285): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6285): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6285): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6285): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6285): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6285): android.os.DeadObjectException
W/System.err( 6285): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6285): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6285): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6285): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6285): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6285): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6285): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6285): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6285): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6285): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6285): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6285): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_6877/cgroup.procs: No such file or directory
W/ActivityManager( 1034): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 10666ms
,D/QRemote ( 6285): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6285): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/ResourcesManager( 7416): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7416): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7416): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7416): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7416): Loading JNI Library
,I/ActivityManager( 1034): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7434 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6285): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7377): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7377): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/BluetoothAdapterApp( 7416): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@372d2ae4 Instance Count = 1
D/BluetoothAdapterApp( 7416): onCreate
D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
D/SiteAdvisor( 7325): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ProfileConfigQcom( 7416): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7416): Adding HeadsetService
D/ProfileConfigQcom( 7416): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7416): Adding A2dpService
,D/ProfileConfigQcom( 7416): [BTUI] HidService is supported
D/ProfileConfigQcom( 7416): Adding HidService
D/ProfileConfigQcom( 7416): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7416): Adding HealthService
D/LGBluetoothFeatureConfig( 7416): isSupportPan() :  mTargetOp=OPEN
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/ProfileConfigQcom( 7416): [BTUI] PanService is supported
D/ProfileConfigQcom( 7416): Adding PanService
D/ProfileConfigQcom( 7416): [BTUI] GattService is supported
D/ProfileConfigQcom( 7416): Adding GattService
D/ProfileConfigQcom( 7416): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7416): Adding BluetoothMapService
D/ProfileConfigQcom( 7416): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 7416): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7377): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7377): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/LGMDMManagerInternal( 7416): Create singleton instance
D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
D/LGBluetoothUserBindClient( 7264): [BTUI] onServiceConnected
,D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
D/UEI.SmartControl( 7434): Quickset Services start...
I/UEI.SmartControl( 7434): Manufacture = LGE
D/UEI.SmartControl( 7434): Id = LGNevo
D/UEI.SmartControl( 7434): File observer start...
E/UEI.SmartControl( 7434): IR Port is disabled: false
,D/UEI.SmartControl( 7434): Starting file observer...
D/UEI.SmartControl( 7434): Extracting JNI libs...
D/UEI.SmartControl( 7434): --- this system supports 32-bit or 64-bit only
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7377): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7377): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothFtpReceiver( 7416): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
V/BluetoothSapReceiver( 7416): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7416): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7416): SapReceiver onReceive 
V/BluetoothSapReceiver( 7416): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7416):  Bluetooth Adapter state = 10
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 7354): [BTUI] STATE_OFF : reset connected device information EasySettings
D/AuthorizationBluetoothService( 2051): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7377): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7377): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
D/QRemote ( 6285): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6285): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6285): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/UEI.SmartControl( 7434): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7434): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7434): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager( 1034): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7458 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 6930:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/wpa_supplicant( 6120): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 6120): monitor socket send errors count : 1
I/wpa_supplicant( 6120): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1916-2\x00 that cannot receive messages
D/WifiMonitor( 1034): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,W/wpa_supplicant( 6120): USIM:  scard_deinit function
D/WifiMonitor( 1034): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1034):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=372492  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1034):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=372493  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/UEI.SmartControl( 7434): --- Selecting new region: 6
,I/UEI.SmartControl( 7434): Model = LG-D855
D/UEI.SmartControl( 7434): QS Service created
W/libprocessgroup( 1034): failed to open /acct/uid_10011/pid_6930/cgroup.procs: No such file or directory
,I/UEI.SmartControl( 7434): Service initServices...
D/UEI.SmartControl( 7434): QS start get config
,D/UEI.SmartControl( 7434): Loading JNI Libs...
,D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
,D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
W/FormManager( 7458): Network not available. Please check & try again.
,I/wpa_supplicant( 6120): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1034): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1034): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1034): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1034):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
V/FormManager( 7458): Network unavailable.
V/FormManager( 7458): Network unavailable.
,D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1034): Killing 6987:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10019/pid_6987/cgroup.procs: No such file or directory
,D/WifiOffDelayIfNotUsed( 1034): stopMonitoring
E/WifiStateMachine( 1034): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1034): useWiFiOffloading() : false
E/WifiStateMachine( 1034): CONFIG_LGE_WLAN_PATH : true
D/WfdsService( 1916): Supplicant Connection state is changed : false
D/WfdsService( 1916): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1916): Set the WFDS Monitor: false
D/WfdsMonitor( 1916): WFDS Monitor is stopped
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/StatusBar.NetworkController( 1458): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1916): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1034): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1034): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1034): batteryPsActivateMsgHandler : this is not treated
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/PCSuite ( 7377): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/LGDMClient( 3975): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/PCSuite ( 7377): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7377): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7264): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/FormManager( 7458): Network not available. Please check & try again.
V/FormManager( 7458): Network unavailable.
D/WiFiOffLoadBroadcast( 7264): MCCMNC not supported: null
,V/FormManager( 7458): Network unavailable.
,I/UEI.SmartControl( 7434): Supports setup maps: true
,D/UEI.SmartControl( 7434): QS start statue = true Error code = 0
I/UEI.SmartControl( 7434): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7434): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7434): ### init IR Blaster...
D/serial_port( 7434): Configuring serial port
E/UEI.SmartControl( 7434): UEIBLaster setting for 616
I/UEI.SmartControl( 7434): Setting serial record hearder size = 2
I/UEI.SmartControl( 7434): configuring settings for MAXQ616
I/UEI.SmartControl( 7434): Get version...
D/UEI.SmartControl( 7434): serial port data available: 21
,D/UEI.SmartControl( 7434): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 7434): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 7434): QS saving settings...
D/UEI.SmartControl( 7434): IR Blaster version: 25672567
,D/UEI.SmartControl( 7434): serial port data available: 4
,I/UEI.SmartControl( 7434): Device manager: loading config....
,D/UEI.SmartControl( 7434): ----------- loading internal config...
,W/ContextImpl( 7434): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7434): Services init done
D/UEI.SmartControl( 7434): QS Service init finished
D/UEI.SmartControl( 7434): QS Service version name: 2.1.91
D/UEI.SmartControl( 7434): QS Service version code: 201091
D/UEI.SmartControl( 7434): Service requested: Control
,E/UEI.SmartControl( 7434): Loading SETTINGS...
D/UEI.SmartControl( 7434): Request IControl service: devices are loaded...
I/QRemote ( 6285): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/ActivityManager( 1034): Killing 6476:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/UEI.SmartControl( 7434): ------ IControl API: 11
I/UEI.SmartControl( 7434): Registering callback...
I/UEI.SmartControl( 7434): ------ IControl API: 19
D/UEI.SmartControl( 7434): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7434): Registering Services Ready callback...
I/UEI.SmartControl( 7434): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7434): -----service ready thread exits
,I/QRemote ( 6285): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6285): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6285): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6285): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6285): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7434): ------ IControl API: 8
D/QRemote ( 6285): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6285): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6285): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6285): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6285): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6285): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1034): failed to open /acct/uid_10027/pid_6476/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7434): Internal service binding...
,D/QRemote ( 6285): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6285): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454460423737]
,D/QRemote ( 6285): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6285): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6285): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6285): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 6285): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiStateMachine( 1034):  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533489334] bl(1) rssi=-127 ag=0 br lr ticks 1,0,0 ls-=0 [56,56,52,50,50] brc=1 lrc=0
,E/WifiStateMachine( 1034):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1533489322] bl(1) rssi=-127 ag=0 br lr ticks 1,0,0 ls-=0 [56,56,52,50,50] brc=1 lrc=0
,D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1034): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1034): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1034): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5235): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5235): type=WIFI subType= reason=null isConnected=false
W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1034): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7501 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1034): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1034): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7501): onCreate
,W/AppUp4:DB( 7501):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7501):  setFingerPrint start
I/AppUp4:DB( 7501):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7501):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7501):  SDK version = 21
I/AppUp4:DB( 7501):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7501): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7501): onReceive
D/LgDataFeature( 7501): LgDataFeature() Constructor: none
D/LgDataFeature( 7501): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7501): Context : android.app.ReceiverRestrictedContext@e91504e
D/AppUp4:CustFacade( 7501): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7501): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7501): begin check event
I/AppUp4:CustModeStarterReceiver( 7501): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7501): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7501): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7501): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7501): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1034): Killing 7024:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1034): failed to open /acct/uid_10080/pid_7024/cgroup.procs: No such file or directory
,W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3975): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1034): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7538 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7538): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7538): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7538): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7538): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7538): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7538): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7538): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7538): LgDataFeature() Constructor: none
D/LgDataFeature( 7538): LgDataFeature() Constructor Done, null
,D/eas_req ( 7538): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 7538): JNI_OnLoad()
,I/HubEmail( 7538): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7538): registerNatives()
I/HubEmail( 7538): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7538): registerNativeMethods()
I/HubEmail( 7538): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7538): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7538): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7458): Network unavailable.
,V/FormManager( 7458): Network unavailable.
W/FormManager( 7458): Network not available. Please check & try again.
I/ActivityManager( 1034): Killing 6680:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = false
,W/libprocessgroup( 1034): failed to open /acct/uid_10097/pid_6680/cgroup.procs: No such file or directory
I/ActivityManager( 1034): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7577 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1034): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7599 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 7041:com.google.android.gms:car/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10005/pid_7041/cgroup.procs: No such file or directory
,I/ActivityManager( 1034): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7616 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 7069:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10005/pid_7069/cgroup.procs: No such file or directory
,I/art     ( 7616): Almond Protected OAT
,D/WeatherApplication( 7616): removeAccount
,D/WeatherApplication( 7616): Account.length = 0
,E/WeatherApplication( 7616): OPERATOR:OPEN
D/WeatherAncestor( 7616): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:47:6
D/Weather.Utils( 7616): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7616): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7616): 2 : This is isUpdating : false
D/WeatherAncestor( 7616): connectivity changed - connection : true
,D/WeatherService( 7616): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7616): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7616): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7616): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7616): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7616): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:47:6
I/ActivityManager( 1034): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7634 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1034): Killing 6953:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10044/pid_6953/cgroup.procs: No such file or directory
,D/LGWifiP2pService( 1034): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1034): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1034):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1034):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7634): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7634): Loading: webviewchromium
,I/LibraryLoader( 7634): Time to load native libraries: 5 ms (timestamps 5989-5994)
I/LibraryLoader( 7634): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7634): Binding Chromium to main looper Looper (main, tid 1) {3ac10b7b}
,I/LibraryLoader( 7634): Expected native library version number "",actual native library version number ""
I/chromium( 7634): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7634): Initializing chromium process, renderers=0
W/art     ( 7634): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  314): registerClient() client 0xb14277a0, uid 10093
,W/AudioManagerAndroid( 7634): Requires BLUETOOTH permission
W/chromium( 7634): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7634): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7634): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 7634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7634): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7634): Build Date: 12/12/14 금
I/Adreno-EGL( 7634): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7634): Remote Branch: 
I/Adreno-EGL( 7634): Local Patches: 
I/Adreno-EGL( 7634): Reconstruct Branch: 
,I/NSApplication( 7634): Starting up...
,I/ActivityManager( 1034): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7704 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1034): Killing 6744:com.lge.clock/u0a10 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_10010/pid_6744/cgroup.procs: No such file or directory
,W/ResourcesManager( 7704): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2321): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2321): num queued entries: 0
I/iu.UploadsManager( 2321): num updated entries: 0
I/iu.SyncManager( 2321): NEXT; no task
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7325): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/GLSActivity( 2051): [ac] getting account id
,W/ContextImpl( 7325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7501): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7501): onReceive
I/GLSUser ( 2051): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/AppUp4:CustFacade( 7501): Context : android.app.ReceiverRestrictedContext@e91504e
,D/AppUp4:CustFacade( 7501): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7501): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7501): begin check event
I/AppUp4:CustModeStarterReceiver( 7501): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3975): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7538): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3975): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/Settings( 7538): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 7458): Network not available. Please check & try again.
I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = false
V/FormManager( 7458): Network unavailable.
,D/WeatherAncestor( 7616): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:47:7
D/Weather.Utils( 7616): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7616): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7616): 2 : This is isUpdating : false
V/FormManager( 7458): Network unavailable.
D/WeatherAncestor( 7616): connectivity changed - connection : true
D/WeatherService( 7616): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2520f27c
D/ForecastDataCache( 7616): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7616): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7616): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7616): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7616): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:47:7
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/UEI.SmartControl( 7434): Internal timer expired: 1
D/UEI.SmartControl( 7434): unbind internal service
,D/serial_port( 7434): close(fd = 25)
,I/UEI.SmartControl( 7434): Serial port is closed.
D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{12bb7ebb type 2 when 378924 com.google.android.gms} when 378924
,I/art     ( 1034): Explicit concurrent mark sweep GC freed 41903(1966KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.965ms total 173.752ms
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1034): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/GAV4    ( 7634): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1034): Killing 6459:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10054/pid_6459/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 387793536730; DSPS: 12847900; Offset : -4303704583
,V/AlarmManager( 1034): ELAPSED_WAKEUP set : Alarm{37f51616 type 2 when 397135 android} when 397135
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 407795408234; DSPS: 13503322; Offset : -4303725299
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 427797162861; DSPS: 14158739; Offset : -4303710121
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 447799261187; DSPS: 14814168; Offset : -4303717587
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 467801735659; DSPS: 15469609; Offset : -4303714908
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 487803512682; DSPS: 16125027; Offset : -4303707802
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 507805545487; DSPS: 16780454; Offset : -4303719725
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 527807639854; DSPS: 17435882; Offset : -4303700216
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 547809465731; DSPS: 18091302; Offset : -4303705627
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 567812029944; DSPS: 18746746; Offset : -4303704761
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 587814092071; DSPS: 19402174; Offset : -4303717830
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 607816069562; DSPS: 20057599; Offset : -4303723902
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 627818066847; DSPS: 20713024; Offset : -4303710287
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 647820229548; DSPS: 21368455; Offset : -4303714569
,I/ActivityManager( 1034): Killing 7307:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1034): failed to open /acct/uid_10037/pid_7307/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 667822089489; DSPS: 22023876; Offset : -4303716303
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 687824133543; DSPS: 22679303; Offset : -4303716980
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 707826231348; DSPS: 23334732; Offset : -4303724626
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 727828091913; DSPS: 23990153; Offset : -4303725478
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 747830722166; DSPS: 24645599; Offset : -4303719736
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 767832835127; DSPS: 25301028; Offset : -4303712592
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 787834670901; DSPS: 25956448; Offset : -4303707977
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 807836495685; DSPS: 26611868; Offset : -4303714248
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 827838558594; DSPS: 27267296; Offset : -4303726534
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 847840710253; DSPS: 27922726; Offset : -4303711210
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 867842792745; DSPS: 28578154; Offset : -4303703758
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 887844569457; DSPS: 29233573; Offset : -4303727687
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 907846643251; DSPS: 29889001; Offset : -4303729009
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
,I/[SystemUI]Clock( 1458): called onTimeUpdated()
I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 927848713191; DSPS: 30544428; Offset : -4303703799
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 947851446674; DSPS: 31199878; Offset : -4303716873
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 967853566093; DSPS: 31855307; Offset : -4303703167
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 987855631189; DSPS: 32510735; Offset : -4303713291
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1007857566702; DSPS: 33166159; Offset : -4303730643
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1027859636173; DSPS: 33821586; Offset : -4303706110
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/WifiController( 1034): battery changed pluggedType: 2
,D/LEDHandler( 1916): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1916): Battery Level Remaining: 100%
D/LEDHandler( 1916): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1047862288094; DSPS: 34477033; Offset : -4303709166
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1067864136003; DSPS: 35132454; Offset : -4303722829
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1087866211672; DSPS: 35787882; Offset : -4303722408
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1107868299268; DSPS: 36443310; Offset : -4303709956
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1127870475615; DSPS: 37098741; Offset : -4303700304
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1147872511440; DSPS: 37754168; Offset : -4303709209
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/PowerManagerServiceEx( 1034): acquireWakeLockInternal: lock=918237470, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,I/ActivityManager( 1034): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7868 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2564): onStartCommand(). Type : 9
,I/art     (  336): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 40.919ms
,I/art     (  336): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 28.266ms
,I/art     (  336): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.642ms
,I/DigitalAppWidgetProvider( 7868): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7868): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@6c6eb13
D/PowerManagerServiceEx( 1034): releaseWakeLockInternal: lock=918237470 [*alarm*], flags=0x0
I/ActivityManager( 1034): Killing 7354:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1034): failed to open /acct/uid_1000/pid_7354/cgroup.procs: No such file or directory
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/WifiController( 1034): battery changed pluggedType: 2
D/LEDHandler( 1916): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1916): Battery Level Remaining: 100%
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1916): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1167874414662; DSPS: 38409590; Offset : -4303698025
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1187876448300; DSPS: 39065017; Offset : -4303709246
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1207878304595; DSPS: 39720438; Offset : -4303714342
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/LEDHandler( 1916): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1916): Battery Level Remaining: 100%
D/LEDHandler( 1916): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/WifiController( 1034): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1458): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
,I/[SystemUI]LGPowerUI( 1458): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]BatterySaverHandler( 1458): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 3975): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/UsageStatsService( 1034): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1227880860056; DSPS: 40375882; Offset : -4303722435
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1247882897027; DSPS: 41031308; Offset : -4303699546
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1267884336812; DSPS: 41686716; Offset : -4303724918
,I/[SystemUI]TimeTickManager( 1458): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1458): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1458): called onTimeUpdated()
I/[SystemUI]Clock( 1458): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
,I/[SystemUI]DateView( 1458): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1458): handleTimeUpdate
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1287891562221; DSPS: 42342312; Offset : -4303701449
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1034): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1034): tsOffsetIs: Apps: 1307893645442; DSPS: 42997741; Offset : -4303724046
,TIME-OUT KILL (timeout was 1200000ms)
```
