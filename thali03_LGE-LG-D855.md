#### Test 506502784dae475_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1455): called onTimeUpdated()
I/LgeClockWidgetControlView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
I/[SystemUI]DateView( 1455): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
,D/AndroidRuntime( 6052): 
D/AndroidRuntime( 6052): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6052): CheckJNI is OFF
D/AndroidRuntime( 6052): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1939): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{1a2480ef #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{1a2480ef #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6071 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6052): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1850): Display #0 changed.
D/SplitWindowPolicy( 1939): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1939): topRunningActivity=ActivityInfo{32945793 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1939): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1939): topRunningActivity=ActivityInfo{a8a43d0 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6071): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6071): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6071): Loading: webviewchromium
,I/LibraryLoader( 6071): Time to load native libraries: 5 ms (timestamps 2730-2735)
I/LibraryLoader( 6071): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6071): Binding Chromium to main looper Looper (main, tid 1) {1bc13bac}
,I/LibraryLoader( 6071): Expected native library version number "",actual native library version number ""
I/chromium( 6071): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6071): Initializing chromium process, renderers=0
W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6071): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  323): registerClient() client 0xb558a940, uid 10311
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21d5be01:true
D/BluetoothAdapter( 6071): 75300981: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6071): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6071): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,I/chromium( 6071): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6071): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6071): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6071): Build Date: 12/12/14 금
I/Adreno-EGL( 6071): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6071): Remote Branch: 
I/Adreno-EGL( 6071): Local Patches: 
I/Adreno-EGL( 6071): Reconstruct Branch: 
,W/chromium( 6071): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6071): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6071): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6071): CordovaWebView is running on device made by: LGE
,W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6071): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6071): Render dirty regions requested: true
I/OpenGLRenderer( 6071): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6071): Enabling debug mode 0
D/Atlas   ( 6071): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{3479d273 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{28ade7fc u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 6071): LgDataFeature() Constructor: none
D/LgDataFeature( 6071): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9afec8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1455): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1455): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1455):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1455): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +648ms (total +734ms)
,I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{28ade7fc u0 com.test.thalitest/.MainActivity t4} time:253182
I/Timeline( 6071): Timeline: Activity_idle id: android.os.BinderProxy@230ff0e5 time:253185
I/chromium( 6071): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6071): 
,D/JsMessageQueue( 6071): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6071): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435084032
D/JX-Cordova( 6071): jxcore cordova android initializing
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
,I/GBMv2   (  340): DFP Enabled. Ignore VFP set
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 254158320167; DSPS: 8469157; Offset : -4312997992
W/jxcore-log( 6071): Initializing JXcore engine
W/jxcore-log( 6071): JXcore engine is ready
,W/jxcore-log( 6071): Starting JXcore engine
W/.test.thalitest( 6071): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[8380]" dev="sockfs" ino=8380 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6071): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6071): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10072]" dev="sockfs" ino=10072 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6071): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6071): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30357]" dev="sockfs" ino=30357 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 6071): Background sticky concurrent mark sweep GC freed 123906(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.604ms total 123.070ms
,W/jxcore-log( 6071): Platform android
W/jxcore-log( 6071): 
,W/jxcore-log( 6071): Process ARCH arm
W/jxcore-log( 6071): 
I/jxcore-log( 6071): JXcore Cordova bridge is ready!,
I/jxcore-log( 6071): 
W/jxcore-log( 6071): JXcore engine is started
,I/chromium( 6071): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6071): 
,I/jxcore-log( 6071): Toggling radios to true
I/jxcore-log( 6071): 
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1037): Message: 1
D/BluetoothManagerService( 1037): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1037): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1037): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1037): JNI:system_update. Event-4
D/WifiService( 1037): New client listening to asynchronous messages
I/ActivityManager( 1037): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6127 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6071, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6071, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6071, uid=10311, packageName=com.test.thalitest
D/LocationManagerService( 1037): getAllProviders()=[passive, gps, network]
,D/Ulp_jni ( 1037): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1037): JNI:system_update. Event-4
E/WifiStateMachine( 1037):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1037): reconnect pid=6071, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1037): [GET_FTM][id=6], offset=12288
I/jxcore-log( 6071): Radios toggled
I/jxcore-log( 6071): 
E/WifiUtil( 1037): wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1037): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1037): wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1037): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1037): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1037): unknown target_country: EU , set to default
E/WifiHW  ( 1037): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1037): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1037): gEnableBmps=1
,W/ResourcesManager( 6127): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6127): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6127): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6127): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6127): Loading JNI Library
,D/SoftapController(  318): Softap fwReload - Ok
,D/CommandListener(  318): Setting iface cfg
D/CommandListener(  318): Trying to bring down wlan0
D/CommandListener(  318): Clearing all IP addresses on wlan0
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1037): InitialState.processMessage what=4
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/WifiHW  ( 1037): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6166 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1037): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1037): useWiFiOffloading() : false
E/WifiStateMachine( 1037): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1037): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1037): connecting to supplicant
,V/WfdStateTracker( 1939): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServerServiceExt( 1037): WIFI_STATE_CHANGED_ACTION [2]
W/wpa_supplicant( 6165): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6165): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6165): Successfully initialized wpa_supplicant
,D/BluetoothAdapterApp( 6127): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@ab12780 Instance Count = 1
,I/wpa_supplicant( 6165): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6165): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterApp( 6127): onCreate
W/ResourcesManager( 6166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6166): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ProfileConfigQcom( 6127): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6127): Adding HeadsetService
D/ProfileConfigQcom( 6127): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6127): Adding A2dpService
D/ProfileConfigQcom( 6127): [BTUI] HidService is supported
D/ProfileConfigQcom( 6127): Adding HidService
D/ProfileConfigQcom( 6127): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6127): Adding HealthService
D/LGBluetoothFeatureConfig( 6127): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6127): [BTUI] PanService is supported
D/ProfileConfigQcom( 6127): Adding PanService
D/ProfileConfigQcom( 6127): [BTUI] GattService is supported
D/ProfileConfigQcom( 6127): Adding GattService
D/ProfileConfigQcom( 6127): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6127): Adding BluetoothMapService
D/ProfileConfigQcom( 6127): [BTUI] HeadsetClientService is NOT supported
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dcc2492:true
,D/BluetoothAdapterState( 6127): make
I/LGFMServiceAdapter( 6127): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6127): init
I/BluetoothAdapterState( 6127): Entering OffState
I/bte_conf( 6127): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6127): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6127): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6127): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6127): [BTUI] lge_load_bluetooth_address
,I/bluedroid-qcom( 6127): get_profile_interface socket
I/GKI_LINUX( 6127): gki_task_entry task_id=1 [BTIF] starting
,W/bdaddr_loader( 6188): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6188): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/lge_bdaddr_loader( 6188): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6188): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6188): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6188): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
I/bluedroid-qcom( 6127): get_profile_interface map_client
D/BluetoothAdapterProperties( 6127): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6127): Name is: G3-1
D/BluetoothManagerService( 1037): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1037): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1037): Message: 40
,D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6127): config_hci_snoop_log
D/BluetoothManagerService( 1037): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1037): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6188): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6188): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6127): Create singleton instance
,D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6166): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6166): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6166): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/wpa_supplicant( 6165): rfkill: Cannot open RFKILL control device
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterState( 6127): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6127): Setting state to 11
I/BluetoothAdapterState( 6127): Bluetooth adapter state changed: 10-> 11
I/LGBluetoothServiceJni( 6127): classInitNative: succeeds
D/BluetoothManagerService( 1037): Message: 60
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1037): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1939): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1455): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6127): make
,D/UsbSettingsControl( 6166): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6166): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6166): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1037): Killing 5418:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
I/BluetoothBondStateMachine( 6127): StableState(): Entering Off State
D/LGBluetoothServiceAdapter( 6127): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
D/LGBluetoothServiceAdapter( 6127): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6127): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6127): File transfer profiles supported!!
V/BluetoothPbapReceiver( 6127): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6127): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6127): ***********state = 11
I/wpa_supplicant( 6165): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_5418/cgroup.procs: No such file or directory
E/BluetoothAdapterService( 6127): File transfer profiles supported!!
D/BluetoothHeadset( 1037): Proxy object connected
I/wpa_supplicant( 6165): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6165): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/HeadsetService( 6127): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6127): classInitNative: succeeds
D/BluetoothHeadset( 1850): Proxy object connected
D/LGBluetoothHfpAdapter( 6127): Version 1.6
D/BluetoothHeadset( 1850): Proxy object connected
D/BluetoothHeadset( 1850): Proxy object connected
D/LGBluetoothFeatureConfig( 6127): isPrivacyLogsEnabled : true
E/WifiStateMachine( 1037):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
I/BluetoothHeadsetServiceJni( 6127): classInitNative: succeeds
D/HeadsetStateMachine( 6127): make
E/WifiStateMachine( 1037):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1037):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1037):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,E/BluetoothAdapterService( 6127): File transfer profiles supported!!
E/WifiStateMachine( 1037):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6166): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6166): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6166): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1037):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1037): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1037):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1037): MAC Addr from driver = c4:9a:02:7b:60:ac
,D/WifiOffDelayIfNotUsed( 1037): setPowerSaveActivated(false)
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1037): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LgDataFeature( 6127): LgDataFeature() Constructor: none
D/LgDataFeature( 6127): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6193 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/WifiStateMachine( 1037): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1037): useWiFiOffloading() : false
E/WifiStateMachine( 1037): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1037): doBoolean: SET update_config 1
,D/HeadsetStateMachine( 6127): max_hf_connections = 1
I/bluedroid-qcom( 6127): get_profile_interface handsfree
D/WifiNative-wlan0( 1037): SET update_config 1: returned true
D/WifiConfigStore( 1037): Loading config and enabling all networks 
D/WifiNative-wlan0( 1037): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1037):    returned network id / ssid / bssid / flags 0	NG700	any	
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/ToneGenerator( 6127): ToneGenerator constructor: streamType=8, volume=1.000000
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioPolicyService(  323): registerClient() client 0xb57e9080, uid 1002
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/AudioPolicyManager(  323): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  323): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  323): getOutput() returns output 2
V/AudioSystem( 6127): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
I/WifiServerServiceExt( 1037): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1037): batteryPsActivateMsgHandler : state:0 event:3
V/AudioFlinger(  323): registerClient() client 0xb57c40d0, pid 6127
V/ToneGenerator( 6127): Create Track: 0xb4928080
V/AudioTrack( 6127): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6127): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  323): getOutputForAttr() usage=3, content=4, tag= flags=00000000
D/WfdService( 1939): Waiting for WifiP2p enabling
V/AudioPolicyManager(  323): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  323): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  323): getOutput() returns output 2
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioSystem(  323): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  323): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3267): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3267): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  323): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  323): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1037): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1037): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1037): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1037): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6127): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6127): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6127): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6127): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 1455): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1455): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1455): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1455): ioConfigChanged() opening already existing output! 4
E/BluetoothAdapterService( 6127): File transfer profiles supported!!
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3267): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3267): ioConfigChanged() opening already existing ou,tput! 4
I/AudioFlinger(  323): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  323): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  323): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  323): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  323): getOutput() returns output 2
V/AudioSystem( 6127): getLatency() output 2, latency 50
V/AudioSystem( 6127): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6127): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  323): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  323): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  323): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  323): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  323): createTrack() lSessionId: 16
E/WifiConfigStore( 1037): readNetworkVariablesFromSupplicantFile key=psk
E/BluetoothAdapterService( 6127): File transfer profiles supported!!
V/AudioTrack( 6127): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  323): acquiring 16 from 6127, for 6127
V/AudioFlinger(  323):  added new entry for 16
V/ToneGenerator( 6127): ToneGenerator INIT OK, time: 256126
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
D/HeadsetStateMachine( 6127): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6127): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6127): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6127): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  323): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6127
D/UsbSettingsControl( 6166): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6166): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/audio_hw_primary(  323): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  323): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  323): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  323): voice_extn_compress_voip_set_parameters: exit
V/voice   (  323): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  323): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  323): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  323): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  323): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  323): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  323): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6127): ToneGenerator destructor
V/ToneGenerator( 6127): stopTone
V/ToneGenerator( 6127): Delete Track: 0xb4928080
V/AudioTrack( 6127): ~AudioTrack, releasing session id from 6127 on behalf of 6127
V/AudioFlinger(  323): releasing 16 from 6127 for 6127
V/AudioFlinger(  323):  decremented refcount to 0
V/AudioFlinger(  323): purging stale effects
V/AudioPolicyService(  323): AudioCommandThread() adding release output 2
V/AudioPolicyService(  323): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  323): AudioCommandThread() waking up
V/AudioPolicyService(  323): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  323): releaseOutput() 2
V/AudioPolicyService(  323): AudioCommandThread() going to sleep
V/AudioFlinger(  323): PlaybackThread::Track destructor
V/AudioFlinger(  323): removeClient_l() pid 6127, calling pid 323
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
E/BluetoothAdapterService( 6127): File transfer profiles supported!!
D/BluetoothA2dp( 1037): Proxy object connected
D/A2dpService( 6127): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6127): classInitNative: succeeds
E/WifiConfigStore( 1037): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
V/Avrcp   ( 6127): make
E/WifiConfigStore( 1037): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/Avrcp   ( 6127): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6127): get_profile_interface avrcp
D/UsbSettingsControl( 6166): [AUTORUN] setTetherStatus() : status=false
D/WifiStateMachine( 1037): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1037): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1037): SET device_name g3_global_com: returned true
E/BluetoothAdapterService( 6127): File transfer profiles supported!!
D/WifiNative-wlan0( 1037): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1037): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1037): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1037): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1037): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1037): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1037): SET device_type 10-0050F204-5: returned true
V/AudioManager( 6127): registerRemoteController: size of Media player list: 0
E/AudioManager( 6127): No RCC entry present to update
E/RemoteController( 6127): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6127): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6127): initQcomNative: succeeds
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6213 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/WifiStateMachine( 1037): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1037): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1037): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1037): Setting external_sim to 1
D/WifiNative-wlan0( 1037): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1037): SET external_sim 1: returned true
I/WifiNative-HAL( 1037): startHal
E/wifi    ( 1037): getStaticLongField sWifiHalHandle 0x989698dc
E/WifiHAL ( 1037): Could not connect handle
D/wifi    ( 1037): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301c76
I/WifiNative-HAL( 1037): Could not start hal
D/WifiStateMachine( 1037): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1037): startHal
E/wifi    ( 1037): getStaticLongField sWifiHalHandle 0x9896985c
E/WifiHAL ( 1037): Could not connect handle
D/wifi    ( 1037): halHandle = 0x0, mVM = 0xb487c280, mCls = 0xb01b76
I/WifiNative-HAL( 1037): Could not start hal
D/WifiNative-wlan0( 1037): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1037): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] [+] updateMediaPlayerInfo
D/WfdsService( 1939): Supplicant Connection state is changed : true
D/WfdsService( 1939): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1939): Set the WFDS Monitor: true
D/WfdsMonitor( 1939): WfdsMonitorThread create
D/WfdsMonitor( 1939): WFDS Monitor is created and started
D/WfdsService( 1939): WiFi: Supplicant connection re-established
W/Settings( 5957): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1037): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1939): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1939): Succeed to open control connection
E/CtrlSupplicant( 1939): Succeed to open monitor connection
V/LGMDMManager( 6127): Create singleton instance
D/WfdsMonitor( 1939): Supplicant connection established
,D/WfdsService( 1939): Connected to the supplicant for wfds
I/BluetoothAdapterState( 6127): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/WifiNative-wlan0( 1037): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,D/WifiNative-wlan0( 1037): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1037): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1037): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1037): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6165): android_multicast_filter_startstop : multicast filter set
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
,D/WifiNative-wlan0( 1037): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1037): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1037): [256,237,622 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
D/WifiNative-wlan0( 1037): RECONNECT: returned true
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1037):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/LGWifiP2pService( 1037): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  318): Setting iface cfg
D/CommandListener(  318): Trying to bring up p2p0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1037): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1037): P2pEnablingState
D/LGWifiP2pService( 1037): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2p socket connection successful
D/LGWifiP2pService( 1037): P2pEnabledState
D/LGWifiP2pService( 1037): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1037): doBoolean: SET persistent_reconnect 1
V/WfdStateTracker( 1939): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1939): WifiP2pState is changed : true
D/WifiScanningService( 1037): SCAN_AVAILABLE : 3
D/RttService( 1037): SCAN_AVAILABLE : 3
D/RttService( 1037): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1037): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1037): startHal
D/WfdsService( 1939): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1037): SET persistent_reconnect 1: returned true
E/wifi    ( 1037): getStaticLongField sWifiHalHandle 0x97b4799c
,E/WifiHAL ( 1037): Could not connect handle
D/wifi    ( 1037): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x90198e
I/WifiNative-HAL( 1037): Could not start hal
E/WifiScanningService( 1037): could not start HAL
D/WifiNative-p2p0( 1037): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1037): SET device_name G3-1: returned true
D/LGWifiP2pService( 1037): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1037): before postfix = G3-1
D/WifiServerServiceExt( 1037): postfix byte check : 4
D/LGWifiP2pService( 1037): after postfix = G3-1
D/WifiNative-p2p0( 1037): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1037): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1037): doBoolean: SET device_type 10-0050F204-5
D/WfdsService( 1939): Receive the WFDS_ENABLE Method
D/WfdsService( 1939): Set the WFDS Monitor: true
D/WfdsService( 1939): Connected to the supplicant for wfds
D/WfdsJNI ( 1939): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6165): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WifiNative-p2p0( 1037): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1037): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WfdsJNI ( 1939): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6165): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1939): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1939): selectPreferredScanChannel [36]
E/WifiStateMachine( 1037):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WfdsService( 1939): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1037):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_START_DRIVER 0 0
D/WfdsService( 1939): isConnected: false
E/WifiStateMachine( 1037):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1037):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1037):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1037):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1037): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6165): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1037):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1037):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1037):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1037): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6165): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1037):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1037):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1037):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1037): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-p2p0( 1037): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SET conc_pref p2p
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6165): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6165): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6165): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1037): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1037):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
I/wpa_supplicant( 6165): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1037):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6165): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,D/WifiNative-wlan0( 1037): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1037): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SCAN
D/WifiNative-wlan0( 1037): SCAN: returned false
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=256272  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WfdsMonitor( 1939): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1939): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=256274  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiStateMachine( 1037):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1037):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,E/WifiStateMachine( 1037):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1037):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1037): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1037): p2pGetDeviceAddress
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
D/WifiNative-HAL( 1037): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1037): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1037): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1037): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1037): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1037): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1037):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1037): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1939): handleP2pThisDeviceChanged
D/WfdsService( 1939): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1939): Update P2p Interface State: 3
D/WifiService( 1037): New client listening to asynchronous messages
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/WifiNative-p2p0( 1037): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1037): sending p2p persistent groups changed broadcast
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6238 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/LGWifiP2pService( 1037): InactiveState
D/LGWifiP2pService( 1037): InactiveState{ when=-56ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-56ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6165): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6165): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6165): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1037): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6165): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1037): InactiveState{ when=-48ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-48ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1939): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1939): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1939): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/ActivityThread( 6193): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6193): No ProfileInfo ,entries
I/LG Account v2.2( 6193): isEnabled: false
I/Feature ( 6193): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6193): [Lifetracker]Country: EU
I/Feature ( 6193): [Lifetracker]Operator: OPEN
I/Feature ( 6193): [Lifetracker]Ranking support: false
I/Feature ( 6193): [Lifetracker]Comfort support: false
I/Feature ( 6193): [Lifetracker]Accessory: true
I/Feature ( 6193): [Lifetracker]Health device: true
I/Feature ( 6193): [Lifetracker]Extra Pedometer: false
I/Feature ( 6193): [Lifetracker]Blood glucose device: false
I/Feature ( 6193): [Lifetracker]Device Number: 3
W/WfdsService( 1939): DefaultState - msg [9441285] is not handled
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
W/FormManager( 6213): Network not available. Please check & try again.
,W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
V/FormManager( 6213): Network unavailable.
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] installed app name: Music
V/FormManager( 6213): Network unavailable.
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6127): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6127): classInitNative
I/BluetoothA2dpServiceJni( 6127): classInitNative: succeeds
D/A2dpStateMachine( 6127): make
I/bluedroid-qcom( 6127): get_profile_interface a2dp
I/GKI_LINUX( 6127): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/LGBluetoothA2dpServiceJni( 6127): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6127): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
D/A2dpStateMachine( 6127): Enter Disconnected: -2
D/HeadsetStateMachine( 6127): Proxy object connected
D/BluetoothPermissionRequest( 6166): onReceive
D/LGBluetoothHfpAdapter( 6127): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6127): Try to query the phonestate on bind
D/LGBluetoothFeatureConfig( 6166):  get() - isFeatureLoaded : false
D/BluetoothPhoneService.BluetoothLTECall( 1850):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1850): Proxy not attached to service
I/BluetoothHidServiceJni( 6127): classInitNative: succeeds
D/BluetoothHeadset( 1850): java.lang.Throwable
D/BluetoothHeadset( 1850): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1850): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1850): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1850): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1850): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1850): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1850): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1850): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/HidService( 6127): Received start request. Starting profile...
I/bluedroid-qcom( 6127): get_profile_interface hidhost
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
I/BluetoothHealthServiceJni( 6127): classInitNative: succeeds
D/HealthService( 6127): Received start request. Starting profile...
,I/bluedroid-qcom( 6127): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6127): classInitNative: succeeds
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
I/BluetoothPanServiceJni( 6127): classInitNative(L105): succeeds
D/PanService( 6127): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6127): initializeNative(L110): pan
I/bluedroid-qcom( 6127): get_profile_interface pan
I/ActivityManager( 1037): Killing 5444:com.android.contacts/u0a19 (adj 15): empty #17
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@246439f9:true
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/LGBluetoothPanAdapter( 6127): [BTUI] getInstance : create [LGBluetoothPanAdapter]
,D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
D/BluetoothAdapterService( 6127): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6127): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6127): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/BtGatt.JNI( 6127): classInitNative(L901): classInitNative: Success!
D/HeadsetStateMachine( 6127): Disconnected process message: 11, size: 0
D/BtGatt.DebugUtils( 6127): handleDebugAction() action=null
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_5444/cgroup.procs: No such file or directory
D/BtGatt.GattService( 6127): Received start request. Starting profile...
D/BtGatt.GattService( 6127): start()
I/bluedroid-qcom( 6127): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6127): advertise manager created
I/ActivityManager( 1037): Killing 5782:com.lge.email/u0a23 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6166): return without doing reset settings.
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/wpa_supplicant( 6165): USIM:  scard_init function
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1037): startHal
,E/wifi    ( 1037): getStaticLongField sWifiHalHandle 0x989698cc
E/WifiHAL ( 1037): Could not connect handle
D/wifi    ( 1037): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5020f6
I/WifiNative-HAL( 1037): Could not start hal
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6165): Trying to associate with SSID 'NG700'
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_5782/cgroup.procs: No such file or directory
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=256555  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=256556  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
I/LGBluetoothMapAdapter( 6127): [BTUI] getInstance : create [LGBluetoothMapAdapter]
I/ActivityManager( 1037): Killing 5464:com.android.gallery3d/u0a27 (adj 15): empty #17
V/BluetoothMapService( 6127): BluetoothMapBinder()
D/BluetoothMapService( 6127): Received start request. Starting profile...
D/BluetoothMapService( 6127): start()
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WifiService( 1037): New client listening to asynchronous messages
,D/LgDataFeature( 6166): LgDataFeature() Constructor: none
,D/LgDataFeature( 6166): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6166): remove : truetruetrue
E/WifiStateMachine( 1037):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1037):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6166): remove1
V/WiFiOffLoadSharedPrefsUtils( 6166): save remove
I/wpa_supplicant( 6165): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=256645  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=256645  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WiFiOffLoadBroadcast( 6166): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=256646
D/WiFiOffLoadBroadcast( 6166): S: false, R: false
,E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=256647
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=256648
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=256648
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=256649
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=256650  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_5464/cgroup.procs: No such file or directory
,D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothMapEmailSettingsLoader( 6127): Found 0 applications
D/BluetoothMapEmailAppObserver( 6127): createReceiver()
D/BluetoothMapEmailAppObserver( 6127): initObservers()
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=256694  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/BluetoothMapEmailAppObserver( 6127): getEnabledAccountItems()
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/BluetoothAdapterService( 6127): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6127): Profile still not running:com.android.bluetooth.gatt.GattService
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterService( 6127): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6127): [BTUI] SIM Extra State :ABSENT
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1037):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/BluetoothAdapterService( 6127): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=256720  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=256720  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=256721
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=256722
D/BluetoothAdapterService( 6127): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/WifiNative-wlan0( 1037): doString: [STATUS]
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/LGBluetoothOppAdapter( 6127): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
V/BluetoothMapService( 6127): Handler(): got msg=1
D/BluetoothAdapterState( 6127): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6127): enable
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
I/bt_hci_bdroid( 6127): init
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
D/WiFiOffLoadUpdatePriority( 6166): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6166): connected SSID: null
I/GKI_LINUX( 6127): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6127): btu_task pending for preload complete event
D/WiFiOffLoadUpdatePriority( 6166): private wpa: "NG700" 300
V/BluetoothFtpReceiver( 6127): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6127): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6127): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6127): SapReceiver onReceive 
V/BluetoothSapReceiver( 6127): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6127):  Bluetooth Adapter state = 11
I/bt_vendor( 6127): bt-vendor : init
I/bt_vendor( 6127): bt-vendor : get_bt_soc_type
E/bt_vendor( 6127): get_bt_soc_type: Failed to get soc type
D/WifiServiceImplEx( 1037): addOrUpdateNetwork pid=6166, uid=1000, packageName=android.uid.system:1000
I/bt_vendor( 6127): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6127): userial_init
,D/bt_hci_bdroid( 6127): set_power 1
E/addOrUpdateNetwork( 1037):  uid = 1000 SSID "NG700" nid=0
I/bt_vendor( 6127): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6127): Starting hciattach daemon
I/bt_vendor( 6127): try to set true
W/sh      ( 6274): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6274): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/qcom-bluetooth( 6275): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1037): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6276 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{337d2cab type 2 when 252378 android} when 252378
,I/qcom-bluetooth( 6298): /system/etc/init.qcom.bt.sh: Transport : smd 
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1037): Got NetworkAgent Messenger
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
I/qcom-bluetooth( 6300): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
W/ResourcesManager( 6276): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/CommandListener(  318): Setting iface cfg
I/qcom-bluetooth( 6302): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/DhcpStateMachine( 1037): StoppedState
E/WifiStateMachine( 1037): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=256837  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/ActivityManager( 1037): Killing 5107:com.wsandroid.suite.lge/1000 (adj 15): empty #17
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=256837  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=256838  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/qcom-bluetooth( 6304): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
I/qcom-bluetooth( 6305): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6306): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6308): ESOC framework not supported
,E/Diag_Lib( 6308):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/bthci_qcomm_linux( 6308): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6308): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6308): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6308): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6308): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6308): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6308): [BTUI] init_riva_entries: set NORMAL power settings
D/AuthorizationBluetoothService( 2110): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5107/cgroup.procs: No such file or directory
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=256959  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=256961  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=256962  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 is current
E/WifiStateMachine( 1037):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 is current
E/WifiStateMachine( 1037):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 is current
E/WifiConfigStore( 1037):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1037): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/[Concierge]Service( 2595): onStartCommand(). Type : 9
I/rmt_storage(  315): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  315): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  315): wakelock acquired: 1, error no: 42
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1037): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1037): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1037): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1037): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1037): will read network variables netId=0
E/WifiConfigStore( 1037): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1037):  writeKnownNetworkHistory() num networks:1 needWrite=false
,D/WiFiOffLoadUpdatePriority( 6166):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6166): configuration updated: 0
E/WifiStateMachine( 1037):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1947730160] from screen [on:0 period:-1947730160]
E/WifiStateMachine( 1037):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1947730159]
I/WifiNative-HAL( 1037): startHal
E/wifi    ( 1037): getStaticLongField sWifiHalHandle 0x989698bc
E/WifiHAL ( 1037): Could not connect handle
D/wifi    ( 1037): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301e3a
I/WifiNative-HAL( 1037): Could not start hal
,D/WifiNative-wlan0( 1037): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  315): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  315): 
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
,D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
E/Diag_Lib(  886): [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/rmt_storage(  315): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb99502 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb99502 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6166): configuration saved: true
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 6213): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/FormManager( 6213): Network unavailable.
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1037): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6315 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/FormManager( 6213): Network unavailable.
,W/ResourcesManager( 6315): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 6315): init()
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6335): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6335): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6335): version 5.5.6 starting
E/dhcpcd  ( 6335): get_duid: m
D/dhcpcd  ( 6335): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6335): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6335): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6335): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6335): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6335): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 6335): wlan0: sending REQUEST (xid 0x16a85d3c), next in 4.54 seconds
W/ExternalStrings( 6315): load override strings
W/ExternalStrings( 6315): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6315): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6315): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6315): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6315): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6315): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6315): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6315): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6315): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6315): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6315): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6315): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6315): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6315): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6315): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6315): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6315): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6315): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6315): onCreate
V/Signer  ( 6315): override build config not found
D/Signer  ( 6315): value of property debug is false
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6315): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6315): Create singleton instance
D/LGMDMWrapper( 6315): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6238): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
E/QC-QMI  ( 6308): qmi_client [6308] 13: failed to locate client data
E/QC-QMI  (  473): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  473): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6348 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 5697:com.android.defcontainer/u0a4 (adj 15): empty #17
I/art     (  352): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.179ms total 11.322ms
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 253us total 11.695ms
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.005ms
I/qcom-bluetooth( 6365): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_5697/cgroup.procs: No such file or directory
W/ResourcesManager( 6348): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/qcom-bluetooth( 6366): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
W/ActivityThread( 6315): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/QRemote ( 6348): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
I/bt_vendor( 6127): bluetooth satus is on
D/bt_hci_bdroid( 6127): preload
D/bt_userial_mct( 6127): userial_open(port:0)
I/bt_vendor( 6127): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6127): Done intiailizing UART
I/bt_vendor( 6127): Done intiailizing UART
I/bt_userial_mct( 6127): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6127): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6127): btu_task received preload complete event
D/bt_userial_mct( 6127): Entering userial_read_thread()
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6127): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6127): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6127): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6127): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6127): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6127): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6127): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6127): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6127): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6127): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6127): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6127): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6127): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6127): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6127): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6127): BTE_InitTraceLevels -- TRC_BTIF
D/QRemote ( 6348): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6348): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6348): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6348): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6348): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6348): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
W/bt-btm  ( 6127): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6127): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e6061 
E/bt-btm  ( 6127): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e6061 
D/QRemote ( 6348): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
E/bt-btif ( 6127): Calling BTA_HhEnable
E/bt-btif ( 6127): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6127): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6127): Name is: G3-1
D/BluetoothManagerService( 1037): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1037): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6127): Scan Mode:20
D/BluetoothAdapterProperties( 6127): Discoverable Timeout:120
D/bt_hci_bdroid( 6127): postload
D/bt_hci_bdroid( 6127): Used up Tx Cmd credits
W/bt-l2cap( 6127): L2CAP - L2CA_Register() called for PSM: 0x000f
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/bte_conf( 6127): Device ID record 1 : primary
D/bte_conf( 6127):   vendorId            = 00c4
D/bte_conf( 6127):   vendorIdSource      = 0001
D/bte_conf( 6127):   product             = 13a1
D/bte_conf( 6127):   version             = 1000
D/bte_conf( 6127):   clientExecutableURL = 
D/bte_conf( 6127):   serviceDescription  = 
D/bte_conf( 6127):   documentationURL    = 
D/bte_conf( 6127): bte_load_did_conf no section named DID2.
W/bt-smp  ( 6127): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6127): Plain text(LSB ~ MSB) = 82 8c 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6127): Encrypted text(LSB ~ MSB) = ed 58 43 d1 c7 e6 73 44 49 6e 10 ca 93 a3 5a 70 
W/bt-btm  ( 6127): Stopping oneshot timer
D/bt_hci_bdroid( 6127): Used up Tx Cmd credits
D/bt_hci_bdroid( 6127): Used up Tx Cmd credits
D/bt_hci_bdroid( 6127): Used up Tx Cmd credits
D/bt_hci_bdroid( 6127): Used up Tx Cmd credits
E/bt_mct  ( 6127): hci lib postload completed
D/BluetoothPanServiceJni( 6127): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6127): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6127): ScanMode =  20
D/BluetoothAdapterProperties( 6127): State =  11
D/BluetoothAdapterProperties( 6127): mDiscoverableTimeout = 120
W/sh      ( 6373): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6373): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/LGBluetoothServiceAdapter( 6127): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6127): Setting state to 12
I/BluetoothAdapterState( 6127): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1037): Message: 60
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1037): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1037): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6127): Entering On State
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6127): [BTUI] OnState
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6127): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6127): [BTUI]         local_name: G3-1
D/BluetoothA2dp( 1037): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 6127): [BTUI] autoConnect() : not allowed
W/bt-smp  ( 6127): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
D/btif_config_util( 6127): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-smp  ( 6127): Plain text(LSB ~ MSB) = d5 a9 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6127): Encrypted text(LSB ~ MSB) = 9e d8 39 5c 1b 1b f4 32 5f 07 bf 4d b0 b2 5f 46 
W/bt-btm  ( 6127): Stopping oneshot timer
D/BluetoothManagerService( 1037): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
E/BluetoothManagerService( 1037): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1037): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 6127): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6127): Plain text(LSB ~ MSB) = f9 39 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6127): Encrypted text(LSB ~ MSB) = 06 a5 50 e3 62 8f 31 4e 21 82 b4 b2 16 19 0a 38 
W/bt-btm  ( 6127): Stopping oneshot timer
I/[SystemUI]BluetoothHandler( 1455): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1939): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1939): Message: 1
D/LGBluetoothAPIService( 1939): MESSAGE_BOOT_COMPLETED
I/BluetoothMapService( 6127): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6127): STATE_ON
V/BluetoothMapService( 6127): Handler(): got msg=1
W/bt-smp  ( 6127): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6127): Plain text(LSB ~ MSB) = a7 17 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6127): Encrypted text(LSB ~ MSB) = 82 21 4f 15 93 76 38 6b ab 76 27 1b f6 d9 21 94 
W/bt-btm  ( 6127): Stopping oneshot timer
D/BluetoothMapMasInstance( 6127): Map Service startRfcommSocketListener
I/LGBluetoothAPIService( 1939): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothMapMasInstance( 6127): MAS initSocket()
D/BluetoothMapMasInstance( 6127):   masId = 00
D/BluetoothMapMasInstance( 6127):   msgTypes = 0e
D/BluetoothMapMasInstance( 6127):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6127):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6127): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6127): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6127): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6127): Accepting socket connection...
D/BluetoothManagerService( 1037): Message: 40
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-smp  ( 6127): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6127): Plain text(LSB ~ MSB) = c0 c3 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6127): Encrypted text(LSB ~ MSB) = 5c ef b9 04 d8 be e2 2e 32 98 d5 21 67 5a d2 4c 
W/bt-btm  ( 6127): Stopping oneshot timer
D/BluetoothAdapterProperties( 6127): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6127): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6127): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6127): getDeviceMode  deviceMode 0
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/qcom-bt-wlan-coex( 6386): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/ContextImpl( 6166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothDeviceModeControllManager( 6127): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
V/BluetoothPbapService( 6127): Pbap Service onCreate
V/BluetoothPbapService( 6127): Starting PBAP service
D/LGBluetoothPbapAdapter( 6127): [BTUI] getInstance : create
V/BluetoothPbapService( 6127): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6127): state: 12
D/LGBluetoothAPIServer( 6127): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6127): [BTUI] onBind()
V/BluetoothPbapService( 6127): Handler(): got msg=1
D/LGBluetoothAPIService( 1939): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1939): Message: 100
D/LGBluetoothAPIService( 1939): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 6127): Pbap Service startRfcommSocketListener
I/QRemote ( 6348): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothPbapReceiver( 6127): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6127): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6127): ***********state = 12
V/BluetoothPbapService( 6127): Pbap Service initSocket
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6127): getBluetoothService() called with no BluetoothManagerCallback
V/[BNRBootReceiver]( 5891): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5891): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5891): Boot Receiver Return
D/LGBluetoothServiceAdapter( 6127): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6127): Succeed to create listening socket 
V/BluetoothPbapService( 6127): Accepting socket connection...
D/QRemote ( 6348): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/LocalBluetoothProfileManager( 6166): Adding local A2DP profile
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/BluetoothManagerService( 1037): Message: 30
D/QRemote ( 6348): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/LocalBluetoothProfileManager( 6166): Adding local HEADSET profile
D/BluetoothManagerService( 1037): Message: 30
D/BluetoothManagerService( 1037): Message: 30
D/BluetoothManagerService( 1037): Message: 30
D/LocalBluetoothProfileManager( 6166): Adding local MAP profile
D/BluetoothMap( 6166): Create BluetoothMap proxy object
D/BluetoothManagerService( 1037): Message: 30
D/BluetoothManagerService( 1037): Message: 30
V/BluetoothPbapService( 6127): Pbap Service onBind
D/LocalBluetoothProfileManager( 6166): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6166): [BTUI] initUserBindClient
W/ContextImpl( 6166): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6166): finishStartingService: stopping service
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/BluetoothA2dp( 6166): Proxy object connected
D/A2dpProfile( 6166): Bluetooth service connected
D/LgDataFeature( 6315): LgDataFeature() Constructor: none
D/LgDataFeature( 6315): LgDataFeature() Constructor Done, null
D/BluetoothHeadset( 6166): Proxy object connected
D/HeadsetProfile( 6166): Bluetooth service connected
D/BluetoothInputDevice( 6166): Proxy object connected
D/HidProfile( 6166): Bluetooth service connected
D/BluetoothPan( 6166): BluetoothPAN Proxy object connected
D/PanProfile( 6166): Bluetooth service connected
D/BluetoothMap( 6166): Proxy object connected
D/MapProfile( 6166): Bluetooth service connected
D/BluetoothMap( 6166): getConnectedDevices()
V/BluetoothMapService( 6127): getConnectedDevices()
D/BluetoothPbap( 6166): Proxy object connected
D/PbapServerProfile( 6166): Bluetooth service connected
D/LGBluetoothUserBindClient( 6166): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6166): onReceive
D/LGBluetoothFeatureConfig( 6166): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6166): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6166): return without doing reset settings.
V/BluetoothOppReceiver( 6127): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6127): [BTUI] startOppService()
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothOppManager( 6127): restoreApplicationData! falsefalsenullnull
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6166): Not supported operator for automatic switch
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/LGBluetoothFeatureConfig( 6127): isPrivacyLogsEnabled : true
V/BtOppService( 6127): onCreate
V/BluetoothOppNotification( 6127): send message
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BtOppService( 6127): Starting RfcommListener
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/BluetoothOppPreference( 6127): Dumping Names:  
D/BluetoothOppPreference( 6127): {}
D/BluetoothOppPreference( 6127): Dumping Channels:  
D/BluetoothOppPreference( 6127): {}
V/BtOppService( 6127): onStartCommand
V/BtOppService( 6127): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6127): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6127): BluetoothFtpReceiver Start Service
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BtOppService( 6127): Deleted complete outbound shares, number =  0
V/BluetoothOppNotification( 6127): new notify threadi!
V/BluetoothOppNotification( 6127): send delay message
V/BtOppService( 6127): Deleted complete inbound failed shares, number = 0
V/BtOppService( 6127): start RfcommListener
V/BluetoothOppProvider( 6127): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@2819e87d on behalf of 
V/BtOppService( 6127): RfcommListener started
V/BtOppRfcommListener( 6127): Starting RFCOMM listener....
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6127): getBluetoothService() called with no BluetoothManagerCallback
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
D/LGBluetoothServiceAdapter( 6127): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6127): Started RFCOMM listener....
I/BtOppRfcommListener( 6127): Accept thread started.
V/BtOppRfcommListener( 6127): Accepting connection...
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6166): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6166): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6166): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/UsbSettingsControl( 6166): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6166): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6166): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6166): [AUTORUN] setTetherStatus() : status=false
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
V/BluetoothFtpService( 6127): Ftp Service onCreate
I/BluetoothFtpService( 6127): Ftp Service onCreate
V/BluetoothFtpService( 6127): Ftp Service onStartCommand
V/BluetoothFtpService( 6127): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@3571a3c3 on behalf of 
V/BluetoothFtpService( 6127): Starting Listening on sockets
V/BtOppService( 6127): ContentObserver received notification
V/BluetoothSapReceiver( 6127): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6127): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6127): SapReceiver onReceive 
V/BluetoothSapReceiver( 6127): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6127):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6127): Calling SAP service start service with action = null
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@d1a5440 on behalf of 
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BluetoothOppNotification( 6127): mUpdateCompleteNotification = true
V/BtOppService( 6127): ContentObserver received notification
V/BluetoothFtpService( 6127): Handler(): got msg=1
V/BluetoothFtpService( 6127): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6127): Ftp Service initSocket
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6127): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@3618f79 on behalf of 
W/BluetoothAdapter( 6127): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6127): outbound: succ-0  fail-0
D/LGBluetoothServiceAdapter( 6127): [BTUI] createSocketChannel FD=81 mFd=78
V/BluetoothFtpService( 6127): Succeed to create listening socket on channel 20
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/AuthorizationBluetoothService( 2110): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppNotification( 6127): outbound notification was removed.
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@1ad724be on behalf of 
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
V/BluetoothOppNotification( 6127): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6127): inbound notification was removed.
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 6127): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1171a87b
V/BluetoothSapService( 6127): Sap Service onCreate
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@23c0b91f on behalf of 
V/BluetoothFtpService:RfcommSocketAcceptThread( 6127): Run Accept thread
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@1a5cceca on behalf of 
V/BluetoothSapService( 6127): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6127): state: 12
V/BluetoothSapService( 6127): Starting SAP server process
V/BluetoothOppNotification( 6127): update too frequent, put in queue
V/BtOppService( 6127): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothSapService( 6127): SAP Service startRfcommListenerThread
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
V/BluetoothSapService( 6127): Sap Service initRfcommSocket
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6127): getBluetoothService() called with no BluetoothManagerCallback
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
W/sapd    ( 6411): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6411): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/LGBluetoothServiceAdapter( 6127): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6127): Succeed to create listening socket 
V/BluetoothSapService( 6127): Accepting socket connection...
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/BT_SAP  ( 6411): Event pipe created
V/BT_SAP  ( 6411): create_server_socket qcom.sap.server
V/BT_SAP  ( 6411): created socket fd 6
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/SiteAdvisor( 6315): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
V/QRemote ( 6348): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6348): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6348): LgDataFeature() Constructor: none
D/LgDataFeature( 6348): LgDataFeature() Constructor Done, null
,V/SoundPool( 6348): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6348): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6348): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6348): doLoad: loading sample sampleID=1
I/QRemote ( 6348): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6348): Start decode
V/MediaPlayer[Native]( 6348): decode(31, 10857164, 17813)
V/MediaPlayerService(  323): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  323): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  323): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  323): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  323): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  323): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  323): player type = 3
V/AwesomePlayer(  323): AwesomePlayer create()
V/AwesomePlayer(  323): reset_l() 
V/AwesomePlayer(  323): cancelPlayerEvents
V/AwesomePlayer(  323): setAudioSink() 
V/AwesomePlayer(  323): reset_l() 
V/AudioCache(  323): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  323): ignored
V/AwesomePlayer(  323): cancelPlayerEvents
D/Utils   (  323): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  323): setDataSource_l dataSource
V/LGParserOSAL(  323): SniffLGParser start
V/LGParserOSAL(  323): MainType:5, SubType=0
V/LGParserOSAL(  323): #### check Mime : application/ogg
V/LGParserOSAL(  323): Detector mimeType:application/ogg, Confidence=1.000000
D/UEI.SmartControl( 5830): QS Service created
E/MediaExtractor(  323): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 5830): Service initServices...
D/UEI.SmartControl( 5830): QS start get config
,D/QRemote ( 6348): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/LGParserOSAL(  323): supported mime: application/ogg
V/AwesomePlayer(  323): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  323): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  323): mBitrate = -1 bits/sec
V/AwesomePlayer(  323): AudioTrack Setting
V/AwesomePlayer(  323): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  323): setAudioSource() 
V/MediaPlayerService(  323): prepare
V/AwesomePlayer(  323): prepareAsync_l() 
V/MediaPlayerService(  323): wait for prepare
V/AwesomePlayer(  323): onPrepareAsyncEvent() 
V/AwesomePlayer(  323): initAudioDecoder() 
W/Utils   (  323): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  323): isOffloadSupported()
V/AudioPolicyManager(  323): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  323): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  323): isAudioPlaybackHookOn() false
V/AwesomePlayer(  323): getUseOffload() = 0 
V/OMXCodec(  323): OMXCodec::Create
V/OMXCodec(  323): findMatchingCodecs()
V/OMXCodec(  323): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  323): matchingCodecs.size()=1
V/OMXCodec(  323): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/QRemote ( 6348): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/OMXCodec(  323): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  323): LG Codec Adapter start
V/OMXCodec(  323): OMXCodec Createtor
V/OMXCodec(  323): setComponentRole
V/OMXCodec(  323): configureCodec protected=0
V/LGCodecAdapter(  323): called getLGCodecSpecificData
V/LGCodecOSAL(  323): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  323): Called LGconfigureCodecMETA
V/LGCodecOSAL(  323): Called LGconfigureCodecMSG
V/LGCodecOSAL(  323): Not support LGCodec
V/OMXCodec(  323): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  323): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  323): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  323): Could not offload audio decode, try pcm offload
W/Utils   (  323): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  323): isOffloadSupported()
V/AudioPolicyManager(  323): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  323): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  323): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  323): init()
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  323): allocateBuffers
V/OMXCodec(  323): allocateBuffersOnPort portIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  323): allocateBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  323): [OMX.google.vorb,is.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb57ff150 on output port
V/OMXCodec(  323): init() mAsyncCompletion wait!!! 
V/LGMDMManager( 6348): Create singleton instance
,V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  323): init() mAsyncCompletion wait!!! 
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  323): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  323): finishAsyncPrepare_l() 
V/AudioCache(  323): notify(0xb54749c0, 5, 0, 0)
V/AudioCache(  323): ignored
V/AudioCache(  323): notify(0xb54749c0, 1, 0, 0)
V/AudioCache(  323): prepared
V/AudioCache(  323): wait - success
V/MediaPlayerService(  323): start
V/AwesomePlayer(  323): play_l() 
V/AwesomePlayer(  323): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  323): createAudioPlayer_l
V/AwesomePlayer(  323): seekAudioIfNecessary_l() 
V/AwesomePlayer(  323): startAudioPlayer_l() 
D/AudioPlayer(  323): start of Playback, useOffload 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  323): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  323): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  323): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045060944
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  323): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  323): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  323): allocateBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
V/OMXCodec(  323): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
I/art     ( 1037): Explicit concurrent mark sweep GC freed 48931(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.035ms total 86.906ms
V/AudioCache(  323): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  323): notify(0xb54749c0, 6, 0, 0)
V/AudioCache(  323): ignored
V/MediaPlayerService(  323): wait for playback complete
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab602000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab603000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb,173c000, 4096)
V/AudioCache(  323): memcpy(0xab604000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab605000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab606000, 0xb173c000, 4096)
,V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab607000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab608000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab609000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab60a000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab60b000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab60c000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab60d000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab60e000, 0xb173c000, 4096)
,V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab60f000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab610000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab611000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab612000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab613000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab614000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab615000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab616000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab617000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab618000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab619000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab61a000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab61b000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab61c000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab61d000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab61e000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab61f000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab620000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab621000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab622000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab623000, 0xb173c000, 4096)
,V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab624000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab625000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab626000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab627000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab628000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab629000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab62a000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab62b000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab62c000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab62d000, 0xb173c000, 4096)
,V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab62e000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab62f000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab630000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab631000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab632000, 0xb173c000, 4096)
V/AudioCache(  323): write(0xb173c000, 4096)
V/AudioCache(  323): memcpy(0xab633000, 0xb173c000, 4096)
V/OMXCodec(  323): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  323): postAudioEOS() 
V/AudioCache(  323): write(0xb173c000, 280)
V/AudioCache(  323): memcpy(0xab634000, 0xb173c000, 280)
V/AwesomePlayer(  323): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  323): onStreamDone
V/AwesomePlayer(  323): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  323): notify(0xb54749c0, 2, 0, 0)
V/AudioCache(  323): playback complete
V/AwesomePlayer(  323): pause_l() 
V/AudioCache(  323): notify(0xb54749c0, 7, 0, 0)
V/AudioCache(  323): ignored
V/AwesomePlayer(  323): cancelPlayerEvents
V/AudioCache(  323): wait - success
V/MediaPlayerService(  323): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  323): Pause Playback at 1068125
V/AwesomePlayer(  323): reset_l() 
V/AudioCache(  323): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  323): ignored
V/AwesomePlayer(  323): cancelPlayerEvents
D/AudioPlayer(  323): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  323): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=6 ,, newState=1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  323): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  323): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  323): AudioPlayer releasing audio source
D/AudioPlayer(  323): AudioPlayer done releasing audio source
,V/AwesomePlayer(  323): reset_l() 
V/AwesomePlayer(  323): cancelPlayerEvents
V/AwesomePlayer(  323): ~AwesomePlayer call
V/AwesomePlayer(  323): reset_l() 
V/AwesomePlayer(  323): cancelPlayerEvents
V/SoundPool( 6348): close(31)
V/SoundPool( 6348): pointer = 0x9ffd8000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1920
,D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
I/dhcpcd  ( 6335): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
I/dhcpcd  ( 6335): wlan0: leased 192.168.1.125 for 86400 seconds
D/dhcpcd  ( 6335): wlan0: adding IP address 192.168.1.125/24
,D/dhcpcd  ( 6335): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6335): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6335): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6335): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6335): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6335): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
,E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/UEI.SmartControl( 5830): Supports setup maps: true
D/UEI.SmartControl( 5830): QS start statue = true Error code = 0
I/UEI.SmartControl( 5830): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5830): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5830): ### init IR Blaster...
D/serial_port( 5830): Configuring serial port
E/UEI.SmartControl( 5830): UEIBLaster setting for 616
I/UEI.SmartControl( 5830): Setting serial record hearder size = 2
I/UEI.SmartControl( 5830): configuring settings for MAXQ616
I/UEI.SmartControl( 5830): Get version...
,D/UEI.SmartControl( 5830): serial port data available: 21
,D/UEI.SmartControl( 5830): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5830): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5830): QS saving settings...
D/UEI.SmartControl( 5830): IR Blaster version: 25672567
,D/UEI.SmartControl( 5830): serial port data available: 4
,I/UEI.SmartControl( 5830): Device manager: loading config....
,D/UEI.SmartControl( 5830): ----------- loading internal config...
W/ContextImpl( 5830): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5830): Services init done
D/UEI.SmartControl( 5830): QS Service init finished
D/UEI.SmartControl( 5830): QS Service version name: 2.1.91
D/UEI.SmartControl( 5830): QS Service version code: 201091
D/UEI.SmartControl( 5830): Service requested: Control
E/UEI.SmartControl( 5830): Loading SETTINGS...
D/UEI.SmartControl( 5830): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5830): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 5830): Internal service binding...
I/QRemote ( 6348): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 5830): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5830): -----service ready thread exits
I/UEI.SmartControl( 5830): ------ IControl API: 11
D/UEI.SmartControl( 5830): File observer start...
E/UEI.SmartControl( 5830): IR Port is disabled: false
D/UEI.SmartControl( 5830): Starting file observer...
I/UEI.SmartControl( 5830): Registering callback...
I/UEI.SmartControl( 5830): ------ IControl API: 19
I/UEI.SmartControl( 5830): Registering Services Ready callback...
I/UEI.SmartControl( 5830): Notify client services are ready...
I/QRemote ( 6348): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6348): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6348): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,D/QRemote ( 6348): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6348): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5830): ------ IControl API: 8
D/QRemote ( 6348): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6348): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6348): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6348): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6348): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6348): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6348): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6348): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6348): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6348): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6348): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1449751217854]
D/QRemote ( 6348): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 5493:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/QRemote ( 6348): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1037): Add DhcpResults: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): RunningState
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6165): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_5493/cgroup.procs: No such file or directory
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
V/QRemote ( 6348): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/QRemote ( 6348): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
,D/QRemote ( 6348): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 100
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/QRemote ( 6348): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1939): handleWifiStateChangedEvent: 1
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
I/StatusBar.NetworkController( 1455): mWifiConnected = true, mWifiLevel = 3
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1037): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1850): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1850):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=,1048576Kbps]
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
I/StatusBar.NetworkController( 1455): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1455): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 28
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): Sending msg: 5 arg1:0 arg2:1
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  318): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524290
W/dsqn    ( 6459): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6459): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
E/DSQN    ( 6459): DSQN ssw
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6348): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
,D/libc-netbsd(  318): res_queryN name = europe.pool.ntp.org succeed
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6348): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6348): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6348): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/LGDataListener(  318): argv[0]=dsqncommand
D/LGDataListener(  318): argv[1]=wlan0
D/LGDataListener(  318): argv[2]=1
D/LGDataListener(  318): notifyDSQN DSQN STARTMONITOR wlan0 1
V/WiFiOffLoadBroadcast( 6166): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6166): MCCMNC not supported: null
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/QRemote ( 6348): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6348): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6348): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:40:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449751218153], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449751218140]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
I/QRemote ( 6348): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 100]
I/QRemote ( 6348): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1455): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1850): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1850):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1455): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1037): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1037): NTP server returned: 1449751218552 (Thu Dec 10 13:40:18 GMT+01:00 2015) reference: 259312 certainty: 24 system time offset: 375
D/LocSvc_java( 1037): Sending msg: 10 arg1:0 arg2:1
D/LocSvc_java( 1037): reportXtraServer 
D/LocSvc_java( 1037):  server1=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1037):  server2=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1037):  server3=
D/LocSvc_java( 1037): xtraDownloadRequest
D/LocSvc_java( 1037): Sending msg: 6 arg1:0 arg2:1
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  318): res_queryN name = xtra3.gpsOneXTRA.net, class = 1, type = 1
V/BluetoothOppNotification( 6127): new notify threadi!
V/BluetoothOppNotification( 6127): send delay message
,V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@28266b58 on behalf of 
V/BluetoothOppNotification( 6127): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@2b20b4b1 on behalf of 
V/BluetoothOppNotification( 6127): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6127): outbound notification was removed.
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@5e10d96 on behalf of 
V/BluetoothOppNotification( 6127): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6127): inbound notification was removed.
V/BluetoothOppProvider( 6127): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6127): created cursor android.database.sqlite.SQLiteCursor@2afaad17 on behalf of 
D/libc-netbsd(  318): res_queryN name = xtra3.gpsOneXTRA.net succeed
,D/LocSvc_java( 1037): calling native_inject_xtra_data
D/LocSvc_java( 1037): Sending msg: 11 arg1:0 arg2:1
,E/WifiStateMachine( 1037):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1947727152] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1947727151] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1037): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1455): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,I/NetworkMonitor( 5174): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  318): res_queryN name = 2.android.pool.ntp.org succeed
D/AlarmManagerService( 1037): Setting time of day to sec=1449751221
W/AlarmManagerService( 1037): Unable to set rtc to 1449751221: Invalid argument
,I/SecureClockService( 1939): Intent.ACTION_TIME_CHANGED 
,I/[SystemUI]Clock( 1455): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2683): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2683): [Log Tracer - Schedule Transition] Time Change Event Received : 2015-12-10 13:40:21...... Request
W/ActivityManager( 1037): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/LgeClockWidgetControlView( 1455): time changed, timezoneChanged : false
I/LIA_Informant_Tips_LogTracer( 2683): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 109, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2683): DateInfo : SmartTips Total Working Day Count = 109
D/LIA_Informant_Tips_DateChangeManager( 2683): DateInfo : UserGuide Working Duration Count = 8
D/LIA_Informant_Tips_DateChangeManager( 2683): DateInfo : Last Date Check Time = 2015-12-10 13:40:21
I/[LGHome]LGDateChangeReceiver( 2065): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
D/KeyguardUpdateMonitor( 1455): handleTimeUpdate
I/[LGHome]LGCalendarIcon( 2065): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/[LGHome]LGCalendarIcon( 2065): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/[LGHome]Launcher( 2065): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6492 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/[Concierge]Service( 2595): onStartCommand(). Type : 9
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6509 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1037): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6526 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 6509): onCreate
W/AppUp4:DB( 6509):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6509):  setFingerPrint start
I/AppUp4:DB( 6509):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6509):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6509):  SDK version = 21
I/AppUp4:DB( 6509):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6509): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6509): onReceive
,I/ReaderUtils( 6492): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,D/LgDataFeature( 6509): LgDataFeature() Constructor: none
D/LgDataFeature( 6509): LgDataFeature() Constructor Done, null
,I/VacuumService( 2110): Vacuum at: now=1449751221796 tag=VacuumService
I/Thermal-Lib( 3102): Thermal-Lib-Client: Client request sent
I/ThermalEngine(  333): Thermal-Server: Thermal received msg from  override
D/AppUp4:CustFacade( 6509): Context : android.app.ReceiverRestrictedContext@edb080a
D/AppUp4:CustFacade( 6509): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6509): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6509): begin check event
I/AppUp4:CustModeStarterReceiver( 6509): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6509): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6509): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6509): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6509): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6552 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/AppConfig( 6526): Total System Memory = 2995761152
D/SystemHelper( 6526): region [EU], country [EU], operator [OPEN], sub-operator []
,I/GoogleURLConnFactory( 2110): Using platform SSLCertificateSocketFactory
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/GAV2    ( 6492): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LGDMClient( 3963): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3292): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3292): DownloadService onCreate
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3292): in removeSpuriousFiles
V/DownloadManager( 3292): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/Uploader( 2110): No account for auth token provided
V/DownloadManager( 3292): created cursor android.database.sqlite.SQLiteCursor@1a8f10f8 on behalf of 3292
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3292): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3292): in trimDatabase
V/DownloadManager( 3292): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3292): created cursor android.database.sqlite.SQLiteCursor@35af3c36 on behalf of 3292
,I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6578 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/LGDMClient( 3963): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,I/jxcore-log( 6071): Test app app.js loaded
I/jxcore-log( 6071): 
V/DownloadManager( 3292): DownloadService onStartCommand
V/DownloadManager( 3292): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = play.googleapis.com, class = 1, type = 1
D/LGDMClient( 3963): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3963): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/BooksApp( 6492): Created application version: 3.2.35 (30235)
,V/DownloadManager( 3292): created cursor android.database.sqlite.SQLiteCursor@92044a4 on behalf of 3292
I/chromium( 6071): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/DownloadManager( 3292): processing inserted download 1
I/chromium( 6071): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/DownloadManager( 3292): processing inserted download 4
V/DownloadManager( 3292): processing inserted download 7
V/DownloadManager( 3292): processing inserted download 8
V/DownloadManager( 3292): processing inserted download 9
V/DownloadManager( 3292): processing inserted download 10
V/DownloadManager( 3292): processing inserted download 16
V/DownloadManager( 3292): processing inserted download 17
V/DownloadManager( 3292): processing inserted download 18
V/DownloadManager( 3292): processing inserted download 21
W/DriveInitializer( 2321): Background init thread started
D/libc-netbsd(  318): res_queryN name = play.googleapis.com succeed
,V/DownloadManager( 3292): DownloadService onDestroy
W/ResourcesManager( 6578): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/GpsLocationProvider( 1037): No APN found to select.
I/LGEmail ( 6578): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6578): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6578): No package identifier when getting value for resource number 0x00000000
,E/Auth.Api.Credentials( 2321): [CredentialSyncAdapter] Unknown sync event.
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2321): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/BooksSync( 6492): Starting books sync
D/DelayedSyncController( 6552): Delaying sync.
D/LgDataFeature( 6578): LgDataFeature() Constructor: none
D/LgDataFeature( 6578): LgDataFeature() Constructor Done, null
I/ActivityManager( 1037): Killing 5810:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/DriveInitializer( 2321): Awaiting to be initialized
W/Uploader( 2110): No account for auth token provided
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_5810/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 5528:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10097/pid_5528/cgroup.procs: No such file or directory
,W/Uploader( 2110):  no longer exists, so no auth token.
W/DriveInitializer( 2321): Background init thread ended
,D/BooksSync( 6492): started syncMyEbooks
,D/eas_req ( 6578): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/Uploader( 2110): No account for auth token provided
I/HubEmail( 6578): JNI_OnLoad()
I/HubEmail( 6578): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6578): registerNatives()
I/HubEmail( 6578): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6578): registerNativeMethods()
I/HubEmail( 6578): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6578): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3267): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3267): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3267): networkInfo.isConnected() = true
D/PhoneState( 3267): setPdpRejectCasuse : false
E/WifiStateMachine( 1037):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=29.2, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:3369] from screen [on:0 period:-1947723770] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-45 f=2412 sc=60 link=72 tx=29.2, 0.0, 0.0  rx=28.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1947723769] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1037): doString: [SIGNAL_POLL]
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6638 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmBroadcastReceiver( 6638): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6638): 1  network is available. Sync DRM Time with NTP
I/art     ( 2110): Explicit concurrent mark sweep GC freed 26319(1425KB) AllocSpace objects, 1(39KB) LOS objects, 51% free, 30MB/62MB, paused 550us total 24.097ms
I/art     ( 1037): Explicit concurrent mark sweep GC freed 50671(2MB) AllocSpace objects, 4(105KB) LOS objects, 33% free, 44MB/66MB, paused 1.292ms total 93.057ms
V/DrmService( 6638): Service onCreate
D/DrmService( 6638): Received new request = 2
I/DrmSntpClient( 6638): Start Sync process
D/DrmSntpClient( 6638): Server : 0
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6658 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings( 6578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  318): res_queryN name = pool.ntp.org succeed
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6658): Almond Protected OAT
I/LGDrmClient( 6638): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  329): eDRM_SetDRMTime +++
I/LGDRM   (  329): [DRM] SET TIME : YR=2015, MON=12, DAY=10
I/LGDRM   (  329): [DRM] SET TIME : HR=12, MIN=40, SEC=22
V/ILGDrmService(  329): eDRM_SetDRMTime ---
I/DrmSntpClient( 6638): Synched
D/DrmService( 6638): Completed !! request = 2
D/DrmService( 6638): Request count = 0
V/DrmService( 6638): Service onDestroy
I/ActivityManager( 1037): Killing 5872:com.lge.eula/1000 (adj 15): empty #17
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1037): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5872/cgroup.procs: No such file or directory
E/BooksAccountManager( 6492): Authentication error
E/BooksAccountManager( 6492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6492): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6492): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6492): null auth token
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/WeatherApplication( 6658): removeAccount
D/WeatherApplication( 6658): Account.length = 0
E/WeatherApplication( 6658): OPERATOR:OPEN
W/ResourcesManager( 1455): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1455): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1397): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do add job
D/LgeQuickCoverNotificationData( 1397): add : 2
D/LgeQuickCoverNotificationData( 1397): do add job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/WeatherAncestor( 6658): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:40:22
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/Weather.Utils( 6658): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6658): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6658): 2 : This is isUpdating : false
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WeatherAncestor( 6658): connectivity changed - connection : true
D/WeatherService( 6658): 2 : isServiceAlived():false forecastCache:null
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ForecastDataCache( 6658): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6658): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 6658): 2 : Cache is not up-to-date, count: 0
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{58c4372 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
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
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/Weather_cast( 6658): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6658): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:40:22
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/libc-netbsd(  318): res_queryN name = www.googleapis.com succeed
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6679 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 5913:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  318): res_queryN name = www.google.com succeed
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_5913/cgroup.procs: No such file or directory
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26735, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1037): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 295006, reason: 10019
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{58c4372 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com succeed
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,D/DelayedSyncController( 6552): Delaying sync.
V/FormManager( 6213): There are no updated forms. The schedule will be deleted.
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6679): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
V/FormManager( 6213): Alarm would be updated, because LastCheckTime has been updated.
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6679): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1037): Killing 5957:com.google.android.talk/u0a72 (adj 15): empty #17
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6679): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6679): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup( 1037): failed to open /acct/uid_10072/pid_5957/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6711 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6711): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6679): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6679): Loading: webviewchromium
I/LibraryLoader( 6679): Time to load native libraries: 2 ms (timestamps 3636-3638)
I/LibraryLoader( 6679): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6679): Binding Chromium to main looper Looper (main, tid 1) {15b4579d}
I/LibraryLoader( 6679): Expected native library version number "",actual native library version number ""
I/chromium( 6679): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6679): Initializing chromium process, renderers=0
W/art     ( 6679): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  323): registerClient() client 0xb1427080, uid 10093
W/AudioManagerAndroid( 6679): Requires BLUETOOTH permission
W/ApiaryClient( 6492): Error response from books API: {
W/ApiaryClient( 6492):  "error": {
W/ApiaryClient( 6492):   "errors": [
W/ApiaryClient( 6492):    {
W/ApiaryClient( 6492):     "domain": "global",
W/ApiaryClient( 6492):     "reason": "required",
W/ApiaryClient( 6492):     "message": "Login Required",
W/ApiaryClient( 6492):     "locationType": "header",
W/ApiaryClient( 6492):     "location": "Authorization"
W/ApiaryClient( 6492):    }
W/ApiaryClient( 6492):   ],
W/ApiaryClient( 6492):   "code": 401,
W/ApiaryClient( 6492):   "message": "Login Required"
W/ApiaryClient( 6492):  }
W/ApiaryClient( 6492): }
,W/chromium( 6679): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6679): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6679): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/ApiaryClient( 6492): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3163159550444911059&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6492): Headers:
W/ApiaryClient( 6492): accept-encoding: [gzip]
W/ApiaryClient( 6492): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6492): gdata-version: 2
I/Adreno-EGL( 6679): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6679): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6679): Build Date: 12/12/14 금
I/Adreno-EGL( 6679): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6679): Remote Branch: 
I/Adreno-EGL( 6679): Local Patches: 
I/Adreno-EGL( 6679): Reconstruct Branch: 
I/NSApplication( 6679): Starting up...
,I/ActivityManager( 1037): Killing 4851:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_4851/cgroup.procs: No such file or directory
,I/GLSActivity( 2110): [ac] getting account id
,I/GLSUser ( 2110): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2321): SYNC; picasa accounts
,D/NetworkLogImpl( 2321): Loaded NetworkSpeedPredictor
I/iu.Environment( 2321): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2321): num queued entries: 0
I/iu.UploadsManager( 2321): num updated entries: 0
I/iu.SyncManager( 2321): NEXT; no task
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6315): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
D/ChimeraCfgMgr( 2321): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  318): res_queryN name = mtalk.google.com succeed
I/ActivityManager( 1037): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6780 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
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
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/ALBootInit( 6780): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6780): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6780): [setNextAlert] start
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{58c4372 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/Alarms  ( 6780): [setNextAlert] (1)
D/Alarms  ( 6780):  minTime  = 0
,D/Alarms  ( 6780):  -- OK multi -- 0
E/jeny.kim( 6780): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6780): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6780): BUILD Country: EU
D/Alarms  ( 6780): broadcastToWidgetProvider : false
,D/Alarms  ( 6780): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/UEI.SmartControl( 5830): Internal timer expired: 2
D/UEI.SmartControl( 5830): unbind internal service
V/SettingsProvider( 1037): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6780): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6780): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1171a87b
V/DigitalAppWidgetProvider( 6780): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1171a87b
,D/QuickCoverProvider( 6780): onReceiver
I/indal   ( 1397): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1397): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6658): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:40:23
D/Weather.Utils( 6658): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 6658): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6658): 2 : This is isUpdating : false
D/serial_port( 5830): close(fd = 24)
,D/WeatherService( 6658): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@18dc6698
D/ForecastDataCache( 6658): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6658): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6658): 2 : Cache is up-to-date, count: 0
I/UEI.SmartControl( 5830): Serial port is closed.
D/GCM     ( 2110): Connected
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 22939(1035KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.341ms total 69.816ms
D/Weather_cast( 6658): 2 : set auto-update time : 12/10 16:40
D/WeatherAncestor( 6658): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:40:23
,D/GCM     ( 2110): Message class com.google.f.a.a.p
I/ActivityManager( 1037): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 5891:com.lge.bnr/1000 (adj 15): empty #17
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 273us total 9.974ms
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 9.015ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.056ms
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5891/cgroup.procs: No such file or directory
,D/TimeService( 6805): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751223410
,D/        ( 6805): TimeServiceNative: User Time to be set is 1449751223410
D/QC-time-services( 6805): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6805): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6805): Lib:time_genoff_operation: pargs->ts_val = 1449751223410
D/QC-time-services(  363): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6805): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  363): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751223410
D/QC-time-services(  363): Daemon:genoff_opr: Base = 2, val = 1449751223410, operation = 0
D/QC-time-services(  363): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/19/70 5:53:6
D/QC-time-services(  363): Daemon:Value read from RTC seconds = 9352386000
D/QC-time-services(  363): Daemon:new time 1449751223410 
D/QC-time-services(  363): Daemon: delta 1440398837410 genoff 1440398837410 
D/QC-time-services(  363): Daemon:genoff_persistent_update: Writing genoff = 1440398837410 to memory
D/QC-time-services(  363): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  363): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  363): Updating the TOD offset
D/QC-time-services(  363): Daemon:genoff_persistent_update: Writing genoff = 1440398837410 to memory
D/QC-time-services(  363): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  363): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  363): Daemon:Update to modem bit set
D/QC-time-services(  363): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  363): Daemon: Base = 2, Value being sent to MODEM = 1124434037410
,E/QC-time-services( 6805): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  363): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  363): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1037): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6830 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1037): Killing 6276:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6276/cgroup.procs: No such file or directory
,W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6830): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6830): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6830): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@74849fe, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@18c7155f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1bc13bac, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@47d0075, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@edb080a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1171a87b, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@18dc6698, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2eaa2ef1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@38299ad6, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2e685157, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@b7d5444, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@4a1c92d, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@9fc8e62, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@35b6abf3, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@381d70b0, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@34fecb29, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3d192eae, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3886144f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2f60e7dc, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@230ff0e5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3f4d87ba, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@739a66b, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@602a5c8, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1e53b661, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1b3c6586, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@b4a3e47, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1f805674, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@15b4579d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@10e95412, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@22e277e3, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@378665e0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@283d099, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2b049f5e, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1a3aaf3f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@161c000c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@737dd55, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf7536a, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb5005b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1a8f10f8, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3de5f9d1, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@35af3c36, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@7b94737, 
D/GeneralPreferenceUtils( 6830): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6830): [init]
I/Config  ( 6830): LGCalendar ver.4.40.16
I/Config  ( 6830): start check model
I/Config  ( 6830): start check native_ca
I/Config  ( 6830): Config Operator=OPEN, Country=EU
D/Config  ( 6830): [setDefaultValuesToPref]
D/Config  ( 6830): [parseProfiles]
,D/ProfilesParser( 6830): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6830): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6830): [updateProfiletoCountryInfo]
D/GeneralPreference( 6830): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6830): [updateWidgets] 
,I/InitNotificationRingtoneService( 6830): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6830): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,I/AlertUtils( 6830): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6830): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6830): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6830): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6830): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6830): onHandleIntent
,D/HolidayDataLoader( 6830): readJsonAsset : holiday.json
,D/MonthWidgetProvider( 6830): [onReceive]
D/CalendarWidgetProvider( 6830): [onReceive]
D/CalendarWidgetProvider( 6830): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6830): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6830): [onReceive]
D/CalendarWidgetProvider( 6830): [onReceive]
D/CalendarWidgetProvider( 6830): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6830): [onUpdateAndInitCalendarTime]
E/HolidayIntentService( 6830): onHandleIntent:holiday data empty
,I/ActivityManager( 1037): Killing 6193:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10037/pid_6193/cgroup.procs: No such file or directory
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DigitalAppWidgetProvider( 6780): onReceive: android.intent.action.ALARM_CHANGED
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WeatherAncestor( 6658): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:40:23
D/Weather.Utils( 6658): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6658): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6658): 2 : This is isUpdating : false
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Weather_cast( 6658): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6658): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:40:23
I/ActivityManager( 1037): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6860 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/BooksAccountManager( 6492): Authentication error
E/BooksAccountManager( 6492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6492): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6492): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6492): null auth token
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{58c4372 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ResourcesManager( 6860): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ApiaryClient( 6492): Error response from books API: {
W/ApiaryClient( 6492):  "error": {
W/ApiaryClient( 6492):   "errors": [
W/ApiaryClient( 6492):    {
W/ApiaryClient( 6492):     "domain": "global",
W/ApiaryClient( 6492):     "reason": "required",
W/ApiaryClient( 6492):     "message": "Login Required",
W/ApiaryClient( 6492):     "locationType": "header",
W/ApiaryClient( 6492):     "location": "Authorization"
W/ApiaryClient( 6492):    }
W/ApiaryClient( 6492):   ],
W/ApiaryClient( 6492):   "code": 401,
W/ApiaryClient( 6492):   "message": "Login Required"
W/ApiaryClient( 6492):  }
W/ApiaryClient( 6492): }
,W/ApiaryClient( 6492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3163159550444911059&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6492): Headers:
W/ApiaryClient( 6492): accept-encoding: [gzip]
W/ApiaryClient( 6492): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6492): gdata-version: 2
D/LgDataFeature( 6860): LgDataFeature() Constructor: none
D/LgDataFeature( 6860): LgDataFeature() Constructor Done, null
,I/Babel   ( 6860): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6860): MmsConfig.loadMmsSettings
,I/Babel   ( 6860): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,I/Babel   ( 6860): MmsConfig.loadFromDatabase
,I/ThermalEngine(  333): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3102): Thermal-Lib-Client: Client request sent
,E/Babel   ( 6860): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6860): MmsConfig.loadFromResources
E/Babel   ( 6860): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6860): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6860): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6860): Unsupported mime audio/evrc
W/AudioCapabilities( 6860): Unsupported mime audio/qcelp
W/VideoCapabilities( 6860): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6860): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6860): Unsupported mime audio/qcelp
W/AudioCapabilities( 6860): Unsupported mime audio/evrc
W/VideoCapabilities( 6860): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6860): Unsupported mime video/divx
W/VideoCapabilities( 6860): Unsupported mime video/divx311
W/VideoCapabilities( 6860): Unsupported mime video/divx4
W/VideoCapabilities( 6860): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6860): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6860): Unsupported mime audio/eac3
,W/AudioCapabilities( 6860): Unsupported mime audio/ac3
W/AudioCapabilities( 6860): Unsupported mime audio/g726
W/AudioCapabilities( 6860): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6860): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6860): Unsupported mime audio/adpcm
W/VideoCapabilities( 6860): Unsupported mime video/theora
W/VideoCapabilities( 6860): Unsupported mime video/mjpg
W/ResourcesManager( 6860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6860): Installed default security provider GmsCore_OpenSSL
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 6860): UserRecoverableAuthException.
,E/Babel   ( 6860): cfq: BadAuthentication
E/Babel   ( 6860): 	at cfn.a(Unknown Source)
E/Babel   ( 6860): 	at f.a(PG:191)
E/Babel   ( 6860): 	at ava.a(PG:88)
E/Babel   ( 6860): 	at ava.a(PG:128)
E/Babel   ( 6860): 	at bjs.a(PG:255)
E/Babel   ( 6860): 	at bep.a(PG:602)
E/Babel   ( 6860): 	at bep.a(PG:469)
E/Babel   ( 6860): 	at bpo.run(PG:1141)
E/Babel   ( 6860): Error getting auth token
E/Babel   ( 6860): bxl
E/Babel   ( 6860): 	at f.a(PG:201)
E/Babel   ( 6860): 	at ava.a(PG:88)
E/Babel   ( 6860): 	at ava.a(PG:128)
E/Babel   ( 6860): 	at bjs.a(PG:255)
E/Babel   ( 6860): 	at bep.a(PG:602)
E/Babel   ( 6860): 	at bep.a(PG:469)
E/Babel   ( 6860): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6860): error sending REQ[fc:8; creat:1449750736203; type:bev-356031096]; took 80 ms (error code == 100)
E/Babel   ( 6860): Account registration failedRedacted-21
E/Babel   ( 6860): bph: null -- null
E/Babel   ( 6860): 	at ava.a(PG:120)
E/Babel   ( 6860): 	at ava.a(PG:128)
E/Babel   ( 6860): 	at bjs.a(PG:255)
E/Babel   ( 6860): 	at bep.a(PG:602)
E/Babel   ( 6860): 	at bep.a(PG:469)
E/Babel   ( 6860): 	at bpo.run(PG:1141)
I/Babel   ( 6860): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6860): Account sign in complete with state 106account: Redacted-21
I/art     ( 6860): Note: end time exceeds epoch: 
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2110): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6860): Unexpected exception while authenticating.
E/Babel   ( 6860): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6860): 	at cfn.b(Unknown Source)
E/Babel   ( 6860): 	at cfn.a(Unknown Source)
E/Babel   ( 6860): 	at f.a(PG:188)
E/Babel   ( 6860): 	at ava.b(PG:143)
E/Babel   ( 6860): 	at bnr.run(PG:5415)
E/Babel   ( 6860): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6860): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6860): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
D/QuickStatusbarLayout( 1397): Notification difference=198
,D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{58c4372 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1397): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): post do just update job
D/LgeQuickCoverNotificationData( 1397): showAll3
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1397): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1397): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{58c4372 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6492): Authentication error
E/BooksAccountManager( 6492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6492): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6492): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6492): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6492): null auth token
,E/WifiStateMachine( 1037):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=24.1, 0.0, 0.0  rx=20.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1947720759] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-44 f=2412 sc=60 link=72 tx=24.1, 0.0, 0.0  rx=20.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1947720757] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1037): doString: [SIGNAL_POLL]
W/ApiaryClient( 6492): Error response from books API: {
W/ApiaryClient( 6492):  "error": {
W/ApiaryClient( 6492):   "errors": [
W/ApiaryClient( 6492):    {
W/ApiaryClient( 6492):     "domain": "global",
W/ApiaryClient( 6492):     "reason": "required",
W/ApiaryClient( 6492):     "message": "Login Required",
W/ApiaryClient( 6492):     "locationType": "header",
W/ApiaryClient( 6492):     "location": "Authorization"
W/ApiaryClient( 6492):    }
W/ApiaryClient( 6492):   ],
W/ApiaryClient( 6492):   "code": 401,
W/ApiaryClient( 6492):   "message": "Login Required"
W/ApiaryClient( 6492):  }
W/ApiaryClient( 6492): }

```
